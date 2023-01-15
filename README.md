# my_Markdown
Resources that I usually use here in Markdown GitHub :)


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



https://docs.github.com/es/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections

---
✏❤ **@ferjml97** 
