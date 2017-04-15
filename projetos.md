# [](#header-1)Faculdade

### [](#header-3)L.I.P.E. TESTE 22


<html>
    <head>
        <link rel="stylesheet" href="css/blueimp-gallery.min.css"><!-- Stylesheet -->
    </head>
    <body>  
        <div id="links">
        <a href="Imgs/LipePhoto/lipe1.png" title="Banana">TESTE</a>
            <a href="Imgs/LipePhoto/lipe2.png" title="Adwadwa">TESTE2</a>
        </div>
        
        <div id="blueimp-gallery-carousel" class="blueimp-gallery blueimp-gallery-carousel">
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
                    container: '#blueimp-gallery-carousel',
                    carousel: true
                }
            );
        </script>
        
        <script src="js/blueimp-gallery.min.js"></script>
    </body>
</html>
