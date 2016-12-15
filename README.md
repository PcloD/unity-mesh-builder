unity-mesh-builder
=====================

Primitive mesh builders for Unity.

![Demo](https://raw.githubusercontent.com/mattatz/unity-mesh-builder/master/Captures/Demo.png)

## Usage

```cs
Mesh mesh = PlaneBuilder.Build(
    5f,     // width
    10f,    // height
    2,      // width segments
    4       // height segments
);
```

## Primitives

- Plane (Parametric)
- Cube
- Cylinder
- Sphere
- Frustum

Another primitives are in progress ...

## Sources

- ProceduralPrimitives - Unity Community Wiki - http://wiki.unity3d.com/index.php/ProceduralPrimitives
- Viewports and Clipping - https://msdn.microsoft.com/en-us/library/windows/desktop/bb206341
