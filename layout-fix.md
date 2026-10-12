---
title: Layout Fix
subject: Geospatial
subtitle: 1-click fix for ArcGis layouts
short_title: Layouts
date: 2026-10-12
authors:
  - name: Vance Russell
    affiliations: 
      - 3point.xyz
    email: vance@3point.xyz
license: CC-BY-4.0
keywords: ArcGIS, geospatial, cartography, mapping
abstract: |
  The default settings used in ArcGIS Pro layouts seldom correspond with a cartographer's intentions, which means that each new layout or one that is being reused has to be manually checked over in terms of page setup, margins, scale bars, north arrows, legends, and grid options so that the unnecessary elements can be turned off and the ones that are needed can be adjusted. The layer credits from map services also add to the difficulty of the situation since they are automatically placed in the layout, are usually positioned well outside the visible area of the page, and are very hard to move or restyle without having to go through repeated trials and errors. This paper presents a one-click Python toolbox tool that solves both of these issues by resetting the default settings of any nonessential layout components and bringing the credits from the service layers into a convenient and consistent location through a single operation. The tool is based on a customizable .pyt template, allowing users to modify the position of the credits, the default page settings, and the elements that are disabled in order to align with their own organization's cartographic standards rather than having to begin from scratch. A step-by-step setup guide is provided so that readers can create and customize their own version in just a few minutes and thus save a great deal of time on all the layouts they make afterwards.
kernelspec:
  name: python3
  display_name: Python 3
exports:
  - format: docx
    template: curvenote
    output: layout.docx
    article_type: Report
  - format: typst
    template: lapreprint-typst
    output: layout.pdf     
---

:::{figure} text-erase.png
:alt: Finger pointing at apps
:::

> "It's a layout, I mean what can you expect?" Get a quote

# background

:::{important} Layouts
:class: dropdown

Layouts are easy, see this guide in arcgis and suggestions from Marc or John on youtube

:::

# Key Steps

## Resources
If you need some help on setup or geospatial analysis in general, please reach out: [info@3point.xyz](mailto:info@3point.xyz)