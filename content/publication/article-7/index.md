+++
title = "Space vehicle radiation pressure modelling: A demonstration on Galileo satellites in GNSS"
date = "2019-03-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["**Zhen Li**"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
# 7 = thesis
# 8 = Patent
publication_types = ["7"]

# Publication name and optional abbreviated version.
publication = "University College London"
publication_short = "UCL"

# Abstract and optional shortened version.

#abstract = "abcde."

abstract = "In an operational sense, orbit prediction is a fundamental requirement in generating the broadcast ephemeris for Global Navigation Satellite System (GNSS) satellites. Galileo as the European GNSS is now under construction and will be fully operational in 2020. Orbit prediction error is a significant component of the error budget of broadcast ephemeris of Galileo satellites. In short, orbit prediction is intrinsically linked to broadcast ephemeris quality. The quality of orbit prediction relies on accurate force models and initial state (position and velocity). The initial state is usually obtained from precise orbit determination. This research focuses on aspects of force modelling. For the Galileo satellites, the largest force not well modelled is radiation pressure. Using the physics of radiation pressure as an entry point, this thesis is organised according to the technical elements (radiation flux, interaction between radiation flux and surfaces) of radiation pressure modelling. In terms of radiation flux modelling, a runtime and accuracy configurable Earth radiation flux model is developed based on the longwave and shortwave Earth flux observations from Clouds and Earth's Radiant Energy System (CERES), a shadow function that considers both the Earth's oblateness and atmospheric effect is developed to scale the solar radiation flux at a satellite's location when the satellite is in eclipse. In terms of the interaction between radiation flux and satellite's surfaces, a fast ray tracing algorithm is implemented and gets a speedup by a factor of 30--50 compared with the classical modelling method. In addition, an empirical solar radiation pressure model (the DREMT) is developed based on box-wing satellite model to cope with the un-modelled residuals of physical models. Finally, both the physical models and empirical models are validated in the orbit prediction test. The orbit contribution of Signal in Space Ranging Error (SISRE) is used as an indicator to assess the quality of a 7-day predicted orbit. The newly developed DREMT improved the orbit by around 50% compared with the widely used empirical models (ECOM-1 and ECOM-2) when satellites are not in eclipse. After applying the physical models as a priori models in orbit prediction, DREMT, EOCM-1, and ECOM-2 get identical prediction performance. The DREMT does not get significant improvements using a priori models because it already contains box-wing satellite information implicitly. It is generally the case that the prediction performance is better in non-eclipse seasons than that in eclipse seasons due to a lack of knowledge regarding satellite attitude in eclipse."

# Featured image thumbnail (optional)
#image_preview = "static/img/ftl.png"

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
#url_pdf = "article-3.pdf"
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
