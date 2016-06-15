Plugin Prism for TinyMCE 4
======================
Insert code with prism for tinyMCE 4

Plugin [prism](http://prismjs.com/) for [tinymce](http://www.tinymce.com)
                      
![Prism](https://cloud.githubusercontent.com/assets/356674/16072472/5ad82f4c-32e1-11e6-9e2e-3024b1e762f4.png)

Authors
-------

 * Gerits Aurelien (Author-Developer) contact[at]aurelien-gerits[point]be
 
 ###Installation
 * Download archive
 * Unzip archive in tinyMCE plugin directory (tiny_mce/plugins/)

###Configuration
 ```html
<script type="text/javascript">
tinymce.init({
	selector: "textarea",
	plugins: [
			"advlist autolink lists link image charmap print preview anchor",
			"searchreplace visualblocks code fullscreen",
			"insertdatetime media table contextmenu paste prism"
			],
	toolbar: "insertfile undo redo | styleselect | bold italic | alignleft aligncenter alignright alignjustify | bullist numlist outdent indent | link image| prism"
	});
</script>
```
