PHP Facebook Gallery
====================

Simple PHP program to display public Facebook galleries. **[Live Demo](http://demos.castletwo.com/facebook-gallery/)**

**Features:**

- Gallery caching to static HTML files
- Uses [prettyPhoto](http://www.no-margin-for-errors.com/projects/prettyphoto-jquery-lightbox-clone/) for large images
- Clean UI based on [Twitter Bootstrap](http://twitter.github.com/bootstrap/)


Audience / Usage
----------------

The intended audience/usage is for businesses who have both a website and Facebook page. 
This gallery will allow you update your photos in one place and have them display on both your Facebook page and website.

Instalation
-----------

- Download files from https://github.com/jveldboom/facebook-gallery/downloads
- Upload to your server
- Change the permission to the "cache" directory to 777
- Enjoy!

Bugs / Issues / Suggestions
---------------------------

Please let us know if you see any bugs or issues. And by all means, if you can help make any improvements, please fork the project and help!

No Queda muy Claro en el Code donde va el ID de el perfil o Fanpage!! :)
Donde va el ID de la Fanpage !!?? 

<?php
define(‘PAGE_ID’, ’00000000000000′);
define(‘APP_ID’,”);
define(‘APP_SECRET’,”);
$face = new FacePageAlbum(PAGE_ID, $_GET['aid'], $_GET['aurl'], APP_ID, APP_SECRET);
?>

Veréis que hay 3 “define” del cuál solo nos interesa el primero, donde hay que substituir los “0000″ por el id de nuestra página de Facebook. En mi caso mi fanpage con la que hago los tests es “140083382761694″ , quedaría así:

define(‘PAGE_ID’, ’188065314541169′);

Gracias!! :)
