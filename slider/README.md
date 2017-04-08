# CSS3 jQuery Slice Slider plugin

Simple responsive slider with awesome CSS3 slice animation.

## Demo

http://github.indyworks.ru/indysliceslider/

## Installation

Include script *after* the jQuery library:

```html
<script src="/path/to/jquery.indySliceSlider.js"></script>
```
Include css:

```html
<link rel="stylesheet" type="text/css" href="css/indySliceSlider.css">
```

### HTML

```html
<section class="indy-slice-slider">
	<section class="slide-container">
		<article class="slice-slide">
			<section class="slice-part" >
				<section class="slice-img-container">
				<section class="slice-img" style="background-image: url(...PATH/TO/IMAGE...);"></section>
				</section>
			</section>
			... YOUR SLIDE CONTENT...
		</article>
		<article class="slice-slide">
		...
		</article>
    </section>
</section>
```

### jQuery

Use the plugin as follows:

```js
$('.indy-slice-slider').indySliceSlider();
```
## License

This plugin is available under [the MIT license](http://mths.be/mit).
