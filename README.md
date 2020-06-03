# Practicing bootstrap

The attached html and css files are how I got started with bootstrap. I followed a youtube tutorial by [Coding Addict](https://www.youtube.com/channel/UCMZFwxv5l-XtKi693qMJptA). Their tutorial is awesome if some one is just new to bootstrap. You can follow [this link](https://www.youtube.com/watch?v=Uhy3gtZoeOM) for their youtube tutorial.

Following below is my some documentation on the same:

- [What is bootstap](https://github.com/tanishabisht/Bootstrap-Practice#What-is-bootstap)
- [How do we get or download bootstrap!!!](https://github.com/tanishabisht/Bootstrap-Practice#How-do-we-get-or-download-bootstrap!!!)
- [Lets Bootstrap](https://github.com/tanishabisht/Bootstrap-Practice#Lets-Bootstrap)
  - [Margin and padding](https://github.com/tanishabisht/Bootstrap-Practice#Margin-and-padding)
  - [Flexbox using bootstrap](https://github.com/tanishabisht/Bootstrap-Practice#Flexbox-using-bootstrap)


## What is bootstap 

If we seach on wikipedia we get this:

> Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains CSS- and (optionally) JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components.

Well put simply for beginners it could be called a library of css classes and javascript pluggins.



## How do we get or download bootstrap!!!

Not much of a great deal for starters we could just paste these in the head tag of our html file.

```
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
```


## Lets Bootstrap 

Ok so basically bootstrap uses this grid system. Every row could be said to be divided into 12 coloumns. 

1. container
2. container-fluid
3. row
4. col



### Margin and padding

1. uses rem values (1 rem = 16 px)
2. margin-left: ml
3. mx-5; left and right margin
4. my-5; top and bottom margin



### Flexbox using bootstrap

1. d-flex class (only direct children)
2. justify-content-start|end|between|around|center (horizontal)
3. align-items-start|end|between|around|center (vertical) 
4. rows are by default parent flexbox container 