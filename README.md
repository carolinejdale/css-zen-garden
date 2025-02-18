# css-zen-garden

[CSS Zen Garden](https://www.csszengarden.com/) by Dave Shea:

CSS Zen Garden is a demonstration of what can be accomplished through CSS-based design.

View source is a feature, not a bug. Thanks for your curiosity and interest in participating!

Here are the submission guidelines for the new and improved csszengarden.com:

- CSS3? Of course! Prefix for ALL browsers where necessary.
- go responsive; test your layout at multiple screen sizes.
- your browser testing baseline: IE9+, recent Chrome/Firefox/Safari, and iOS/Android
- Graceful degradation is acceptable, and in fact highly encouraged.
- use classes for styling. Don't use ids.
- web fonts are cool, just make sure you have a license to share the files. Hosted
- services that are applied via the CSS file (ie. Google Fonts) will work fine, but
- most that require custom HTML won't. TypeKit is supported, see the readme on this
- page for usage instructions: https://github.com/mezzoblue/csszengarden.com/

And a few tips on building your CSS file:

- use :first-child, :last-child and :nth-child to get at non-classed elements
- use ::before and ::after to create pseudo-elements for extra styling
- use multiple background images to apply as many as you need to any element
- use the Kellum Method for image replacement, if still needed: http://goo.gl/GXxdI
- don't rely on the extra divs at the bottom. Use ::before and ::after instead.