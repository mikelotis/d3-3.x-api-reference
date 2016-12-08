> [API Reference](API-Reference.md) ▸ [Geometry](Geometry.md) ▸ **Polygon Geom**

**The [D3 4.0 API Reference](https://github.com/d3/d3/blob/master/API.md) has moved. This page describes the D3 3.x API.**

<a name="polygon" href="Polygon-Geom.md#polygon">#</a> d3.geom.<b>polygon</b>(<i>vertices</i>)

Returns the input array of vertices with additional methods attached, as described below.

<a name="area" href="Polygon-Geom.md#area">#</a> polygon.<b>area</b>()

Returns the signed area of this polygon. If the vertices are in counterclockwise order, the area is positive, otherwise it is negative.

<a name="centroid" href="Polygon-Geom.md#centroid">#</a> polygon.<b>centroid</b>()

Returns a two-element array representing the centroid of this polygon.

<a name="clip" href="Polygon-Geom.md#clip">#</a> polygon.<b>clip</b>(<i>subject</i>)

Clips the *subject* polygon against this polygon. In other words, returns a polygon representing the intersection of this polygon and the *subject* polygon. Assumes the clip polygon is counterclockwise and convex.
