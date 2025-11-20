---
title: "Hybrid Image Generation"
excerpt: "Generating hybrid images using different methods" # 간략한 설명
collection: projects
image: portfolio-1.jpg # 표시할 이미지 파일명
date: 2023-12-01
---

## Project Description
This work implements image convolution to generate hybrid images. The core technical decisions revolve around implementing a flexible convolution function and comparing its performance against an optimized library function. The following images shows the result of generating a hybrid image (a cat/dog combination) using both the naive and FFT methods.

![Hybrid_Image]( /images/projects/hybrid_image.png )

*The resulting image exhibits the expected property of hybrid images: the cat is visible when the image is large (high spatial frequencies) and the dog becomes more visible as the image gets smaller (low spatial frequencies).*

![Comparison]( /images/projects/comparison.png )

*Time comparison between different methods*
