# CSS
CSS rules

A CSS rule uses selectors followed by one or more declarations, as shown in the following figure:

![image](https://cloud.githubusercontent.com/assets/7290124/23862868/74ccffb0-080e-11e7-91be-4cf558e72fa8.png)

Selectors can be any of the following:

#Type Selector:

These are represented by the name of a specific HTML element. They are used
to select all specific types of an element in a document—for example:
```CSS
body {color: red}
```
#Class Selector:

Each HTML can be assigned a class using the class attribute. You then assign
a name to it that can be accessed by CSS—for example:
```CSS
<h1 class="mytitle">This is a header</h1>
```
To apply one style to the class declared in HTML in the tag header, you precede the name of the class
with a period (.):
```CSS
.mytitle {font-family: Verdana}
```
#ID Selector:
Each HTML element can be assigned an ID, which is a unique reference for this
element in the document—for example:
```CSS
<section id="mystyle"></section>
```
To select an element that has been assigned a certain ID in CSS, you add the pound key (#) before the
value of the ID:
```CSS
#mystyle {color: black}
```
