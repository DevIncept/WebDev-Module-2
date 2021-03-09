
  <p align="center">
  <h2 align="center"><b>📜 Introduction to Responsive Design 📜 </b></h2>
 <p align="center">
Responsive Design adapts itself to any user device. Responsive design ensures that Web Design displays on desktops, Laptops, and mobile-tablet devices are Standard, Flexible, and User Friendly.
</p>
</p>

*** 
<details>
  <summary markdown="span"> Responsive Design Topics 📁  </summary>

1. Introduction to Responsive Design.<a href="#Resp">👇</a>
2. Responsive Design Breakpoints<a href="Rushikesh_CSS_BreakResp.md">👉</a>
3. Media Queries.<a href="Rushikesh_CSS_MediaQ.md">👉</a>

</details>

***

<img align="right" width="250px" height="200px" alt="GIF" src="https://media.giphy.com/media/xT0Gqn9yuw8hnPGn5K/giphy.gif" >

<p align ="left">

- Responsive Web Design (RWD) -
    - Introduction & History.   
    - Concepts.
    - Implement RWD.
    
</p>

***

<p align="center" id="Resp"><b><i>Topic : Responsive Web Design (RWD) </i><b></p>
  
***

✔️ Introduction & History - 

- Responsive web design (RWD) is a web design approach, In which web pages display properly on different devices and screen sizes. 
- First Responsive Layout - Audi.com (2001)
- Demand for RWD is increasing because of an increase in mobile users.
- CSS plays Main Role in Responsive web design.

***

✔️ Concepts - 
1. CSS Grids -
   - CSS Grid has 12 columns - total width of 100%, and it will shrink and expand as  the browser window resize.
  
2. Flexible Media -
   - In Responsive web design,the media adapt browsing environment.
   - Sometimes few elements need to be resized or Completely removed from certain Devices. 
   - Achieved Using CSS Concepts like box-model, Units.
   - Images, Typography also Important in making media Flexible.
3. CSS Breakpoints -
   - CSS breakpoints are points where the content of website Changes according to the device width. 
   - <i> More about CSS Breakpoint.</i> <a href="Rushikesh_CSS_BreakResp.md">👉</a>
4. Media Queries -
   - Media queries introduced in CSS 3.
   - It uses `@media` rule to Apply Certain CSS properties only if a Given condition is true.
   - <i> More about Media Query.</i> <a href="Rushikesh_CSS_MediaQ.md">👉</a>

***
✔️ Implement RWD  -

Quick Look on Implementing RWD- 

1. Set Viewport - Viewport gives browser instructions on how to control the Web page and its dimensions & scaling. 
   
🖊️ In `<meta>` Tag -

```html

<meta name="viewport" content="width=device-width, initial-scale=1.0">

```
2. Responsive Images and Font-size -
   - Responsive Images Scale According to Browser Size.
   - `max-width` property is used.  

🖊️ For Images - 
```html

<img src="img_Name.jpg" style="max-width:100%;height:auto;">

```
- Font size set with `vw` unit- viewport width. 
- Viewport is the browser window size. 1vw = 1% of viewport width.

***

<img align="right" height="150px" alt="GIF" src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif">


<p aligh="left">
  
- Additional Information -
  - 🔗  CSS Official [Website.](https://www.w3.org/Style/CSS/)
  - 🔗 [ CSS Box-Model.](https://www.w3.org/TR/CSS22/box.html)
  - 🔗 [CSS Media Queries.](https://www.w3.org/TR/css3-mediaqueries/)
   - 🔗 MDN Web Docs- [Media queries.](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

***
