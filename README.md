---
Summary: |-
  Refer to the reference guides for
  https://www.markdownguide.org/basic-syntax/
  https://www.markdownguide.org/extended-syntax/
tags:
  - markdown
  - cheat-sheet
  - md-script
---

# Markdown Cheat Sheet

Refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax/) and [extended syntax](https://www.markdownguide.org/extended-syntax/).

Basic Syntax
======HEADER==========
---

# H1 -32 -2em
## H2 -24 -1.5em
### H3 -20 -1.25em
#### H4 -16 -1em
##### H5 -14 -0.875em
###### H6 -13.6 -0.85em

```
H1
===
H2
---
```


**bold text**
*italicized text*

> blockquote

 Ordered List
---
1. First item
2. Second item
3. Third item

Unordered List
---
- First item
- Second item
- Third item

`code`

---

[Markdown Link](https://www.markdownguide.org)
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).


![alt text for image](https://www.markdownguide.org/assets/images/tux.png)

URLs and Email Addresses
---
<https://www.markdownguide.org>
<fake@example.com>


Extended Syntax
---

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

Heading ID
---
### My Great Heading {#custom-id}
`<h3 id="custom-id">My Great Heading</h3>`


 Definition List
 ---
term
: definition


~~The world is flat.~~

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

That is Emoji:-  :joy:

I need to highlight these ==very important words==.

Subscript
---
H~2~O

Superscript
---
X^2^


 [go up  🔼](#Markdown%20Cheat%20Sheet)
 
---

Callout:

> [!info] hello world this is just a callout for you and for what 

> [!example]- this is a text
> hello world this is just a callout for you and for what 
> this is just a beginning for out journey 

> [!NOTE]
> hello world this is just a callout for you and for what 
> this is just a beginning for out journey 

> [!warning]
> hello world this is just a callout for you and for what 
> this is just a beginning for out journey 

> [!quote]
> hello world this is just a callout for you and for what 
> this is just a beginning for out journey 

 > hello world
 >> this is a text 

Emoji:

:exclamation: Use emoji icons to enhance text. :+1:  Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    Markup : Code appears between colons :EMOJICODE:



- [ ] An uncompleted task
- [x] A completed task


- [ ] An uncompleted task
    - [ ] A subtask


1. A numbered list
    1. A nested numbered list
    2. Which is numbered
    2. Which is numbered
    2. Which is numbered  
      2. Which is numbered  
      2. Which is numbered  
      2. Which is numbered  
      2. Which is numbered  
    2. Which is numbered  
    2. Which is numbered  
2. Which is numbered
2. Which is numbered
2. Which is numbered

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
        * Sub-nested bullet etc
          * Sub-nested bullet etc
          * Sub-nested bullet etc
            * Sub-nested bullet etc
            * Sub-nested bullet etc
* Bullet list item 2
* Bullet list item 2


First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | \|

    Markup :  # Heading 1 #
    
    -OR-
    
    Markup :  ============= (below H1 text)

---

added github 5 types of callouts

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.



