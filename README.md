# BrickLayers - A Brick Art Gallery database
### My Final Project for the 2025 DataTalks.club Data Engineering Zoomcamp

For the informations relating to the zoomcamp final project guidelines applied to this specific project, you can go directly to sections (add sections)

## Introduction

The project contained in this Github Repo aims to generate a database with data on famous art pieces and the toy brick pieces (such as Lego, for instance) necessary to build renditions of these famous paintings.

<div align="center">
  <img src="https://github.com/user-attachments/assets/6b190051-292d-4d28-a58e-06b7d79fea2b" width="300" />
  <p><em>Figure 1: A version of 64x64 pieces of Meisje met de parel (Girl with a Pearl Earring), to be built with Lego pieces.</em></p>
</div>

### Main motivations

For the technical component of the project, jump to section [The Project](https://github.com/)

### DataTalks.Club Zoomcamp
This is my iteration of the final project propposed by the organizers of the Data Engineering Zoomcamp.
For those who eventually stumble upon this repository and are not aware, the Data Talks Club Engineering Zoomcamp is a nine week free bootcamp. More info on Data Talks Club on their [website](https://datatalks.club/). They have top notch teachers and courses, on different areas of data. I highly recommend checking their work and have learned a lot troughout the course.

### Foreseeable use cases

I wanted to deliever the project, but also make something interesting, and on top of that, to make a positive impact at the same time. So here are some possible uses I can foresee for this database:

- For **anyone** fascinated by art or Lego
- For **parents and educators** who wish to spark interest in art. Interesting for many age ranges (I assume*), for multiple reasons. Whether helping develop motor skills and better eye for telling nuances in colors, or for studies of art and history, or simply cultivating creativity for older kids. 
- For Lego **hobbyists**, if renditions of artworks could enrich their ideas. Even though paintings in smaller scale may lose important details, interesting playsets can be made. Imagine a Lego set rendition of famous museum rooms, such as the Mona Lisa room at the Louvre, or even a miniature Sistine Chapel*. Scales between paintings and the playset scene may need to be distorted, but imagination can perform the heavy lifting.
- For **those interested in decoration, professional or not**, with added flexibility of Lego. Imagine having an interesting rendition of "Starry Night" on your wall or even the "*Creation of Adam*", the famous scene from the Sistine Chapel ceiling, now on your own ceiling. Lego as a rendering technique offers the possibility of determining the size (and price) of painting renditions. If a more nuanced color analysis is needed, data will be able to provide the predominant colors of each (Lego) painting.

*Please be wary that I am not a professional in this area. Be sure to check Lego age restrictions too.  
**Neither data on Louvre paintings nor on Sistine Chapel frescoes will, at the current moment, be present in this version of the dataset. 

## The Project

Description of the project in more technical terms.

### Guidelines and goals

The project guidelines are described on the course's [github](https://github.com/DataTalksClub/data-engineering-zoomcamp/tree/main/projects). They delineate minimum requirements, but allow the participant to choose their preferred tools and programming languages. 

### Pipeline Type

For this project, **batch** pipelines will be created.

### Chosen tools for the project

Cloud Storage: **Google Cloud**

Data Warehouse: **Google BigQuery**

Infrastructure as Code (IaC): **Terraform**

Workflow Orchestration: **Kestra**

Batch Processing: **PySpark** or **DBT** (to be defined)

**Ideally, a CI/CD tool will be used, as well as versioning and testing.**

### Chosen Datasets

The chosen Dataset will be obtained from the [Metropolitan Museum of Art API](https://metmuseum.github.io/).

Data on available colors of Lego pieces will be used. For this, the csv files available on [Rebrickable](https://rebrickable.com/downloads/) will be used.

(MAYBE) data available in wikipedia will be generated to create QR codes, to be built in Lego, to direct people either to the wikipedia page, or the MET page about the painting.

## System Design






























