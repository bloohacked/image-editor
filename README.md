# image-editor

## what is this
this is a way to edit images on web pages for pranks.

## how do I use this
first add thease 2 bookmarklets
###### enable
```
var enabled = true; var images = document.images; for(let i=0;i<images.length;i++) { images[i].addEventListener("click", function(e) { if(enabled==true){ this.src = prompt("enter a new image url"); } }, false);}
```
###### disable
```
enabled = false;
```
than click an image and paste in a new image url.
