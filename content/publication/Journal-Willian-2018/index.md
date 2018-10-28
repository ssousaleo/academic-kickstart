+++
title = "On the Identification of Design Problems in Stinky Code: Experiences and Tool Support"
date = 2018-03-21T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Willian Oizumi","Leonardo Sousa","Anderson Oliveira","Alessandro Garcia","Anne Benedicte Agbachi","Roberto Oliveira","Carlos Lucena"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Journal of the Brazilian Computer Societyg"
publication_short = "In *SBES'18*"

# Abstract and optional shortened version.
abstract = "Background: Developers often have to locate design problems in the source code. Several types of design problems may manifest as code smells in the program. A code smell is a source code structure that may reveal a partial hint about the manifestation of a design problem. Recent studies suggest that developers should ignore smells occurring in isolation in a program location. Instead, they should focus on analyzing stinkier code, i.e., program locations—e.g., a class or a hierarchy—affected by multiple smells. There is evidence that the stinkier a program location is, the more likely it contains a design problem. However, there is no empirical evidence on whether developers can effectively identify a design problem in stinkier code. Developers may struggle to make an analysis of inter-related smells affecting the same program location. Besides that, the analysis of stinkier code may require proper tool support due to its analysis complexity. However, there is little knowledge on what are the requirements for a tool that helps developers in revealing stinkier program locations. As a result, developers may not be able to identify design problems due to tool issues. Method: To address this matter, we aimed at achieving three goals. In the first case, we proposed Organic—a tool supporting the analysis of stinky code. In the second case, we applied a mixed-method approach to analyze if and how developers can effectively find design problems when reflecting upon stinky code—i.e., a program location affected by multiple smells. We conducted a study with 11 software professionals. Finally, in the third case, we aimed at understanding if Organic could be used by developers to identify design problems. To achieve this goal, we used a method from the Semiotic Engineering theory. This method enabled us to evaluate what are the tool issues that may hinder the identification of design problems in stinky code. Result: Our study revealed that only 36.36% of the developers found more design problems when explicitly reasoning about multiple smells as compared to single smells. Moreover, 63.63% of the developers reported much lesser false positives when using the first approach as compared to the latter. The second study, in its turn, showed that most developers may be unable to identify design problems in stinky code without proper tool support. Conclusion: Our experiences, in particular the second study, helped us to refine the features of Organic for better supporting developers in reflecting upon stinkier code. For example, analyses of stinky code scattered in class hierarchies or packages is often difficult, time-consuming, and requires proper visualization support. Moreover, without effective support, it remains time-consuming to discard stinky program locations that do not represent design problems."
abstract_short = " "


# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).s
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["agglomeration", "code smells", "design problems", "symptoms", "theory"]

# Links (optional).
#url_pdf = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
url_source = "https://doi.org/10.1186/s13173-018-0078-y"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1186/s13173-018-0078-y"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Journal of the Brazilian Computer Society**](https://journal-bcs.springeropen.com/)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++
