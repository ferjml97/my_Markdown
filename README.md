# my_Markdown
Resources that I usually use here in Markdown GitHub :)

### Basic writing and formatting syntax
#### Headings

To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the size of the heading.

# The largest heading
## The second largest heading
###### The smallest heading

#### Styling text
You can indicate emphasis with bold, italic, strikethrough, subscript, or superscript text in comment fields and .md files.

Style	Syntax	Keyboard shortcut	Example	Output
Bold	** ** or __ __	Command+B (Mac) or Ctrl+B (Windows/Linux)	**This is bold text**	This is bold text
Italic	* * or _ _     	Command+I (Mac) or Ctrl+I (Windows/Linux)	*This text is italicized*	This text is italicized
Strikethrough	~~ ~~		~~This was mistaken text~~	This was mistaken text
Bold and nested italic	** ** and _ _		**This text is _extremely_ important**	This text is extremely important
All bold and italic	*** ***		***All this text is important***	All this text is important
Subscript	<sub> </sub>		<sub>This is a subscript text</sub>	This is a subscript text
Superscript	<sup> </sup>		<sup>This is a superscript text</sup>	This is a superscript text

### Quoting code
You can call out code or a command within a sentence with single backticks.  
The text within the backticks will not be formatted.  
You can also press the Command+E (Mac) or Ctrl+E (Windows/Linux) keyboard shortcut  
to insert the backticks for a code block within a line of Markdown.

Use `git status` to list all new or modified files that haven't yet been committed.
Rendered inline code block

To format code or text into its own distinct block, use triple backticks.

Some basic Git commands are:
```
git status
git add
git commit
```

Supported color models
In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.
Rendered supported color model.

Here are the currently supported color models.

Color	Syntax	Example	Output
HEX	`#RRGGBB`	`#0969DA`	Rendered supported color model in HEX format.
RGB	`rgb(R,G,B)`	`rgb(9, 105, 218)`	Rendered supported color model in RGB format.
HSL	`hsl(H,S,L)`	`hsl(212, 92%, 45%)`	Rendered supported color model in HSL format.




### Adding a quote
Markdown has many other options for formatting your content.  
Here, you'll add a horizontal rule to divide your page and a blockquote to format your favorite quote.

> QUOTE

### Align
<p align="center">
  <a href="https://rahuldkjain.github.io/gh-profile-readme-generator">
    <img alt="GitHub Profile Readme Generator" src="./src/images/mdg.png" width="60" />
  </a>
</p>


### Bottons

[`CONTRIBUTING`](CONTRIBUTING.md)

With table...

### Code

```sql
  SELECT Put you code
```


### Index

<details><summary>EXAMPLE</summary>
<p>

### Index
- [Description 1](https://link.com)  
- [Description 2](https://link.com)  
- [Description 3](https://link.com)  
  - [Description 3.1](https://link.com)  
  - [Description 3.2](https://link.com)  
  - [Description 3.3](https://link.com)  
  - [Description 3.4](https://link.com)  
  
---

CODE MARKDOWN:

```
### Index
- [Description 1](https://link.com)  
- [Description 2](https://link.com)  
- [Description 3](https://link.com)  
  - [Description 3.1](https://link.com)  
  - [Description 3.2](https://link.com)  
  - [Description 3.3](https://link.com)  
  - [Description 3.4](https://link.com)  
```

</p>
</details>

---

### Tables

<details><summary>EXAMPLE</summary>
<p>

<div align = "center">
<table>
  <tr><th> <b> Consultas </b> </th></tr>
  <tr><td>
    
  | N° | Reporte | Check|
  |:---:|:---:|:---:| 
  | 1 | Clientes que han comprado más en valor.  | ✔️ |
  | 2 | Clientes que han comprado más en cantidad.  | ✔️ |
  | 3 | Productos más vendidos en valor.  | ✔️ |
  | 4 | Productos más vendidos en cantidad.  | ✔️ |
  | 5 | Productos menos vendidos en valor.  | ✔️ |
  | 6 | Productos menos vendidos en cantidad.  | ✔️ |
  | 7 | Valor de las ventas agrupadas por mes.  | ✔️ |
  | 8 | Valor de las ventas agrupadas por producto y mes.  | ✔️ |

</table>
Tabla 2. Consultas </br> </br>
</div>

CODE MARKDOWN:

```
<div align = "center">
<table>
  <tr><th> <b> Consultas </b> </th></tr>
  <tr><td>
    
  | N° | Reporte | Check|
  |:---:|:---:|:---:| 
  | 1 | Clientes que han comprado más en valor.  | ✔️ |
  | 2 | Clientes que han comprado más en cantidad.  | ✔️ |
  | 3 | Productos más vendidos en valor.  | ✔️ |
  | 4 | Productos más vendidos en cantidad.  | ✔️ |
  | 5 | Productos menos vendidos en valor.  | ✔️ |
  | 6 | Productos menos vendidos en cantidad.  | ✔️ |
  | 7 | Valor de las ventas agrupadas por mes.  | ✔️ |
  | 8 | Valor de las ventas agrupadas por producto y mes.  | ✔️ |

</table>
Tabla 2. Consultas </br> </br>
</div>
```

</p>
</details>

---

### Creating Mermaid diagrams

Mermaid is a Markdown-inspired tool that renders text into diagrams.  
For example, Mermaid can render flow charts, sequence diagrams, pie charts and more.  
For more information, see the Mermaid documentation.

To create a Mermaid diagram, add Mermaid syntax inside a fenced code block with the mermaid language identifier.  
For more information about creating code blocks, see "Creating and highlighting code blocks."

For example, you can create a flow chart:

<details><summary>EXAMPLE</summary>
<p>

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

CODE MARKDOWN:

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

</p>
</details>

---

### Creating a collapsed section

You can temporarily obscure sections of your Markdown by creating a collapsed section that the reader can choose to expand.  
For example, when you want to include technical details in an issue comment that may not be relevant or interesting to every reader,  
you can put those details in a collapsed section.

Any Markdown within the <details> block will be collapsed until the reader clicks  to expand the details.  
Within the <details> block, use the <summary> tag to create a label to the right of .

<details><summary>EXAMPLE</summary>
<p>
<details><summary>CLICK ME</summary>
<p>

#### We can hide anything, even code!

```ruby
   puts "Hello World"
```

</p>
</details>


CODE MARKDOWN:

```
<details><summary>CLICK ME</summary>
<p>

#### We can hide anything, even code!

```ruby
   puts "Hello World"
```

</p>
</details>

```
</p>
</details>


https://docs.github.com/en/get-started/writing-on-github
https://docs.github.com/es/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections

---
✏❤ **@ferjml97** 
