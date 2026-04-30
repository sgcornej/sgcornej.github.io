---
title: 'Blue Whale Migration Animation'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me


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

abstract: This project visualizes blue whale migration patterns using spatial-temporal data aggregated by month over multiple years. The work combines cartographic design and animation techniques to represent movement patterns across the Pacific Ocean. Using ArcGIS Pro, the project integrates point data, customized symbology, and automated workflows to create a dynamic visualization of whale locations through time.

# Summary. An optional shortened abstract.
summary: Animated map showing monthly blue whale migration patterns using ArcGIS Pro.
tags:
  - Cartography
  - Animation
  - ArcGIS Pro

# Display this page in the Featured widget?
featured: true

# Custom links
links:
  - type: source
    url: https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/how-to-make-this-animated-map-of-blue-whale-migration


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

This project focuses on high-density data visualization, exploring how advanced symbology—such as glows, shadows, and transparency—can be used to reveal patterns in 16 years of blue whale tracking data.

To represent temporal patterns, the data were aggregated into monthly groups and visualized through a 12-frame animation. The workflow combined cartographic design with automation, using arcpy to filter data and export consistent map layouts for each time step. This approach allows flexibility to adjust styling, temporal grouping, or spatial extent and quickly regenerate the animation.

### Animation
![Blue whale migration](whale_animation.gif)

### Sources and Credits
- Data: Movebank – Blue Whale tracking dataset (Mate et al., 2019)  
- Design inspiration and workflow: John Nelson (2023), *Make This Blue Whale Migration Animation*  
- Basemap and bathymetry: Esri Living Atlas
