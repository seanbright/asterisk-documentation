---
title: Wiki Organization and Style Guide
pageid: 28315986
---

 

 

Overview
========

This page should serve as a guide for creating organized, consistent, easy to consume content on the Asterisk wiki. It covers organization, content design and formatting.

You can find research all over the web on why these goals are important. Here's a link to [Nielson Norman Group on How Users Read on the Web](http://www.nngroup.com/articles/how-users-read-on-the-web/)

Organization of Pages
=====================

Spaces, parent and child pages
------------------------------

All Asterisk documentation pages are contained within the Asterisk space. Most of those editing on wiki.asterisk.org will only have edit permissions within the Asterisk space.

Within the Asterisk space there are many top-level parent pages available. We've included some info about each below to help you decide where a page goes.

* [About the Project](/About-the-Project) - Any general information about the project. Licensing, History, What is Asterisk?
* [Getting Started](/Getting-Started) - Information relevant to completely new users, information on installation and how to get rolling into configuration and the rest of the documentation.
* [Operation](/Operation) - Details concerning Asterisk's operation. That is, starting and stopping the Asterisk daemon, command line operation and other non-configuration tasks.
* [Fundamentals](/Fundamentals) - Basic, key and core concepts of Asterisk. Some of the most important foundational things to know about Asterisk.
* [Configuration](/Configuration) - How everything is configured. Where are the files? How do I use them? How do I program dialplan? How do I use the APIs?
* [Deployment](/Deployment) - Examples, tutorials, how-tos and recommendations for specific use-cases or scenarios of deployment. How do I deal with Asterisk in a NATed environment? How do I build a simple PBX?
* [Development](/Development) - All information regarding the development of Asterisk itself.
* [Asterisk Test Suite Documentation](/Test-Suite-Documentation/Test-Development/Home/Asterisk-Test-Suite-Documentation) - Documentation for the test suite! Primarily for developers.
* [Asterisk Security Vulnerabilities](/About-the-Project/Asterisk-Security-Vulnerabilities) - How the project handles security vulnerabilities.
* [Asterisk Community](/Asterisk-Community) - Anything falling under community. The places we meet, our code of conduct, community services.

Plus there are a few sections titled "Asterisk X Documentation" where X is the version. These sections are reserved for command reference content, mostly pushed to the wiki via scripts that pull from the source documentation.




---

**Note:**  Pages created or modified by "wikibot" are generated by scripts.

  



---


On this Page


Considerations before creating new content
------------------------------------------

Find out if a new page is really needed. Check the following:

* Have you searched the Asterisk space to see if it exists already?
* Is there already *some* content that you could use to build on?
* Is there related content which should be consolidated with your new content?

If obsolete related content exists and you decide to delete, rename or move it, then check the following:

