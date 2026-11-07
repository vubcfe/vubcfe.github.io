---
layout: page
title: Reliable crop monitoring
description: Multi-scale remote sensing with Sentinel and UAV data
importance: 1
category: satellite imagery
related_publications: true
---

This work maps and monitors crops in Vietnam for smart agriculture, starting with coffee in the Central Highlands. It uses Sentinel-2 and Sentinel-1 time series for crop mapping and yield estimation. The question behind it is how reliable these maps and estimates are: how their errors change across seasons, years and regions, under cloud cover and lower resolution, and how well a model's own uncertainty matches its real error when checked against field data.

The work is now being extended to combine two scales. Sentinel data cover whole regions every few days at 10 m resolution, while UAV imagery gives centimetre-level detail and 3D crop structure. UAV measurements, checked against ground control points and manual field measurements, will serve as a reference with known error for satellite models. This raises its own reliability questions: the error introduced by the scale gap, by different acquisition dates and by co-registration, and how far a model trained on a few UAV-surveyed fields can be trusted over a whole region. A further line studies how compression and on-device processing affect map accuracy.

## Related publications

{% cite le2026aidriven bui2026residualtail bui2026spectrally %}
