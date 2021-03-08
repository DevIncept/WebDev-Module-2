
## Topic :-  So here we will be looking at **FLEXBOX PROPERTIES** 

<br>

<br>

#  ***PROPERTY FOR PARENT*** 
<br>

## *Display Property* 

<br>

This defines a flex container; inline or block depending on the given value

```css
.main{
    display:flex;
}
```
<br>




<br> 

<br>

## *Flex-direction Property* 

<br>

It defines the direction of flex the container items should be in row or coloumn

```css
.main{
    flex-direction: row | column;
}
```
<br>



<br>

<br>

## *Flex-Wrap Property* 

<br>

In this flex items will try to fit in one line. We can change that and allow the items to wrap as needed with this property.

- **nowrap :-** All items will be on one line
- **wrap :-**  flex items will wrap onto multiple lines, from top to bottom.

```css
.main{
    flex-wrap: nowrap | wrap;
}
```
<br>



<br>

<br>

## *Justify-Content Property* 

<br>

This defines the alignment along the main axis. It helps distribute extra free space that is leftover 

- **flex-start :-** Items are placed toward the start of the flex-direction.
- **flex-end :-** Items are placed toward the end of the flex-direction.
- **center :-** In this the Items are centered along the line

```css
.main{
    justify-content: flex-start | center;
}
```
<br>



<br>


**[Reference](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) Checkout this link for more Properties** :link:

<br>

<br>

<br>


#  ***PROPERTY FOR CHILD*** 

<br>


## *Order Property* 

<br>


The order property controls the order in which the items appear in the flex container.

```css
.item{
    order:3;
}
```
By default the order is Zero

<br>



<br>

<br>


## *Flex-Grow Property* 

<br>


This defines the ability for a flex item to grow if necessary

```css
.item{
    flex-grow:3;
}
```
Negative numbers are Invalid

<br>



<br>

<br>

## *Align-Self Property* 

<br>


This allows the default alignment to be overridden for individual flex items.

```css
.item{
    align-self: center | auto;
}
```

<br>

<br>



<br>


**[Reference](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) Checkout this link for more Properties** :link:

<br>

<br>
