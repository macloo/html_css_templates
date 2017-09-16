# HTML and CSS templates

Extremely simple templates for starting a small project.

Below is an overview of the terms. Open the similarly named HTML file and its CSS to see it in action.

## basic

A plain vanilla HTML page with no CSS.

[Example page](http://macloo.github.io/html_css_templates/basic.html)

File: basic.html

## box-sizing

Web pages by beginners often look horribly different in different Web browsers. Often this can be traced back to the ways in which `margin` and `padding` are specified in the CSS. Some web browsers interpret some aspects of `margin` and `padding` differently from other browsers.

Resource: [box-sizing](https://tympanus.net/codrops/css_reference/box-sizing/)

[Example page](http://macloo.github.io/html_css_templates/boxsizing.html)

## flexbox

Beginners can get very confused about the differences among `flex`, `float`, `grid`, and `inline-block` (all covered below). Think of `flex` as the modern solution to solving challenges with a set of small items (or boxes) on a page. However, for a full-page layout solution, look to `grid` instead.

[Browser support for CSS flexbox](http://caniuse.com/#feat=flexbox) is very good.

Resource 1: [Using CSS Flexible Boxes](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)

Resource 2: [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

Resource 3 (video): [Flexbox Tutorial: Real Layout Examples](https://www.youtube.com/watch?v=k32voqQhODc)

[Example page](http://macloo.github.io/html_css_templates/flexbox.html)

## floats

In CSS, float declarations are commonly used to place elements (such as images, or sidebars) on a page. They pose challenges for beginners, in large part because usually they must be "cleared" after use.

Problems with floats also arise because of the box-sizing issue (see above): when there is not enough space for a floated item, elements "fall down" below instead of floating side by side, as you intended. The error with insufficient space can be caused by the width of margins and padding — the sum of all the widths is greater than you calculated. This can also occur as part of inheritance (the "cascade" of Cascading Style Sheets).

Resource 1: [float](https://developer.mozilla.org/en-US/docs/Web/CSS/float) (a great reference at Mozilla Developer Network)

Resource 2: [CSS Floats 101](https://alistapart.com/article/css-floats-101)

Video: [Comparing floats with positioning (demo)](https://www.youtube.com/watch?v=LaQZj1pXxG4&index=28&list=PLZFU-W6LLeecJuSQh20QUU_gCmS30sLTB) Relative, absolute, and fixed position are discussed after floats.

## grid

The CSS grid has revolutionized grid-style page layouts, making floats and inline-block styles unnecessary in many cases (but not all). Good planning is required before you can implement the grid effectively. See also `flexbox` above.

[Browser support for CSS grid](http://caniuse.com/#feat=css-grid) is pretty good but not yet universal.

Resource 1: [Basic concepts of grid layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout)

Resource 2 (video): [CSS Grid Changes EVERYTHING](https://www.youtube.com/watch?v=7kVeCqQCxlk)

Resource 3: [Building Production-Ready CSS Grid Layouts Today](https://www.smashingmagazine.com/2017/06/building-production-ready-css-grid-layout/) &mdash; by the guy in the video

## inline-block

It's possible to replace the `float` techniques with `display: inline-block`. Each method has issues, and each method requires that we use `box-sizing` to make it work properly. Beginners must understand that they cannot use the two together; it's an either/or choice.

Resource: [What’s the Deal With Display: Inline-Block?](https://designshack.net/articles/css/whats-the-deal-with-display-inline-block/)

## Normalize.css

This stylesheet is widely used throughout the web design community to smooth out all the differences among browsers. Load this first, then load your own CSS file. All the HTML files here (except basic.html) use Normalize.

Resource: [Normalize.css](https://necolas.github.io/normalize.css/)

## universal selector

The web design community expresses various opinions about use of the universal selector (\*) in CSS. It should not be overused.

Resource: [Universal selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors) (MDN)

## viewport / responsive pages

All the pages here use the <em>viewport meta tag</em> in the HTML `head` element. It helps to make your pages look good on small screens, i.e. mobile. However, just slapping the tag on your page does not instantly fix everything.

Resource 1: [Stop using the viewport meta tag (until you know how to use it)](http://blog.javierusobiaga.com/stop-using-the-viewport-tag-until-you-know-ho)

Resource 2: [Use CSS media queries for responsiveness](https://developers.google.com/web/fundamentals/design-and-ui/responsive/#css-media-queries)
