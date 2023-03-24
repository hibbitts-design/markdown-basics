# Markdown


## What is Markdown? 
Markdown is a syntax to format the display of content stored as plain text - similar but simpler than HTML formatting


## Why Markdown? 

* System-independent
* Text only format (perfect for version control)
* Separation of content vs. presentation
* Human-readable (i.e. more than HTML)
* Can also contain HTML snippets

## Markdown Examples


### Headings

Headings from `h1` through `h6` are constructed with a `#` for each level:

<h1> # h1 Heading </h1>
<h2> # h2 Heading </h2>
<h3> # h3 Heading </h3>
<h4> # h4 Heading </h4>
<h5> # h5 Heading </h5>
<h6> # h6 Heading </h6> 


### Horizontal Rule

---


### Emphasis

**This is bold text**

__This is also bold text__

*This is italic text*

_This is also italic text_

~~Strikethrough~~


### Blockquotes


> This is an example Blockquote.


### Lists

Unordered

- Create a list by starting a line with `-`, or `*`
- Sub-lists are made by indenting 2 spaces:
  - So this is a sub-list item!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


### Code

Inline `code`

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

### Tables

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


### Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica

[link to another Markdown file](/another-markdown-file.md)


### Images

![Minion](https://octodex.github.com/images/pusheencat.png)
