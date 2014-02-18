HTML and CSS templates
======================

Extremely simple templates for starting a small project.

[Checklist for HTML and CSS knowledge](http://bit.ly/html_css_checklist): Read and check whether you understand each of these essentials.

##box-sizing

Web pages by beginners often look horribly different in different Web browsers. Often this can be traced back to the ways in which margin and padding are specified in the CSS. Some Web browsers interpret some aspects of margin and padding differently from other browsers.

Resource: [* { Box-sizing: Border-box } FTW](http://www.paulirish.com/2012/box-sizing-border-box-ftw/)

Resource: [The CSS Box Model](http://css-tricks.com/the-css-box-model/) This is a pretty good illustrated explanation of the box model, which is at the root of the box-sizing issue.

##reset stylesheet

The Web design community includes various opinions about use of a reset stylesheet for CSS.

Resource: [The Pros and Cons of CSS Resets](http://www.vanseodesign.com/css/css-resets-pros-cons/)

##universal selector

The Web design community also expresses various opinions about use of the universal selector (*) in CSS. I used the universal selector in the stylesheet css/boxsizing.css in this collection.

Resource: [Universal Selector ‘*’ Reset](http://www.cssreset.com/scripts/universal-selector-css-reset/)

##floats

In CSS, float declarations are commonly used to place elements (such as images, or sidebars) on a page. They pose challenges for beginners, in part because usually they must be "cleared" after use.

Problems with floats also arise because of the box-sizing issue (see above): when there is not enough space for a floated item, elements "fall down" below instead of floating side by side, as you intended. The error with insufficient space can be caused by the width of margins and padding -- the sum of all the widths is greater than you calculated. This can also occur as part of inheritance (the "cascade" of Cascading Style Sheets).

Resource: [float](https://developer.mozilla.org/en-US/docs/Web/CSS/float) -- a great reference at Mozilla Developer Network

