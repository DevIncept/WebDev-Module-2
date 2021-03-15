 <h2 align="center"><b>📜 Introduction to CSS 📜 </b></h2>
 <p align="center">
Cascading Style Sheet Control look and feel of Web Pages. We use it to style  HTML documents and to display its element more creatively. Basically it gives life to HTML Structure. 
</p>


*** 
<details>
  <summary markdown="span"> CSS Topics 📁  </summary>

1. CSS Version History.<a href="#history">👇</a>
2. External Style Sheet using Multiple Style Sheets.<a href="Rushikesh_CSS_MultipleStyleSheet.md">👉</a>
3. Value Lengths and Percentages.<a href="Rushikesh_CSS_ValueLenPer.md">👉</a>

</details>

***

<img align="right" height="175px" alt="GIF" src="https://media.giphy.com/media/UTRXtonjpNJraR8BhR/giphy.gif" />


  
* CSS Background -
 
 * 👨‍💻 Developers- Håkon Wium Lie & Bert Bos. 
 * 📑 Published by	World Wide Web Consortium.[ (W3C) ](https://www.w3.org/TR/CSS2/) 
 * 📅 Initial release Date - 17	Dec. 1996.
 * 🔗 The Official  [Definition](https://www.w3.org/TR/CSS/#css) by W3C.
   

***

<P align="center" id="history"><b><i>Topic 1 : CSS Version History.</i><b></p>
  
****
  
✔️ ***CSS 1 -***

CSS 1 is Published on December 17, 1996. it is the first CSS specification to become an official W3C Recommendation. 

📝 ***Capabilities -***

1. Font properties - Typeface & Emphasis.
2. Color of text & backgrounds.
3. Text attributes - Spacing in words, letters, and lines of text.
4. Alignment of text, images & tables.
5. Margin, border, padding, and Positioning.

***

✔️ ***CSS 2 -***

CSS level 2 Published in May 1998 recommended by w3c. 


📝 ***Capabilities -***

- Absolute, Relative, and Fixed positioning of elements.
-  z-index.
-  Media types. 
-  Aural style sheets Support.
-  Bidirectional text. 
-  Font properties - Shadows.
  
Now, CSS 1, CSS2 are not Recommendations of w3c.

***

✔️ ***CSS 2.1 -***

CSS level 2 Revision 1/CSS 2.1 Improves CSS 2. this specification was updated several times. the latest version
was released on April 12, 2016.

✔️ ***CSS 3 -***

CSS 3 was published in June 1999. it's divided into several separate documents called "modules". modules add new Capabilities and features. CSS 4 is under development. 


***


<img align="right" height="175px" alt="GIF" src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif"/>


<p aligh="left">
  
- Additional Information -
  - 🔗 The World Wide Web Consortium (W3C) [Official Website.](https://www.w3.org)
   - 🔗  CSS Official [Website.](https://www.w3.org/Style/CSS/)
   - 🔗 CSS Current [Work Page.](https://www.w3.org/Style/CSS/current-work)
   - 🔗 CSS Official [Working Group.](https://www.w3.org/Style/CSS/members)
   
  
  




<br>
<br>
<br>



***

<P align="center" id="multiple"><b><i>Topic 2 <u>Examples</u>: External Style Sheet using Multiple Style Sheets.</i><b></p>
  
***


✔️ External Style Sheet using Multiple Style Sheets - 

- External CSS is linked to HTML document using `<link>`.
- Used to style Complete HTML Document.
- Multiple External Files contains all style of HTMl document. 
- `.css` Extension is used for External CSS file. Any Text/Code editor can be used for write External CSS (ex. VS code, Brackets, Atom)
- Used to Oraganize and style Large HTML document.(ex.Separate Style for Desktop and Mobile View of same Website)
- Priority Depends on Last Declared Style Sheet.


📝 Multiple External CSS Files Example -

🖊️ Link External CSS inside head -

```html
<head>

<!--External CSS 1 -->
<link rel="stylesheet" href="styleFirst.css">

<!--External CSS 1 -->
<link rel="stylesheet" href="styleSecond.css">

</head>

```
🖊️ Inside `styleFirst.css` External CSS File -

```css

h5 {
 color: MidnightBlue;
 text-align:center;
 text-decoration: overline wavy OrangeRed;
}

```
🖊️ Inside `styleSecond.css` External CSS File -

```css

h6 {
 color: MidnightBlue;
 text-align:center;
 text-decoration: underline wavy OrangeRed;
}

```
🖊️ Inside HTML Body

```html
<h5>This is example of Multiple External CSS. (styleFirst.css)</h5>
<h6>This is example of Multiple External CSS. (styleSecond.css)</h6>
```


📄 Output -

<!-- <h5 style="color:MidnightBlue;text-align:center;text-decoration: overline wavy OrangeRed;">This is example of Multiple External CSS. (styleFirst.css)</h5>
<h6 style="color:MidnightBlue;text-align:center;text-decoration: underline wavy OrangeRed;">This is example of Multiple External CSS. (styleSecond.css)</h6> -->

<p align=" center"><img alt="mulitple css ex" src="multiple.png"></p>
***


✔️ ***External Style sheet can be used in two ways:***

1. Case I - Placing Internal and External Style Sheet in Same document. 
2. Case II - Linking 2 Separate Style Sheet in Same Document. 

>In both Cases If Same element, class or id is declared then priority depends on last declared style sheet. Example code. 


📝 ***Case I - Placing Internal and External Style Sheet in Same document.***

🖊️ Link External CSS inside head before Internal CSS -

```html
<head>
<!--External CSS -->
<link rel="stylesheet" href="ExternalStyle.css">

<!--Internal CSS -->
<style>
h5 {
 color: MidnightBlue;
 text-align:center;
 text-decoration: overline wavy OrangeRed;
}
</style>
</head>

```
🖊️ Inside `ExternalStyle.css` External CSS File -

```css

h5 {
 color: CornflowerBlue;
 text-align:center;
 text-decoration: underline dotted OrangeRed;
}

```

🖊️ Inside HTML Body

```html
<h5>Case I Mulitple External Sheet Example.</h5>
```


📄 Output -

<!-- <h5 style="color:MidnightBlue;text-align:center;text-decoration: overline wavy OrangeRed;">Case I Mulitple External Sheet Example.</h5>

***
🖊️ If `ExternalStyle.css` declared after Internal CSS then,

📄 Output - 

<h5 style="color:CornflowerBlue;text-align:center;text-decoration: underline dotted OrangeRed;">Case I Mulitple External Sheet Example.</h5> -->

<p align=" center"><img alt="mulitple css ex" src="mcase1.png"></p>


***

📝 Case II - Linking 2 Separate Style Sheet in Same Document. 


🖊️ Link Multiple External CSS inside head  -

```html
<head>
<!--External CSS 1 -->
<link rel="stylesheet" href="External_First.css">

<!--External CSS 2 -->
<link rel="stylesheet" href="External_Second.css">
</head>

```
🖊️ Inside `External_First.css` External CSS File -

```css

h5 {
 color: DarkMagenta;
 text-align:center;
 text-decoration: overline underline dashed OrangeRed;
}

```

🖊️ Inside `External_Second.css` External CSS File -

```css

h5 {
 color: CornflowerBlue;
 text-align:center;
 text-decoration: overline underline wavy OrangeRed;
}

```

🖊️ Inside HTML Body

```html
<h5>Case II Mulitple External Sheet Example.</h5>
```


📄 Output -

<!-- <h5 style="color:MidnightBlue;text-align:center;text-decoration: overline underline wavy OrangeRed;">Case II Mulitple External Sheet Example.</h5>

***
🖊️ If `External_First.css` declared after `External_Second.css` then,

📄 Output - 

<h5 style="color:CornflowerBlue;text-align:center;text-decoration: overline underline dashed OrangeRed;">Case II Mulitple External Sheet Example.</h5> -->

<p align=" center"><img alt="mulitple css ex" src="mcase2.png"></p>

***
<p align="center">Multiple Style Sheet <br><a href="Rushikesh_CSS_MultipleStyleSheet.md"><img src="https://image.flaticon.com/icons/png/128/130/130871.png?ga=GA1.2.454436195.1606303868" width="30px" height="30px"/></a></p>



***

<img align="right" height="175px" alt="GIF" src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif"/>


<p align="left">
  
- Additional Information -
  - 🔗 The World Wide Web Consortium (W3C) [Official Website.](https://www.w3.org)
   - 🔗  CSS Official [Website.](https://www.w3.org/Style/CSS/)
   - 🔗 CSS Current [Work Page.](https://www.w3.org/Style/CSS/current-work)
   - 🔗 CSS Official [Working Group.](https://www.w3.org/Style/CSS/members)
   
   
