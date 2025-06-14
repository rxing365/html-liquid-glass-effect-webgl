# Liquid Glass WebGL Demo

**A WebGL and shader-powered glass effect UI, inspired by Apple's WWDC 2025 design.**



## Overview

This project showcases a glass-like UI component with real-time refraction, reflection, and frosted glass effects using WebGL and custom shaders.



## Features

- **Real-time Normal Calculation:**  
  UI component normals are calculated in real time, allowing you to dynamically adjust the shape and refraction parameters.
- **Live Refraction:**  
  The background is refracted through the glass UI, producing the illusion of depth and light bending.
- **Edge Reflection:**  
  The glass border features realistic highlight effects.
- **Frosted Glass:**  
  A blur layer simulates the appearance of frosted or matte glass.



## Optimization Notes

Currently, normal calculations are performed on the fly using JavaScript and GPU shaders to explore normal generation techniques. If your component shapes are fixed, you can precompute normal maps and use them with SVG filters. This eliminates the need for WebGL and JavaScript, just CSS.



## Screenshot

![截屏2025-06-10 20 58 13](https://github.com/user-attachments/assets/ae779dfd-5e45-4dd2-9a91-cda333405475)



## Live Demo

[View the live demo](https://rxing365.github.io/html-liquid-glass-effect-webgl/)

## Watch The Video

[Bilibili](https://www.bilibili.com/video/BV1vwM3zFESr)

[X](https://x.com/Rxing5/status/1932612927586250974)


## Credits

Apple WWDC 2025 Liquid Glass UI.
