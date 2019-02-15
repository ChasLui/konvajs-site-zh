title: HTML5 Canvas Custom Hit Detection Function Tutorial
---

To create a custom hit draw function for a shape with Konva, we can set
the `hitFunc` property.  A hit draw function is the function that Konva
will use to draw a region used for hit detection.  Using a custom draw hit
function can have several benefits, such as making the hit region larger
so that it's easier for users to interact with a shape, making some portions
of a shape detectable and others not, or simplifying the hit draw function
in order to improve rendering performance.

Also take a look into some [best practices](/docs/shapes/Custom.html) of writing custom `sceneFunc` that can be used for `hitFunc` too.

`hitFunc` is a function with two arguments: [Konva.Context](/api/Konva.Context.html) renderer and a shape instance.

Instructions: Mouseover, mouseout, mousedown, and mouseup over the star and
observe that the hit region is an over sized circle encompassing the shape.


{% iframe /downloads/code/events/Custom_Hit_Region.html %}

{% include_code Konva Custom_Hit_Region Demo events/Custom_Hit_Region.html %}
