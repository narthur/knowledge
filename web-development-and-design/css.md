# CSS

[Clippy](http://bennettfeely.com/clippy/) \#webapp - “CSS clip-path maker”

[Conditions for CSS Variables](http://kizu.ru/en/fun/conditions-for-css-variables/) \#article - “So, what we need is a way to use a sin­gle CSS vari­able for set­ting dif­fer­ent CSS prop­er­ties to dif­fer­ent val­ues, but not based di­rectly on this vari­able \(that is — those val­ues shouldn't be cal­cu­lated from our vari­able\). We need con­di­tions.” Using CSS variables as booleans.

[CSS Before and After pseudo elements explained - part two: the content property](https://www.youtube.com/watch?v=xoRbkm8XgfQ) \#video - "The before and after CSS pseudo elements are great, and they have the content property which a lot of people don't really know how powerful it actually is, so in this video I show you some fun things you can do with it, from a markupless tool tip to a quick dive into CSS counters, which are awesome!"

[CSS Filters Playground](http://bennettfeely.com/filters/)

[CSS Gradients with background-blend-mode](http://bennettfeely.com/gradients/) - “New CSS gradient possibilities with the background-blend-mode property.”

[CSS Guidelines](https://cssguidelin.es) \#article - “High-level advice and guidelines for writing sane, manageable, scalable CSS”

[CSS Lint](http://csslint.net/) \#webapp - “Will hurt your feelings\* \(And help you code better\)”

[CSS stacking contexts: What they are and how they work](https://tiffanybbrown.com/2015/09/css-stacking-contexts-wtf/index.html) \#article - "So what is a **stacking context**? A stacking context is an element that contains a set of layers. This can be a _root_ stacking context, as created by the `html` element. Or it can be a _local_ stacking context, as created by specific properties and values."

[CSSYNTH](http://bennettfeely.com/cssynth/)

[Image Effects with CSS](https://bennettfeely.com/image-effects/)

[Managing CSS Projects with ITCSS](https://speakerdeck.com/dafed/managing-css-projects-with-itcss) - Presentation slides.

[Navicon Transformations](https://codepen.io/bennettfeely/pen/twbyA) \#demo

[pointer-events](https://css-tricks.com/almanac/properties/p/pointer-events/) \#article - “The pointer-events property allows for control over how HTML elements respond to mouse/touch events – including CSS hover/active states, click/tap events in Javascript, and whether or not the cursor is visible.” Also allows you to pass click events through an element to whatever it’s behind it by using \`pointer-events: none;\` \#chris\_coyier \#css-tricks

[Pure CSS Parallax Websites](https://keithclark.co.uk/articles/pure-css-parallax-websites/) \#article - "This article demonstrates how to use CSS transforms, perspective and some scaling trickery to create a pure CSS parallax scrolling website." 👍Be careful, though. Applying `perspective` to a root element [breaks fixed positioning](https://stackoverflow.com/questions/26386038/why-does-perspective-changes-fixed-position-in-css) by establishes a new stacking context.

[Purgecss](https://www.purgecss.com/) - "[Purgecss](https://github.com/FullHuman/purgecss) is a tool to remove unused CSS. It can be used as part of your development workflow. Purgecss comes with a JavaScript API, a CLI, and plugins for popular build tools."

[Quantity Queries for CSS](http://alistapart.com/article/quantity-queries-for-css) \#article - “This is your guide to creating style breakpoints for quantities of HTML elements, much as you already do with @media queries for viewport dimensions. I’m not pointing at some blurry specification in the distance or a twinkle in an implementer’s eye. We’re going to do this today, with CSS that’s already available.”

[The stacking context](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Positioning/Understanding_z_index/The_stacking_context) \#article - "The **stacking context** is a three-dimensional conceptualization of HTML elements along imaginary z-axis relative to the user, who is assumed to be facing the viewport or the webpage. HTML elements occupy this space in priority order based on element attributes."

[Understanding CSS Layout And The Block Formatting Context](https://www.smashingmagazine.com/2017/12/understanding-css-layout-block-formatting-context/) \#article - By Rachel Andrew. “There are a few concepts in CSS layout that can really enhance your CSS game once you understand them. This article is about the Block Formatting Context \(BFC\). You may never have heard of this term, but if you have ever made a layout with CSS, you probably know what it is. Understanding what a BFC is, why it works, and how to create one is useful and can help you to understand how layout works in CSS.” 👍

[Understanding Variable Scope And Variable Injection In Less CSS](https://www.bennadel.com/blog/2642-understanding-variable-scope-and-variable-injection-in-less-css.htm) \#article - "The Less CSS preprocessor allows you to define variables that can be used throughout your CSS structure; however, as I have been digging into Less CSS more, I have found the rules around variable assignment and variable visibility to be a bit confusing. Sometimes variables can be overridden; sometimes they can't. Sometimes they can bubble-up; sometimes they can't. As such, I thought this would make a valuable exploration."

[VisBug](https://chrome.google.com/webstore/detail/visbug/cdockenadnadldjbbgcallicgledbeoc) \#extension - "Open source web design debug tools built with JavaScript: a FireBug for designers." \#chrome

[What No One Told You About Z-Index](https://philipwalton.com/articles/what-no-one-told-you-about-z-index/) \#article - "The problem with z-index is that very few people understand how it really works. It’s not complicated, but it if you’ve never taken the time to read its specification, there are almost certainly crucial aspects that you’re completely unaware of."

## Frameworks

[Bootstrap](https://getbootstrap.com/) - “Build responsive, mobile-first projects on the web with the world’s most popular front-end component library. Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. Quickly prototype your ideas or build your entire app with our Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery.”

[tailwindcss](https://tailwindcss.com/) - "A utility-first CSS framework for rapidly building custom designs. Tailwind CSS is a highly customizable, low-level CSS framework that gives you all of the building blocks you need to build bespoke designs without any annoying opinionated styles you have to fight to override."

## Grid

[Auto-Sizing Columns in CSS Grid: \`auto-fill\` vs \`auto-fit\` \| CSS-Tricks](https://css-tricks.com/auto-sizing-columns-css-grid-auto-fill-vs-auto-fit/) \#article - "One of the most powerful and convenient CSS Grid features is that, in addition to explicit column sizing, we have the option to repeat-to-fill columns in a Grid, and then auto-place items in them. More specifically, our ability to specify how many columns we want in the grid and then letting the browser handle the responsiveness of those columns for us, showing fewer columns on smaller viewport sizes, and more columns as the screen estate allows for more, without needing to write a single media query to dictate this responsive behavior."

[A Complete Guide to Grid \| CSS-Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/) - "CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows, unlike [flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) which is largely a 1-dimensional system. You work with Grid Layout by applying CSS rules both to a parent element \(which becomes the Grid Container\) and to that element’s children \(which become Grid Items\)."

[CSS Grid.](https://cssgrid.io/) \#course - "LEARN CSS GRID WITH WES BOS IN 25 PRETTY GOOD VIDEOS"

[CSS Grid: Moving From CSS Frameworks To CSS Grid \(2018 and beyond\) - YouTube](https://www.youtube.com/watch?v=paMmgo4MhQ8) \#video - "For the first time since its inception, CSS now has a real two-dimensional layout tool in the CSS Grid specification. We’ve had to resort to using floats, inline blocks and most recently, Flexbox. Because using these for layout is essentially a hack, we’re often tempted to resort to grid frameworks like those provided by Foundation and Bootstrap."

[Why CSS grid-area is the best property for laying out content](https://www.youtube.com/watch?v=duH4DLq5yoo) \#video - "CSS Grid is amazing, and grid-area just make it so much better. When grid first launched I loved the idea of grid areas, but didn't get fully on board as it seemed like a little too much work... but once you start actually using them on a regular basis, you realize that while the initial setup in slightly longer, in the long run you can save a boat load of time!"

## Resets

[CSS Remedy](https://github.com/mozdevs/cssremedy) - "Start your project with a remedy for the technical debt of CSS. A gift to you from Mozilla Developer Outreach."

[Eric Meyer: Reset CSS](https://meyerweb.com/eric/tools/css/reset/) - "The reset styles given here are intentionally very generic. There isn't any default color or background set for the `body` element, for example. I don't particularly recommend that you just use this in its unaltered state in your own projects. It should be tweaked, edited, extended, and otherwise tuned to match your specific reset baseline. Fill in your preferred colors for the page, links, and so on."

[Normalize.css](https://necolas.github.io/normalize.css/) - "[Normalize.css](https://github.com/necolas/normalize.css/) makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing."

[Reboot](https://getbootstrap.com/docs/4.0/content/reboot/) - "Reboot, a collection of element-specific CSS changes in a single file, kickstart Bootstrap to provide an elegant, consistent, and simple baseline to build upon."

## Transformation

Less

[PostCSS](https://postcss.org/) - "A tool for transforming CSS with JavaScript"

[Revisiting the rendering tier](https://www.theguardian.com/info/2019/apr/04/revisiting-the-rendering-tier) \#article - "From 62,783 lines of Sass to CSS-in-JS. Introducing the new server rendering layer for theguardian.com"

Sass

## Sources

[CSS-Tricks](https://css-tricks.com/) - "CSS-Tricks is created, written by, and maintained by [Chris Coyier](https://chriscoyier.net/) and [a team](https://css-tricks.com/about/) of swell people. It is built on WordPress and powered up by [Jetpack](https://css-tricks.com/jetpack/). It is made possible through [sponsorships](https://css-tricks.com/advertising/) from products and services we like."

[Kevin Powell](https://www.youtube.com/user/KepowOb/featured) \#channel - [Personal website](https://www.kevinpowell.co/). "Helping you learn how to make the web, and make it look good while you're at it. ❡ With a new video every Wednesday, I'll be bringing you How Tos and Tutorials, and well as simple tips and tricks. I'm mostly looking to help people who are new to the world of web development."

[Wes Bos](https://wesbos.com/) - "I create awesome web sites and web applications. Hire me to build you a website, teach you to code or speak at your event."

