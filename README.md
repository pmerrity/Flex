# Flex (1.1.0)
Flex is a responsive grid system. It is based on a 24-column grid system and contains standard media query breakpoints for mobile (480px), tablet (768px), and desktop (992px) so you don't have to worry about it!

### What's New? (v1.1.0)
- Adding border-box box-sizing to the columns, and everything within them will inherit the CSS property. No more hassle with borders and padding!
- Changed the weird ".col-4p8" to ".col-4-8".
- Updated the breakspoints by 1px to break properly.
- New things! Added padding classes to throw some quick.
- More Sarcasm!

### Why Should I Use This?
Because most frameworks are a piece of poo. Nobody wants 500MB worth of useless junk added to their nifty site! Unless that's your thing...I use this for all of most of my projects, templating, and various client sites because I don't need 500MB crappy framework files that slow down my site.

### Features
- Put your site on a diet and feed it a whopping 3kb grid.
- Optimized breakpoints at 480px, 600px, 768px, and 992px.
- Not 500MB.
- No more "column-8 column-sm-200 column-bigmac" classes on every single tag! Flex just works.
- Not working 100% the way you'd like it to? Change it yourself. It's easy. Figure it out. I mean...Fully Customizable! Written in SCSS for your convenience.

### hOw U uSe It?!!?/
The grid is light and simple to master! There are a number of classes you can use (not a million):
- .row -- A wrapper that is clearfix ready (prevents collapsing when children are floated).
- .col-{#} -- Replace {#} with a number 1 - 24 to determine number of columns it spans. (i.e. col-24 = 100%).
- .no-float -- Overrides the "float: left" property in each .col-# class. Use with .auto-margin
- .auto-margin -- Makes an element block-level and centers it within the parent. Example: maybe you want an element to be 50%, but  centered instead of to the left.
- .pull-right -- Columns float left by default. Want it on the right? Use this.

##### New!
- .pad-{size} -- This standard padding is simple. Want a teeny bit of padding? Just add .pad-xs to any class and voila! 5px padding all around. Available sizes: xxs, xs, sm, md, lg, xl, xxl (5px, 10px, 20px, 40px, 80px, 120px 180px respectively).
- .pad-{direction}-{size} -- Similar to the top, but the if you want it to only go horizontal or vertical, just add "horiz" or "vert" (i.e. .pad-vert-sm = padding: 10px 0px).