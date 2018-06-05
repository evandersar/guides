---
title: HTML Entities
---



**Advantage of using an entity name:** An entity name is easy to remember.
**Disadvantage of using an entity name:** Browsers may not support all entity names, but the support for numbers is good.

#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->

=======

# HTML Entities

## Overview

###	What are HTML Entities?

HTML entities are characters that are used to replace reserved characters in HTML or for characters that do not appear on your keyboard. Some characters are reserved in HTML. If you use the less than(<) or greater than(>) signs in your text, the browser might mix them up with tags.

###	What are they used for?
  
As mentioned about HTML entities are used in order to replace reserved characters that are reserved by HTML.

### How do you use them?

A character entity looks similar to this:
```html
<!-- format &[entity_name]; -->
<!-- example for a less-than sign (<) -->
&lt;
```
Or
```html
<!-- &#[entity_number]; -->
<!-- example for a less-than sign (<) -->
&#60;
```
  
## Reference Guide

This is by no means an exhaustive list but the links below will be able to give you more entities if the ones below do not work for your needs. Happy Coding :bowtie: 


| Character | Entity Name | Entity Number |	Description |
|       |       | &#32; | Space |
|-------|-------|-------|-------|
|   !   |       | &#33; | Exclamation mark |
|-------|-------|-------|------------------|
|   "   |	      | &#34; | Quotation mark |
|-------|-------|-------|----------------|
|   #   |	      | &#35; | Number sign |
|-------|-------|-------|-------------|
|   $   |       | &#36; | Dollar sign |
|-------|-------|-------|-------------|
|   %   |	      | &#37; | Percent sign |
|-------|-------|-------|--------------|
|   &   |	&amp;	| &#38; | Ampersand |
|-------|-------|-------|-----------|
|   '   |		    | &#39;	| Apostrophe |
|-------|-------|-------|------------|
|   (   |		    | &#40; | Opening/Left Parenthesis |
|-------|-------|-------|--------------------------|
|    )  |		    | &#41; | Closing/Right Parenthesis |
|-------|-------|-------|---------------------------|
|   *   |		    | &#42; | Asterisk |
|-------|-------|-------|----------|
|   +   |		    | &#43; | Plus sign|
|-------|-------|-------|----------|
|   ,   | 		  | &#44;	| Comma |
|-------|-------|-------|-------|
|   -   |		    | &#45;	| Hyphen |
|-------|-------|-------|--------|
|   .   |		    | &#46;	| Period |
|-------|-------|-------|--------|
|   /   | 	    | &#47;	| Slash |
|-------|-------|-------|-------|


#### More Information:
There are plenty of HTML entites references out there; some examples are:
* [Table of Entities - W3](https://dev.w3.org/html5/html-author/charref)
* [W3 Schools](https://www.w3schools.com/html/html_entities.asp)
* [Freeformatter](https://www.freeformatter.com/html-entities.html)
