+++
# Projects widget.
# This widget displays all projects from `content/project/`.

date = "2016-04-20T00:00:00"
draft = false

title = "Projects"
subtitle = ""
widget = "projects"

# Order that this section will appear in.
weight = 20

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.
# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"
  
[[filter]]
  name = "R Packages"
  tag = ".r-package"

[[filter]]
  name = "Shiny Apps"
  tag = ".shiny"

[[filter]]
  name = "Rstats"
  tag = ".rstats"
  
[[filter]]
  name = "PhD Thesis"
  tag = ".phd-thesis"

[[filter]]
  name = "Personal Projects"
  tag = ".personal-projects"
  
[[filter]]
  name = "P2P Finance"
  tag = ".p2p"

+++
