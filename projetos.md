# [](#header-1)Faculdade

### [](#header-3)L.I.P.E. TESTE 9


<html>
    <head>
        <link rel="stylesheet" href="css/blueimp-gallery.css">
        <link rel="stylesheet" href="css/blueimp-gallery-indicator.css">
        <link rel="stylesheet" href="css/blueimp-gallery-video.css"><!-- Stylesheet -->
    </head>
    <body>
        <div id="links">
            <a href="Imgs/LipePhoto/lipe1.png" title="Banana">
            </a>
            <a href="Imgs/LipePhoto/lipe2.png" title="Apple">
            </a>
            <a href="Imgs/LipePhoto/lipe3.png" title="Orange">
            </a>
        </div>
        <div id="blueimp-image-carousel" class="blueimp-gallery blueimp-gallery-carousel">
            <div class="slides"></div>
            <h3 class="title"></h3>
            <a class="prev">‹</a>
            <a class="next">›</a>
            <a class="play-pause"></a>
        </div>
        
        <script src="js/blueimp-helper.js"></script>
        <script src="js/blueimp-gallery.js"></script>
        <script src="js/blueimp-gallery-fullscreen.js"></script>
        <script src="js/blueimp-gallery-indicator.js"></script>
        <script src="js/blueimp-gallery-video.js"></script>
        <script src="js/blueimp-gallery-vimeo.js"></script>
        <script src="js/blueimp-gallery-youtube.js"></script>
        <script src="js/vendor/jquery.js"></script>
        <script src="js/jquery.blueimp-gallery.js"></script>
        
        <script>
            blueimp.Gallery(
                document.getElementById('links').getElementsByTagName('a'),
                {
                    container: '#blueimp-gallery-carousel',
                    carousel: true
                }
            );
        </script>

    </body>
</html>
