---
title: 'Global Climate Time Series Animation'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sara Cornejo
date: '2025-01-24'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Course Assignment – Geospatial Visualization"
publication_short: In *ICW*

abstract: This project presents an animated visualization of global climate patterns using monthly precipitation data. Developed in ArcGIS Pro, the work combines raster datasets from WorldClim with vector layers from Natural Earth to create a consistent and stylized globe representation. The animation highlights seasonal variability in precipitation through time, using standardized symbology and automated export workflows.

# Summary. An optional shortened abstract.
summary:  Animated global climate visualization using ArcGIS Pro and monthly raster datasets.
tags:
   - Cartography
  - Climate Data
  - ArcGIS Pro
  - Raster Analysis
  - Animation
  - Geospatial Visualization

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.5555/123456

# Custom links
links:
  - type: source
    url: https://www.worldclim.org/
  - type: source
    url: https://www.naturalearthdata.com/

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Created as part of a geospatial visualization assignment. Based on a tutorial by Nelson Schäfer / NelloMaps."
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
This project was developed as part of a geospatial visualization assignment focused on creating animated climate maps. The workflow involved processing global precipitation raster data, applying consistent symbology across monthly datasets, and designing a globe-style map layout in ArcGIS Pro.

Individual map frames were exported and combined into an animated GIF to visualize seasonal changes in precipitation. The final result emphasizes how cartographic design and animation can be used to communicate temporal environmental patterns.

**Credits:**  
Activity based on a tutorial by Nelson Schäfer / NelloMaps.  
Data sources: WorldClim and Natural Earth.  
GIF creation script adapted from course materials (Felipe Sanchez, 2025).

<img src="output.gif" alt="Global climate animation" width="700">
