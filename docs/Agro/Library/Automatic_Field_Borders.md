---
title: Automatic Boundary
description: This section wil explain how to access field borders using a longitude and a latitude as the input. 
# icon: fontawesome/question
status: new
---

# Automatic Field Borders

## Description

This analytic automatically generates field boundaries based on point coordinates (longitude and latitude). 
The feature is accessible via both the API and the GeosysApp.
Postman collection is available.
Your account requires specific permissions to access this API. Please contact us to request access.

## Baseline data

It leverages super-resolution Sentinel-2 imagery at 1-meter resolution to delineate field borders with high precision.

## API 

<swagger-ui src="https://api.geosys-na.net/field-borders/v1/swagger/index.html"/>

### GET URL examples

- url = f"https://api.geosys-na.net/field-borders/v1/AutomaticBoundary?location={longitude},{latitude}&simplified_geom=true"
- url = "https://api.geosys-na.net/field-borders/v1/AutomaticBoundary?location=-54.889741119522725,-15.457580011321795&simplified_geom=true"

## Performance and accuracy

Intersection of Union average accuracy score of 0.94-0.96.

## Use case and product

This analytic is used in:
    - [Portfolio](/earthdaily-documentation/Agro/Portfolio/portfolio_product_site_draft/)
    - 
