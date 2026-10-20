---
title: "Shift-Variant Color-Coded Diffractive Spectral Imaging System"
authors:
  - Henry Arguello
  - Samuel Pinilla
  - Yifan Peng
  - Hayato Ikoma
  - Jorge Bacca
  - Gordon Wetzstein
date: "2021-11-01T00:00:00Z"
doi: "10.1364/OPTICA.439142"
publishDate: "2021-11-01T00:00:00Z"

publication_types: ["2"]

publication: In *Optica*
publication_short: Optica

abstract: "State-of-the-art snapshot spectral imaging (SI) systems introduce color-coded apertures (CCAs) into their setups to obtain a flexible spatial-spectral modulation, allowing spectral information to be reconstructed from a set of coded measurements. Besides the CCA, other optical elements, such as lenses, prisms, or beam splitters, are usually employed, making systems large and impractical. Recently, diffractive optical elements (DOEs) have partially replaced refractive lenses to drastically reduce the size of the SI devices. The sensing model of these systems is represented as a projection modeled by a spatially shift-invariant convolution between the unknown scene and a point spread function (PSF) at each spectral band. However, the height maps of the DOE are the only free parameters that offer changes in the spectral modulation, which causes the ill-posedness of the reconstruction to increase significantly. To overcome this challenge, our work explores the advantages of the spectral modulation of an optical setup composed of a DOE and a CCA. Specifically, the light is diffracted by the DOE and then filtered by the CCA, located close to the sensor. A shift-variant property of the proposed system is clearly evidenced, resulting in a different PSF for each pixel, where a symmetric structure constraint is imposed on the CCA to reduce the high number of resulting PSFs. Additionally, we jointly design the DOE and the CCA parameters with a fully differentiable image formation model using an end-to-end approach to minimize the deviation between the true and reconstructed image over a large set of images. Simulation shows that the proposed system improves the spectral reconstruction quality in up to 4 dB compared with current state-of-the-art systems. Finally, experimental results with a fabricated prototype in indoor and outdoor scenes validate the proposed system, where it can recover up to 49 high-fidelity spectral bands in the 420–660 nm."

summary: "Shift-variant color-coded diffractive spectral imaging system jointly designing DOE and CCA parameters for high-fidelity spectral reconstruction."

tags:
  - Diffractive Optics
  - Spectral Imaging
  - Computational Imaging
  - Optical Design
featured: true

url_pdf: "https://opg.optica.org/fulltext.cfm?uri=optica-8-11-1424&id=464500"
url_source: "http://opg.optica.org/optica/abstract.cfm?URI=optica-8-11-1424"
url_code: "https://github.com/jorgebaccauis/Shift-Variant-System"

image:
  caption: ""
  focal_point: Smart
  preview_only: false
---

Project website: https://jorgebaccauis.github.io/Shift-Variant-System/
