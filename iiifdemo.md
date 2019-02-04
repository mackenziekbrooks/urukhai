---
layout: page
title: IIIF demo
---

<div id="openseadragon1" style="width: 100%; height: 500px; border: 1px solid grey"></div>

<script src="/assets/js/openseadragon/openseadragon.min.js"></script>

<script type="text/javascript">
    var viewer = OpenSeadragon({
        id: "openseadragon1",
      minZoomImageRatio: 1,
      prefixUrl: "/assets/js/openseadragon/images/",
      tileSources: "http://iiif.wlu.edu/iipsrv?IIIF=huon/converted/b065v.tif/info.json",
 
    });

</script>
