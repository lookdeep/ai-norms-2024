---
layout: single
title:  "Continuous Patient Monitoring with AI: Real-Time Analysis of Video in Hospital Care Settings"
toc: true
toc_label: "Navigation"
toc_icon: "bars"
toc_sticky: true
header:
    overlay_image: assets/images/overview.png
    overlay_filter: 0.85
    caption: "LookDeep Health System Overview. From Figure 1 of article."
    actions:
        - label: "Explore Plots <i class='fa fa-external-link'></i>"
          url: "https://lookdeep.vercel.app/"
        - label: "Read Paper <i class='fa fa-external-link'></i>"
          url: "https://www.frontiersin.org/journals/imaging/articles/10.3389/fimag.2025.1547166/abstract"
        - label: "Run Code <i class='fa fa-external-link'></i>"
          url: "https://colab.research.google.com/drive/1v0Egoyt5pBmTmb9iEV8RZFSzhym5XpU4?usp=sharing"
        - label: "Download Dataset - CSV file (3.88 MB) <i class='fa fa-external-link'></i>"
          url: "https://raw.githubusercontent.com/lookdeep/ai-norms-2024/refs/heads/main/data/data_by_patient_hour_scrubbed.csv"

---
**Authors**: Paolo Gutierrez Gabriel (corresponding), Peter Rehani, Tyler Troy, Tiffany Wyatt, Michael Choma and Narinder Singh

> _The manuscript was accepted by 'Frontiers in Imaging - Imaging Applications' on February 18, 2025._

# Welcome! 
![Figure 1 of manuscript](assets/images/overview.png "LookDeep Health System")
_Figure 1 of manuscript_

You are likely here because you read the titled manuscript and are looking for the public data and associated code that was mentioned. 

Thank you for your interest in analyzing these anonymized computer vision predictions, aggregated at the patient-day-hour level. 
We invite you to explore the trends reported in the manuscript (and more), and provide the materials below as support.

# Dataset
This project page is about a new, fully anonymized dataset (unnamed).
This data consists of computer vision predictions recorded from hundreds of patients over a 6-month period, aggregated at the patient-day-hour level. 

![Example trend](assets/images/trends_plot.png "Percent Time Alone")

_Example trend plot, rendered in [Vercel App](https://lookdeep.vercel.app/)_

These trends provide hour-over-hour insight into various patient behaviors and room conditions, including but not limited to:
```
**Metadata:**
- model_name
- day_loc
- hour_loc
- monitor_id
- division_name
- group_ADC
- gender
- group_age
- ts

**Data:**
- num_samples
- percent_alone
- count_fence_crossed
- percent_fence_crossed
- percent_bed_active
- percent_scene_active
- count_alone_active
- percent_alone_active
- count_alone_fence_crossed
- percent_alone_fence_crossed
- percent_staff
- percent_supervized
- percent_supervized_staff
- percent_supervized_other
- percent_supervized_staff_fence_crossed

```

*Details*:
- computer vision predictions come from Models v4 and v5 -> see manuscript for evaluation

# Resources
_Links open in a new window._
* [accepted manuscript](https://www.frontiersin.org/journals/imaging/articles/10.3389/fimag.2025.1547166/abstract)
* [arXiv pre-print](https://arxiv.org/abs/2412.13152) 
* [colab notebook](https://colab.research.google.com/drive/1v0Egoyt5pBmTmb9iEV8RZFSzhym5XpU4?usp=sharing)
* [company website](https://lookdeep.health/technology/)
* [download data](https://raw.githubusercontent.com/lookdeep/ai-norms-2024/refs/heads/main/data/data_by_patient_hour_scrubbed.csv) - `data/data_by_patient_hour_scrubbed.csv`
* [github repository](https://github.com/lookdeep/ai-norms-2024) - use `main` branch

# Citation
If you would like to reference this work, please use:
```
@article{gabriel2025continuouspatientmonitoringai,
   author={Paolo Gabriel, Peter Rehani, Tyler Troy, Tiffany Wyatt, Michael Choma and Narinder Singh},
   title={Continuous Patient Monitoring with AI: Real-Time Analysis of Video in Hospital Care Settings},
   journal={Frontiers in Imaging},
   volume={4},
   year={2025},
   url={https://www.frontiersin.org/journals/imaging/articles/10.3389/fimag.2025.1547166},
   DOI={10.3389/fimag.2025.1547166},
}
```

# Change Log
 * 2025-02-28
    - connect Colab notebook
    - update links and references to manuscript
 * 2025-02-18
    - manuscript was accepted!
 * 2025-01-17
    - update project image
    - manuscript is under review! 
 * 2025-01-06
    - link to pre-print in header(s)
    - alphabetize "Resources"
 * 2024-12-31
    - update layout for accessibility
 * 2024-12-30 
    - update dataset description to include `division_name`
    - add "interactive demo" link to resources and banner
 * 2024-12-18 
    - update project page with dataset
 * 2024-12-17 
    - initialize project page and link to pre-print