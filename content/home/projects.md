+++
# Projects widget.
# This widget displays all projects from `content/project/`.

date = "2016-04-20T00:00:00"
draft = false

title = "Projects"
subtitle = ""
widget = "projects"

# Order that this section will appear in.
weight = 30

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 1

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"
  
[[filter]]
  name = "Ongoing"
  tag = ".ongoing"

[[filter]]
  name = "Images"
  tag = ".archeomatica, .vedi, .tsp"

[[filter]]
  name = "Video"
  tag = ".archeomatica, .vedi, .recfusion"

[[filter]]
  name = "3D Data"
  tag = ".archeomatica, .medicalresearch"

+++

