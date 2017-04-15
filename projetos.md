# [](#header-1)Faculdade

### [](#header-3)L.I.P.E. TESTE 28


<html>
    <head>
        <link rel="stylesheet" href="css/blueimp-gallery.min.css">
    </head>
    <body>
        <script src="js/blueimp-gallery.min.js"></script>
        <div id="links">
        <a href="Imgs/LipePhoto/lipe1.png" title="Banana">TESTE</a>
            <a href="Imgs/LipePhoto/lipe2.png" title="Adwadwa">TESTE2</a>
        </div>
        
        <div id="blueimp-image-carousel" class="blueimp-gallery blueimp-gallery-carousel blueimp-gallery-display">
            <div class="slides"></div>
            <h3 class="title"></h3>
            <a class="prev">‹</a>
            <a class="next">›</a>
            <a class="play-pause"></a>
            <ol class="indicator"></ol>
        </div>
        
        <script>
            blueimp.Gallery(
                document.getElementById('links').getElementsByTagName('a'),
                {
                    container: '#blueimp-image-carousel',
                    carousel: true
                }
            );
        </script>
    </body>
    
</html>
