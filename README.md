# EMBRACE Checklist: Environmental Machine-learning, Baseline Reporting, And Comprehensive Evaluation 
<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->

## Table of Contents
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#studies-citingusing-the-embrace-checklist">Studies Citing/Using the EMBRACE Checklist</a></li>
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


## Studies Citing/Using the EMBRACE Checklist

The EMBRACE Checklist has been cited or used across a growing range of environmental research applications. Studies with publicly shared completed checklists are highlighted below, with all other citing/using studies available for expansion. Let us know if you used/shared checklist but not in the list below.

| Year | First Author | Study | Source | Checklist |
| --- | --- | --- | --- | --- |
| 2026 | Y Yan | <a href="https://doi.org/10.1021/acs.est.6c07399" target="_blank" rel="noopener noreferrer">Beyond Site-Specificity: Machine Learning Uncovers N2O Emission Patterns across Biological Nitrogen Removal Processes</a> | Environmental Science & Technology | <a href="Studies%20adopted/Yan%20et%20al.%20(2026)_Checklist_Machine%20Learning%20Uncovers%20N2O%20Emission%20Patterns_EST.pdf" target="_blank" rel="noopener noreferrer">Downloading</a> |
| 2026 | S Xu | <a href="https://www.sciencedirect.com/science/article/pii/S0043135426000382" target="_blank" rel="noopener noreferrer">Enhanced modeling of chlorine-organic reaction kinetics to assess the fate of environmental chemicals in disinfection process</a> | Water Research | <a href="Studies%20adopted/Xu%20et%20al.%20(2026)_Checklist_Enhanced%20modeling%20of%20chlorine-organic%20reaction%20kinetics_WR.pdf" target="_blank" rel="noopener noreferrer">Downloading</a> |
| 2026 | HY Cai | <a href="https://www.sciencedirect.com/science/article/pii/S0959652626008206" target="_blank" rel="noopener noreferrer">A mechanistic machine learning framework to decode reverse osmosis membrane retention mechanism for neutral low-molecular-weight organics</a> | Journal of Cleaner Production | <a href="Studies%20adopted/Cai%20et%20al.%20(2026)_Checklist_A%20mechanistic%20machine%20learning%20framework%20to%20decode%20reverse%20osmosis_JCP.pdf" target="_blank" rel="noopener noreferrer">Downloading</a> |
| 2026 | C Xiao | <a href="https://www.sciencedirect.com/science/article/pii/S0043135426004124" target="_blank" rel="noopener noreferrer">Impact of corrosive groundwater on water infrastructure and public health in the contiguous United States</a> | Water Research | <a href="Studies%20adopted/Xiao%20et%20al.%20(2026)_Checklist_Impact%20of%20corrosive%20groundwater%20on%20water%20infrastructure_WR.docx" target="_blank" rel="noopener noreferrer">Downloading</a> |
| 2026 | J Lei | <a href="https://www.sciencedirect.com/science/article/pii/S030147972600575X" target="_blank" rel="noopener noreferrer">Predicting aerobic granular sludge structural instability: An intelligent early-warning framework integrating convolutional neural network and fluorescence fingerprint features</a> | Journal of Environmental Management | <a href="Studies%20adopted/Lei%20et%20al.%20(2026)_Checklist_Predicting%20aerobic%20granular%20sludge%20structural%20instability_JEM.pdf" target="_blank" rel="noopener noreferrer">Downloading</a> |
| 2025 | X Liu | <a href="https://pubs.acs.org/esthag/article/59/38/20499/3812632" target="_blank" rel="noopener noreferrer">Identifying key taxa for algal blooms in a large aquatic ecosystem through machine learning</a> | Environmental Science & Technology | <a href="Studies%20adopted/Liu%20et%20al.%20(2025)_Checklist_Identifying%20Key%20Taxa%20for%20Algal%20Blooms_EST.pdf" target="_blank" rel="noopener noreferrer">Downloading</a> |
| 2025 | Z Liu | <a href="https://www.sciencedirect.com/science/article/pii/S0301479725026246" target="_blank" rel="noopener noreferrer">An artificial intelligence modeling framework based on microbial community structure prediction enhances the pollutant removal efficiency of the algae-bacteria granular sludge system</a> | Journal of Environmental Management | <a href="Studies%20adopted/Liu%20et%20al.%20(2025)_Checklist_An%20artificial%20intelligence%20modeling%20framework%20based%20on%20microbial%20community%20structure_JEM.pdf" target="_blank" rel="noopener noreferrer">Downloading</a> |
| 2025 | N da Luz | <a href="https://doi.org/10.1021/acsestengg.5c00637" target="_blank" rel="noopener noreferrer">Look Out Below: Predicting Wastewater Infrastructure Service Type at the Land Parcel Scale</a> | ACS ES&T Engineering | <a href="Studies%20adopted/da%20Luz%20et%20al.%20(2026)_Checklist_Predicting%20Wastewater%20Infrastructure%20Service%20Type_EST%20Eng.pdf" target="_blank" rel="noopener noreferrer">Downloading</a> |
| 2025 | Y Pei | <a href="https://www.sciencedirect.com/science/article/pii/S2772416625003717" target="_blank" rel="noopener noreferrer">Deep Learning-Based Screening of Zebrafish Embryo Malformations for Assessing the Developmental Toxicity and EC50 Estimation of Disinfection By-Products</a> | Journal of Hazardous Materials Advances | <a href="Studies%20adopted/Pei%20et%20al.%20(2026)_Checklist_Deep%20learning-based%20screening%20of%20zebrafish%20embryo%20malformations_JHMA.docx" target="_blank" rel="noopener noreferrer">Downloading</a> |

