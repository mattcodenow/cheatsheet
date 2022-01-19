# Cascading Stylesheets (CSS)
[<< Back To Home](../README.md)

## Basics

### Syntax
```css
selector {
  attribute: value;
  attribute2: value2;
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
      attribute: value;
      attribute2: value2;
    }
  </style>
</head>
```