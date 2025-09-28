# EMBRACE Checklist: Environmental Machine-learning, Baseline Reporting, And Comprehensive Evaluation 
<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->

## Table of Contents
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#workflow">Workflow</a></li>
      </ul>
    </li>
    <li>
      <a href="#usage">Usage</a>
      <ul>
        <li><a href="#format-and-types">Format and Types</a></li>
        <li><a href="#document-save">Document Save</a></li>
      </ul>
    </li>
    <li><a href="#interactions-and-contributing">Interactions and Contributing</a></li>
    <li><a href="#exhibition-and-Examples">Exhibition and Examples</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>



<!-- ABOUT THE PROJECT -->
## About The Project

To help researchers, readers, reviewers, and editors better communicate envrionmental ML research work, we developed the [EMBRACE Checklist](https://github.com/starfriend10/EMBRACE/blob/main/Checklist%20and%20Instructions/EMBRACE%20Checklist%20version%201.0.pdf) that aims to enhance understanding of the feasibility of proposed projects, the completeness of ongoing research, and the robustness of finished work. Before adopting the checklist, it is encouraged to consult previously published review work and viewpoint for specific terminologies and concepts.

> [!NOTE]
> * A comprehensive review study was conducted to investigate common pitfalls and best ML practices in Environmental Science and Engineering (ESE) areas, please check: Zhu, J.-J., Yang, M., & Ren, Z. J. (2023). Machine learning in environmental research: common pitfalls and best practices. *Environmental Science & Technology*, 57(46), 17671-17689. [https://doi.org/10.1021/acs.est.3c00026](https://doi.org/10.1021/acs.est.3c00026)
> * A viewpoint summarizes the general usage of this checklist and advocates to better faciliate an engaged learning community in ESE, please check: Zhu, J.-J., Boehm, A. B., & Ren, Z. J. (2024). Environmental Machine-learning, Baseline Reporting, And Comprehensive Evaluation: The EMBRACE Checklist. *Environmental Science & Technology*, 58(45), 19909–19912. [https://doi.org/10.1021/acs.est.4c09611](https://doi.org/10.1021/acs.est.4c09611).
<br>
<img src="https://github.com/starfriend10/EMBRACE/blob/main/Figures/Community-benefits.png" width="600">

### Community-Owned Tool
The objective of introducing this [Checklist](https://github.com/starfriend10/EMBRACE/blob/main/Checklist%20and%20Instructions/EMBRACE%20Checklist%20version%201.0.pdf) is to develop a ease-to-use tool to provide essential and important data reporting along your environmental ML work. It only costs you 5-10 minutes to complete the 3-page checklist. The ultimate goal is to foster an active learning community and promote self-beneficial practices in environmental ML research. We encourage interested researchers to join and contribute this effort, potentially establishing standards that benefit the broader community.
- [x] For <b>Researchers</b>: The Checklist helps guidance on essential steps and requirements to develop ML models for environmental research. Clear data reporting streamlines the publication process and enhances the impact of the research work.
- [x] For <b>Readers</b>: The Checklist (shared by researchers) contains key information of the research work, making it easier to follow, understand, and utilize the data, methodology, and findings of the research.
- [x] For <b>Reviewers</b>: The Checklist (along with manuscript) provides clear information which minimizes potential confusion during the review process, allowing reviewers to better understand the study’s novelty and contributions.
- [x] For <b>Editors</b>: The Checklist (submitted by researchers along with their manuscripts) helps editors screen the work based on the scope and quality.
<br>

![CL_SS](https://github.com/starfriend10/BestML/blob/main/Figures/EMBRACE%20Checklist%20Snapshot.jpg)


## Getting Started

The checklist includes "project overview" and eight sections that follow a typical flowchart of ML model development:
* Project overview helps to record the general information of your ongoing or finished study. You can also use it to track potential problems during your research.
* Section 1 includes reporting study objectives and feasibility assessment, aiding researchers in evaluating their available resources more effectively.
* Section 2 covers reporting on data sources, including types, ethics, as well as details regarding the number and quality of data points.
* Section 3 outlines reporting on data cleaning, enrichment, feature engineering, data splitting, and final data descriptions.
* Section 4 focuses on reporting the supervised learning methods chosen and the overall modeling framework.
* Section 5 highlights key aspects of model evaluation and hyperparameter optimization (HPO).
* Section 6 emphasizes the need for a deeper understanding and reporting of model interpretability, explainability, and causality.
* Section 7 focuses verifying data leakage management.
* Section 8 encourages the sharing of data and code when possible.
<img src="https://github.com/starfriend10/EMBRACE/blob/main/Figures/EMBRACE%20Checklist%20Main%20Structure.png" width="800">

### Prerequisites

> [!TIP]
> We strongly recommend to read the [review work](https://doi.org/10.1021/acs.est.3c00026) and [viewpoint](https://doi.org/10.1021/acs.est.4c09611) before using the checklist. When using the checklist, you can refer to the [Instructions](https://github.com/starfriend10/EMBRACE/blob/main/Checklist%20and%20Instructions/Checklist%20instructions%20(10-2024).pdf) for additional information.


### Workflow

The checklist can be used at any stage of life cycle of your research, including project initialization, ongoing work, finished study, and educational learning.

<img src="https://github.com/starfriend10/BestML/blob/main/Figures/EMBRACE%20Checklist_workflow.png" width="800">


## Usage

> [!IMPORTANT]
> The checklist is designed to easy check and fill. You may consult [Instructions](https://github.com/starfriend10/EMBRACE/blob/main/Checklist%20and%20Instructions/Checklist%20instructions%20(10-2024).pdf) for detailed explanations. 

### Format and Types

<img src="https://github.com/starfriend10/BestML/blob/main/Figures/Info%20Format%20and%20Type.png" width="600">

### Document Save

We encourage you to share your checklist directly, so lengthy sentences or contents in a short cell can be read via reader interaction. However, you can also follow the instructions below if you prefer to save the checklist as a read-only document. 
* When using Microsoft Windows, please follow these step: “File” >> “Print” >> Select “Microsoft print to PDF” in “Printer” >> Print >> Save it as a new PDF document.
![CL_SS](https://github.com/starfriend10/BestML/blob/main/Figures/MSWIN%20SAVE.jpg)

* When using macOS, please follow these step:
![CL_SS](https://github.com/starfriend10/BestML/blob/main/Figures/MACOS%20SAVE.jpg)
Or check [this webpage](https://faq.maplesoft.com/s/article/Why-can-I-not-Print-to-PDF-on-my-Mac?language=en_US) for the same direction.


* For examples of common problems and less robust applications, please refer to the [Instructions](https://github.com/starfriend10/EMBRACE/blob/main/Checklist%20and%20Instructions/Checklist%20instructions%20(10-2024).pdf).
* For shared checklists from fellow researchers, please check the following Exhibition table.



## Interactions and Contributing

* If you find this checklist useful, please help to spread it to build an engaging community for environmental ML research. If the checklist helps your ML research, we appreciate your credit to our work. Please cite the viewpoint.
* The best approach to share your checklist is to use it as supporting information when submitting your manuscript, so researchers (yourself), editors, reviewers, and readers can all benefit from the transparent and complete data reporting.
* If you'd like to share your checklist data alone without used as supporting information or because of other situations (e.g., old studies/papers), we are also happy to share them. Please send your checklist to Dr. Junjie Zhu at Princeton University (junjiez@princeton.edu or ranmuweijie@gmail.com) via email. Please name your checklist document "Finished_date EMBRACE Checklist version_number for Your_research" (e.g., "20240901 EMBRACE Checklist 1.0 for Zhu et al. (2023)") and send an email entitled "Sharing EMBRACE Checklist from Your_name" (e.g., "Sharing EMBRACE Checklist from Junjie Zhu"). To better classify the shared checklists, please also provide your research application domain (e.g., Water Quality and Treatment) in your email and your contact email (if other than your sending email address). We will do a quick data completeness inspection and share it ASAP. It is worth noting that sharing your checklist is completely volunteer per your agreement on releasing your research information once you send your document to us. Therefore, we and other fellow researchers appreciate your sharing. If you shared your checklist and would like to update the existing document, please identify the document and explain the reason. We will revise it accordingly.
* Sharing your checklist may enhance the impact of your research by increasing visibility among colleagues. Therefore, it is important to ensure the accuracy of reported data, which is a self-responsible QA/QC. From the prespective of other fellow researchers, the accuracy of the checklist information relies solely on the reporting researcher. While we encourage researchers to share their checklists, it is crucial to ensure responsible data reporting.
* If you find other important items need to be added or there are any places need to be corrected, particularly if they are common and representative in ESE areas, please feel free to let us know. One strightforward way is to send an email to Dr. Junjie Zhu with your thoughts and supporting materials. Alternatively, you can post issues with clear descriptions. It is likely that your suggestion will be accepted for future development of the checklist.



## Exhibition and Examples

| Sharing Date | Application Domain | Checklist Sharing | Paper Link | Publication Date | Author Name | Author Contact | Additional Info. |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 09/05/2024 | Resource Recovery | [PURL](https://github.com/starfriend10/EMBRACE/blob/main/Research%20Sharing/20240905%20EMBRACE%20Checklist_Yang%20et%20al.%20(2024).pdf) | [DOI](https://doi.org/10.1021/acs.est.4c00060) | 05/13/2024 | Meiqi Yang | [Email](mailto:meiqiy@princeton.edu) | Material discovery with DLM |
| 09/05/2024 | Resource Recovery | [PURL](https://github.com/starfriend10/EMBRACE/blob/main/Research%20Sharing/20240905%20EMBRACE%20Checklist_Yang%20et%20al.%20(2023).pdf) | [DOI](https://doi.org/10.1021/acs.est.2c06382) | 03/27/2023 | Meiqi Yang; Junjie Zhu | [Email](mailto:meiqiy@princeton.edu) | Separation predictions with rigorous data leakage management |
| 09/04/2024 | Hydrology and Water Quantity | [PURL](https://github.com/starfriend10/EMBRACE/blob/main/Research%20Sharing/20240904%20EMBRACE%20Checklist_Zhu%20et%20al.%20(2022b).pdf) | [DOI](https://doi.org/10.1016/j.watres.2022.118714) | 07/15/2022 | Junjie Zhu | [Email](mailto:junjiez@princeton.edu) | Probabilistic predictions with 95% PI |
| 09/04/2024 | Water Quality and Treatment | [PURL](https://github.com/starfriend10/EMBRACE/blob/main/Research%20Sharing/20240904%20EMBRACE%20Checklist_Zhu%20et%20al.%20(2022a).pdf) | [DOI](https://doi.org/10.1021/acsestengg.1c00469) | 06/15/2022 | Junjie Zhu | [Email](mailto:junjiez@princeton.edu) | Metaheuristic-optimized deep learning |
| 09/04/2024 | Water Quality and Treatment | [PURL](https://github.com/starfriend10/EMBRACE/blob/main/Research%20Sharing/20240904%20EMBRACE%20Checklist_Zhu%20et%20al.%20(2018).pdf) | [DOI](https://doi.org/10.1016/j.watres.2017.10.053) | 01/01/2018 | Junjie Zhu | [Email](mailto:junjiez@princeton.edu) | Multi-objective optimized data-driven |



## License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg



## Contact

**Junjie Zhu** - [@Jun_Jie_Zhu](https://twitter.com/Jun_Jie_Zhu) - junjiez@princeton.edu or ranmuweijie@gmail.com

Project Link: [https://github.com/starfriend10/EMBRACE](https://github.com/starfriend10/EMBRACE)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Acknowledgments
**Zhiyong Jason Ren**. Professor, CEE department, Princeton University. ***Project initialization main contributor***

**Alexandria B. Boehm**. Professor, CEE department, Stanford University. ***Project initialization main contributor***

[**Meiqi Yang**](https://github.com/meiqiyang53). Ph.D. Candidate, CEE department, Princeton University. ***Checklist in-house testing and verification***

**Zhonghua Zheng**. Assistant Professor, EES department, The University of Manchester. ***Checklist in-house testing***

[**Sina Borzooei**](https://github.com/SinaBorzooeiIVL). IVL Swedish Environmental Research Institute. ***Checklist in-house testing***



