# image-orientation-fix

Lightweight solution for fixing image orientation issues. This tool reads the EXIF data of the given image in order to determine the appropiate transformations required to normalize image orientation.

Example usage:

```php
require_once 'OFImage.php'; 
 
$image = new OFImage( 'test.jpg' ); 
$image->fix(); 
$image->save( 'test_fixed.jpg' );
```
