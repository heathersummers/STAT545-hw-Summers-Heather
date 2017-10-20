
Guest Lecture by Tamara Munzer
==============================

### October 19, 2017

Table of Contents:
------------------

[Types: Datasets and data](#types-datasets-and-data)

-   [Dataset types](#dataset-types)

-   [Attribute types](#attribute-types)

[Derive](#derive)

[Targets](#targets)

-   [All Data](#all-data)

-   [Attributes](#attributes)

-   [Network Data](#network-data)

-   [Spatial Data](#spatial-data)

[Marks vs Channels](#marks-vs-channels)

[Grouping](#grouping)

-   [Marks as Links](#marks-as-links)

-   [Grouping in Channels](#grouping-in-channels)

[Colors](#colors)

Types: Datasets and data
------------------------

### Dataset types

-   tables
-   networks
-   spatial
    -   field (continuous)
    -   geometry (spatial --&gt; selection of different points/positions)

### Attribute types

-   categorical
-   ordered

Derive
------

#### Don't just draw what you're given

-   decide what is right to show
-   create it with a series of transformations from the original dataset
-   draw that
-   different measurements for representing the centrality metric of the tree/network/graph

Targets
-------

### All Data

-   trends
-   outliers
-   features

### Attributes

#### One attribute

-   distribution
-   extremes

#### Many attributes

-   dependency
-   correlation
-   similarity

### Network Data

-   topology

### Spatial Data

-   shape

Marks vs Channels
-----------------

-   marks = geometric primitives
-   channels = somewhat correspond to aesthetics in R, control appearance of marks, can redundantly code with multiple channels

-   Examples of Magnitude Channels:
    -   position on common scale
    -   tilt/angle
    -   area (2D size)
    -   color luminance (how bright)
    -   color saturation (how colorful)
    -   curvature
    -   volume (3D size)
-   Examples of Identity Channels:
    -   spatial region
    -   color hue (what color)
    -   motion
    -   shape
-   expressiveness principle
-   match channel and data characteristics
-   effectiveness principle
-   encode most important attributes with highest ranked channels
-   spatial position ranks high for both
-   people are better able to understand (i.e. accuracy) positions compared to angles, etc.
-   attributes of position and hue (color) are fully separable
-   attributes of size and hue (color) have some interference
-   attributes of width and height have some/significant interference
-   attributes of red and green have major interference

Grouping
--------

### Marks as Links

-   containment (shade the box containing the point in order to signify grouping)
-   connection (connect the points with a line)

### Grouping in Channels

-   proximity
    -   same spatial region
-   similarity

Colors
------

-   if using the rainbow scale for ordered color look into whether to use fine- or large-grained scale
-   ColorBrewer is a really good tool
-   Viridis --&gt; good for color scales that are color blind friendly
