+++
title = "Bilateral international migration flow estimates updated and refined by sex"
date = "2022-04-14"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Guy J. Abel", "Joel E. Cohen"]

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
publication = "In *Scientific Data* 173 (9)."
publication_short = ""

# Abstract and optional shortened version.
abstract = "Females and males often migrate at different rates. Official data on sex-specific international migration flows are missing for most countries, prohibiting comparative measures to identify and address inequalities. Here we use six methods to estimate male and female five-year bilateral migration flows between 200 countries from 1990 to 2020. We validate the estimates from each method through correlations of several migration measures with equivalent reported statistics in countries that collect flow data. We find that the Pseudo-Bayesian demographic accounting method performs consistently better than the other estimation methods for both female and male estimated flows. The estimates from all methods indicate a decline in the share of female migration flows from 1990–1995 to 2005–2010 followed by a recovery over the decade since 2010."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.


# Links (optional).
doi = "10.1038/s41597-022-01271-z"
url_code = "https://figshare.com/collections/Bilateral_international_migration_flow_estimates_by_sex/5800838"
url_dataset = "https://figshare.com/collections/Bilateral_international_migration_flow_estimates_by_sex/5800838"
url_pdf = "https://rdcu.be/cLkwX"
url_preprint = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "", url = ""}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
# image = "headers/global-flow-sex.png"
# caption = "Bilateral international migration flow estimates by sex"

+++

Follow the links above to download the data. Below are a couple of extra animations I created to show some of the data. These were created using in  [R](https://guyabel.com/categories/r/)  using code adapted from this [post](https://guyabel.com/post/animated-directional-chord-diagrams/)

#### Sex differences

<style>
video {
  /* override other styles to make responsive */
  width: 100%    !important;
  height: auto   !important;
  max-height: 720px
}
</style>

<video loop="loop" controls>
<source src="sex-abel.mp4" type="video/mp4"/>
</video>

#### Changes over time

<video loop="loop" controls>
<source src="time-abel.mp4" type="video/mp4"/>
</video>
