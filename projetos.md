# [](#header-1)Faculdade

### [](#header-3)L.I.P.E. TESTE 2


<html>
    <link rel="stylesheet" href="css/blueimp-gallery.js"> <!-- Stylesheet -->
    <body>
        <div id="blueimp-gallery" class="blueimp-gallery"> <!-- Gallery widget -->
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
            document.getElementById('links').onclick = function (event) {
                event = event || window.event;
                var target = event.target || event.srcElement,
                    link = target.src ? target.parentNode : target,
                    options = {index: link, event: event},
                    links = this.getElementsByTagName('a');
                blueimp.Gallery(links, options);
            };
        </script>
        
        <script src="js/blueimp-gallery.min.js"></script> <!-- Gallery script -->
    </body>
</html>
