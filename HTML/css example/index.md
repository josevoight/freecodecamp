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