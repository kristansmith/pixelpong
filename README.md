pixelpong
=========

jQuery/PHP plugin component for easy "fade on hover" alternate image creation 

##USAGE
- simple include the pixelpong folder in your js directory
- check the .php file for your img directory constant
- include the .js file in your HTML page <script src="js/pixelpixie/jquery.pixelpixie.js" type="text/javascript"></script>
- add a class of .pixelpong to any images you want to create overlays for
- add the following code to you .css

    .pixelpongFrame{ position:relative;}
    .pixelpongFrame img.pixelpong{position:absolute; top:0; left:0; z-index:50;}
