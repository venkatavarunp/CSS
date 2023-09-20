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
