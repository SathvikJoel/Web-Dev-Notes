# CSS

---

**Cascading Style Sheets**

## Inline CSS

There is a style attribute in HTML that can style that particular element

Eg:

```HTML
<body style="background-colur: blue">
...
</body>
```

This way of styling is more hectic and error prone

## Internal CSS

By default all the elements in HTML are styled with the defualt style of the browser [Find default style here](https://www.w3schools.com/cssref/css_default_values.asp)


Style could be applied to elements by using the `style` tag in the head section

```HTML
<head>
<style>

hr{
    background-color: red;
}
<!---
This chanegs all the he elements in the page to red
--->
</style>
</head>
```

> All the elements in the HTML are essentially boxes

## External CSS

You can place the style of the code in seperate file and link it to the HTML file

**To Link** :

```HTML
<head>
<link rel="stylesheet" href="css/styls.css">
</head>
```
**In styles.css**

```
Place all the styling in your external css file
```

The order of priority is :

> id selectors > class selectors Inline CSS > Internal CSS > External CSS

**The best practise is to use external CSS**

## CSS Syntax

```
selector {property : value ;}
```
**selector** : Who?

**property**: What?

**value**: How?

Note: It is recommended to place the properties in alphabetical orders

The list of exhaustive CSS properties can be found here : [CSS Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

## CSS Class Selectors

Every HTML tag has a `class` attribute 

You can use this to style only the elements that have the same class

A html tag can have multiple classes seperated by space

```HTML
<h1 class="class1 class2">
This is a heading
</h1>
```
It will be styled according to both the classes

**CSS Syntax**

(assume that there is a class called bacon)
```
.bacon{
    color:red;
}
```

Divide the style sheets into two parts : 
1. `TAG SELECTORS`
2. `CLASS SELECTORS`

## CSS Comments

`/* This is a comment */` 

## `class` vs `id`

1. There can only be one html element with a given `id` name whereas there can be multiple tags with the same `class` name

2. A given `html` element can have multiple `class` names but only one `id` name

**CSS Syntax**
```
#heading {
    color: red;
}
```
## CSS Pseudo-Classes

HTML elements can have states like : hover, i.e., The state of the HTML tag when it is hovered.

**CSS Syntax**
```
img:hover{
    border: 1px solid red;
}
```

This will decide the style of the image when it is hovered

