+++
title = "Planning and Localizing under Contact Uncertainty"

# Date first published.
date = "2017-07-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Brad Saund"]
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "Master's thesis"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Contacting the world can provide stability, support, and sensory information, however, many robots avoid contact whenever possible. Contacts present the physical danger of large forces as well as challenging computational issues, but enabling robots to reason about contacts extends the capabilities of robots to perceive and act in the world. This thesis explores both localization and planning where contacts are required. Contact measurements are sparse and precise, and contact forces are sudden and hard. In this work, several common techniques in robotics are adapted to better handle the local nature of contacts. A particle filter is augmented to both update from a precise measurement that would ordinarily eliminate most particles, and also accommodate internal model uncertainty. An efficient information gain metric is defined using these particles to predict useful future measurements. A new contact dynamics model and associated cost function are created for a robotic arm, which although different than the real dynamics, are conditioned well for use in existing planning methods. This artificial but useful dynamics model is shown in both trajectory optimization and sampled-based planning."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
# https://www.tandfonline.com/doi/full/10.1080/15384047.2016.1250047

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "glioma_wikipedia_commons.jpg"
#caption = "Glioma of the left parietal lobe. CT scan with contrast enhancement. Source: #https://commons.wikimedia.org/wiki/File:Glioma.gif"

+++
{{% staticref "file/thesis.pdf" "newtab" %}} PDF {{% /staticref %}}
