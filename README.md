# PBRStudy

###### Presentation Slides and References of ["Physically Based Rendering, 2nd Edition"](http://www.pbrt.org/) Book

From movies to video games, computer-rendered images are pervasive today. Physically Based Rendering introduces the concepts and theory of photorealistic rendering hand in hand with the source code for a sophisticated renderer.

## The Book

<I>Physically Based Rendering</I>, Second Edition describes both the mathematical theory behind a modern photorealistic rendering system as well as its practical implementation. A method known as “literate programming” combines human-readable documentation and source code into a single reference that is specifically designed to aid comprehension. Through the ideas and software in this book, you will learn to design and employ a full-featured rendering system for creating stunning imagery.

This new edition greatly refines its best-selling predecessor by adding sections on bidirectional light transport; stochastic progressive photon mapping; a significantly-improved subsurface scattering implementation; numerical robustness issues in ray-object intersection; microfacet reflection models; realistic camera models; and much more. These updates reflect the current state-of-the-art technology, and along with the lucid pairing of text and code, ensure the book's leading position as a reference text for those working in rendering.

The author team of Matt Pharr, Greg Humphreys, and Pat Hanrahan garnered a 2014 Academy Award for Scientific and Technical Achievement from the Academy of Motion Picture Arts and Sciences based on the knowledge shared in the first and second editions of the book this book. The Academy called the book a “widely adopted practical roadmap for most physically based shading and lighting systems used in film production.”

## Presenter

- Chris Ohk
- Bong-Suk Jo
- Hee-Gyo Jung
- Tae-Hoon Woo

## Contents (Presentation Slides - Korean)

<img align="right" src="http://www.pbrt.org/images/bookcover.png">

### Chapter 1: Introduction

- Presentation Slides is omitted.
    - Literate Programming
    - Photorealistic Rendering and The Ray-Tracing Algorithm
    - pbrt: System Overview
    - How to Proceed through This Book
    - Using and Understanding The Code

### Chapter 2: Geometry and Transformations

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%202.pptx)
    - Coordinate systems
    - Vectors
    - Points
    - Normals
    - Rays
    - Three-Dimensional Bounding Boxes
    - Transformations
    - Applying Transformations
    - Animating Transformations
    - Differential Geometry

### Chapter 3: Shapes

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%203%2C%20Part%201.pptx)
    - Basic Shape Interface
    - Spheres
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%203%2C%20Part%202.pptx)
    - Spheres
    - Cylinders
    - Disks
    - Other Quadrics
    - Triangle and Meshes
- Presentation Slides is omitted.
    - Subdivision Surfaces

### Chapter 4: Primitives and Intersection Acceleration

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%204.pptx)
    - Primitive Interface and Geometric Primitives
    - Aggregates
    - Grid Accelerator
    - Bounding Volume Hierarchies
    - Kd-Tree Accelerator
    - Debugging Aggregates

### Chapter 5: Color and Radiometry

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%205.pptx)
    - Spectral Representation
    - The SampledSpectrum Class
    - RGBSpectrum Implementation
    - Basic Radiometry
    - Working with Radiometric Integrals
    - Surface Reflection

### Chapter 6: Camera models

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%206.pptx)
    - Camera Model
    - Projective Camera Models
    - Environment Camera

### Chapter 7: Sampling and Reconstruction

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%207%2C%20Part%201.pptx)
    - Sampling Theory
    - Image Sampling Interface
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%207%2C%20Part%202.pptx)
    - Stratified Sampling
    - Low-Discrepancy Sampling
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%207%2C%20Part%203.pptx)
    - Best-Candidate Sampling Patterns
    - Adaptive Sampling
    - Image Reconstruction
    - Film and the Imaging Pipeline

### Chapter 8: Reflection models

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%208%2C%20Part%201.pptx)
    - Basic Interface
    - Specular Reflection and Transmission
    - Lambertian Reflection
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%208%2C%20Part%202.pptx)
    - Microfacet Models
    - Fresnel Incidence Effects
    - Measured BRDFs

### Chapter 9: Materials

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%209.pptx)
    - BSDFs
    - Material Interface and Implementations
    - Bump Mapping

### Chapter 10: Texture

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2010%2C%20Part%201.pptx)
    - Sampling and Antialiasing
    - Texture Coordinate Generation
    - Texture Interface and Basic Textures
    - Image Texture
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2010%2C%20Part%202.pptx)
    - Image Texture
    - Solid and Procedural Texturing
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2010%2C%20Part%203.pptx)
    - Noise

### Chapter 11: Volume scattering

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2011.pptx)
    - Volume Scattering Processes
    - Phease Functions
    - Volume Interface and Homogeneous Media
    - Varying-Density Volumes
    - Volume Aggregates
    - The BSSRDF

### Chapter 12: Light Sources

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2012.pptx)
    - Light Interface
    - Point Lights
    - Distant Lights
    - Area Lights
    - Infinite Area Lights

### Chapter 13: Monte Carlo Integration I, Basic concepts

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2013%2C%20Part%201.pptx)
    - Background and Probability Review
    - The Monte Carlo Estimator
    - Basic Sampling of Random Variables
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2013%2C%20Part%202.pptx)
    - Metropolis Sampling
    - Transforming between Distributions
    - 2D Sampling with Multidimensional Transformations

### Chapter 14: Monte Carlo Integration II, Improving Efficiency

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2014%2C%20Part%201.pptx)
    - Russian Roulette and Splitting
    - Careful Sample Placement
    - Bias
    - Importance Sampling
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2014%2C%20Part%202.pptx)
    - Sampling Reflection Functions
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2014%2C%20Part%203.pptx)
    - Sampling Light Sources
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2014%2C%20Part%204.pptx)
    - Volume Scattering

### Chapter 15: Light Transport I, Surface Reflection

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2015%2C%20Part%201.pptx)
    - Direct Lighting
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2015%2C%20Part%202.pptx)
    - The Light Transport Equation
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2015%2C%20Part%203.pptx)
    - Path Tracing
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2015%2C%20Part%204.pptx)
    - Instant Global Illumination
    - Irradiance Caching
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2015%2C%20Part%205.pptx)    
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2015%2C%20Part%206.pptx)
    - Particle Tracing and Photon Mapping
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2015%2C%20Part%207.pptx)
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2015%2C%20Part%208.pptx)
    - Metropolis Light Transport

### Chapter 16: Light Transport II, Volume Rendering

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2016%2C%20Part%201.pptx)
    - The Equation of Transfer
    - Volume Integrator Interface
    - Emission-Only Integrator
    - Single Scattering Integrator
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2016%2C%20Part%202.pptx)
- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2016%2C%20Part%203.pptx)
    - Subsurface Scattering

### Chapter 17: Light Transport III, Precomputed Light Transport

- [Presentation Slides](https://github.com/utilForever/PBRStudy/blob/master/Physically%20Based%20Rendering%20-%20Chapter%2017.pptx)
    - Basis Functions: Theory
    - Spherical Harmonics
    - Radiance Probes
    - Precomputed Diffuse Transfer
    - Precomputed Glossy Transfer

### Chapter 18: Retrospective and The Future

- Presentation Slides is omitted.
    - Design Retrospective
    - Throughput Processors

## License

<img align="right" src="http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png">

The class is licensed under the [MIT License](http://opensource.org/licenses/MIT):

Copyright &copy; 2017 [Chris Ohk](http://www.github.com/utilForever), Bong-Suk Jo, Hee-Gyo Jung and Tae-Hoon Woo

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
