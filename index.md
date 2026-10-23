---
layout: default
---
# Welcome to the System Modeling Group

Our major research directions concerns deep learning for biomedical applications, human mobility and digital epidemiology. 

## Deep learning

  * Pain recognition
    * In laboratory Mice
    * In Bovines
      
  * Digital Pathology
    * Kidney Segmentation
    * Lymphoma Classification
    * Organoid Classification
    * Canine Vaginal Cytology
  
  * Behavior analysis
    * RFID sensor-based animal tracking
    * Video-based group behavior
    * Sensor (accelerometer) based lameness recognition
      
  * Natural Language Processing
    * Adverse events from free text reports

  * Graph Neural Networks
    * Contact pattern analysis

Here is a showcase of my projects:

{% capture carousel_data %}
[
  {
    "image": "grad_cam_cow.png",
    "text": "Feature visualization using Grad-CAM for pain recognision in cows",
    "link": ""
  },
  {
    "image": "taylor_mouse.png",
    "text": "Feature visualizition via deep Taylor decomposition for pain recognision in mice",
    "link": "https://https://doi.org/10.1371/journal.pone.0228059"
  }
]
{% endcapture %}

{% assign slides = carousel_data | from_json %}
{% include carousel.html slides=slides %}




