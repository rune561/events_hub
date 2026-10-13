Quick Check Q1:  You change the footer colour in styles.css. How many pages update? What if the same 
colour was only set with an inline style on index.html? 
ans) 4 pages were update. If the footer color is set with an inline style only on index.html, then only the index.html page will have that inline footer color; the other pages will not get it.

Quick Check Q2:  Which is more specific: h1 or #welcome? If both set color, which wins? Write a one-line 
proof from your page.  
Ans) #welcome is more specific than h1 because an ID selector has a higher specificity than an element selector. Therefore, if both selectors set a different color, the #welcome rule will win.
 For example, if h1 { color: blue; } and #welcome { color: red; }, an <h1 id="welcome"> will appear red.

Quick Check Q3:  Convert #0369a1 into an approximate rgb(...) value (you may use a colour picker). Why 
do designers often prefer hex in stylesheets?  
Ans) #0369a1 can be converted to approximately rgb(3, 105, 161). Designers often prefer hexadecimal colors in stylesheets because they are short, easy to read, and easy to reuse. For example, #0369a1 is simpler and more compact than rgb(3, 105, 161), making CSS code cleaner.

Quick Check Q4:  Set a nav link to display: none, then to visibility: hidden. What is the difference in the 
layout?   
Ans) When display: none is used, the nav link is completely removed from the page, so it takes up no space in the layout. When visibility: hidden is used, the nav link becomes invisible but still takes up its original space. Therefore, display: none changes the layout, while visibility: hidden keeps the layout space unchanged.

Quick Check Q5:  In your wireframe, how many event cards appear side-by-side at phone width? At 
desktop width?   
Ans) In a typical responsive wireframe, 1 event card appears side-by-side at phone width, while 3 event cards appear side-by-side at desktop width. This allows the cards to stack vertically on smaller screens and fit across the page on larger screens.

Quick Check Q6:  Why must styles.css be linked AFTER the Bootstrap CSS file? What happens if you reverse 
the order and both set h1 colour?  
Ans) styles.css should be linked after the Bootstrap CSS file so that your own CSS rules can override Bootstrap’s default styles when both have the same specificity. If you reverse the order and both Bootstrap and styles.css set the h1 color, the Bootstrap rule may override your custom style. Therefore, putting styles.css last gives your custom design priority.

