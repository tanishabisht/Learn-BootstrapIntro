# Learn - Bootstrap Layout

This README document explains how to get started with Bootstrap, a popular CSS framework that aids in creating responsive and mobile-first websites. It follows a tutorial by [Coding Addict on YouTube](https://www.youtube.com/watch?v=Uhy3gtZoeOM), which is particularly helpful for beginners.

**Bootstrap** includes pre-designed CSS classes and optional JavaScript plugins that can be used to style and interact with various elements like forms, buttons, navigation bars, and other interface components.

## How to Obtain Bootstrap
To use Bootstrap, you can simply include its CSS and JavaScript files in your HTML document by linking to them in the `<head>` section of your HTML file.

```html
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
```


## Grid in Bootstrap
Bootstrap’s layout is based on a grid system, where each row is divided into 12 columns. This makes it easier to place and align content in a structured way.
- `container` and `container-fluid` for setting the maximum width of the content.
- `row` to define a horizontal group of columns.
- `col` to specify column sizes inside rows.


## Flexbox in Bootstrap
- **Flex Container:** Use `d-flex` to create a flex container. `row` is by default parent flexbox container 
- **Alignment:** Control the alignment of flex items using classes like `justify-content-start|end|between|around|center (horizontal)`, `align-items-start|end|between|around|center (vertical)`, etc., to set the alignment along the horizontal or vertical axis.


## Margin and Padding
Bootstrap uses 'rem' units for margins and paddings (where 1 rem equals 16 pixels). For margins, you can use classes like `ml` for margin-left, `mx-5` for horizontal margins, and `my-5` for vertical margins.