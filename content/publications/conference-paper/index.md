---
title: 'Global Climate Time Series Animation'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-01-30T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['report']

# Publication name and optional abbreviated publication name.
publication: Course Assignment - Geospatial Visualization
publication_short: 

abstract: This project presents an animated visualization of global climate patterns using monthly precipitation data. Developed in ArcGIS Pro, the work combines raster datasets from WorldClim with vector layers from Natural Earth to create a consistent and stylized globe representation.

# Summary. An optional shortened abstract.
summary: Animated global climate visualization using ArcGIS Pro and monthly raster datasets.
tags:
  - Cartography

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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


This project explores the use of animation and cartography to visualize global climate patterns through time.

Using ArcGIS Pro, I created monthly map frames from precipitation raster data and combined them into an animated GIF to show seasonal variation. The workflow included applying consistent symbology across all rasters, designing a globe-style projection, and exporting frames for animation.

**Credits:**  
Activity based on a tutorial by Nelson Schäfer / NelloMaps.  
Data sources: WorldClim and Natural Earth.

![Global climate animation](output.gif)
