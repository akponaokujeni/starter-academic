---
title: Regression-based unmixing using synthetic training data
summary: " "
tags:
date: "2021-07-12"

# Optional external URL for project (replaces project detail page).
external_link:

image:
  caption: 
  focal_point: Smart


links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
<br />
**Background**<br />
Most terrestrial ecosystems are characterized by mixtures of different land cover types, by spatial transitions between land cover types and by abrupt and gradual land cover change processes. Mapping fractions of multiple land cover classes through spectral unmixing provides a quantitative means to describe such ecosystem characteristics across space and time.

<br />
**Research**<br />
A specific methodological focus of my research is on regression-based unmixing with synthetic training data. Based on a spectral library and random synthetic mixing, continuous artificial training samples are generated and used for land cover fraction mapping through regression modeling. This approach was originally developed in the context of urban mapping and has been brought forward with regard to vegetation mapping in natural and semi-natural ecosystems as well as time series applications.

Regression-based unmixing with synthetic training data has become a core method in several research projects and publications. The approach has been implemented as a user-friendly application in the 👉[EnMAP-Box](https://enmap-box.readthedocs.io/en/latest/) and is documented in detail for 👉[E-learning](https://enmap-box.readthedocs.io/en/latest/usr_section/application_tutorials/urban_unmixing/tutorial.html). The method is also available in the python package 👉[HUB-Workflow](http://hub-workflow.readthedocs.io) and integrated into the 👉[FORCE](https://force-eo.readthedocs.io/en/latest/index.html) processing engine. 


<br />
**Selected publications**<br />

* Okujeni, A., Jänicke, C., Cooper, S., Frantz, D., Hostert, P., Clark, M., Segl, K., & van der Linden, S. (2021). Multi-season unmixing of vegetation class fractions across diverse Californian ecoregions using simulated spaceborne imaging spectroscopy data. Remote Sensing of Environment. [https://doi.org/10.1016/j.rse.2021.112558](https://doi.org/10.1016/j.rse.2021.112558) 

* Senf, C., Laštovička, J., Okujeni, A., Heurich, M., & van der Linden, S. (2020). A generalized regression-based unmixing model for mapping forest cover fractions throughout three decades of Landsat data. Remote Sensing of Environment, 240, 111691. [https://doi.org/10.1016/j.rse.2020.111691](https://doi.org/10.1016/j.rse.2020.111691)

* Priem, F., Okujeni, A., van der Linden, S., & Canters, F. (2019). Comparing map-based and library-based training approaches for urban land-cover fraction mapping from Sentinel-2 imagery. International Journal of Applied Earth Observation and Geoinformation, 78, 295-305. [https://doi.org/10.1016/j.jag.2019.02.003](https://doi.org/10.1016/j.jag.2019.02.003)

* Okujeni, A., Canters, F., Cooper, S.D., Degerickx, J., Heiden, U., Hostert, P., Priem, F., Roberts, D.A., Somers, B., & van der Linden, S. (2018). Generalizing machine learning regression models using multi-site spectral libraries for mapping vegetation-impervious-soil fractions across multiple cities. Remote Sensing of Environment, 216, 482-496. [https://doi.org/10.1016/j.rse.2018.07.011](https://doi.org/10.1016/j.rse.2018.07.011)

* Okujeni, A., van der Linden, S., Suess, S., & Hostert, P. (2017). Ensemble learning from synthetically mixed training data for quantifying urban land cover with support vector regression. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 10, 1640-1650. [https://doi.org/10.1109/JSTARS.2016.2634859](https://doi.org/10.1109/JSTARS.2016.2634859)

* Okujeni, A., van der Linden, S., Tits, L., Somers, B., & Hostert, P. (2013). Support vector regression and synthetically mixed training data for quantifying urban land cover. Remote Sensing of Environment, 137, 184-197. [https://doi.org/10.1016/j.rse.2013.06.0079](https://doi.org/10.1016/j.rse.2013.06.007)