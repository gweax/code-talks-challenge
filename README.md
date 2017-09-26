# Code.Talks minification challenge

At the Code.Talks conference, I created a CSS-only slideshow, which I minified to 1024 bytes. Can you do better?

Feel free to fork this repository and create a pull-request when you're done. I will accept pull-requests when the rules below are met. I may clarify these rules in the future, so if your solution obeys the letter of the law, but not the spirit, I may reject it.

## Rules

### Validity

- The resulting HTML must be valid. Use the [W3 HTML Validator](https://validator.w3.org/)
- The contained CSS must be valid. Use the [W3 CSS Validator](https://jigsaw.w3.org/css-validator/)
- The contained JS must be valid. You could use the [Esprima JS Validator](http://esprima.org/demo/validate.html)
- The contained JS may trigger as many ESLint warnings as you wish. You could use the [ESLint demo](https://eslint.org/demo/)

### Loose

In addition to the validity rules, the following rules apply:

- The HTML must contain a title element with the content "Poem" (without the quotes).
- The HTML must contain three slides with the contents of (without the quotes)
    1. "To you I profess:"
    2. "The way to success"
    3. "Is found in the power of CSS"
- Each slide must have an aspect ratio of 16/9.
- Each slide must be scaled to be contained in the viewport, as large as possible (some margins are fine).
- The transition from one slide to another must be animated.
- The slideshow must work without JavaScript, without having to change the URL manually to switch to a slide.
- There must be a key or a combination of keys to switch to the next slide. This key has to be the same for all slides. You may use JavaScript for the keyboard navigation.
- The slides must be consecutively numbered, starting at 1.
- The slides must have a different background color than the document.

### Strict

In addition to the validity and loose rules, the following rules apply:

- The resulting file must be equal in respect to content, looks and features to the original `slide-show.html`.
- The markup structure, the CSS and the JavaScript must be robust. That is, if another slide is added, or more elements are added to a slide, no changes to the markup structure, the CSS and the JavaScript should be necessary.
