# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements


### Links

- Here is my Git website solution:https://83ya.github.io/Product-Preview-FrontEnd-Mentor-challenge/

## My process
I first made the wrote the HTML code in VS code. I added the tags like <p> and <h1> for the description and brand name respsectively. I used a <table> for the prices. And I used the <button> tag for the button. I also added classes and ids which 
is usedful for my external css.
  
I then created a css file and started styling from top to bottom. I started with the container class. I wanted to do flexbox box but unsure if I used them correctly. I used positioning in styling the elements. For the fontm I followed the suggested font and searched then in googlefonts. I copied from that website and pasted it in my css file.

 There has been alot of searching or re-searching for solutions in google. I searched in google how to make a line-height for the paragraphs. I found frequently check the results in the google chrome to see if the changes I made in the code will take effect. There are times that nothings happens or it would ruin the entire design.

  I had trouble re-sizing the image . I don't know what happened butr after I restarted my laptop the image just started to fit in the container. 
  
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned CSS positioning like absolute and relative though I still need to practice it more. I was able to use container and DIV as well.

<!---HTML CODE--->
 <div class="container"> 
          <!--This is the image-->
          <img  class="product" src="images\image-product-desktop.jpg" alt="product">     
  
<!---CSS CODE-->
  
.container{
    display: flex;
    position: absolute;
    top: 50px;
    left: 10%;
    margin-left: 20%;
    border: none;
    border-radius: 10px;
    background-color: hsl(0, 0%, 100%);
    max-height: 30em;
    max-width: 30em;
}
/*This is the image class*/
.product{
    position: relative;    
    height:50px;
   max-width: 50%;
}



### Continued development

I still really need to learn more about flexbox , gird and positioning. I really struggle with using them and also to make the sizing adaptable to the device.

### Useful resources

https://www.w3schools.com/css/css_positioning.asp - This helped me to learn more about positioning.
  
https://www.youtube.com/watch?v=Pp7UXS3P6jY&list=PLxLWP49nS_V5ySalVQJ27eLkSC1QBgnhT&index=37- This helped me to learn more about positioning.


## Author

- Website - [Atria Montejo] (https://83ya.github.io/Product-Preview-FrontEnd-Mentor-challenge/)


## Acknowledgments

I actually did this on my own so I am unsure if I did them corrrectly. Kudos to FrontEnd Mentor for this challenge and the resources that I used. I hope I learn more .
