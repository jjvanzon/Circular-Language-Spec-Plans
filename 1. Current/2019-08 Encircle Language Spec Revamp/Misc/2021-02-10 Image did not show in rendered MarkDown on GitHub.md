- Image does not show in rendered MarkDown on GitHub.
- MarkDown: ![Image in Sub Folder](images/ImageInSubFolder2.jpg)
- Folder itself is "Images" (starts with upper case letter).
- Resolved URL has "images" (starts with lower case letter): https://github.com/jjvanzon/JJ.Demos.MarkDownTest/blob/master/Sub-Folder%20with%20MD's/images/ImageInSubFolder2.jpg
- Changing resolved URL's "images" to "Images" leads to the (not raw) image page.

- Exp: Changing image reference to starting with capital letter.
- Image does show in rendered MarkDown on GitHub.
- MarkDown: ![Image in Sub Folder](Images/ImageInSubFolder2.jpg)

- Hyp: precise casing matters in image URL's.
- Exp: I might stick to URL-friendlier notation: lower case letters, dashes between words.