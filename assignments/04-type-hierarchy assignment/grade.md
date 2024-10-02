# Grade

HTML Code Quality: 1/1
CSS Code Quality: 1.75/2
Design Matching: 0.5/1
File Organization & Commits: 1/1
Total: 4.25/5

## Comments
- `html` file should be called `index.html` with a lowercase `i`
- `css` file should be called `main.css` and should be in a `css` folder inside of the `04-type-hierarchy` folder.
- You did not include a link to Google Fonts nor did you set up the `@font-face` so the `Roboto` font is not loading correctly.
- The `h3`, and `h6` should have `text-transform: uppercase;` applied.

Here are the clamp values to match my scales:
```css
h1 {
  font-size: clamp(1.802rem, 4.854vw, 3.052rem);
}
  
h2 {
  font-size: clamp(1.602rem, 4.043vw, 2.441rem);
}
  
h3 {
  font-size: clamp(1.424rem, 3.377vw, 1.953rem);
}
  
h4 {
  font-size: clamp(1.266rem, 2.829vw, 1.563rem);
}
  
h5 {
  font-size: clamp(1.125rem, 2.375vw, 1.25rem);
}

h6 {
  font-size: 1rem;
}
```