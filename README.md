# CKEditor plugin string counter
========

This plugin inserts counter into a footer that contains the current character of an editor (include tags). 

To activate the plugin you must include this plugin - "strlen".  If textarea have maxlength attribute, its show after slash.

Examples
========

To create an editor with character counter:

``` javascript
CKEDITOR.replace('contentTextarea', {
	height: 200,
	extraPlugins: 'strlen',
	maxLength: 0,
	toolbar: 'TinyBare',
	toolbar_TinyBare: [['Bold','Italic','Underline'],['Undo','Redo'],['Cut','Copy','Paste']]
});
```
		
