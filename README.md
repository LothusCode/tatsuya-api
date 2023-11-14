# TatsuyaAPI - Choose it and change.
TatsuyaAPI is an API for developing spigot plugins that facilitates and gives you resolutions for calculating complex regions such as parallelepipeds and irregular triangles and three-dimensional shapes. There are more than 30 forms available. TatsuyaAPI also gives you complex animation presets for you to use in your plugins. Say goodbye to complex calculations, use TatsuyaAPI. 

# Documentation

## Creating shapes

### Custom dimensions Triangle
```java
Triangle triangle = PolygonBuilder
 .shape(PolygonShape.TRIANGLE)
 .base(3).height(2).build();
```
