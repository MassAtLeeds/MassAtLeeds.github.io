---
layout: postMB
title:  defaultMB
categories: maps
---
 <script src="https://raw.github.com/MassAtLeeds/RouteFactor/master/tr.js"></script>


<div> <div id='map' style="position:absolute; top:0; bottom:0; width:60%; "></div>
</div>

<script>
var map = L.mapbox.map('map', 'examples.map-9ijuk24y')
    .setView([53.8, -1.55], 13);
    var gj = new L.geoJson(tr, {
        
       }).addTo(map);
</script>


This was created via:

{% highlight html %}
<div id='map' style="position:absolute; top:0; bottom:0; width:60%; "></div> 

<script>
var map = L.mapbox.map('map', 'examples.map-9ijuk24y')
    .setView([40, -74.50], 9);
</script>
{% endhighlight %}


