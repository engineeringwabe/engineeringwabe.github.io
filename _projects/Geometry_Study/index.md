---
layout: post
title: "Composite Heat Shield Using FDM"
description: >
  This project investigates the use of Fused Deposition Modeling (FDM) to fabricate heat shield
  tiles featuring bio-inspired geometries. By conducting controlled thermal tests on a range of
  geometrical designs, the study aims to identify configurations that best preserve structural
  integrity over time. This research integrates additive manufacturing with nature-inspired
  engineering to advance lightweight, thermally robust solutions for aerospace and other
  high-temperature applications.
skills: 
  - CAD & 3D Modeling
  - ANSYS Simulations
  - LATEX
  - Team Collaboration & Teamwork
  - Analysis
main-image: /main.png
---

## Contribution 
The primary goal of this project was to examine how different structural patterns affect thermal resistance and deformation when exposed to high temperatures. We began by researching materials best suited for our design constraints and thermal requirements. In parallel, we developed four geometric categories for our test samples: a flat plate (control), two honeycomb variations, three spike-based geometries, and two scale-like patterns.

After selecting a suitable material, we imported our CAD models into ANSYS. Due to limited time and resources, we used simulations to identify the highest-performing geometries before moving to physical testing. We conducted transient thermal conduction simulations in ANSYS by assigning material properties, generating an appropriate mesh, applying boundary conditions, and analyzing the resulting thermal profiles.

{% include image-gallery.html images="models.png" height="400" class="center-image" %}
{% include image-gallery.html images="Sims.png" height="400" class="center-image" %}

Once we validated the simulation results, we selected the top-performing geometries and fabricated them using carbon fiber nylon. We conducted physical tests using a controlled jig setup and a heat gun, maintaining consistency in variables across trials. To benchmark performance, we tested both carbon fiber nylon and standard nylon samples. Ultimately, our results revealed clear trends that corroborated the findings from our simulations.

The trials demonstrated that carbon fiber-reinforced nylon significantly enhanced thermal resistance, with prototypes successfully withstanding sustained exposure to high-temperature gradients with longer hat resistance over a period of time. This marks a substantial improvement over unreinforced polymers, confirming the material's suitability for thermal shielding in high-performance propulsion components.

{% include image-gallery.html images="jig.png" height="400" class="center-image" %}
{% include image-gallery.html images="Set-up.png" height="400" class="center-image" %}

---
## Challenges/Lessons
Another major challenge was that this was our first time using ANSYS for simulation. There was a steep learning curve in understanding how to properly set up the model, apply realistic boundary conditions, and interpret thermal and structural results. It required significant time spent exploring tutorials, troubleshooting errors, and seeking help from peers and instructors. However, this process helped us develop strong foundational skills in simulation and gave us the confidence to integrate it into our design workflow moving forward. Despite these challenges, I gained valuable experience working through uncertainty in a real engineering context.



