# PrognRoll

> A tiny, lightweight jQuery plugin that creates scroll progress bar on the page

## Install

Load jQuery and include PrognRoll file

```html
<script src="jquery.js"></script>
<script src="src/prognroll.js"></script>
```

or use CDN

```html
<script src="https://code.jquery.com/jquery-3.1.1.min.js"></script>
<script src="https://rawcdn.githack.com/mburakerman/prognroll/5f8df2b06051e1508396d276d470e1153a4f8d1b/src/prognroll.js"></script>
```

## Usage

To see scrolling progress on your page, you need to activate PrognRoll.

```js
$(function() {
  $("body").prognroll();
});
```
That's it!

You can also customize the progress bar. These are default settings.

```js
$(function() {
  $("body").prognroll({
    height: 5, // progress bar height
    color: "#50bcb6", // progress bar background color
    custom: false // if you make it true, you can add your custom div and see it's scroll progress on the page
  });
});
```

## Examples

Body

```html
<body>
<!-- Content -->
</body>
```
```js
$(function() {
  $("body").prognroll();
});
```
[Body demo on CodePen](https://codepen.io/anon/pen/NQqLOG)

Custom div

```html
<div class="box">
<!-- Content -->
</div>
```

```js
$(function() {
  $(".box").prognroll({
    custom: true
  });
});
```
[Custom div demo on CodePen](https://codepen.io/anon/pen/oKXPQP)

## Size

1 kb minified

## License

Licensed under the MIT License.
