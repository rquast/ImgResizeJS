# JS-Img-Resize
> A simple, dependancy-free image resizer written in JavaScript

## Usage

```html
<script src="ImgResize.min.js"></script>
```

```javascript
var w = 800;
var h = 550;
var allowEnlarge = false;
var imageResize  = ImageResizer(w, h, allowEnlarge);

// Crop
imageResize.crop(300, 400);      // {w:300, h:400}

// Resize to height
imageResize.resizeToHeight(300); // {w: 436.3636363636363, h: 300}

// Resize to width
imageResize.resizeToWidth(300);  //  {w: 300, h: 206.25}

// Scale
imageResize.scale(150);          // {w: 1200, h: 825}

// Resize
imageResize.resize(300, 400);    // {w:300, h:400}

```
