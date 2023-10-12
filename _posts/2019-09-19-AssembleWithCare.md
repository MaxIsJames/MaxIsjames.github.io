---
layout: post
title:  "Assemble With Care"
show_date: true
tags: [Technical Artist, Artist]
featured_image_thumbnail:
featured_image: assets/images/posts/AssembileWithCareExplode.gif
featured_text: Experiments in painterly rendering and design.
---

Assemble With Care is a beautiful narrative puzzle game, that sees you restore objects that have sentimental value to
their owners, and explore their relationships to one another.

I worked on Assemble With Care, with a very small team, as an **Artist** and the sole __Technical Artist__, brought onto the 
project at the very beginning of development in order to develop a unique art style that would capture the bold painterly strokes of our concept art, in real time.

![AWC.jpg](assets/images/posts/AWC.jpg)

Developed by ustwo Games and released for iOS and Android devices,
you can find out more about this game at [assemblegame.com](https://www.assemblegame.com/)

---

# Rendering Experiments

This was a challenging brief, I was tasked not only with creating a rendering style that would not only compliment and enhance the act of manipulating and reconfiguring intricate broken machinery,
but would also translate the strokes of the concept art directly to the screen. This was not about capturing the _feel_ of the art, but recreating it as faithfully as possible in real time 3D.

Some of our most exciting experiments used a novel post processing technique, that took a number of deferred buffers and a customisable
sampling kernel, and combined them together to reconstruct the image in the style of a loose dry brush painting.

![Painterly Rendering](assets/images/posts/painterlygif.gif)

Given the technical nature of the game, care had to be given to preserve important signifiers and attempt to reinforce readability. We gave pixels an 'importance' value that would allow their colour to bleed over their neighbours, highlights and black lines painted last on top of all other colours, just as a painter would.

| ![Painterly Rendering](assets/images/posts/AwcPainterlyCropped.gif) | ![Painterly Rendering](assets/images/posts/AwcCameraCropped.gif) |

While this rendering approach was pared back and we eventually decided to remove it completely due to the specific gameplay readability 
constraints of this project, I think the results are still very compelling and would be a great match for a integrating real time 3D elements into similarly
styled 2D illustrations.