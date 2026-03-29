+++
# Teaching section with manual course links
widget = "portfolio"
headless = true
active = true
weight = 30

title = "Teaching"
subtitle = ""

[content]
  page_type = "project"
  filter_default = 0

  [[content.filter_button]]
    name = "Courses"
    tag = "Courses"

  # Manual entries for courses
  [[content.projects]]
    title = "Cosmology and Astroparticle Physics"
    description = "Graduate-level course on cosmology and astroparticle physics."
    tags = ["Courses"]
    url = "cosmology-astroparticles-course/"

  [[content.projects]]
    title = "Introduction to Astrophysics"
    description = "Undergraduate course covering basic astrophysics concepts."
    tags = ["Courses"]
    url = "intro-astrophysics-course/"

  [[content.projects]]
    title = "Data Analysis Workshop"
    description = "Hands-on workshop on scientific data analysis."
    tags = ["Workshops"]
    url = "data-analysis-workshop/"

[design]
  columns = "1"
  view = 5
  flip_alt_rows = false

[design.background]
  # Optional: uncomment and customize background
  # color = "navy"
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  # image = "background.jpg"
  # image_darken = 0.6
  # text_color_light = true  

[advanced]
  css_style = ""
  css_class = ""
+++