<details>
<summary><b>View all 44 studies (35 additional citing/using studies)</b></summary>

<br>

| Year | First Author | Study | Source | Checklist |
| --- | --- | --- | --- | --- |
| 2026 | Y Lai | <a href="https://www.nature.com/articles/s41893-026-01766-2" target="_blank" rel="noopener noreferrer">Intelligent fouling monitoring in membrane-based wastewater treatment</a> | Nature Sustainability | Citing/Using |
| 2026 | Y Cao | <a href="https://www.sciencedirect.com/science/article/pii/S0043135426001065" target="_blank" rel="noopener noreferrer">Data-driven assessment of nitrogen and phosphorus buffering capacity across 460 Chinese watersheds: Spatial patterns, drivers, and future projections</a> | Water Research | Citing/Using |
| 2026 | JM Xu | <a href="https://www.sciencedirect.com/science/article/pii/S0043135426009954" target="_blank" rel="noopener noreferrer">Machine learning-integrated multi-objective application and optimization framework for sulfur-based reactive filler towards nutrient removal</a> | Water Research | Citing/Using |
| 2026 | J Chen | <a href="https://doi.org/10.1021/acsestengg.5c00822" target="_blank" rel="noopener noreferrer">From Meteorological Perturbation Mechanisms to Sewer Methane Forecasting: A Causal and Machine Learning Approach</a> | ACS ES&T Engineering | Citing/Using |
| 2026 | A Arab | <a href="https://www.sciencedirect.com/science/article/pii/S0309170826001016" target="_blank" rel="noopener noreferrer">Physics-informed neural network surrogate for reactive nitrate transport in groundwater</a> | Advances in Water Resources | Citing/Using |
| 2026 | Z Liao | <a href="https://www.sciencedirect.com/science/article/pii/S0043135426003374" target="_blank" rel="noopener noreferrer">Molecular-level insights into oxidant sensitivity of algal extracellular organic matter and disinfection by-product formation during chlorination/ozonation</a> | Water Research | Citing/Using |
| 2026 | H Ran | <a href="https://www.sciencedirect.com/science/article/pii/S1383586626005708" target="_blank" rel="noopener noreferrer">Effects of feature selection on predictive performance and interpretability in data-driven modeling: A case study of membrane flux prediction after Fenton pretreatment</a> | Separation and Purification Technology | Citing/Using |
| 2026 | R Starostka | <a href="https://iwaponline.com/wst/article/doi/10.2166/wst.2026.229/111060" target="_blank" rel="noopener noreferrer">Emerging themes, opportunities, and future directions for modeling decentralized wastewater resource recovery and treatment systems</a> | Water Science and Technology | Citing/Using |
| 2026 | JX Lou | <a href="https://www.nature.com/articles/s41598-026-57033-z" target="_blank" rel="noopener noreferrer">Elucidating response effects of anammox-based nitrogen removal processes for municipal wastewater using big data analysis and automated machine learning</a> | Scientific Reports | Citing/Using |
| 2026 | M Jiang | <a href="https://www.sciencedirect.com/science/article/pii/S0959652626014630" target="_blank" rel="noopener noreferrer">Deciphering the multivariable interactions of MOFs in heavy metal adsorption via explainable machine learning for sustainable and resource-efficient adsorbent development</a> | Journal of Cleaner Production | Citing/Using |
| 2026 | W Chen | <a href="https://www.sciencedirect.com/science/article/pii/S0301479726014970" target="_blank" rel="noopener noreferrer">Toward explainable and generalizable data-driven modeling in real wastewater treatment plants: Utilizing bidimensional interpretable deep learning and cross-scenario transfer learning</a> | Journal of Environmental Management | Citing/Using |
| 2026 | E Akor | <a href="https://pubs.rsc.org/ra/article-abstract/16/14/12475/1231065" target="_blank" rel="noopener noreferrer">Machine learning prediction and calibration of cellulose-based solid-phase extraction performance for pharmaceuticals across aqueous matrices</a> | RSC Advances | Citing/Using |
| 2026 | L Zhang | <a href="https://www.sciencedirect.com/science/article/pii/S016977222600210X" target="_blank" rel="noopener noreferrer">A systematic review of forward simulation-based methods for point-source water pollution localization</a> | Journal of Contaminant Hydrology | Citing/Using |
| 2026 | Y Lu | <a href="https://doi.org/10.1021/acs.est.5c17667" target="_blank" rel="noopener noreferrer">Molecular Representation and Closed-Loop Validation for Toxicity Assessment of Organic Compounds in Ambient Air PM2. 5</a> | Environmental Science & Technology | Citing/Using |
| 2026 | Y Yu | <a href="https://www.biorxiv.org/content/10.64898/2026.01.27.701970.abstract" target="_blank" rel="noopener noreferrer">An enzyme-level benchmark based on environmental bacterial laccases for predicting contaminant fate in water</a> | bioRxiv | Citing/Using |
| 2026 | F Guo | <a href="https://www.mdpi.com/2073-4441/18/7/863" target="_blank" rel="noopener noreferrer">Data-Driven Modeling and Optimization of a Modified Ludzack–Ettinger Process Using ML and DL for Effluent Quality Prediction</a> | Water | Citing/Using |
| 2026 | AB Boehm | <a href="https://doi.org/10.1021/acs.estlett.6c00742" target="_blank" rel="noopener noreferrer">Essential Elements of Manuscripts Describing New Methods for Measuring Environmental Contaminants at Environmental Science & Technology and Environmental Science & Technology Letters</a> | Environmental Science & Technology Letters | Citing/Using |
| 2026 | CC Chang | <a href="https://doi.org/10.1021/acsestwater.6c00535" target="_blank" rel="noopener noreferrer">Stability-Aware Machine Learning Enables Reliable Identification of Water Pollution Drivers for Environmental Decision-Making</a> | ACS ES&T Water | Citing/Using |
| 2025 | C Ma | <a href="https://www.sciencedirect.com/science/article/pii/S0043135425004889" target="_blank" rel="noopener noreferrer">Treatment options of nitrogen heterocyclic compounds in industrial wastewater: From fundamental technologies to energy valorization applications and future process design strategies</a> | Water Research | Citing/Using |
| 2025 | SL Rich | <a href="https://pubs.acs.org/estlcu/article-abstract/12/11/1462/3677894" target="_blank" rel="noopener noreferrer">FAIR and effective communication of data on chemical contaminant biotransformation in the environment</a> | Environmental Science & Technology Letters | Citing/Using |
| 2025 | H Ding | <a href="https://pubs.acs.org/doi/abs/10.1021/acs.est.5c06257" target="_blank" rel="noopener noreferrer">A multi-model ensemble for advanced prediction of reverse osmosis performance in full-scale zero-liquid discharge systems</a> | Environmental Science & Technology | Citing/Using |
| 2025 | F Li | <a href="https://pubs.acs.org/doi/abs/10.1021/acs.est.5c07025" target="_blank" rel="noopener noreferrer">AI-Enhanced SERS with Probe Combinations for Concurrent Identification and Quantification of Coexisting Metal Ions in Water</a> | Environmental Science & Technology | Citing/Using |
| 2025 | Y Cheng | <a href="https://www.sciencedirect.com/science/article/pii/S0043135425018184" target="_blank" rel="noopener noreferrer">Unraveling electronic structure modulation mechanism in cobalt spinel Fenton-like catalysis by integrating density functional theory and machine learning</a> | Water Research | Citing/Using |
| 2025 | H Elnakar | <a href="https://www.sciencedirect.com/science/article/pii/S1944398625006149" target="_blank" rel="noopener noreferrer">Automated machine learning and SHAP-based interpretation of PFOA removal via electrochemical oxidation</a> | Desalination and Water Treatment | Citing/Using |
| 2025 | C Ren | <a href="https://pubs.acs.org/doi/abs/10.1021/acs.est.5c08681" target="_blank" rel="noopener noreferrer">Machine learning-driven inverse design for low-carbon and cost-effective organic acid leaching of spent ternary lithium batteries</a> | Environmental Science & Technology | Citing/Using |
| 2025 | YW Kim | <a href="https://www.sciencedirect.com/science/article/pii/S0043135425009674" target="_blank" rel="noopener noreferrer">A modular deep learning surrogate model for simulating harmful algal blooms in complex process-based systems</a> | Water Research | Citing/Using |
| 2025 | A Elahi | <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12573789/" target="_blank" rel="noopener noreferrer">Machine Learning, Generalization, and Transfer Learning for Predicting the Exceedance of Fecal Indicator Bacteria Thresholds at Beaches</a> | Environmental Science & Technology | Citing/Using |
| 2025 | G Yu | <a href="https://www.sciencedirect.com/science/article/pii/S0956053X25003149" target="_blank" rel="noopener noreferrer">Machine learning predicting sintering temperature for ceramsite production from multiple solid wastes</a> | Waste Management | Citing/Using |
| 2025 | C Schür | <a href="https://doi.org/10.1016/j.comtox.2025.100367" target="_blank" rel="noopener noreferrer">On the comparability between studies in predictive ecotoxicology</a> | Computational Toxicology | Citing/Using |
| 2025 | M Yu | <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12090006/" target="_blank" rel="noopener noreferrer">Ethical frameworks for data-driven environmental health studies in the AI era</a> | Environment & Health | Citing/Using |
| 2025 | X Yang | <a href="https://doi.org/10.15302/J-SSCAE-2025.04.017" target="_blank" rel="noopener noreferrer">Development of microbial technology and industry in environmental engineering</a> | Strategic Study of CAE | Citing/Using |
| 2025 | G Yu | <a href="https://www.tandfonline.com/doi/abs/10.1080/03601234.2025.2489259?casa_token=pcO1Gdzh27QAAAAA:GduV7Z2FvHbWH8VvgXj-y35-wxa2_vnDMD05DhheZwfmwlznMUHOaV-b8nMGL753WL-EPvIwmvGfkw" target="_blank" rel="noopener noreferrer">Development of an interpretable QSAR model for predicting acute oral toxicity of organophosphates in rats based on GA-MLR algorithm</a> | Journal of Environmental Science and Health, Part A | Citing/Using |
| 2025 | ZA Zhang | <a href="https://www.sciencedirect.com/science/article/pii/S0048969725016560" target="_blank" rel="noopener noreferrer">Introduce multivariate two-dimensional information to establish a data-driven volume estimation model for complex microplastic fibers</a> | Science of the Total Environment | Citing/Using |
| 2025 | HL Madsen | <a href="https://scholarspace.manoa.hawaii.edu/items/12ba542f-9658-4b48-8985-8fa8474d1aa1" target="_blank" rel="noopener noreferrer">Monitoring Disinfection in Onsite Wastewater Treatment Systems with a Combination of Online Sensors and Water Sample Analysis for Early Treatment Failure Detection</a> | Master's thesis, University of Hawaiʻi at Mānoa | Citing/Using |
| 2025 | ND Ngo | <a href="https://doi.org/10.2139/ssrn.5966375" target="_blank" rel="noopener noreferrer">Quantitative Reasoning Evaluation of Large Language Model Performance in Indoor Air Quality Engineering</a> | SSRN | Citing/Using |

</details>

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
* **Optional checklist sharing:** Researchers who would like to share a completed EMBRACE Checklist, including for previously published studies, are welcome to contact Dr. Junjie Zhu at Princeton University (junjiez@princeton.edu or ranmuweijie@gmail.com). With your permission, selected checklists may be shared as examples in this repository.
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


