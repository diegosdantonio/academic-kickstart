---
title: "Development of a Real-time Simulation for AC-DC Hybrid Microgrids"
authors:
- María C. Salas-Castaño
- Diego Salazar-D'antonio
- Oswaldo López-Santos
date: "2020-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: "Lecture Notes in Computer Science"
publication_short: ""

abstract: "This paper describes the development of a real-time simulation platform able to analyze the behavior of an AC-DC hybrid microgrid in face of different generation-consumption scenarios and using different kind of control systems. The proposed tool is a multiple-input multiple-output (MIMO) control plant assembled using building blocks which contain simplified models of photovoltaic (PV) modules, wind turbines (WT), battery arrays (energy storage units, ESU), and different types of DC and AC loads. The variable used as output of these blocks is the power which is the main innovative feature of the simulation. By defining a generation profile, PV and WT are modeled taking into account the environmental conditions and the efficiency of the maximum power point tracking (MPPT) algorithms. ESUs are modeled from the intrinsic characteristics of the batteries considering constant-current-constant-voltage charge and using the standard State of Charge (SoC) approach to compute autonomy. To define a consumption profile, DC loads are modeled as constant resistive (CRL), constant-current (CCL) and constant-power (CPL) loads, whereas the AC loads are modeled by means of their active power. Unidirectional and bidirectional power conversion stages are modeled using an efficiency profile which can be obtained from experiments with the real converters. The control of the microgrid is accomplished through the power extracted or transferred by these converters. In order to validate the accuracy of the simulation platform and its potentiality, a distributed control is proposed to perform the corresponding tests obtaining the presented results. As it is demonstrated, the developed platform is powerful for the study of control techniques and power management strategies for real hybrid microgrids."

# Summary. An optional shortened abstract.
summary: "This paper describes the development of a real-time simulation platform able to analyze the behavior of an AC-DC hybrid microgrid in face of different generation-consumption scenarios and using different kind of control systems. The proposed tool is a multiple-input multiple-output (MIMO) control plant assembled using building blocks which contain simplified models of photovoltaic (PV) modules, wind turbines (WT), battery arrays (energy storage units, ESU), and different types of DC and AC loads. The variable used as output of these blocks is the power which is the main innovative feature of the simulation. By defining a generation profile, PV and WT are modeled taking into account the environmental conditions and the efficiency of the maximum power point tracking (MPPT) algorithms. ESUs are modeled from the intrinsic characteristics of the batteries considering constant-current-constant-voltage charge and using the standard State of Charge (SoC) approach to compute autonomy. To define a consumption profile, DC loads are modeled as constant resistive (CRL), constant-current (CCL) and constant-power (CPL) loads, whereas the AC loads are modeled by means of their active power. Unidirectional and bidirectional power conversion stages are modeled using an efficiency profile which can be obtained from experiments with the real converters. The control of the microgrid is accomplished through the power extracted or transferred by these converters. In order to validate the accuracy of the simulation platform and its potentiality, a distributed control is proposed to perform the corresponding tests obtaining the presented results. As it is demonstrated, the developed platform is powerful for the study of control techniques and power management strategies for real hybrid microgrids."

tags:
- Cascaded multilevel inverter
- Automatic testing
- LabVIEW
- Computational tool
- PSIM
- Simulation
featured: true

# links:
# - name: ""
#   url: "https://link.springer.com/chapter/10.1007/978-3-030-00350-0_42"
url_pdf: https://drive.google.com/file/d/1L8L3vf2xHqFDRCMZ2VAUmkGXVdjTjiQR/view?usp=sharing
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: https://drive.google.com/file/d/1ClClFNgkJtGZZ-zfX2lkQbst4BSYMn-x/view?usp=sharing
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image: 
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

