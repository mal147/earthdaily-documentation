---
title: Automatic Boundary
description: This section wil explain how to access field borders using a longitude and a latitude as the input. 
# icon: fontawesome/question
status: new
---

# Automatic Field Borders

## Description

This analytic provides automatic field borders for a point (longitude and latitude coordinates).
This feature is available through API and through the GeosysApp.

## Baseline data

Sentinel-2 super-resolution images at 1m resolution are used to create these fields borders. 

## API 

<swagger-ui src="https://api.geosys-na.net/field-borders/v1/swagger/index.html"/>

### GET URL examples

url = "https://api.geosys-na.net/field-borders/v1/AutomaticBoundary?location={longitude}, {latitude}&simplified_geom=true"
url = "https://api.geosys-na.net/field-borders/v1/AutomaticBoundary?location=-54.889741119522725, -15.457580011321795&simplified_geom=true"

## Performance and accuracy

Intersection of Union average accuracy score of 0.94-0.96.

## Use case and product

This analytic is used in:
    - [Portfolio](/earthdaily-documentation/Agro/Portfolio/portfolio_product_site_draft/)
    - 
