# Texel Density Scale Calculator

A web-based tool for calculating texture scaling factors to achieve consistent texel density across 3D assets.


## What It Does

Calculates the exact scale factor needed to convert textures between different densities and resolutions. Input your current texture specs and target requirements - get the precise scaling value to use in image editing software or ComfyUI.
The calculator assumes a 1:1 UV mapping where the texture covers exactly the mesh size specified. 

LINK TO TOOL: [Texel Density Scale Calculator](https://olivierwierda.github.io/Texel-Density-Scaling-Calculator/)

## Why It's Useful

**For Game Developers & 3D Artists:**
- Ensures consistent texture quality across all assets
- Eliminates guesswork when scaling textures
- Prevents textures from looking blurry or overly sharp compared to surroundings
- Optimizes texture memory usage by hitting exact target resolutions

**Common Use Cases:**
- Converting downloaded textures to match your project's texel density standard
- Scaling terrain textures for specific mesh sizes
- Preparing assets for different LOD levels
- Batch processing texture libraries

## How to Use

1. **Input current texture data:**
   - Density (px/cm) - how detailed your source texture is
   - Resolution (pixels) - current texture dimensions

2. **Set your targets:**
   - Mesh size (meters) - physical size in your 3D scene
   - Target density (px/cm) - desired detail level
   - Target resolution (pixels) - final texture dimensions

3. **Apply the scale factor** in your image editor or ComfyUI to resize the texture

The tool shows whether you're upscaling or downscaling, and calculates the difference between ideal resolution (for perfect density) and your target resolution.

**Example:** Scale an 8K texture from 10.8 px/cm down to 2.05 px/cm for a 10×10m terrain tile → get exact scale factor for ComfyUI.
MIT License

Copyright (c) 2025 [Olivier Wierda]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
