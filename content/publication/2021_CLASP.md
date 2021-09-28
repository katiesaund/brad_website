+++
title = "CLASP: Constrained Latent Shape Projection for Refining Object Shape from Robot Contact"

# Date first published.
date = "2021-11-16"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Brad Saund", "Dmitry Berenson"]
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
publication = "CoRL (Conference on Robotic Learning)"
publication_short = "CoRL"

# Abstract and optional shortened version.
abstract = "Robots need both visual and contact sensing to effectively estimate the state of their environment. Camera RGBD data provides rich information of the objects surrounding the robot, and shape priors can help correct noise and fill in gaps and occluded regions. However, when the robot senses unexpected contact, the estimate should be updated to explain the contact. To address this need, we propose CLASP: Constrained Latent Shape Projection. This approach consists of a shape completion network that generates a prior from RGBD data and a procedure to generate shapes consistent with both the network prior and robot contact observations. We find CLASP consistently decreases the Chamfer Distance between the predicted and ground truth scenes, while other approaches do not benefit from contact information."

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
{{% staticref "file/CLASP.pdf" "newtab" %}} 
Download the pdf{{% /staticref %}}

#Watch the demo: 

#{{< youtube f3nLH875nik >}}


