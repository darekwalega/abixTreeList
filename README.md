abixTreeList
============

JQuery plugin to create treeview from HTML list

## Usage

Include the jQuery library:
```html
<script src="http://code.jquery.com/jquery-1.11.0.min.js"></script>
```

Include the js and css files from js and css folders:
```html
<script src="js/abixTreeList.min.js"></script>
<link href="css/abixTreeList.css" rel="stylesheet">
```

Include the Twitter Bootstrap css file:
```html
<link href="http://netdna.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap.min.css" rel="stylesheet">
```

Create html list like this:
```html
<ul id="tree">
  <li>one</li>
  <li>two
    <ul>
      <li>two - 1</li>
      <li>two - 2</li>
      <li>two - 3</li>
    </ul>
	</li>
  <li>three</li>
</ul>
```

Initialize plugin:
```javascript
$(document).ready(function() {
  $('#tree').abixTreeList();
});
```

## Options

Change icons:
```javascript
$(document).ready(function() {
  $('#tree').abixTreeList({
    collapsedIconClass  : 'myicon-plus',
    expandedIconClass   : 'myicon-minus'
  });
});
```

## Demo

Example usage in file: demo.html
