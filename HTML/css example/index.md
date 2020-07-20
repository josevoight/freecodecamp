# class to style an element 
- ex: 
- <h2 class="blue-text"> CatPhotoApp </h2>

- to call it on the style block 
- ex: 
<style>
  .blue-text {
 </style>

# font size of an element 
- font size is controlled by tbe font-size css property 
- ex: 
h1 {
  font-size: 30px;
}



7/8/2020
# set the font family of an element 
ex: font-family: sans-serif; 

# import a basic Google font 
- google font is a free library font 
ex: <link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">

- this is the lobster font 

# size your image d
- width controls an element's width 
ex: 
<style>
  .larger-image {
    width: 500px;
  }
</style>

# add borders your elements 
- CSS borders have properties like style, color and width.
ex:
<style>
  .thin-red-border {
    border-color: red;
    border-width: 5px;
    border-style: solid;
  }
</style>

# add borders around your elements 
- border have properties like style, color and width.
  .thick-green-border{
    border-width: 10px;
    border-color: green;
    border-style: solid;
  

  7/12/2020
# add rounded corners with border-radius 
ex:
border-radius: 10px;

# make circular images with a border-radius 

- by using percent 
ex: border-radius: 50%;

# background color to a div element 
- by using background-color property 
ex: background-color: green;

# set the id of an element 
- addition to classes, we can also use the #id attribute 
- id attributes should be unique 
ex: id="cat-photo-form"

# using an id attributes to style an element 
- id is not reusable and should only be applied to one element 
- id has a higher important than class id ----> class 
ex: #cat-photo-element ---> to call an element 


# adjust the padding of an element 
- HTML are essentially little rectangles 
 3 properties control the space that surround each HTML element: 
 - padding 
 - margin 
 - border 
 ex: padding: 20px;

 # adjust the margin of an element 
 - margin controls the amount of space between an element border and surrounding elements 
 ex: margin: 20px;

 # add a negative margin to an element 
 - margin controls the amount of space between an element border and surrounding elements 
 - if you set marginto a negative value, then the element will grow larger 
 ex: margin: -15px;
 

 7/23/2020
 # add different padding to each side of an element 
 -  css allows us to control the padding of all four individual sides of an element with the 
 - padding-top, padding-right, padding-bottom, and padding-left properties.

 # different margins to each side of an element 
-  to control the margin of all four individual sides of an element with the margin-top, margin-right, margin-bottom, and margin-left properties.
- margin is used to create space around elements 

# use clockwise notation to specify the padding of an element 
- instead of calling each padding properties, we can specify them all in one line.'
ex: padding: 10px 20px 10px 20px;
- clock: top,right, bottom, and left 

# clockwise notation to specify the margin of an element
- same as padding 
ex: 40px 20px 20px 40px;
- top right bottom left

# use attribute selectors to style elements 
- [attr=value] --> attributes selector to style the checkboxes
- This selector matches and styles elements with a specific attribute value. For example, the below code changes the margins of all elements with the attribute type and a corresponding value of radio:
ex:
    [type='radio'] {
  margin: 20px 0px 20px 0px;
}


7/14/2020
# undestand absolute versus relative units 
- pixels (px) are a type of length unit which is what the tells the browser how to size or space an item. 
- lenght units are absolute and relative 
- absolute units tie to phsyical units of lenght such as in and mm 
- relative units such as em or rem 
- em is based on the size of an element's font 
ex:  padding: 1.5em;

7/15/2020
# style the html body element 
- every html page has a body page 
ex: backgroud-color: black;

# inherit styles from the body element 
- you can style the the body element and everything inside the body will be style too unless you use class or id to overrode our body element CSS declaration. their style in a way you want without the body affecting the content 
- what can override a css class? another css class -- the order that you put the class in the css style matters
- The second declaration will always take precedence over the first. Because .blue-text is declared second, it overrides the attributes of .pink-text
- id will always take precendence to class 
- override class declarations with inline styles 
-in style will override any class or id style
- the last override style and override all css style 
ex: color: red !important;

7/16/2020
# use Hex code for specific colors 
- there is many ways to represent color in css 
- hexadecimal code or hex fo short 
- in css, we can use 6 hex to represent color 
ex: #000000; ->>> black color


7/17/2020   
# Abbreviated Hex code 
ex: red color #FF0000 ---> #F00 

# Use RGB values to color elements 
- using RGB values to color in css 
ex: black rgb(0, 0, 0)
- use rgb to mix color 
ex: blue ->> rgb(0, 0, 255)
    red ->>  rgb(255, 0, 0)

# Use css variables to change several elements at once 
- css varibles are a powerful way to change many css style properties at once by changing only one value 
ex: --penguin-skin: gray; ---> an example of css variable

# Attach a fallbadck value to a css variable 
ex: background: var(--penguin-skin, black);

# Improve compatibility with browser fallbacks
- fallbacks helps us avoid compatibility issues 

//Inherit css variables 
- using :root element to make the use of inheritance
- :root is a pseudo-class selector that matches the root element of the document, usually the html element. By creating your variables in :root, they will be available globally and can be accessed from any other selector in the style sheet.

// coding for tomorrow 
- end with css and learn more aobut it 
- read the html and css book