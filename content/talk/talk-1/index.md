---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Space vehicle radiation pressure modelling: A demonstration on Galileo satellits in GNSS"
event:
event_url:
location: Shanghai Astronomical Observatory
address:
  street:
  city: Shanghai
  region: Shanghai
  postcode:
  country: China
summary:
abstract: "The advances of GPS technology, and the broader development of other satellite systems (Galileo, BeiDou, etc.) have made GNSS an important tool in precision applications such as establishment of ITRF and precise orbit determination of LEO space vehicles. These applications require precise positions of GNSS satellites. Radiation pressure as the largest non-conservative force acting on GNSS satellites is a key in precise orbit determination. The recent progresses of physics-based radiation pressure modelling approaches for the Galileo satellites will be introduced. The modelling of radiation pressure includes the radiation flux modelling and how radiation flux interacts with the satellite surfaces. A new triangular mesh is used to build a runtime and accuracy configurable Earth radiation flux based on the CERES Earth radiation flux observations. In addition, when satellites go into eclipses, the solar radiation flux at the satellite’s location is reduced. A new shadow function model named PPM_atm is developed considering both Earth’s oblateness and the atmospheric effects. Over 700 components are used in building 3D models of the Galileo satellites to model the interactions between radiation flux and satellite surfaces in the ray tracing. Besides, a physics based empirical model is also developed to absorb the un-modelled physical effects. Both orbit prediction and orbit determination show that the use of UCL models improved the orbit quality of Galileo satellites."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-02-19T10:00:00Z
date_end: 2019-02-19T11:00:00Z
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-01-02T13:17:45Z

authors: [Zhen Li]
tags: []


# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
# url_slides: "talk/talk-1/talk-1.pptx"
url_code:
url_pdf: "talk-1.pdf"
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
