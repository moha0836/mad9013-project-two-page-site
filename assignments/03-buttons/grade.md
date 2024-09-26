# Grade

HTML Code Quality: 0.75/1
CSS Code Quality: 0.75/2
Design Matching: 1/1
File Organization & Commits: 0.75/1
Total: 3.25/5

## Comments

### HTML
- `<div>` elements should only ever be added when the existing html structure is unable to create the layout you want to make.
- You have applied no styling to you `<div>` elements. That is typically an indicator that the `<div>` is not needed and should be removed.

### CSS
- Do not use `px` units. They are absolute units and cause accessibility issues. You should only be using `em` and `rem`.
- Use `em` for `padding` and `border-radius` size. This will allow the `padding` to grow/shrink based on the size of the text. If you do so, you don't need to change the `padding` on the small/large buttons;
- `.btn--primary` class is not necessary. Put all primary styles on the base `.btn` so that applying just `btn` to an element makes it look correct as a primary button.
- Don't apply `margin` on the buttons as we want these styles to be flexible and useable in all kinds of locations when we may not want `margin`.
- You should set the `border` property on the original `.btn` and have it match the `background-color`. That will have the heights match between the normal and outline variants.
- You should include both a `:hover` and a `:focus`

### File Organization & Commits
- There were a number of file organization issues, some of which I fixed for your already. Something that still needs to be fixed:
  - CSS file should be called `main.css` and should be in a `css` folder inside of the `03-buttons` folder.

Review your files for specific comments.