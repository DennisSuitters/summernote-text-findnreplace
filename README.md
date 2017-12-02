# summernote-text-findnreplace
A plugin for the [Summernote](https://github.com/summernote/summernote/) WYSIWYG editor.

Adds a button to the Toolbar that adds an area to the Toolbar that allows Find and Replace text in the editor.

Here are the functions you can do with this plugin:
- Find text which the results are highlighted with a notification of how many instances were found.
- Selecting text before opening the findNReplace plugin will copy the selected text into the find field.
- Selecting text after optening the findNReplace plugin will replace the selection with text entered in the replace field.

![summernote-text-findnreplace](summernote-findnreplace.png)

### Installation

#### 1. Include JS

Include the following code after including Summernote:

```html
<script src="summernote-text-findnreplace.js"></script>
```

#### 2. Supported languages
Currently available in English!

#### 3. Summernote options
Finally, customize the Summernote Toolbar.

```javascript
$(document).ready(function() {
    $('#summernote').summernote({
    tabsize:2,
    toolbar:[
        ['custom',['findnreplace']],
        ['style',['style']],
        ['font',['bold','italic','underline','clear']],
        ['fontname',['fontname']],
        ['color',['color']],
        ['para',['ul','ol','paragraph']],
        ['height',['height']],
        ['table',['table']],
        ['insert',['media','link','hr']],
        ['view',['fullscreen','codeview']],
        ['help',['help']]
    ]});
```

#### 4. Check out our other Summernote Plugins via our main Github page.
- [Diemen Design](https://github.com/DiemenDesign/)
