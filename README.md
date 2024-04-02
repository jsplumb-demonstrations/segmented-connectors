## Segmented connectors

### What are segmented connectors?

This connector type consists of a set of straight line segments, with the option to smooth the segments into a series of Bezier curves. This type of connector is useful for a wide range of different UIs - flowcharts, process flows, CAD applications - anything where the user wants fine grained control of the path that the edges follow.
Editing paths

The editor for this connector type supports three operations:

- Segment end points can be dragged around
- The scissors icon cuts a segment into two.
- The trashcan icon deletes a segment. This icon is not shown when the connector has only one segment.

### Path smoothing

Segmented connectors can be rendered with "smoothing" enabled, in which mode the path is represented as a series of Bezier splines.

Smoothing can be switched on via the `smooth` flag in the connector options. In this demonstration, you can toggle smoothing via the Toggle smoothing button.
Editing smooth paths

When smoothing is switched on, the drag handles mark the control points of the Bezier curves.

### Further reading

- Read more about segmented connectors in the docs on this page: https://docs.jsplumbtoolkit.com/toolkit/6.x/lib/connectors#segmented
- See this demo at [https://jsplumbtoolkit.com/demonstrations/segmented-connectors](https://jsplumbtoolkit.com/demonstrations/segmented-connectors)
