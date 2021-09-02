+++
title = "Vision and force based autonomous coating with rollers"
date = 2020-07-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["Yayun Du", "Zhaoxing Deng", "Zicheng Fang", "Yunbo Wang", "Taiki Nagata", "Karan Bansal", "Mohiuddin Quadir", "Mohammad Khalid Jawed"]

# Publication type.

# Legend:

# 0 = Uncategorized

# 1 = Conference paper

# 2 = Journal article

# 3 = Preprint / Working Paper

# 4 = Report

# 5 = Book

# 6 = Book section

# 7 = Thesis

# 8 = Patent

publication_types = ["1"]

# Publication name and optional abbreviated version.

publication = "In 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems"
publication_short = "In IROS (2020)"

# Abstract.

abstract = "Coating rollers are widely popular in structural painting, in comparison with brushes and sprayers, due to thicker paint layer, better color consistency, and effortless customizability of holder frame and naps. In this paper, we introduce a cost-effective method to employ a general purpose robot (Sawyer, Rethink Robotics) for autonomous coating. To sense the position and the shape of the target object to be coated, the robot is combined with an RGB-Depth camera. The combined system autonomously recognizes the number of faces of the object as well as their position and surface normal. Unlike related work based on two-dimensional RGB-based image processing, all the analyses and algorithms here employ three-dimensional point cloud data (PCD). The object model learned from the PCD is then autonomously analyzed to achieve optimal motion planning to avoid collision between the robot arm and the object. To achieve human-level performance in terms of the quality of coating using the bare minimum ingredients, a combination of our own passive and builtin active impedance control is implemented. The former is realized by installing an ultrasonic sensor at the end-effector of robot working with a customized compliant mass-spring-damper roller to keep a precise distance between the end-effector and surface to be coated, maintaining a fixed force. Altogether, the control approach mimics human painting as evidenced by experimental measurements on the thickness of the coating. Coating on two different polyhedral objects is also demonstrated to test the overall method."

# Summary. An optional shortened abstract.

summary = "2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)"

# Digital Object Identifier (DOI)/

doi = ""

# Is this a featured publication? (true/false)

featured = false

# Tags (optional).

# Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.

# tags = ["So"]

tags = ["Autonomous coating", "roller coating", "vision", "force feedback", "point cloud data", "human-level performance"]

# Projects (optional).

# Associate this publication with one or more of your projects.

# Simply enter your project's folder or file name without extension.

# E.g. `projects = ["deep-learning"]` references

# `content/project/deep-learning/index.md`.

#projects = ["RoboticArmControl"]

# Otherwise, set `projects = []`.

projects = [""]

# Slides (optional).

# Associate this publication with Markdown slides.

# Simply enter your slide deck's filename without extension.

# E.g. `slides = "example-slides"` references

# `content/slides/example-slides.md`.

# Otherwise, set `slides = ""`.

slides = "example"

# Links (optional).

url_pdf = "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9341619"
#url_code = "#"
#url_dataset = "#"
#url_project = ""
#url_slides = ""
#url_video = "https://www.youtube.com/watch?v=upDizLiNd2s&t=2s"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).

# Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.

#links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image

# To use, add an image named `featured.jpg/png` to your page's folder.

[image]

# Caption (optional)

# caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

# Focal point (optional)

# Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight

focal_point = ""
+++

{{% alert note %}}
Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
{{% /alert %}}
