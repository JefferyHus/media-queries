# CSS Media queries

#### Html viewport meta

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

#### External stylesheet

```html
<link rel="stylesheet" type="text/css" href="smallscreen.css" media="only screen and (max-width: 480px)" />
```

#### Imported styles withing the style element

```css
@import "smallscreen.css" only screen and (max-width: 480px);
```

#### Default css media rules

This is the default screen, device sizes for a responsive design.

```css
/* #### Mobile Phones Portrait #### */
@media screen and (max-device-width: 480px) and (orientation: portrait){
  /* some CSS here */
}

/* #### Mobile Phones Landscape #### */
@media screen and (max-device-width: 640px) and (orientation: landscape){
  /* some CSS here */
}

/* #### Mobile Phones Portrait or Landscape #### */
@media screen and (max-device-width: 640px){
  /* some CSS here */
}

/* #### iPhone 4+ Portrait or Landscape #### */
@media screen and (min-device-width: 320px) and (-webkit-min-device-pixel-ratio: 2){
  /* some CSS here */
}

/* #### iPhone 5 Portrait or Landscape #### */
@media (device-height: 568px) and (device-width: 320px) and (-webkit-min-device-pixel-ratio: 2){
  /* some CSS here */
}

/* #### iPhone 6 and 6 plus Portrait or Landscape #### */
@media (min-device-height: 667px) and (min-device-width: 375px) and (-webkit-min-device-pixel-ratio: 3){
  /* some CSS here */
}

/* #### Tablets Portrait or Landscape #### */
@media screen and (min-device-width: 768px) and (max-device-width: 1024px){
  /* some CSS here */
}

/* #### Desktops #### */
@media screen and (min-width: 1024px){
  /* some CSS here */
}
```
