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

## FAQ
**Where can I talk with you?**<br>Here: https://discord.gg/J4mwTJR

**What should I use, theme.css or autotheme.css?**<br>That really depends on you. If you are a developer and want
to change stuff, download the theme.css, however if you wish for a theme that updates, use **autotheme.css** :P

**How can I get a background on this theme?**<br>Use the **autotheme.css** and import the plugin from [Plugins.md](https://github.com/AlexFlipnote/Discord_Theme/blob/master/Plugins.md)

**How do I use plugins?**<br>There should be a screenshot of an example in [Plugins.md](https://github.com/AlexFlipnote/Discord_Theme/blob/master/Plugins.md)

**How do I use the theme?**<br>[BeautifulDiscord](https://github.com/beautiful-discord-community/resources/wiki/Installing-BeautifulDiscord) should be useful to use the skin

**Does it support BetterDiscord?**<br>Yes, however I do highly recommended to use **BeautifulDiscord**<br>
( You can find BetterDiscord version [here](https://github.com/AlexFlipnote/Discord_Theme/blob/master/assets/BetterDiscord.theme.css) )

**I found a bug, what do I do?**<br>Make a **Pull Request / Issue**

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
