+++
title = "Belief Representations for Planning with Contact Uncertainty (PhD Thesis)"

# Date first published.
date = "2021-09-18"

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
publication_types = []

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = """
While reaching for your morning coffee you may accidentally bump into the table, yet you reroute your motion with ease and grab your cup. An effective autonomous robot will need to have a similarly seamless recovery from unexpected contact. As simple as this may seem, for decades manufacturing robots were not able to sense contact quickly and precisely enough to stop during a collision, so robots in factory environments lived in tightly controlled and expensively precise work zones. Recent collaborative robots can now stop after collision so successfully they have been deemed safe to work around people. However unexpected contact is still treated as an error that an operator is expected to resolve. Robots operating in our less-structured daily environments will need to reason about the information they have gained from contact and replan autonomously.

This thesis examines planning under uncertainty with contact sensitive robot arms. First addressed is the specific information gained from sensing contact. Most robots do not have skin and cannot precisely sense the location of contact. This leads to the proposed *Collision Hypothesis Set* model for representing a belief over the possible occupancy of the world sensed through contact. To capture the specifics of planning in a heavily occluded environment with this measurement model, we develop a POMDP approach called the *Blindfolded Traveler's Problem* and propose several strategies for practical approximate solutions. Finally, we examine belief representations for the occupancy of the world to more closely approximate a rich prior over possible objects. We propose a neural network for shape completion that combines both visual and contact information.
"""
  
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
#Add this below link to pdf when final video is ready: Watch the demo: 
#remembertoupdateyoutubelink{{< youtube EjCq1Q4nNUc >}}

+++
{{% staticref "file/PhdThesis.pdf" "newtab" %}} 
Download my PhD Thesis{{% /staticref %}}



