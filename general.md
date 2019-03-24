---
test page for markdown
---

Table of Contents
(`Cmd+Shift+P` -> `Create TOC`)
<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [h1 Heading](#h1-heading)
	- [h2 Heading](#h2-heading)
		- [h3 Heading](#h3-heading)
			- [h4 Heading](#h4-heading)
				- [h5 Heading](#h5-heading)
					- [h6 Heading](#h6-heading)
	- [Horizontal Divs](#horizontal-divs)
	- [Emphasis](#emphasis)
	- [Blockquotes](#blockquotes)
	- [Lists](#lists)
	- [Todo](#todo)
	- [Code](#code)
	- [Tables](#tables)
	- [Links](#links)
	- [Images](#images)
	- [LaTeX Math Equations](#latex-math-equations)

<!-- /code_chunk_output -->


# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Divs

___

---

***


## Emphasis

`Cmd+B` to make bold
**This is bold text**
__This is also bold text__

`Cmd+I` to make italic
*This is italic text*
_This is also italic text_

`Alt+S` to make strikethrough
~~Strikethrough~~


## Blockquotes

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.
> > > 1. syntax can be **inserted** in blockquotes 


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


4. You can use sequential numbers...
5. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Todo

`Alt+C` to check/uncheck

- [x] milk
- [ ] apple


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```


## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)


## Images

![Minion](https://octodex.github.com/images/minion.png)


## LaTeX Math Equations

`Cmd+M` to insert inline equations (double: display)

inline: 
$x^n + y^n = z^n$ 
$\omega=d\phi / dt$

display:
$$ I = \int \rho R^{2} dV $$

align:

$$\begin{array}{rcl} f: R^3 & \to & R \\ (x,y,z) & \to & x + y + z \\ f(x,y,z) & = & x + y + z \end{array}$$

$$\begin{array} {lcl} f(x) & = & (a+b)^2 \\ & = & a^2+2ab+b^2 \end{array}$$

matrix:

$$\left| \begin{array}{cc} x_{11} & x_{12} \\ x_{21} & x_{22} \end{array} \right|$$

$$\begin{bmatrix} 0 & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & 0 \end{bmatrix}$$