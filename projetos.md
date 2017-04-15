# [](#header-1)Faculdade

### [](#header-3)L.I.P.E. TESTE 17


<html>
    <head>
        <link rel="stylesheet" href="css/blueimp-gallery.min.css"><!-- Stylesheet -->
    </head>
    <body>        
        <div id="blueimp-image-carousel" class="blueimp-gallery blueimp-gallery-carousel">
            <div class="slides"></div>
            <h3 class="title">Fotos</h3>
            <a class="prev">‹</a>
            <a class="next">›</a>
            <a class="play-pause"></a>
        </div>
        
        <div id="links">
            <a href="Imgs/LipePhoto/lipe1.png" title="Banana" data-description="This is a banana.">Banana</a>
            <a href="Imgs/LipePhoto/lipe2.png" title="Apple" data-description="This is an apple.">Apple</a>
        </div>
        
        blueimp.Gallery(
        document.getElementById('links'),
        {
            onslide: function (index, slide) 
            {
                var text = this.list[index].getAttribute('data-description'),
                    node = this.container.find('.description');
                node.empty();
                if (text) 
                {
                    node[0].appendChild(document.createTextNode(text));
                }
            }
        }
        );
        
        <script src="js/blueimp-gallery.min.js"></script>

    </body>
</html>
