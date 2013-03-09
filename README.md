# Wealcash-colorpicker

Is a JQuery Plugin to provide a color picker.

This plugin can be used with [twitter boostrap](http://twitter.github.com/bootstrap/) 

## Usage

 - Inport css and javascript

 - Call the function wealcolorpicker

## Example

### Simple Grid

    <div id="grid"></div>
    
    ...
    
    <script>
        $('#grid').wealpalette();
    </script>
    
If you wanna change default values:

    <script>
        $('#grid').wealpalette({between: 3, variant: 7, expurge: 2});
    </script>
    
### Using twitter bootstrap dropdown:

    <input class="weal-colorpicker"/>
    
    ...
    
    <script>
        $('#grid').wealpalette({between: 3, variant: 7, expurge: 2, dropdown: true}});
    </script>
    
## Handling Events

    $('.weal-colorpicker').on('colorSelected', function (event){
       $("body").css("background-color", event.color);
	      console.log(event.color);
    });

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
