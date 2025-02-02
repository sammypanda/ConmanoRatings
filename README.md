<h1 align="center">ConmanoRatings</h1>

<h6 align="center">All Conmano's favourite media!</h6>

<p align='center'>
    <img alt="screenshot of the website showing a list of entries from games like bad parenting rated 7.72, welcome home rated 5.5, pretend it's not there rated 4.5 (they all have uniform media art to the left of them). The background has a white retro OSX pattern and the top rightmost side of the screen has a checkbox labelled 'Scroll'" src='docs/assets/screenshot.png' width='60%' height='auto'></img>
</p>

<br>

## Custom CSS
Paste these in to modify your OBS source to achieve different settings.
### autoscroll
```css
/* autoscroll CSS without button */
#scrollbox {
  display: none;
}
label[for="scrollbox"] {
  display: none;
}
.list { /* can change speed by changing '10s' */
  animation: autoscroll 10s infinite linear;
}
```

### transparent background
```css
/* transparent background */
body {
  background: transparent !important;
}
```