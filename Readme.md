# sudoku_js

Sudoku js is a simple plugin for making any table element into a sudoku game.

```html
<table id="sudoku"></table>
```

# Installation

Load the [plugin](https://github.com/geon696/sudoku_js) into your page.

> !Warning!
> The script contains the jquery code inside. You might need to be > handle the `$` accordingly.

```html
<script src="./path/to/the/downloaded/plugin/sudoku.js"></script>
```

# How to use

After creating the html element from above, and adding the script into your page just load it in another script

```html
<script type="text/javascript">
	$(document).ready(function(){
		$("table#sudoku").sudoku();
	});
</script>
```