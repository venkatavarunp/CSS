# CSS
## CSS Selectors
elements can be selected by
- element 
- class name (can be used to apply styles for multiple elements and can be reused)
- by id (can only be declared once and cannot be used again)
```css
h1{
    /* styles */
}

.class{
    /* styles */
}

#id{
    /* styles */
}
```
To style a particular element inside an element we can use 
```css
article header p{
    /* styles */
}
```
## psuedo classes
to select particular elements we can use psuedo classes
```css
li:first-child {
  font-weight: bold;
}
li:last-child {
  font-style: italic;
}
li:nth-child(even) {
  color: red;
}
```
# Layouts
## Absolute Position
To place an element with respective to an elementwe can use Position absolute 
```css
.cart {
  position: relative;
}
.cart::after {
  content: "5";
  position: absolute;
  top: -5px;
  left: 30px;
}
```
value 5 is position relative to cart class element
## Psuedo Elements 
CSS can help us to interact with elements using Psuedo elements
```
h1::first-letter{
  /*styles*/
}
h1::first-line{
  /*styles*/
}
h1::before{
  /*styles*/
}
h1::after{
  /*styles*/
}
```
## FlexBox
used for building 1 dimension layouts 
![image](https://github.com/venkatavarunp/CSS/assets/130353146/e42a18b8-08f1-4e84-a177-d59cc4478e74)


