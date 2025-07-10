---
layout: page
title: Deep Reinforcement Learning for UAV Base Station Dynamic Positioning
description: Developed a DRL model to optimize UAV positioning for network coverage in telecommunications.
importance: 1
category: Reinforcement Learning
---

This project was my Bachelor's Thesis at Universitat Politècnica de València. I developed a Deep Reinforcement Learning model for dynamically positioning UAV Base Stations to optimize network coverage.

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}

## Abstract

Mobile communications are essential in today's society, defining how we communicate and relate, and influencing how we live. Optimizing this valuable asset is essential to provide the best possible experience in a sustainable way. To improve network performance and energy efficiency, future generations of communications are expected to incorporate base stations capable of repositioning easily, without human intervention, using ground vehicles or unmanned aerial vehicles, such as drones.

In this thesis, we propose an intelligent solution that allows such mobile base stations to adapt and learn user movement patterns, and find their optimal position in real time. To quantify user experience, we use the average data rate of users. To guide these decisions and learn optimal policies, we have used advanced learning techniques, in more detail, deep reinforcement learning (DRL).

As a first point of work, it is important to emphasize the use, development and optimization of an advanced simulation environment for 4G/5G/6G mobile communication networks, called Giulia, based on Python. This optimization involved transforming a substantial number of operations to more efficient methods, such as using GPU through the PyTorch library. As the main contribution of this work, we implemented advanced DRL techniques, adapting them to our specific problem, which combine the power of deep neural networks (DNN) with reinforcement learning optimization. Through the work of this thesis, we have laid solid foundations and knowledge about the integration of DRL with complex simulation environments for real-time decision making. We have demonstrated that the use of statistics on received signal power, angle of arrival, and user data rate is sufficient information to learn movement patterns of user groups, and optimize in real time the movement of mobile base stations that aim to maximize the experience of said users. The results of the thesis indicate that DRL can be used in the next generations of communication networks that can be controlled by autonomous agents in real time.

Supervised by Prof. Valery Naranjo Ornedo and Dr. David López Pérez. Investigated DRL applicability in telecom scenarios, including multi-layer environments and user distributions.

Methodology: Utilized DRL algorithms to train agents in simulated environments, considering factors like user distribution and signal strength. Achieved improved coverage metrics compared to static positioning.

Key outcomes: Enhanced network efficiency in dynamic scenarios, with potential applications in 5G/6G networks.

## Key Learnings

- Developed and optimized the Giulia simulation environment for 4G/5G/6G networks, including GPU acceleration using PyTorch for efficient computations.
- Gained expertise in Deep Reinforcement Learning (DRL) techniques, adapting them to dynamic positioning problems in telecommunications.
- Learned to integrate DRL with complex simulation environments for real-time decision-making, using metrics like received signal power, angle of arrival, and user data rates.
- Built foundational knowledge in autonomous agent control for next-generation communication networks.

## Performance Highlights

- Demonstrated that DRL agents can learn user movement patterns and optimize UAV base station positions in real-time, leading to improved average data rates.
- Achieved enhanced network coverage and efficiency compared to static positioning methods, particularly in dynamic user distribution scenarios.
- Validated the approach in multi-layer environments, showing potential for 5G/6G applications with autonomous real-time control.
