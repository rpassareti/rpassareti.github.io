# [](#header-1)Faculdade

### [](#header-3)L.I.P.E. a



<html>
<link rel="stylesheet" href="css/blueimp-gallery.min.css">
<div id="blueimp-gallery" class="blueimp-gallery">
    <div class="slides"></div>
    <h3 class="title"></h3>
    <a class="prev">‹</a>
    <a class="next">›</a>
    <a class="close">×</a>
    <a class="play-pause"></a>
    <ol class="indicator"></ol>
</div>

<div id="links">
    <a href="Imgs/lipe1.png" title="Lipe 1">
        <img src="Imgs/lipe1.png" alt="Lipe 1">
    </a>
    <a href="Imgs/lipe2.png" title="Lipe 2">
        <img src="Imgs/lipe2.png" alt="Lipe 2">
    </a>
    <a href="Imgs/lipe3.png" title="Lipe 3">
        <img src="Imgs/lipe3.png" alt="Lipe 3">
    </a>
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




<script src="js/blueimp-gallery.min.js"></script>

</html>
