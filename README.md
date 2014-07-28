pyramidcss
==========

Ultra flexible grid system where you can use columns of all sizes (until 960 pixels and 100%).

### Install

Just include the pyramid.css or pyramid.min.css in your head.

*If using Bootstrap, after Bootstrap CSS link*

```
<link href="<path-to-file>/pyramid.min.css" type="text/css" rel="stylesheet" /> 
```

### Example
Lets build a simple structure with a left sidebar en two columns of 50%.

``` HTML
<div class="container">
  <div class="row">
    <div class="col-md-x-180 col-xs-x-60 gutter-xs-20 sidebar">
      .. sidebar / with gutter ..
    </div>
    <div class="col-xs-p-50 gutter-xs-20 left-column">
      .. left column / with gutter ..
    </div>
    <div class="col-xs-p-50 right-column">
      .. right column / no gutter ..
    </div>
  </div>
</div>
```

