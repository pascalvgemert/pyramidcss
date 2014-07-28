pyramidcss
==========

Ultra flexible grid system where you can use columns of all sizes (until 960 pixels and 100%).

I started Pyramid CSS as a new grid system to use pixels and percentages in the same row.
This idea is freshly baked in CSS code, so feedback / optimalizations are welcome.

You can also contact / follow me on twitter:
[@pascalvgemert](http://www.twitter.com/pascalvgemert)

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

### Usage

Use `col-sm-x-..` for pixel width's (*0px* until *960px* in steps of *10px*).  
Use `col-sm-p-..` for percentage width's (*0%* until *100%* in steps of *5%*).  
Use `xs`, `sm`, `md` and `lg` for responsiveness, just like Bootstrap.  
Use `gutter-sm-..` for gutter width's (*0px* until *60px* in steps of *10px*).  
Use `hide-sm` or `show-sm` for showing and hiding for responsive matters.
Use `clear-sm` to reset the columns.
