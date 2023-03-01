---
layout: post
title: Post Application of Markdown
image-card: "assets/img/rpothumbnail.png"
image-feature: "assets/img/rposhort.png"
image-banner: "assets/img/rpofeature.png"
description: "Let's accept it. We face a global IT talent shortage. There are more than 11 million job openings in America today."
permalink: blog/post-application-of-markdown
---
<!-- # Representation of Heading1
## Representation of Heading2
### Representation of Heading3
#### Representation of Heading4
##### Representation of Heading5
###### Representation of Heading6 -->

<!-- Bold text -->
**To make text bold**

<!-- Italic text -->
*To make text italic*

<!-- Blockquotes -->
> This is a blockquote.
>> Nested blockquotes.
>>> More nesting.

<!-- Markdown Underlined -->
<ins>This is an underlined text</ins>

<!-- Strike through text -->
~~This is strike through text~~

<!-- Inline Link -->
[Link1](https://www.interviewbit.com/practice/)

[A relative Link]({{ site.baseurl }}/contact-us)
<!-- Image -->
![alt text](https://d3n0h9tb65y8q.cloudfront.net/public_assets/assets/000/002/559/original/Inline_Style.png?1642758105)


<!-- ordered lists -->
1. Level 1 ordered list
    1. Level 2
        - Level 3
            - Level 4
2. Level 1
    1. Level 2
3. Level 1
    1. Level 2

<!-- unordered lists can be created with an asterisk(*), (+), or (-) signs  -->
* Element 1 unordered list
* Element 2
* Element 3

<!-- Nested unordered list -->
- Level 1
    - Level 2
        - Level 3
            - Level 4
- Level 1
    - Level 2
- Level 1
    - Level 2


| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text | 

<!-- Markdown Boxed -->
<table>
<tr>
<td>The table first row definition.</td>
<td>The table first row definition.</td>
<td>The table first row definition.</td>
</tr>
<tr>
<td>The table second row definition.</td>
<td>The table second row definition.</td>
<td>The table second row definition.</td>
</tr>
</table>

```
This is an
example of
multiline code block.
```
<!-- Task Lists -->
- [x] Buy Eggs.
- [ ] Buy Milk.
- [ ] Wash Clothes.


<!-- Horizontal line -->
_____________________________________________________________________________


*Asterick








<!-- NoT -->
{% unless site.button-heading == 'submit' %}
Hey, Unless!(If not true, then it will do something)
{% endunless %} 

<!-- switch case -->
{%  case handle %}
{% when 'cookie' %}
This is a cookie.
{% when 'cake' %}
This is a cake.
{% else %}
This is not a cookie/cake.
{% endcase %}