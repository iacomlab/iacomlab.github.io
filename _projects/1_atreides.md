---
layout: page
title: ATREIDES
description: Agent-based simulation for predictive policing through data-driven and multi-tiered models
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

Crime is one of the greatest threats to urban security. Around 80% of the world’s population live in countries with high levels of criminality. Predictive policing, i.e. the collection and analysis of data about previous crimes for prediction of individuals or areas with an increased probability of criminal activity, has turned to be a critical concern to help developing policing strategies and is recognized as a key element of police work. USA is the country with most experience in integrating predictive policing within their policing practice. Recently, European Comission has pointed out that new technologies and capabilities are needed to preventing and fighting crime. However, many reluctances have arisen due to the lack of transparency and bias of most existing predictive solutions which often underestimate the complexity of urban-crime modeling. Crime is a complex phenomenon affected by many factors, that must be taken into account by predictive models and has critical impact on the quality of predictions.

Simulation modeling, and specially, agent-based modeling and simulation (ABMS) techniques, are suitable for capturing dynamic interactions among individuals and with their environment. ABMS techniques have been applied to the study of crime, mainly for testing theoretical models and prevention strategies, and for crime-pattern mining. However, the actual potential of ABMS could be found at their capability of dynamically modeling the interactions between the crime-actor (offenders, victims, polices and citizens) agents and the environment in which they act. ABMS can contribute to obtain more accurate representations of reality, but two main challenges need to be faced before: realistic spatial environments and accurate representation of agents. In this sense, the availability of rich data sources on crime and on urban environments can undoubtedly improve crime simulations and increase their transferability to the real-world.

This project will be part of the collaboration, which since 2018 has been taking place between UMA researchers and the Territorial Intelligence-Analysis Group of the National Police Force, who are also members of this proposal. The main goal of ATREIDES is to enhance the intelligence, operation, investigation, and decision-making capabilities of law enforcement agencies (LEAs), through an ABMS platform. The platform will include three tiers of models that could cooperate to simulate complex and realistic urban scenarios from heterogeneous data sources. We will take advantage of our experience on latent-trait models and other user-modeling techniques to construct novel crime-actor behavioral models. Mobility is a key element of urban simulation, which also has a relevant effect on crime and is often underestimated in simulations. For this purpose, we will used our expertise on multiobjective heuristic search to make realistic and novel approaches to model human mobility in urban environments. The third tier will pursue a collection of overlay and network-based models in different layers involving information such as traffic, pedestrian flow, weather, socio-economic aspects, etc. To ensure the success of the project, data processing and the development of models and tools must be transparent, understandable and tailored to the needs of LEAs. A pilot study will be performed using the city of Málaga as a testbed and, through a case of study, a special focus will be put on gender-based crime prevention.


To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: ATREIDES
    description: Agent-based Simulation for Predictive Policing through Data-Driven and Multi-Tiered Models
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
