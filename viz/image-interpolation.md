## image interpolation

![](figures/interpolation.png)
https://matplotlib.org/stable/gallery/images_contours_and_fields/image_antialiasing.html

### pre-RGB
- data is up and down sampled & values are filled in/interpolated & then colormapped

### post-RGB
- data is colormapped and then the colormapped data is transformed s.t there are colors that may not be in the color bar  (that are not in $\nu^{-1}$) 
 
 > This behaviour is more like a typical image processing package, but note that purple is not in the original colormap, so it is no longer possible to invert individual pixels back to their data value.
