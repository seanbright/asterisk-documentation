---
search:
  boost: 0.5
title: SHELL
---

# SHELL()

### Synopsis

Executes a command using the system shell and captures its output.

### Description

Collects the output generated by a command executed by the system shell<br>

``` title="Example: Shell example"

exten => s,1,Set(foo=${SHELL(echo bar)})


```

/// note
The command supplied to this function will be executed by the system's shell, typically specified in the SHELL environment variable. There are many different system shells available with somewhat different behaviors, so the output generated by this function may vary between platforms. If 'live\_dangerously' in 'asterisk.conf' is set to 'no', this function can only be executed from the dialplan, and not directly from external protocols.
///


### Syntax


```

SHELL(command)
```
##### Arguments


* `command` - The command that the shell should execute.<br>

    /// warning
Do not use untrusted strings such as **CALLERID(num)** or **CALLERID(name)** as part of the command parameters. You risk a command injection attack executing arbitrary commands if the untrusted strings aren't filtered to remove dangerous characters. See function **FILTER()**.
///



### Generated Version

This documentation was generated from Asterisk branch 16 using version GIT 