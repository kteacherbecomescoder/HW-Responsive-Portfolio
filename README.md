# Responsiveness Assignment - Either Bootstrap or Responsive

## Overview

In this assignment, you'll create **two different portfolios**. The first will be building
your portfolio layout using the *Bootstrap CSS Framework*. The second will be enhancing
the portfolio with a *mobile-responsive layout*.

### Instructions

### Assignment One Instructions (BOOTSTRAP) - The title will be either Bootstrap or Responsive Portfolio

* I made a repo in Github and included 3 html pages in it. They are contact, portfolio and index.htm 

* Using Bootstrap, recreate your portfolio site with the following items:

   * A navbar

   * A responsive layout 

     * eg. On `xs` and `sm` screens, content should take up the entire screen. On `md` and larger screens, you should have some margins on the left and right side of the screen. Check out various sites on your mobile device versus your computer to see this in action!

   * Responsive images

* Your Bootstrap solution should minimize use of media queries.



### Assignment Two Instructions - (RESPONSIVE - No Bootstrap)

* Repeat steps 1 and 2 from above.
* Note: Be sure not to include any dot files (e.g. .git, .gitignore) from the `Basic-Portfolio` repo.

* Use three `@media screen` tags, each with one of these `max-width`s: `980px`, `768px` and `640px`.

   * You use `980px` because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.

   * `768px` is about the width of a tablet and `640px` is about the width of a phone in landscape.

* Make the position of the header `static` (the default positioning) when the screen is `640px` wide.

* Be sure to include the `viewport` tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices.
