---
title: Elements
type: pages
draft: false
url: elements
date: 2022-02-16T16:26:54.217Z
---
If you're looking for a fresh new look for your website, you'll love the new Netlify theme. It's easy to use and customize, and it has all the features you need to create a beautiful site. Plus, it's responsive so it looks great on any device.

- - -

# Simple default styles for headings

## Simple default styles for headings

### Simple default styles for headings

#### Simple default styles for headings

##### Simple default styles for headings

###### Simple default styles for headings

- - -

> *Graphic design is the paradise of individuality, eccentricity, heresy, abnormality, hobbies, and humors. — George Santayana*

- - -

You can use the mark tag to highlight text.

This line of text is meant to be treated as deleted text.

*This line of text will render as underlined*

This line of text is meant to be treated as fine print.

**This line rendered as bold text.**

*This line rendered as italicized text.*

attr

HTML

- - -


{{< youtube K4TOrB7at0Y >}}

- - -

### Contact Form

{{<contact-form>}}

- - -

### Amazon Product Ad With Your Query

{{< amzn term="Gaming Laptops" >}}

- - -

### Syntax Highlighting

```js
'use strict';
var markdown = require('markdown').markdown;
function Editor(input, preview) {
  this.update = function() {
    preview.innerHTML = markdown.toHTML(input.value);
  };
  input.editor = this;
  this.update();
}
```