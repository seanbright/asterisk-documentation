---
title: Asterisk Channel Data Stores
pageid: 4259988
---

Asterisk Channel Data Stores
============================

##### What is a data store?

A data store is a way of storing complex data (such as a structure) on a channel so it can be retrieved at a later time by another application, or the same application.

If the data store is not freed by said application though, a callback to a destroy function occurs which frees the memory used by the data in the data store so no memory loss occurs.

##### A datastore info structure

```

static const struct example_datastore {
 .type = "example",
 .destroy = callback_destroy
};

```

This is a needed structure that contains information about a datastore, it's used by many API calls.

##### How do you create a data store?

1. Use ast_datastore_alloc function to return a pre-allocated structure  

2. Attach data to pre-allocated structure.  

 Ex: datastore->data = mysillydata;

3. Add datastore to the channel  

 Ex: ast_channel_datastore_add(chan, datastore);  

 This function takes two arguments: (pointer to channel, pointer to data store)

Full Example:

```

void callback_destroy(void *data)
{
 ast_free(data);
}

struct ast_datastore *datastore = NULL;
datastore = ast_datastore_alloc(&example_datastore, NULL);
datastore->data = mysillydata;
ast_channel_datastore_add(chan, datastore);

```

!!! note 
    NOTE
    Because you're passing a pointer to a function in your module, you'll want to include this in your use count. When allocated increment, when destroyed decrement.

[//]: # (end-note)

##### How do you remove a data store?

1. Find the data store  

2. Remove the data store from the channel  

3. If we want to now do stuff to the data on the data store

4. Free the data store (this will call the destroy call back)  

 Ex: ast_channel_datastore_free(datastore);  

 This function takes one argument: (pointer to data store)

##### How do you find a data store?

1. Find the data store  

 Ex: datastore = ast_channel_datastore_find(chan, &example_datastore, NULL);  

 This function takes three arguments: (pointer to channel, datastore info structure, uid)
