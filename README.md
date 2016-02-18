# Gallery Plugin

See the demo: http://ivangm4.github.io/

This plugin makes it easier to display a gallery of 9 images. You can structure and increase the images quickly and easily following the next steps:

<b>1.- Add the following markup:<b>
```html
<!-- Remember: You have to put the same title twice in div of each image. -->
<div class="container">
	<div class="image col-md-4">
		<img src="urlimage1" title="Title 1"/>
		<div class="galleryTitle">Title 1</div>
	</div>
	
	...
	
	<div class="image col-md-4">
		<img src="urlimage9" title="Title 9"/>
		<div class="galleryTitle">Title 9</div>
	</div>
</div>
```

<b>2.- Link stylesheets:<b>
```html
<!-- Gallery. -->
<link rel="stylesheet" href="css/gallery.css">
<!-- Bootstrap. -->
<link rel="stylesheet" href="css/bootstrap.min.css">
```

<b>3.- Don't forget to add the jQuery library:<b>
```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
<script>window.jQuery || document.write('<script src="js/jquery-1.12.0.min.js"><\/script>')</script>
```

<b>4.- Link the jQuery file:<b>
```html
<script type="text/javascript" src="js/gallery.js"></script>
```
