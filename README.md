# logseq-bujo-theme
Custom white and dark theme for https://logseq.com/ desktop app.

If you'd like to support my work: https://paypal.me/piotrsss :)

![](https://raw.githubusercontent.com/PiotrSss/logseq-bujo-theme/main/logseq-dark.jpeg)
![](https://raw.githubusercontent.com/PiotrSss/logseq-bujo-theme/main/logseq-white.jpeg)

---

Find and remove that part of the code from custom.css, if you don't like dots in background:
```css
.white-theme #app-container {
    background-image: radial-gradient(#e0e0e0 5%, #fff 5%);
    background-position: 0 0;
    background-size: 25px 25px;
}

.dark-theme #app-container {
    background-image: radial-gradient(#373737 5%, #181818 5%);
    background-position: 0 0;
    background-size: 25px 25px;
}
```
