# Pasta CSS 

<center>
    <img src = "https://github.com/manushifva/pasta-css/blob/master/images/pasta.png?raw=true" style = "width: 200%; height: 200%;">
</center>

Pasta CSS is a simple CSS set for a website. Works well with Bootstrap, and Font Awesome.

## Usage
1. At first, clone this repo. 
2. Add the depedencies to your HTML: 

    `<link rel = "stylesheet" href = "/path/to/pasta.css">`

    Or, you can use the jsDelivr CDN: 

    `https://cdn.jsdelivr.net/gh/manushifva/pasta-css@master/pasta.css`

## Class list

Category: 
- [Button](#button)
- [Form and popup](#form-and-popup)
- [Header](#header)
- [Heading](#heading)
- [Label and input](#label-and-input)
- [Loader bar](#loader-bar)
- [Table](#table)

### Category: Button <a id = "#button"></a>
### `button`
Create a button.

### `long`
Optional attribute for button. Make the button fill 100% available space.

### `big`
Optional attribute for button. Make the button fill 50% bigger.

### `border`
Optional attribute for button. Make the button transparent, show the border only, Available only for dark-theme.

### `red`
Optional attribute for button. Set the red as button's background color.

### `green`
Optional attribute for button. Set the green as button's background color.

### Category: Form and popup <a id = "#form-and-popup"></a>
### `form`
Create a form.

### `popup`
Create a popup. Popup willn't shown if it doesn't has `toggle` class.

    ### `header`
    Create a popup header. Only works if the parent is `popup`.

    ### `content`
    Create a content header. Only works if the parent is `popup`.

### Category: Header<a id = "#header"></a>
### `header`
Create a header
    ### `header-menu`
    Create a parent for `header-menu-content`. Only works if the parent is `header`.

        ### `header-menu-content`
        Create a header menu. Only works if the parent is `header-menu`.

### `transparent`
Optional attribute for header. Make the header background transparent.

### Category: Heading <a id = "#heading"></a>
### `h1`
H1 Tag alias.

### `h2`
H2 Tag alias.

### `h3`
H3 Tag alias.

### `h4`
H4 Tag alias.

### `h5`
H5 Tag alias.

### `h6`
H6 Tag alias.

### Category: Label and input<a id = "#label-and-input"></a>
### `label`
Create a input label.

### `input`
Create a input form.

    ### `icon`
    Create a input icon. Only works if the parent is `input`.

### `input-box`
Create a padding box. 

### `fill`
Optional attribute for input-box. Make the input-box background filled.

### Category: Loader bar<a id = "#loader-bar"></a>
### `loader-bar`
Create a loader bar.
    ### `loader child`
    Create a loader child. Only works if the parent is `loader-bar`.    

### Category: Table<a id = "#table"></a>
### `table`
Create a table.

## Credit
Font: Nunito, by Vernon Adams, Cyreal
