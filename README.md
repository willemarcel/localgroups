Local OpenStreetMap Groups
===========

This is an annotated map of local OpenStreetMap user groups worldwide. 

Wait, don't we already have one of those? Yes, [http://usergroups.openstreetmap.de/](here). But that map relies on adding specific code to the OpenStreetMap wiki and consequently, a lot of groups just don't appear on that map. 

### Adding your local group

If you want to add your group, here's how. 

**If you're familiar with GeoJSON and Github**, fork this repository, add your group to the GeoJSON file, and submit a pull request.

**If you don't know what all that means**, simply [https://github.com/osmlab/localgroups/issues/new](open an issue) with the details of your group and we'll make sure it gets added.

#### Point or polygon?

The simplest way to add your group is by adding a point that reflects where your local group is active. Even better is to add a polygon to cover the area that your local group services. Use [http://geojson.io](geojson.io) to draw one.

### Using this map elsewhere

If you click on the geoJSON file above, you will see a pretty map. You can click on the markers to see the information assiciated with each group.

You can use this map elsewhere by adding this bit of code to your web page:

    <script src="https://embed.github.com/view/geojson/osmlab/localgroups/blob/master/osmgroups.geojson"></script>

Or you can use the geoJSON directly in any way you see fit.

Happy mapping!
