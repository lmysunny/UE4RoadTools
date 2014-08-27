UE4RoadTools
============
Tools for creating and editing roads and paths for Unreal Engine 4.


Current Status
--------------
Right now, you can drag in a Road actor, manipulate the spline, and add segments to the road.
It generally works pretty well.

The biggest current issue is the UI. You need to maintain the segments array manually in the editor,
and create the correct number of segments. Drilling down into the segments array to change settings
like the number of subdivisions or the spline scale is mildly annoying.

Any setting that can be pulled directly from the spline data (spline point position/rotation/scale) works
great.
