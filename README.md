# Fiber Analyzer GUI

**Fiber Analyzer GUI** is a Python-based desktop application for the **automated multiscale morphometric analysis of fibrous networks** from scanning electron microscopy (SEM) images. The software provides accurate, reproducible, and efficient characterization of fiber morphology in both pure fiber networks and mixed fiber–particle systems.

Developed at the **University of Louisiana at Lafayette**, Fiber Analyzer GUI enables researchers to quantify key structural parameters while significantly reducing the time, subjectivity, and variability associated with manual measurements.

---

## Related Publication

This software accompanies the following publication:

**Title:** **Automated Multi-Scale Morphometry Analysis of Fibrous Networks**

***Authors:** **Sandesh Giri, Kenneth Gordon, Karson Vidrine, Ling Fei*, and Sen Liu***

**Published:** *American Chemical Society (ACS), March 2026.*

**DOI:** *https://doi.org/10.1021/acsomega.6c00451*

If you use this software in your research, please cite both the software and the associated publication.

---

## Features

* Automated segmentation of fibrous networks from SEM images
* Supports both pure fiber networks and mixed fiber–particle morphologies
* Dual-pipeline image processing framework
* Adaptive Contour-based Diameter Estimation (ACDE) for accurate fiber diameter measurement
* Automated measurements of:

  * Fiber diameter
  * Fiber length
  * Aspect ratio
  * Particle detection
  * Fiber morphology statistics
* Batch image processing
* Interactive graphical user interface (GUI)
* Export of quantitative measurements for further analysis

---

## Method Overview

Fiber Analyzer GUI integrates two complementary analysis pipelines:

### Pure Fiber Networks

A filter-based segmentation pipeline designed for continuous fibrous structures.

### Mixed Fiber–Particle Systems

Morphological filtering combined with aspect-ratio thresholding to accurately separate elongated fibers from particulate matter.

### Fiber Diameter Estimation

The software implements **Adaptive Contour-based Diameter Estimation (ACDE)**, an active contour (snake) based algorithm that measures fiber diameter at multiple skeletal locations, providing robust multiscale morphometric characterization.

---

## Installation

### Windows

Download the latest executable from the Releases page.

No Python installation is required.

---

## Usage

1. Launch **Fiber Analyzer GUI**.
2. Load an SEM image.
3. Select the desired analysis settings.
4. Run automated morphometric analysis.
5. Review visualization and quantitative results.
6. Export measurements for statistical analysis.

---

## Repository Structure

```text
Fiber-Analyzer-GUI/
│
├── README.md
├── LICENSE
├── Releases/
└── Source files
```

---

## Citation

If you use Fiber Analyzer GUI in your research, please cite:

**Journal Article**

```bibtex
@article{giri2026automated,
  title={Automated Multi-Scale Morphometry Analysis of Fibrous Networks},
  author={Giri, Sandesh and Gordon, Kenneth and Vidrine, Karson and Fei, Ling and Liu, Sen},
  journal={ACS Omega},
  volume={11},
  number={12},
  pages={19799--19810},
  year={2026},
  DOI: {https://doi.org/10.1021/acsomega.6c00451},
  publisher={ACS Publications}
}
```

**Software**

```bibtex
@software{Giri2026FiberAnalyzer,
  author = {Sandesh Giri},
  title = {Fiber Analyzer GUI},
  year = {2026},
  version = {1.1.0},
  url = {https://github.com/Sandesgiri/Fiber-Analyzer-GUI}
}
```

---

## License

This repository is distributed under the **MIT License**.

The accompanying journal publication is published under the **CC BY-NC-ND 4.0** license.

---

## Acknowledgments

This work was developed as part of research conducted at the **University of Louisiana at Lafayette**.

We thank all collaborators and funding agencies that supported this work.

---

## Contact

For questions, suggestions, or collaborations, please open an issue in this repository or contact the corresponding authors through the associated publication.
