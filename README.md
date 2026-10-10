# Galaxy 3D

An interactive 3D spiral galaxy made of tens of thousands of particles, built with Three.js and custom WebGL shaders.

## Features
- Spiral arms with inner stars orbiting faster than outer ones
- Camera follows mouse or touch movement
- Press and hold to scatter the galaxy; release to pull it back together
- Three color themes: Fire, Silver, Ice
- Tunable settings at the top of the script (star count, arms, spin, size)
- Fewer particles automatically on small screens

## Run it
Open `index.html` in a browser (needs an internet connection to load Three.js from a CDN), or:

```bash
npx serve .
```

## Tech
JavaScript · Three.js · WebGL (GLSL shaders) · HTML · CSS
