+++
title = "Fast solar radiation pressure modelling with multiple reflections"
date = "2018-03-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["**Zhen Li**","Marek Ziebart","Santosh Bhattarai","David Harrison","Stuart Grey"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Advances in Space Research"
#publication_short = "ISBI"

# Abstract and optional shortened version.

#abstract = "abcde."

abstract = "Physics based SRP (Solar Radiation Pressure) models using ray tracing methods are powerful tools when modelling the forces on complex real world space vehicles. Currently high resolution (1 mm) ray tracing with secondary intersections is done on high performance computers at UCL (University College London). This study introduces the BVH (Bounding Volume Hierarchy) into the ray tracing approach for physics based SRP modelling and makes it possible to run high resolution analysis on personal computers. The ray tracer is both general and efficient enough to cope with the complex shape of satellites and multiple reflections (three or more, with no upper limit). In this study, the traditional ray tracing technique is introduced in the first place and then the BVH is integrated into the ray tracing. Four aspects of the ray tracer were tested for investigating the performance including runtime, accuracy, the effects of multiple reflections and the effects of pixel array resolution.Test results in runtime on GPS IIR and Galileo IOV (In Orbit Validation) satellites show that the BVH can make the force model computation 30-50 times faster. The ray tracer has an absolute accuracy of several nanonewtons by comparing the test results for spheres and planes with the analytical computations. The multiple reflection effects are investigated both in the intersection number and acceleration on GPS IIR, Galileo IOV and Sentinel-1 spacecraft. Considering the number of intersections, the 3rd reflection can capture 99.12%,99.14%, and 91.34% of the total reflections for GPS IIR, Galileo IOV satellite bus and the Sentinel-1 spacecraft respectively. In terms of the multiple reflection effects on the acceleration, the secondary reflection effect for Galileo IOV satellite and Sentinel-1 can reach 0.2 nm/s2 and 0.4 nm/s2 respectively. The error percentage in the accelerations magnitude results show that the 3rd reflection should be considered in order to make it less than 0.035%. The pixel array resolution tests show that the dimensions of the components have to be considered when choosing the spacing of the pixel in order not to miss some components of the satellite in ray tracing. This paper presents the first systematic and quantitative study of the secondary and higher order intersection effects. It shows conclusively the effect is non-negligible for certain classes of misson."

# Featured image thumbnail (optional)
#image_preview = "static/img/ftl.png"

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
#url_pdf = "article-1.pdf"
#url_preprint = "https://arxiv.org/abs/1810.07842"
#url_code = "https://github.com/nabsabraham/focal-tversky-unet"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#[[url_custom]]
#name = "Journal"
#url = "https://link.springer.com/article/10.1007/s10584-014-1174-4"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true
  
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "ftl.png"
#caption = "My caption :smile:"

+++
