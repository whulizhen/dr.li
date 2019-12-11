+++
title = "A shadow function model based on perspective projection and atmospheric effect for satellites in eclipse"
date = "2018-10-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["**Zhen Li**","Marek Ziebart","Santosh Bhattarai","David Harrison"]

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
#publication_short = "ASR"

# Abstract and optional shortened version.

#abstract = "abcde."

abstract = "Accurate Solar Radiation Pressure (SRP) modelling is critical for correctly describing the dynamics of satellites. A shadow function is a unitless quantity varying between 0 and 1 to scale the solar radiation flux at a satellite’s location during eclipses. Errors in modelling shadow function lead to inaccuracy in SRP that degrades the orbit quality. Shadow function modelling requires solutions to a geometrical problem (Earth’s oblateness) and a physical problem (atmospheric effects). This study presents a new shadow function model (PPM_atm) which uses a perspective projection based approach to solve the geometrical problem rigorously and a linear function to describe the reduction of solar radiation flux due to atmospheric effects. GRACE (Gravity Recovery And Climate Experiment) satellites carry accelerometers that record variations of non-conservative forces, which reveal the variations of shadow function during eclipses. In this study, the PPM_atm is validated using accelerometer observations of the GRACE-A satellite. Test results show that the PPM_atm is closer to the variations in accelerometer observations than the widely used SECM (Spherical Earth Conical Model). Taking the accelerometer observations derived shadow function as the “truth”, the relative error in PPM_atm is - 0.79 % while the SECM 11.07%. The influence of the PPM_atm is also shown in orbit prediction for Galileo satellites. Compared with the SECM, the PPM_atm can reduce the radial orbit error RMS by 5.6 cm over a 7-day prediction. The impacts of the errors in shadow function modelling on the orbit remain to be systematic and should be mitigated in long-term orbit prediction."

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
