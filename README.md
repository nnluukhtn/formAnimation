[jQuery Form Animation Plugin](https://github.com/nnluukhtn/formAnimation) - Form Animation: when form validation <3 animate.css
================================

The jQuery Form Animation Plugin provides drop-in animation for your existing forms, while making all kinds of customizations to fit your application really easy.

## Getting Started

### Downloading the required libraries

jQuery can be downloaded from https://jquery.com/

jQuery Validation Plugin can be downloaded from http://jqueryvalidation.org/

### Including it on your page

Include jQuery and the plugin on a page. Then select a form to add animation and call the `formAnimation` method.

```html
<form>
	<input required>
</form>
<script src="jquery.js"></script>
<script src="jquery.validate.js"></script>
<script src="formAnimation.js"></script>
<script>
$("form").formAnimation({ animatedClass: 'shake' });
</script>
```

Alternatively include jQuery and the plugin via requirejs in your module.

```js
define(["jquery", "jquery.validate", "formAnimation"], function( $ ) {
	$("form").formAnimation({ animatedClass: 'shake' });
});
```

## Reporting issues and contributing code

Bug reports and pull requests are welcome on GitHub at https://github.com/nnluukhtn/formAnimation.

## License
Copyright &copy; Luu Nguyen<br>
Licensed under the MIT license.
