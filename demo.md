![logos](images/logo5.png)

# Demo

To see Saké in action, check out [demo stack 1](http://104.198.43.42/stack1.json) or [demo stack 2](http://104.198.43.42/stack2.json).

### Tips for navigating the OHIF viewer
- Scroll wheel or up/down arrows to view different slices.
- Right click and drag to zoom in and out.
- Middle click and drag to pan.

### Creating a segmentation with Saké
1. Click the **Segment** button to activate the tool.
1. Click on region of interest. The plugin will fill out the bounding polygon.
1. Drag the center square up and down to adjust the threshold of the algorithm.
1. Drag individual vertices to fine tune the polygon.
1. Scroll through the slices to propagate segmentation in 3D.

### Saké tips
- The maximum area of a segment has been capped. The tool rejects attempts to click on a large region or to increase the threshold too much.
- Thresholds are propagated only to unseen slices. Adjust the threshold before scrolling to nearby slices to propagate the threshold.
- The **Save** button will send all the polygon segments back to the server.
- Dragging a vertex off the slice will delete the whole 3D segment.

### Screencast: Coming Soon

[Next](http://sakeviewer.com/conclusion.html)