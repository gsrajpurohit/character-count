# Character Count - Jquery Input Character Counter Plugin
counts the character entered into an input or textarea also limits the maximum characters

### 1. Get a copy of the plugin
You can download the plugin from GitHub.

### 2. Load the required files
Inside the page's head tag include the char-count's CSS file.
```
<link rel="stylesheet" type="text/css" href="css/char-count.css" />
```

In the page's footer, just before, include the required JavaScript files.

```
<script src="js/char-count.min.js"></script>
```

### 3. Create the HTML markup
`<input id="my-input" />`

### 5. Instantiate the Character Counter plugin
```
<script type="text/javascript">
    jQuery( document ).ready(function( $ ) { 
        $( '#my-input' ).char_count({ 
            maxValue: 30,
            showMaxValue: true,
            background: "#34BC00",
            hideOnBlur: false,
            position: "top", 
        }); 
    }); 
</script>
```
### Demo
[Demo](https://jsfiddle.net/g_s_rajpurohit/ucdgj9yt/4/).

### Support
If you found a bug or have a feature suggestion, please email me on rajpurohitganpat@gmail.com.
If you need help with implementing the char-count in your project feel free to contact me on rajpurohitganpat@gmail.com.

License The plugin is available under the [MIT license](https://opensource.org/licenses/MIT).

