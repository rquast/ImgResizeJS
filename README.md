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
imageResize.crop(300, 400);      // {dest_w:300, dest_h:400}

// Resize to height
imageResize.resizeToHeight(300); // {dest_w: 436.3636363636363, dest_h: 300}

// Resize to width
imageResize.resizeToWidth(300);  // {dest_w: 300, dest_h: 206.25}

// Scale
imageResize.scale(150);          // {dest_w: 1200, dest_h: 825}

// Resize
imageResize.resize(300, 400);    // {dest_w:300, dest_h:400}

```
