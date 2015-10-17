---
layout: post_blank
title:  Some Basics about Markdown!!
by: Dan
---


How to format things you're editing.
====================================

We're using a language called Markdown. It's kind of like a simpler HTML for text documents (which is really what any code actually is).

You see that line of equals symbols above that first paragraph? (you'll only see that if you're looking at the source code.) That's making the headline-sized font. You're just underlining stuff that you want to look like that.

You can do a smaller headline too
----------------------------------

We usually call those "subheads" and they're great for titles within a page.

You can also make lists:

* Like this
* and this
* and also this

that stuff at the very top of the text document
------------------------------------------------

That's called "YAML Frontmatter" and is super important to how this site comes together because it calls the template that will actually format the whole page (that's in the "template" section), it adds the title to the top of the page ("title") and even adds the author name ("by"). That it's surrounded by those three dashes is really important, because that tells Jekyll, the little program that runs to convert these text files into web pages, that it should treat it differently than the rest of the page.
