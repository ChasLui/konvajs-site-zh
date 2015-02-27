title: Optimizing Strokes Tip
---

### Remove stroke from hit

If you have a shape with fill and very small stroke you can set `shape.strokeHitEnabled(false)` to remove stroke from hit graph.
Don't use this property if your stroke is critical for hit detection.

### Disable shadow for stroke

If you don't really need shadow for stroke you can set `shape.shadowForStrokeEnabled(false)`.
Remember that shadow will be disable if you are using `Konva.Line` without fill.


{% iframe /downloads/code/performance/Listening_False.html %}

{% include_code Konva Disable Listening Shapes Demo performance/Listening_False.html %}