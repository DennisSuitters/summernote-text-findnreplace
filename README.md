# summernote-text-findnreplace
A plugin for the [Summernote](https://github.com/summernote/summernote/) WYSIWYG editor.

Adds a button to the Toolbar that opens a Modal that allows Find and Replace text in the editor.

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

#### 4. Check out our other Summernote Plugins
- [Summernote Image Attributes](https://github.com/StudioJunkyard/summernote-image-attributes)
  - Add Button to Image Popup to enable editing various Image Attributes, including adding Links.
- [Summernote Image Caption It](https://github.com/StudioJunkyard/summernote-image-captionit)
  - Add Button to Image Popup to add FigCaption and Figure Elements using the TITLE or ALT Text.
- [Summernote Image Shapes](https://github.com/StudioJunkyard/summernote-image-shapes)
  - Add Button to Image Popup to enable selecting Bootstrap Image Shapes.
- [Summernote Video Attributes](https://github.com/StudioJunkyard/summernote-video-attributes)
  - Insert Video's from various Streaming Services, with Options Editing.
- [Summernote Cleaner](https://github.com/StudioJunkyard/summernote-cleaner)
  - Clean Pasted and Existing Markup, mainly for cleaning text from Office Document software.
- [Summernote Save Button](https://github.com/StudioJunkyard/summernote-save-button)
  - Add a Save Button to the Toolbar when Summernote is inside a form with a Textarea to easily save your document.
- [Summernote SEO](https://github.com/StudioJunkyard/summernote-seo)
  - Adds a Dropdown to the Toolbar that allows extracting selected text and inserts it into input elements for editing.
