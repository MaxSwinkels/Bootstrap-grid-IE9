# Bootstrap 4 Grid for IE9

Bootstrap 4 drops the support of Internet Explorer 9 and becomes fully flexbox where the grid system does not work in IE9. Adding this conditional CSS makes the site functionally workable again in IE9.

### Usage

1. Add the following conditional statements to the <head> of your page but after the Bootstrap 4 CSS:
```
<!--[if IE 9]>
  <link href="/css/bootstrap-grid-ie9.css" rel="stylesheet">
<![endif]-->
```

