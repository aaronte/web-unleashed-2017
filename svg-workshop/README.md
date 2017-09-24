<h1 align="center">Building & Animating SVGs</h1>

Speaker: [Sarah Drasner](https://twitter.com/sarah_edo)
[Workshop Repo](https://github.com/sdras/advanced-svg-workshop)

**Optimize SVGs**
- [UI: SVG OMG](https://jakearchibald.github.io/svgomg/)
- [CLI: SVGO](https://github.com/svg/svgo)


**Code Pen Examples**
- [Infographics](https://codepen.io/sdras/full/JdJgrB)
- [Polygons](https://codepen.io/sdras/pen/gppEwd)
- [Robots <3](https://codepen.io/sdras/pen/qdLJLJ)


**Correct tools for SVG animations**
- CSS/SCSS (for small interactions) - Recommended
- GSAP (GreenSock) - Recommended
- React-Motion
- Snap.svg
- Web Animations API (waiting for support)
- velocity.js
- mo.js
- d3.js

**[Only Use](http://slides.com/sdrasner/adv-svg-2?token=FxyYIMcu#/5)**
- Opacity
- Transforms
- Hardware Acceleration
```scss
@mixin accelerate($name) {
 will-change: $name;
 transform: translateZ(0);
 backface-visibility: hidden;
 perspective: 1000px;
}

.foo {
  @include accelerate(transform);
}
```

**Tools for Prototyping**
- Principle
- FramerJS
- After Effects
- Keynote
- Straight Up Code (Most Recommended)

**Nice to Have & Necessary vs Easy to Implement & Difficult**
- http://slides.com/sdrasner/adv-svg-2?token=FxyYIMcu#/76

**Animating Gradients**
- [Clippath vs Masking](https://css-tricks.com/masking-vs-clipping-use/)

**Crazy Text Animations**
- https://codepen.io/sdras/pen/RNWaMX
