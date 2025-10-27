---
layout: splash
title: "Tryaksh Gupta"
author_profile: true

header:
  overlay_color: "#0e1117"
  overlay_image: /assets/images/hero-mesh-gradient.jpg   # add this image (see step 4)
  actions:
    - label: "Download Résumé"
      url: /assets/6_2025_GuptaTryakshResume.pdf         # drop the PDF into /assets
      class: "btn btn--primary"

intro: |
  I build practical simulation & robotics products—going from workflow mapping to shipped SDKs and customer wins.

feature_row:
  - image_path: /assets/images/icons/robot-arm.svg
    alt: "Robotics Motion Planning"
    title: "Robotics Motion Planning"
    excerpt: "Path-planning SDK: collision-free motions in CAD environments; 3 OEM collabs."
    url: /projects/#robotics-motion-planning
    btn_label: "See project"
    btn_class: "btn--primary"
  - image_path: /assets/images/icons/mesh.svg
    alt: "Meshing SDKs"
    title: "CSM/CVM Meshing"
    excerpt: "Customer workflows powering 4 apps; AI-guided meshing initiative."
    url: /projects/#meshing-workflows
  - image_path: /assets/images/icons/cds.svg
    alt: "CDS Relaunch"
    title: "CDS Relaunch"
    excerpt: "Market repositioning & C++ workflows → 2 new customer wins."
    url: /career/#cds-relaunch
  - image_path: /assets/images/icons/battery.svg
    alt: "Battery Research"
    title: "Solid-State Battery Research"
    excerpt: "JMPS 2024: particle-scale fracture modeling & stress-dependent kinetics."
    url: /projects/#battery-modeling
  - image_path: /assets/images/icons/tesla.svg
    alt: "Tesla"
    title: "Tesla Cell Engineering"
    excerpt: "Electrostatic cleaning prototype deployed on high-volume lines."
    url: /career/#tesla
  - image_path: /assets/images/icons/paper.svg
    alt: "Publication"
    title: "Publication"
    excerpt: "Sharp-interface fracture in solid-state batteries (JMPS, 2024)."
    url: "https://doi.org/10.1016/j.jmps.2023.105490"

lottie_src: /assets/animations/robot-gears.json  # optional animation
---

{% include feature_row id="feature_row" %}

<div class="home-lottie">
  <lottie-player src="{{ page.lottie_src }}" background="transparent" speed="1" loop autoplay></lottie-player>
</div>
