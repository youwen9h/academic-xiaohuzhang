+++
# Project title.
title = "Deadline Scheduling"

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "Scheduling of jobs with deadlines, such as EV charging, internet streaming, and communications."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Machine Learning","Deadline Scheduling", "Restless Bandits"]

# Optional external URL for project (replaces project detail page).
#external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"

# Links (optional).
#url_pdf = ""
#url_slides = ""
#url_video = ""
#url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by Zhe Yu"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
The deadline scheduling problem, in its most generic setting, is the scheduling of jobs with different workloads and deadlines for completion. Typically, not enough servers are available to satisfy all the demand; the cost of processing may vary with time and unfinished jobs incur penalties. 
In this project, we are interested in the stochastic deadline scheduling problem where key parameters of the problem such as job arrivals,workloads, deadlines of completion, and processing costs are stochastic. In particular, we consider the problem of maximizing discounted rewards over an infinite scheduling horizon.
A prototype application of such a problem is the charging of electric vehicles (EVs) at a charging service center. In such applications, EVs arrive at the service center randomly, each with its charging demand and deadline for completion. The charging cost depends on the cost of electricity at the time of charging, and a penalty is imposed when the service provider is unable to fulfill the request. Similar applications include the scheduling of packet transmission for real-time wireless networks, of jobs at data centers, of nursing personnel in hospitals, for internet streaming, and at customer service centers.
