# Bootstrap 4 Grid for IE9

Bootstrap 4 drops Internet Explorer 9 support and goes full flexbox whereby the grid system is not working in IE9, but you can add it back by simply adding this conditional CSS.

### Usage

1. Add the following conditional statements to the <head> of your page but after the Bootstrap 4 CSS:
```
<!--[if IE 9]>
  <link href="/css/bootstrap-grid-ie9.css" rel="stylesheet">
<![endif]-->
```

