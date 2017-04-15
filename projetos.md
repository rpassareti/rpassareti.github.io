# [](#header-1)Faculdade

### [](#header-3)L.I.P.E. TESTE 5


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
            <a href="Imgs/LipePhoto/lipe1.png" title="Banana">
                <img src="Imgs/LipePhoto/lipe1  .png" alt="Banana">
            </a>
            <a href="Imgs/LipePhoto/lipe2.png" title="Apple">
                <img src="Imgs/LipePhoto/lipe2.png" alt="Apple">
            </a>
            <a href="Imgs/LipePhoto/lipe3.png" title="Orange">
                <img src="Imgs/LipePhoto/lipe3.png" alt="Orange">
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
        
        <script src="js/blueimp-gallery.min.js"></script> <!-- Gallery script -->
    </body>
</html>
