 # *Morganella* spp visualization

**Visualization of the average spectra Matrix-Assisted Laser Desorption Ionization-Time Of Flight Mass Spectrometry (MALDI-TOF MS) of the strains of  <i>Morganella</i> spp. using MALDIquant [1], MALDIrppa [2] and plotly [3] R packages is available [3] R packages is available [here](https://agodmer.github.io/Morganella/Visualisation_Morga_spectra).**

For information concerning this visualization : A. godmer alexandre.godmer@aphp.fr

This work was performed for article (Article in submission) : Evaluation of a Machine Learning approach to distinguished relevant species of *Morganella* spp. by MALDI-TOF mass spectrometry

Mathilde DUQUE1, Cécile EMERAUD<sup>1</sup><sup>,</sup><sup>2</sup><sup>,</sup><sup>3</sup>, Rémy A BONNIN<sup>1</sup><sup>,</sup><sup>2</sup><sup>,</sup><sup>3</sup>, Quentin GIAI-GIANETTO<sup>4</sup><sup>,</sup><sup>5</sup> Laurent DORTET<sup>1</sup><sup>,</sup><sup>2</sup><sup>,</sup><sup>3</sup>, Alexandre GODMER<sup>6</sup><sup>,</sup><sup>7</sup>

<sup>1</sup> Team "Resist" UMR1184 "Immunology of Viral, Auto-Immune, Hematological and Bacterial diseases (IMVA-HB)," INSERM, Université Paris-Saclay, CEA, LabEx LERMIT, Faculty of Medicine, Le Kremlin-Bicêtre, France.

<sup>2</sup> Bacteriology-Hygiene Unit, Bicêtre Hospital, Assistance Publique-Hôpitaux de Paris, Le Kremlin-Bicêtre, France.

<sup>3</sup> Associated French National Reference Center for Antibiotic Resistance: Carbapenemase-Producing Enterobacteriaceae, Le Kremlin-Bicêtre, France.

<sup>4</sup>Institut Pasteur, Université Paris Cité, Bioinformatics and Biostatistics HUB, Paris, France

<sup>5</sup>Institut Pasteur, Université Paris Cité, Proteomics Platform, Mass Spectrometry for Biology Unit, UAR CNRS 2024, Paris, France

<sup>6</sup> INSERM, U1135, Centre d’Immunologie et des Maladies Infectieuses, Sorbonne Université, Cimi-Paris, Paris, France

<sup>7</sup> AP-HP (Assistance Publique Hôpitaux de Paris), Département de Bactériologie, Groupe Hospitalier Universitaire, Sorbonne Université, Hôpital, Saint-Antoine, Paris, France

## Abstract

**Background:** The genus *Morganella*, including clinically isolated species M. sibonii and M. morganii, has a critical yet underexplored role in clinical microbiology. Despite the clinical relevance of *Morganella* spp., current MALDI-TOF MS commercial systems fail to differentiate between its species. Whole genome sequencing (WGS) is the most effective method to distinguish species. However, this method is often impractical for routine lab use due to its complexity.

**Objectives:** This study aims to leverage Machine Learning (ML) techniques with MALDI-TOF MS to enhance the identification accuracy of *Morganella* spp., comparing it with the gold-standard molecular methods.

**Methods:** We applied ML algorithms to a collection of 235 *Morganella* spp. strain to develop an optimized identification model. WGS was used to characterize these strains and perform their phylogenetic analysis.

**Results:** WGS effectively categorized 209 strains as M. morganii and 26 as M. sibonii. The ML-based classifiers showed improved identification accuracy (44 with accuracy at 1), with potential implications for understanding the pathophysiology and epidemiology of Morganella spp.

**Discussion:**  Improving MALDI-TOF mass spectrometry capacity to distinguish *Morganella* species,  could enhance knowledge about the prevalence and implications of *Morganella* spp. in human pathology, paving the way for further research.


### References

[1] Gibb S, Strimmer K. MALDIquant: a versatile R package for the analysis of mass spectrometry data. Bioinformatics. 2012 Sep 1;28(17):2270-1. doi : https://doi.org/10.1093/bioinformatics/bts447 . Epub 2012 Jul 12. PMID: 22796955.

[2] Javier Palarea-Albaladejo, Kevin Mclean, Frank Wright, David G E Smith, MALDIrppa: quality control and robust analysis for mass spectrometry data, Bioinformatics, Volume 34, Issue 3, 01 February 2018, Pages 522 - 523, doi : https://doi.org/10.1093/bioinformatics/btx628

[3] Sievert C (2020). Interactive Web-Based Data Visualization with R, plotly, and shiny. Chapman and Hall/CRC.# MABSc
# Morganella