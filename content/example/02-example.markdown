---
title: "Workflows for getting spatial data into R"
linktitle: "2: Getting your spatial data into R"
date: "2021-09-01"
toc: yes
menu:
  example:
    parent: Examples
    weight: 2
type: docs
editor_options: 
  chunk_output_type: console
---

Today's exercise and assignment will focus on getting different types of spatial data into R; exploring the CRS, extent, and resolution of those objects; and aligning objects with different projections. We'll look at ways to do this using the `sf`, `sp` (with `rgdal`), `raster`, and `terra` packages. 

## Getting started
Remember that we'll be using GitHub classroom so you'll need to introduce yourself to git and then clone the Assignment 2 repository. The instructions are in [Example 1](/example/01-example/)