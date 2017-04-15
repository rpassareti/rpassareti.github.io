# [](#header-1)Faculdade

### [](#header-3)L.I.P.E.



<html>
<body>
<link rel="stylesheet" href="css/blueimp-gallery.min.js">

<div id="links">
    <a href="https://raw.githubusercontent.com/rpassareti/rpassareti.github.io/master/Imgs/LipePhoto/lipe1.png" title="Lipe 1">
        <img src="https://raw.githubusercontent.com/rpassareti/rpassareti.github.io/master/Imgs/LipePhoto/lipe1.png" alt="Lipe 1">
    </a>
    <a href="Imgs/LipePhoto/lipe2.png" title="Lipe 2">
        <img src="Imgs/LipePhoto/lipe2.png" alt="Lipe 2">
    </a>
    <a href="Imgs/lipe3.png" title="Lipe 3">
        <img src="Imgs/lipe3.png" alt="Lipe 3">
    </a>
</div>

<!-- The Gallery as inline carousel, can be positioned anywhere on the page -->
<div id="blueimp-gallery-carousel" class="blueimp-gallery blueimp-gallery-carousel">
    <div class="slides"></div>
    <h3 class="title"></h3>
    <a class="prev">‹</a>
    <a class="next">›</a>
    <a class="play-pause"></a>
    <ol class="indicator"></ol>
</div>



<script>blueimp.Gallery(
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
