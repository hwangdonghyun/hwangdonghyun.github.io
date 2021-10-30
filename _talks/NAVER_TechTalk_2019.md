---
title: "Synthesizing Pseudo-2.5D Content from Monocular Videos for Mixed Reality"
collection: talks
type: "Talk"
permalink: /talks/naver_2019
venue: "Green Factory, South Korea"
date: 2019-02-01
location: "Korea"
---

Free-viewpoint video (FVV) is a kind of advanced media that provides a more immersive user experience than traditional media. It allows users to interact with content because users can view media at the desired viewpoint and is becoming a next-generation media. 
In creating FVV content, existing systems require complex and specialized capturing equipment and has low end-user usability because it needs a lot of expertise to use the system. This becomes an inconvenience for individuals or small organizations who want to create content and limits the end user’s ability to create FVV-based user-generated content (UGC) and inhibits the creation and sharing of various created content. 
To tackle these problems, ParaPara is proposed in this work. ParaPara is an end-to-end system that uses a simple yet effective method to generate pseudo-2.5D FVV content from monocular videos, unlike the previously proposed systems. First, the system detects persons from the monocular video through a deep neural network, calculates the real-world homography matrix based on the minimal user interaction, and estimates the pseudo-3D positions of the detected persons. Then, person textures are extracted using general image processing algorithms and placed at the estimated real-world positions. Finally, the pseudo-2.5D content is synthesized from these elements. The content, which is synthesized by the proposed system, is implemented on Microsoft HoloLens; the user can freely place the generated content on the real world and watch it on a free viewpoint. 


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/jJ0z4fb02VU/0.jpg)](https://www.youtube.com/watch?v=jJ0z4fb02VU)
