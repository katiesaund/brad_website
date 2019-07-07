+++
# Project title.
title = "Computer vision aided laundry sorting"

# Date this page was created.
date = 2017-01-01

# Project summary to display on homepage.
summary = "Computer vision aided laundry sorting"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Computer vision", "manipulation"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  # caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

At the University of Michigan in collaboration with my lab I made our robot, Victor, pick through a pile of laundry to find a specific shirt. Computer vision segmented the clothing and if the target shirt was not visible or not reachable an algorithm decided which clothing item to pick. A grasp planner and motion planner moved directed the robot arm to grab an item. The pick was verified by computer vision and non-target objects were discarded until the target was found.
{{< youtube Ye3lTp2l1is >}}
