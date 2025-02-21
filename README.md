# MarkdownDemo
A basic demonstration on using Markdown in GitHub

## Hello, welcome to my demonstration on how to do markdown. 👋
You will learn the most basic things about Markdown. 👔

*******
### Table of Contents
1. [What is Markdown?](#whatismarkdown)
2. [Why use Markdown?](#why)
3. [Markdown Syntax](#syntax)
*******

<div id='whatismarkdown' />

## What is Markdown ? 🤔
Markdown is used extensively for formatting content on the GitHub platform.
It is a lightweight markup language designed to simplify the process of formatting text, making it easy to read and write in its raw form while still being convertable to HTML or other rich text formats. This syntax allows writers to focus more on content and less on its presentation, making it particularly popular in web development, content writing, and technical documentation.

`SIMPLY: IT'S JUST ANOTHER TYPE OF TEXT FILE, LIKE .txt .doc ....( now it's .md) AND IT HAS SOME SPECIAL SYNTAX.` 

<div id='why' />

*There is no clearly defined Markdown standard. This has led to fragmentation as different vendors write their own variants of the language to correct flaws or add missing features...*

This demonstration will mainly focus on GitHub flavored Markdown.

## Why use markdown ? ¯\\__(ツ)_/¯
Because it's:
* **EASY** : The syntax is so easy that you can learn in a minute or two then write without noticing anything weird or geeky.
* **FAST** : It saves time compared to other types of text files/formats. It helps boost the productivity and workflows of writer.
* **CLEAN** : Both the syntax and output are clean, not messy with our eyes and simple to manage.
* **FLEXIBLE** : With just a little set-up, your text will be translated cross any platform out there, editable in any text-editing software and convertible to a wide array of formats.
<br></br>
**In short**, normal users will find it useful in any cases, especially when you are in need of something better than plain text but less functional than Microsoft Word.
<br></br>
**For Developers**, if you are lazy to write HTML code , you will love markdown. **Moreover**, **Github** and many sites favor markdown for readme file of projects. That means you gonna meet markdown in your life one way or another.

<div id='syntax' />

## Markdown Syntax #️⃣
All Syntax can be found [here](https://daringfireball.net/projects/markdown/syntax) . It would take a lot of effort to describe syntax in text (they will be formatted) so please consider this table below for the whole basics syntax.

| Format        | Syntax      | Example |
| ------|-----|-----|
| Italic  	| \*Text\* 	| *This is italic* 	|
| Bold  	| \*\*Bold\*\* 	| **This is bold** 	|
| Inline links 	| \[Description text\](url here) 	| A [link](http://www.github.com) 	|
| Images 	| \![Caption\](url to img) 	| An image ![image](https://i.imgur.com/vUiouM8.png)	|
| Link+images 	| \[\![Caption\](url to img)\](url to a page)\] 	| Click me [![me](https://i.imgur.com/vUiouM8.png)](https://www.github.com) 	|
| Footnotes  	| I have more \[^1\] to say.   \[^1\]: say it down here. 	| <a href="#section1">Hey,Please read the note below this table.  	|
| Line breaks 	| Double space + enter 	|  	|
| Unordered Lists 	| \* Item1     \*Item 2 	| <ul><li>item1</li><li>item2</li><li>item3</li><li>item4</li></ul> 	|
| Ordered Lists 	| 1. Item a    2. Item b 	| <ol><li>itema</li><li>itemb</li><li>itemc</li><li>itemd</li></ol>  	|
| Mixed Lists 	| 1. Item 1      * item 1a 	|  <ol><li>itema</li></ol><ul><li> item1</li></ul>	|
| Block quote 	| \> Quoted text 	|  <blockquote>Stay Hungry Stay Foolish</blockquote> 	|
| Preformatted 	| Begin each line with,two spaces or more to,make text look,e x a c t l y,like,you,type i,t. 	|   Begin each line with,two spaces or more to,make text look,e x a c t l y,like,you,type i,t. 	|
| Code 	| \`Insert Code\` 	| `cout<<"Hello world";` 	|
| Code block/ Syntax highlighting 	| \`\`\`insert code\`\`\` 	|  <a href="#section1">Hey,Please read the note below this table. 	|
| Headers 	| \#, \##, \###, \####, \#####, \###### (from h1 to h6) 	| <h1>This is a h1 header</h1> <h2>This is a h2 header</h2> <h3>This is a h3 header</h3> <h4>This is a h4 header</h4> <h5>This is a h5 header</h5> <h6>This is a h6 header</h6>	|
| Strike through 	| \~\~Insert text here\~\~ 	| ~~I am dead~~ 	|
| Tables 	| \| Tables   \|      Are      \|  Cool \| \|\----------\|\:\-------------\:\|------\:\| \| col 1 is\|  left-aligned \| $1600 \| | ![](http://i.imgur.com/EItt7mh.png) |
|Footnotes| Footnote[\^1\] <br> [\^1\]: Text reference | Here is a simple footnote[^1]. With some additional text after it. | 
[^1]: My footnote reference.

<br></br>
<p id="section1">Note: **Footnote** actually doesnt render properly in table, but it kinda looks like this</p>

![](http://i.imgur.com/pmeBr28.png)
<br></br>
The same goes for **block code/syntax hightlighting**. It kinda looks like this picture :

![](http://i.imgur.com/z8KrxAz.png).

These characteristics are dependent upon each markdown flavor.  

<br></br>

### Details
This isn't a markdown thing but it is another example of using HTML tags in a Markdown file. It has the same effect as an accordian.
<details>
  <summary>Title 1</summary>
  <p>Some hidden content goes here</p>
</details>
<details>
  <summary>Title 2</summary>
  <p>Same stuff here</p>
</details>

```html
<details>
  <summary>Title 1</summary>
  <p>Some hidden content goes here</p>
  Here is some more without a paragraph tag
</details>
<details>
  <summary>Title 2</summary>
  <p>Same stuff here</p>
</details>
```

## Useful notes 📋 :
* Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown’s formatting syntax. One commonly used backslash escape character is : \
`So? \*This\* isnt italic  anymore but is surrounded by literal asterisks.`
* Markdown does support Emojii :laughing: :laughing: :kissing_heart: :innocent: :green_heart: ( get some emojies [here](http://www.emoji-cheat-sheet.com/) )
* You can use \<br/> tag to force line break.
* Double space then enter if you want to make a new line if there is trouble making new lines.
* Any URL (like http://www.github.com/) will be automatically converted into a clickable link.

<br></br>
<br></br>

## Question Time ❔
<details>
  <summary>What syntax is used to create a heading in Markdown?</summary>
  Headings are created using the hash symbol (#), with the number of hashes indicating the heading level.
</details>

<details>
  <summary>What syntax is used to create bold text in Markdown?</summary>
  Bold text is created by wrapping text with double asterisks on both beginning and end of the text.
</details>

<details>
  <summary>What syntax is used to create italic text?</summary>
  Italic text is created by wrapping text with a single asterisk on both beginning and end of the text.
</details>

<details>
  <summary>TRUE or FALSE : Markdown allows you to create tables without using HTML.</summary>
  TRUE. Standard Markdown and GitHub Flavored Markdown support table creation using pipe symbols (|) to separate columns and hyphens (-) to create the header row.
</details>

<details>
  <summary>TRUE or FALSE : There is a defined Markdown standard for GitHub flavored Markdown.</summary>
  FALSE. There is no clearly defined Markdown standard.
</details>
