# HTML

----

> HTML = HyperText Markup Language
>
> Use mdn documentation for more info on HTML
> 
> w3schools.com also has good tutorials
> 
> devdocs.io also has good tutorials

## HTML Quick Commands

### Basic Tags



### Text Tags

| Syntax      | Description |
| :-----------: | :-----------: |
| `<em> </em>` | Italics, Emphasis |
| `<strong> </strong>` | Bold, Strong | 
| `<h1> </h1>` -- `<h6> </h6>` | Headings |



### Links



### Formatting


| Syntax      | Description |
| :-----------: | :-----------: |
| `<p> </p>` | Paragraph | 
| `<br> </br>` | Line Break |


### Lists


### Graphical Elements

| Syntax      | Description |
| :-----------: | :-----------: |
| `<hr> </hr>` | Horizontal Rulr | 

### Forms


### Tables



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


