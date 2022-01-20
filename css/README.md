# Cascading Stylesheets (CSS)
[<< Back To Home](../README.md)

## Basics

### Syntax
```css
selector {
  property: value;
  property2: value2;
}
```

## Adding CSS To HTML

### External CSS Document
Adding an external .css file to an .html file inside the `head` tag:
```html
<head>
  <link rel="stylesheet" type="text/css" href="./path/to/styles.css" />
</head>
```

### Internal CSS Styles
Adding .css inside an .html file inside the `head` tag:
```html
<head>
  <style>
    selector {
      property: value;
      property2: value2;
    }
  </style>
</head>
```

### Inline CSS Styles
Add styling directly to an html tag using the `style` tag attribute:
```html
<div style="property: value; property2: value2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
```

## Images

### Perfect Background Image
Reference: [https://css-tricks.com/perfect-full-page-background-image/](https://css-tricks.com/perfect-full-page-background-image/)  
A background image that fills up the entire parent container, in this case the whole page using the `html` tag as a selector:
```css
html { 
  background: url(images/bg.jpg) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
```