* [check for inbound links](https://confluence.atlassian.com/display/DOC/Viewing+Page+Information). If there are many referrers from external sources, you should ask the Asterisk project manager and others before renaming or deleting that page.
* If there are inbound links from wiki.asterisk.org pages, then we can of course go update those. For links from external sources, we have to decide how much we value breaking or not breaking those links.

Will the content fill more than a single screen-worth of space? If so, then you probably want to split it into multiple pages, or one page with sub-pages. When linking on a forum or mailing list, this makes it easier to link to specific chunks of content with shorter URLs.

Use the General Asterisk Wiki Page template for creating a new page with a very basic outline. It should include the Table of Contents macro discussed later on. The template is listed in the templates dialog when creating a new page.

Content Design
==============

Design the content for a particular audience
--------------------------------------------

**Consider the audience** for the content you are writing. A good clue is the section of the wiki you are placing the article in.

For example, pages in the Getting Started section should be oriented towards a completely new Asterisk user. That means the content should have a very narrow focus, making sure to explain concepts discussed and if a tutorial, provide small manageable chunks of tasks.

While it is acceptable to add content for very experienced Asterisk users, on the other end of the scale we do want to limit ourselves. Though Asterisk runs on Linux, the purpose of this wiki is not to teach Linux fundamentals. Pages in the Getting Started section do set the expectation that you should be familiar with Linux to use Asterisk.

**Set expectations**. In a section like Deployment, which could contain content for new users or experienced administrators, you should state requirements or experience at the beginning of the content.

Style based on purpose of content
---------------------------------

As the heading says, the purpose of your content should determine what style you craft it in.

* **Explanatory or Descriptive** - These styles are useful for reference material. Pages describing configuration sections, (as opposed to how-to configure) and feature or functionality descriptions all should be written in these styles.
* **Procedural** - Configuration how-to, tutorials, examples and guides often include this style which often features lots of bulleted lists and step by step instructions.
* **Frequently Asked Questions** - Often a FAQ appears as a list of questions with their answers. Only use this style when there is no other better way to do it. You could format a lot of content this way, but it doesn't make sense most of the time.

Grammar, Punctuation, Spelling
------------------------------

The Ubuntu documentation team has a good guide for [grammar, punctuation and spelling](https://wiki.ubuntu.com/DocumentationTeam/StyleGuide/SpellingPunctuationGrammar). Other than those rules, follow typical English language and writing conventions. It is always a good idea to have at least one or two other editors review your content for obvious problems.

Content Formatting and Markup
=============================

Naming a page
-------------

Page names should be concise. i.e., The simplest summary of the content within it or under it. That means taking into consideration sub-pages if the page in question is a top-level parent page.

Page names should be written in [Title Case](http://www.grammar-monster.com/lessons/capital_letters_title_case.htm).

The page name will be included in the URL the wiki generates, so try to avoid any special characters or symbols and keep it as short as possible.

Headings
--------

Good use of headings allows a reader to quickly break-down the content on the page to find what they need. Each heading should be a concise summary of the content under that heading.

Most pages won't use more than two or three levels of headings. h1 for sections, h2 for sub-sections, and h3 if you really need to break those sub-sections down further. If you find yourself getting into a lot of h3 or h4 headings, consider creating sub-pages rather than including so much nested content on a single page.

Use [Title Case](http://www.grammar-monster.com/lessons/capital_letters_title_case.htm) for h1 headings. For lower headings use only sentence case; that is, only use capitalization how you would in a typical sentence.

Linking
-------

As you review content that you have written, try to link words to other content relevant to what you are discussing. Especially if it would help the user understand that topic.

There are a variety of ways to link to other pages and content. All of them are described in the confluence documentation, in [Working with Links](https://confluence.atlassian.com/display/CONF55/Working+with+Links).

When linking from an external site, outside Confluence, it is important to use a permalink. Here is an excerpt from the Confluence documentation:

The best way to link to a Confluence page from outside Confluence, for example on a website or in an email message, is to use the tiny link which is a permanent URL. This ensures that the link to the page is not broken if the page name changes.

To access the permanent URL for a page:

1. View the page you wish to link to.
2. Choose **Tools** > **Link to this page**.
3. Copy the **Tiny Link**.
4. Use the tiny link in your website or email message.

You do not need to use the tiny link to link to pages within your Confluence site. Confluence automatically updates links when you rename or move a page to another space.

Common macros
-------------

Confluence provides a variety of macros serving all sorts of functions. The confluence documentation on [Working with Macros](https://confluence.atlassian.com/display/DOC/Working+with+Macros) is very helpful to understand their usage. Below we'll list some macros that are commonly used with notes on how to use them specific to the Asterisk wiki.

### Macro - Table of Contents

The TOC macro should be put at the top right-hand side of the page.

To make sure it aligns correctly you need to place a section macro, then two column macros inside the section. After that put a panel macro inside the second column and finally the TOC goes inside the panel. You can then edit the panel title to say something like "On this Page". For an example you can edit this page itself. Look at the very top and see how the TOC is laid out inside the the other macros.

Always set the TOC maxlevel to 2, as it is generally not necessary for a page-level TOC to have more detail.

### Macro - No Format

Often when pasting text from an Asterisk log or the CLI you can run into issues as characters may be interpreted by the WYSIWYG editor as markup. Use the No Format macro to include a block of text to which no formatting will be applied.

### Macro - Expand

This macro gives you a click-able link where upon being clicked provides a slide-out panel of content. Use this when you need to fit many large chunks of example code or terminal output into a small section. It'll prevent the code from taking up all the screen real-estate and then requiring the user to scroll through it all.

### Macro - Warning, Info, Note, Tip

Try to avoid using these call-out boxes too often as they can be visually distracting and a few too many can make a page noisy. They are most useful with sparing application.

* Info - Most tame visually. Use this when you want to call-out a specific, brief piece of info that isn't necessarily critical, but could be very helpful.
* Note - A bright yellow exclamation sign. Maybe you want to share a word of caution or advise about requirements. "This example only works with a feature added in 11.1.1!"
* Tip - A bright green check mark. Useful when you want to mention shortcuts to a process already described detail, or call out brief command-line trick related to your content.
* Warning - This is bright red and very eye-catching. Use when you need to call out a piece of information very critical that could cause major problems for the user if not read or understood.