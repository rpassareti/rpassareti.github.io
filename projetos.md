# [](#header-1)Faculdade

### [](#header-3)L.I.P.E. TESTE 6


<html>
    <link rel="stylesheet" href="css/blueimp-gallery.css"> <!-- Stylesheet -->
    <body>
        <div id="blueimp-image-carousel" class="blueimp-gallery blueimp-gallery-carousel">
            <div class="slides"></div>
            <h3 class="title"></h3>
            <a class="prev">‹</a>
            <a class="next">›</a>
            <a class="play-pause"></a>
        </div>
        
        <div id="links"><!-- Gallery images -->
            <a href="Imgs/LipePhoto/lipe1.png" title="1">
                <img src="Imgs/LipePhoto/lipe1  .png" alt="1">
            </a>
            <a href="Imgs/LipePhoto/lipe2.png" title="2">
                <img src="Imgs/LipePhoto/lipe2.png" alt="2">
            </a>
            <a href="Imgs/LipePhoto/lipe3.png" title="3">
                <img src="Imgs/LipePhoto/lipe3.png" alt="3">
            </a> <!-- Gallery images -->
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
        
        <script src="js/blueimp-gallery.js"></script> <!-- Gallery script -->
    </body>
</html>
