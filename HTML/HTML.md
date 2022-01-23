# HTML

----

> HTML = HyperText Markup Language
>
> HyperText means that text is linked between pages
>
> Use mdn documentation for more info on HTML
> 
> w3schools.com also has good tutorials
> 
> devdocs.io also has good tutorials

## HTML Quick Commands

---

### Basic Tags



### Text Tags

| Syntax      | Description |
| :-----------: | :-----------: |
| `<em> </em>` | Italics, Emphasis |
| `<strong> </strong>` | Bold, Strong | 
| `<h1> </h1>` -- `<h6> </h6>` | Headings |



### Links

| Syntax      | Description |
| :-----------: | :-----------: |
| `<a> </a>` | Anchor Tag |
| `<a href="URL"> </a>` | Create a hyperlink to a URL, either a URL on internet or another HTML page |

### Formatting


| Syntax      | Description |
| :-----------: | :-----------: |
| `<p> </p>` | Paragraph | 
| `<br>` | Line Break |


### Lists

| Syntax      | Description |
| :-----------: | :-----------: |
| `<ul> </ul>` | Unordered List(ul) |
| `<li> </li>` | Encompasses each List Item(li) |
| `<ol start=? type=?> </ol>` | Ordered list(ol) with type and start number |

### Graphical Elements

| Syntax      | Description |
| :-----------: | :-----------: |
| `<hr> </hr>` | Horizontal Rulr | 
| `<img src=? alt=?>` | Image `alt`: Alternate Text  |

### Forms


### Tables

| Syntax      | Description |
| :-----------: | :-----------: |
| `<table> </table>` | Table |
| `<tr> </tr>` | Table Row to be used in `Head`, 'Body|
| `<td> </td>` | Table cell to be used in `Table row` |
| `<thead> </thead>` | Table Header |
| `<tbody> </tbody>` | Table Body |
| `<tfoot> </tfoot>` | Table Footer |
| `<th> </th>` | Table cell to be used in `Table Header` |

### A Typical Table in HTML

```HTML
<table>
    <thead>
      <tr>
        <th>Heading1</th>
        <th>Heading2</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>(1,1)</td>
        <td>(1,2)</td>
      </tr>
      <tr>
        <td>(2,1)</td>
        <td>(2,2)</td>
      </tr>
    </tbody>
  </table>
```

* `<thead>`, `<tbody>`, `<tfoot>` are optional but recommeded to use since later we can style them seperately


## The Anatomy of HTML

```HTML
<h1>Hello World!</h1>
```

| Syntax      | Description |
| :-----------: | :-----------: |
| `<h1>`      | Start Tag   |
| `</h1>`     | End Tag     |
| `Hello World!` | Content  |


```HTML
<hr size="3">
```

| Syntax      | Description |
| :-----------: | :-----------: |
| `<hr>`      |  Tag   |
| `size="3"`     | HTML Attribute   |

* `<br>` is a `Self-closing tag`. It doesnt need a closing tag

* `Tag omission` describes whether end tag is needed or not in the documentation

* `attributes` are used to add extra information to the tag

* `<!--   -->` is a comment

## HTML Boilerplate code

```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    
  </body>
</html>
```
* look at [docs.emmet.io](docs.emmet.io/cheat-sheet) for more info on emmet and its code completion shortcuts

* `<!DOCTYPE html>` Document type declaration when the browser renders the code

* `<html> </html>` anything in between is considered html code

* The HTML code contains `<head>` and `<body>` tags

* `<head>` contains meta tags and other informationabout the page like meta, title, etc..

* Character set is used to endcode the text in the page and `utf-8` is standard for HTML 5

* The title is what the browser will diaplay in the tab of the browser

* There are a lot of other meta attributes that can be used to add extra information to the page that search engines use in a lot of ways
  
## Writing HTML

* Use proper indenting or use a package like `Atom Beautify` to make code look better

* 


