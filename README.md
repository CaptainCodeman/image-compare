_[Demo and API docs](http://captaincodeman.github.io/image-compare/)_

##&lt;image-compare&gt;

`image-compare` enables visual comparison of images by swiping between them.

Unlike most other image comparison libraries, it allows zooming and scrolling so
that areas of an image can be compared in detail and smoothing is disabled so the
pixel-level detail can be clearly examined.

Both images are also loaded using `<img>` elements instead of a `background-image`
of a `<div>` which, on chrome at least, results in flickering and changes when
comparing large images reduced in size.

Example:

    <image-compare src="original.jpg" with="replacement.jpg"></image-compare>

The images should be the same size
