# Discord_Theme, Documentation
( Created by **AlexFlipnote#0021** & **CyberRonin#5517** )

## Writing the theme
Template for each object
```css
/* Target */
/* BOTH */
.stuff
/* DARK */
.theme-dark .stuff
/* LIGHT */
.theme-light .stuff
/* END: Target */
```

## Colour usage
In our theme, we have a global variable called :root, it can be found similar to this
```css
:root {
  /*--<var>: <value>*/
  --accent: mediumpurple;
  --dark-primary: #212121;
  --dark-secondary: #303030;
}
```
**Usage:**
```css
#user-profile-modal .header {
  background-color: var(--dark-primary);
  background-image: none;
}
```
Having global variables makes colours easier to change, rather than changing one by one.
This might not be supportive when it comes to browsers **( Tested & works on: Chrome, Firefox )**
