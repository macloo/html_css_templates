# HTML and CSS templates

Extremely simple templates for starting a small project.

Here's an overview of the terms. Open the similarly named HTML file and its CSS to see it in action.

## box-sizing

Web pages by beginners often look horribly different in different Web browsers. Often this can be traced back to the ways in which `margin` and `padding` are specified in the CSS. Some web browsers interpret some aspects of `margin` and `padding` differently from other browsers.

Resource: [box-sizing](https://tympanus.net/codrops/css_reference/box-sizing/)

## floats

In CSS, float declarations are commonly used to place elements (such as images, or sidebars) on a page. They pose challenges for beginners, in part because usually they must be "cleared" after use.

Problems with floats also arise because of the box-sizing issue (see above): when there is not enough space for a floated item, elements "fall down" below instead of floating side by side, as you intended. The error with insufficient space can be caused by the width of margins and padding — the sum of all the widths is greater than you calculated. This can also occur as part of inheritance (the "cascade" of Cascading Style Sheets).

Resource: [float](https://developer.mozilla.org/en-US/docs/Web/CSS/float) (a great reference at Mozilla Developer Network)

Resource: [CSS Floats 101](https://alistapart.com/article/css-floats-101)

## inline-block

It's possible to replace the `float` technique with `display: inline-block`. Each method has issues, and each method requires that we use `box-sizing` to make it work properly. Beginners must understand that they cannot use the two together; it's an either/or choice.

Resource: [What’s the Deal With Display: Inline-Block?](https://designshack.net/articles/css/whats-the-deal-with-display-inline-block/)

## Normalizer.css

This stylesheet is widely used throughout the web design community to smooth out all the differences among browsers. Load this first, then load your own CSS file.

Resource: [Normalizer.css](https://necolas.github.io/normalize.css/)

## universal selector

The web design community expresses various opinions about use of the universal selector (\*) in CSS. It should not be overused.

Resource: [Universal Selector ‘*’ Reset](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors)

## viewport / responsive pages

All the pages here use the <em>viewport meta tag</em> in the HTML `head` element. It helps to make your pages look good on small screens, i.e. mobile. However, just slapping the tag on your page does not instantly fix everything.

Resource 1: [Stop using the viewport meta tag (until you know how to use it)](http://blog.javierusobiaga.com/stop-using-the-viewport-tag-until-you-know-ho)

Resource 2: [Use CSS media queries for responsiveness](https://developers.google.com/web/fundamentals/design-and-ui/responsive/#css-media-queries)
