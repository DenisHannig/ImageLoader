# ImageLoader
Currently ther first version of the ImageLoader depends on the jQuery library. So make sure to use it in your project, too!

## Usage
1. Include the image-loader.lib.js Library to your HTML Project:
```bash
<html>
  <head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="image-selector.lib.min.js"></script>
    ...
  </head>
  ...
</html>
```

3. Add the custom element tag <image-selector></image-selector> to your HTML document:
```bash
<image-selector id="any_id">
  <image-option id="id1" title="Option 1" image="filename/or/url/" />
  <image-option id="id2" title="Option 2" image="filename/or/url/" />
  ...
</image-selector>
```

5. It will be automatically initialized by the image-loader.lib.js Library.
