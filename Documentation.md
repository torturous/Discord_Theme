# Discord_Theme, Documentation
( Theme created by **AlexFlipnote#0021** & **CyberRonin#5517** )

---

## Writing the theme
Template for each object
> Some stuff can't be separated like Server Settings.

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

---

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

---

## Source-Code Information
This CSS code is 100% self-made, if you do wish to use this code for your creation, please do, just remember to give proper credits to this theme.

Using this theme in any YouTube videos, Screenshots or any other sharing platforms is totally fine. We respect the ability to share experience with everyone else.

The CSS code is made to fit the current code of **Discord Canary**, which is an early version of **Discord**, if you wish to download Canary, click on one of these links:<br>
[Windows](https://discordapp.com/api/download/canary?platform=win)
[Mac](https://discordapp.com/api/download/canary?platform=osx)
[Linux.deb](https://discordapp.com/api/download/canary?platform=linux&format=deb)
[Linux.tar.gz](https://discordapp.com/api/download/canary?platform=linux&format=tar.gz)
