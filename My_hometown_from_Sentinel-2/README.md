In this notebook I'm going to investigate my hometown area seen from the "eyes" of Sentinel-2 satellites, part of the ESA Copernicus constellation.

Instead of accessing data through one of the many portals available in the web, I will request data through APIs (Sentinel Hub in the specific).

In order to retrieve meaningful data from optical bands, request will be calibrated to get the first least cloud-free image from the chosen date.

Examples with some of the most common indices will be shown in two ways: first getting data from a boundig box area around my hometown, second cropping the image for its administrative area bounding.
