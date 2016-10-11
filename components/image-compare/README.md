_[Demo and API docs](http://captaincodeman.github.io/image-compare/)_

##&lt;image-compare&gt;

`image-compare` enables visual comparison of images by swiping between them.

**Status**: *Experimental / Work in progress, likely only works in Chrome*

Unlike most other image comparison libraries which simply provide a before and
after comparison, this was designed for comparing images in detail (specifically
as a visual aid while working on an upload component that provides image resizing,
sharpening, and re-encoding as Jpeg or WePp). It allows zooming and scrolling so
that areas of an image can be compared in detail and smoothing is disabled to the
pixel-level differences between them can be clearly examined.

Both images are also loaded using `<img>` elements instead of a `background-image`
of a `<div>` to avoid the flickering that the latter introduced when viewing large
images.

Example of use:

    <image-compare src="original.jpg" with="replacement.jpg"></image-compare>

NOTE: Both images should be the same dimensions.

Source images / some styling based on [this article](https://codyhouse.co/gem/css-jquery-image-comparison-slider/)
