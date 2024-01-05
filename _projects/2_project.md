---
layout: page
title: Hypomimia Coach
description: An AU-based Digital Therapy System for Hypomimia Detection & Rehabilitation with Parkinson's Disease
img: assets/img/project_hypomimia_coach/cover.jpg
importance: 2
category: work
giscus_comments: true
---

# Introduction
Parkinson's disease, common in individuals aged 60 and above, involves facial movement disorders known as 'mask-like face.' This impairs expressive abilities, necessitating urgent development of new technologies for early identification. Computer-assisted detection systems, advancing with medical technology, capture subtle facial details efficiently. These systems, equipped with powerful computing and intelligent algorithms, analyze abnormal facial areas for reliable identification of low expression symptoms. Facial rehabilitation training for Parkinson's patients improves expression, muscle control, and motor skills, positively impacting disease progression.

This project, rooted in AI and human-computer interaction, utilizes visual and auditory information. It relies on the MDS-UPDRS scale, constructing a model for early identification of bradykinesia symptoms and an auxiliary rehabilitation program. The goal is to create an age-appropriate digital therapeutic mobile app, validated clinically for new technologies.

# Hypomimia Detection
The user activates the detection function, and the camera captures facial information, returning the recognition result for 'mask-like face.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_hypomimia_coach/img1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    hypomimia detection user interface design
</div>
We applied an AU intensity prediction method in hypomimia diagosis task. Hypomimia in Parkinson's disease is characterized by slowed facial movements, limited motion range, monotonous expressions, and a rigid countenance. The analysis of AU provides a more precise approach to capturing hypomimia-related facial features. GCN enables us to exploit the interconnectedness among facial action units, thereby enhancing model precision and robustness. 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_hypomimia_coach/img2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    hypomimia detection technical pipline
</div>

# Hypomimia Rehabilitation

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_hypomimia_coach/img3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    hypomimia rehabilitation user interface design
</div>
Based on existing research on rehabilitation massage exercises for 'mask-like face' in Parkinson's disease, this project combines theoretical foundations from clinical experts. Leveraging the existing artificial intelligence facial action unit recognition framework, it designs a rehabilitation exercise program based on facial action expression units.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_hypomimia_coach/img4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    AU-based facial exercise design
</div>
Chinese opera, characterized by its diverse regional variations, elicits empathetic responses within local audiences. Furthermore, leveraging the phonetic distinctiveness of Chinese opera's pronunciation facilitates improved single-character pronunciation training for seniors, we have chosen Chinese opera as the back for rehabilitation training. We strategically match distinct training content with various styles of traditional opera music.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_hypomimia_coach/img5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Chinese opera music and filter design
</div>

Rehabilitation training is offered in two modes: basic training and advanced training.The basic training encompasses exercises targeting various facial regions, such as eye, brow, nose, lip, swallowing, and pronunciation training, as well as combination exercises.The advanced training is conducted in the form of facial operatic exercises, allowing users to select training content of varying duration and difficulty levels based on their preferences.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_hypomimia_coach/img6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    basic training and advanced training workflow
</div>

# Doctor Management System
This project offers a Parkinson's patient management system for healthcare professionals. The system records patients' medical information and logs and analyzes data from their gaming and training activities. Through these records and analyses, doctors can easily diagnose patients' conditions and make informed decisions for further treatment.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_hypomimia_coach/img7.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    doctor management system user interface design
</div>


# Conclusion
This project comprehensively employs motor, emotional, and cognitive pathways to enhance the lives of Parkinson's patients. Through facial movement training, it improves facial expression and communication skills, alleviating depressive moods through engaging facial exercises. Using human-computer interaction in a gaming format enhances cognitive abilities. Patients engage in personalized rehabilitation training in a pleasant atmosphere, continually adjusting facial movements with real-time feedback. By integrating these pathways, the project offers a comprehensive rehabilitation solution, effectively improving facial function, emotional well-being, and cognitive abilities. Based on digital therapy, the project also supports smart aging. With the increasing aging population, software-driven proactive health intervention technologies can enhance the accessibility and efficiency of chronic disease management.