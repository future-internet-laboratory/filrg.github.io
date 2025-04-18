---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}**Team**

## Meet Our Team of Researchers and Innovators
Our team is a dynamic blend of faculty and students passionate about immersive multimedia, networking, and smart applications. Together, we drive cutting-edge research and real-world innovation.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

# 🎉 Life at FIL

From research achievements to lab celebrations, our journey is shaped by the people who make it possible. Here's a glimpse into our vibrant community life.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/fil/graduation-2024.jpg" %}
{% include figure.html image="images/fil/YEP-2025.jpg" %}
{% include figure.html image="images/fil/8-3-2025.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
