+++

title = "Hardware implementation and control design of generator emulator in multi-converter system"
date = 2013-03-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Liu Yang","__**Xiaohu Zhang**__","Yiwei Ma","Jing Wang","Lijun Hang","Keman Lin", "Leon M. Tolbert", "Fred Wang", "Kevin Tomsovic"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*in Proceedings of Twenty-Eighth Annual IEEE Applied Power Electronics Conference and Exposition (APEC)*, 2013."
publication_short = "*IEEE APEC*"

# Abstract and optional shortened version.
abstract = "In this project to develop a reconfigurable electrical grid emulator, a Hardware Test-Bed (HTB) is being developed that emulates large scale power system generators and loads by using power electronic converters. Source converters in the HTB system are designed to emulate generators. A synchronous generator model is implemented in the converter to calculate the voltage references in the dq axis, and a voltage controller is added to achieve zero steady state error. A traditional cascade controller with inner current control and outer voltage control brings additional output impedance to the generator model, and causes voltage tracking error during transients. To minimize the controller output impedance and eliminate controller influence on the generator model, a single voltage loop with current differential feedback is proposed in this paper. Combined with rescaled generator parameters, circulating current elimination, and dead time compensation, simulation and experiments are performed in the HTB. The results verify the effectiveness of the controller and demonstrate the dynamic generator emulator behavior."

abstract_short = " A synchronous generator model is implemented in the converter to calculate the voltage references in the dq axis, and a voltage controller is added to achieve zero steady state error.."

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["2011_htb"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Hardware Testbed"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/6520618"
url_preprint = "https://www.researchgate.net/profile/Xiaohu_Zhang/publication/260737971_Hardware_implementation_and_control_design_of_generator_emulator_in_multi-converter_system/links/5939ee630f7e9b32b749b816/Hardware-implementation-and-control-design-of-generator-emulator-in-multi-converter-system.pdf"
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
#doi = "10.1109/CAMSAP.2011.6135900"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

+++

