You can the live site here:

![Live Site](http://ugaliguy.github.io/)


#### What did you learn about CSS padding, borders, and margin by doing this challenge?

I learned that html elements can be represented by a box - the *box model*. Let's make an analogy with a package you have received (let's say from Amazon). The things that interest us most - text or images - are the contents of this package. The packing material that protects your contents from being damaged by collisions with other boxes is the *padding*. The box that your content is shipped in is the *border*. The *margin* is the space that surrounds your box. 

#### What did you learn about CSS positioning?

I learned that positioning is very tricky. First you need to determine whether the position should be static, fixed, relative, or absolute. I'm still trying to understand the differences and consequences of choosing one over the other. Once you've made a decision, you can use padding, border, and margins to fine tune your positioning.

#### What aspects of your design did you find easiest to implement? What was most difficult?

The easiest aspects were aesthetic considerations such as background color, font families, and link decorations (e.g. setting links to be underlined only when hovering over them). One time-saving lesson I learned was not to sweat over font families (unless you are a designer). I spent a lot of time trying to find the ideal font for my pages and it only occurred to me, after a while, that setting font-family to 'sans serif' for the body and 'serif' for paragraphs of text took away a lot of guess work.

The most difficult aspect was positioning the footer. I wanted the footer to stay at the bottem of the page. My first thought was to give it a fxed position at the bottom and this worked for the index page, but not the blog-index or blog pages themselves. This showed me that I did notfully understand the position attribute. I did a bit of research and found (http://www.w3schools.com/css/css_positioning.asp) to be very helpful. In particular, the following passage 

> However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

This is exactly what I wanted to happen. This is what led me to set a margin-bottom in the body - so that the footer would always be "pushed" downward by the body on top of it.

#### What did you learn about adding and formatting elements with CSS in this challenge?

I learned to test often. I learned to add elements one at a time and to try to use any formattiing attributes with those elements before adding other elements.
I pushed myself to use CSS to do everything. I still haven't figured out some things - e.g.. how to achieve line breaks using CSS - but I'm thinking about it.