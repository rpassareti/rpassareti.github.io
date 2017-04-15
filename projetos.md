# [](#header-1)Faculdade

### [](#header-3)L.I.P.E. TESTE 3


<html>
    <link rel="stylesheet" href="css/blueimp-gallery.js"> <!-- Stylesheet -->
    <body>
        <div id="blueimp-gallery-carousel" class="blueimp-gallery blueimp-gallery-carousel"> <!-- Gallery widget -->
        <div class="slides"></div>
        <h3 class="title"></h3>
        <a class="prev">‹</a>
        <a class="next">›</a>
        <a class="close">×</a>
        <a class="play-pause"></a>
        <ol class="indicator"></ol> <!-- Gallery widget -->
        </div>
        
        <div id="links"><!-- Gallery images -->
            <a href="https://raw.githubusercontent.com/rpassareti/rpassareti.github.io/master/Imgs/LipePhoto/lipe1.png" title="Banana">
                <img src="https://raw.githubusercontent.com/rpassareti/rpassareti.github.io/master/Imgs/LipePhoto/lipe1.png" alt="Banana">
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
