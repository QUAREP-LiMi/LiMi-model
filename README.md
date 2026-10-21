<img align="right" src="https://github.com/WU-BIMAC/MicroMetaApp.github.io/blob/master/images/Nature%20Methods_COVER.png">

The **[Light-Microscopy (LiMi) Model](https://quarep.org/working-groups/wg-7-metadata/limi-model/)** of metadata specifications originally arose as a **global community initiative** led by the [4D Nucleome](https://www.4dnucleome.org/) Imaging Working Groug and the [BINA](https://www.bioimagingna.org/qc-dm-wg) Quality Control and Data Management Working Group and is now maintained and revised under the [governance](https://doi.org/10.5281/zenodo.20733501) of [QUAREP-LiMi](https://quarep.org/working-groups/wg-7-metadata/limi-model/).
 
For more information about **LiMi-Model**, please read [Hammer et al., (2021) Nature Methods](https://doi.org/10.1038/s41592-021-01327-9), which was featured on the **Nature Methods FOCUS ISSUE** on [Reporting and reproducibility in microscopy](https://www.nature.com/collections/djiciihhjh). 

> **Learn More!** If you are a newby and you want to learn more about the importannce of metadata and quality control to ensure reproducibility, quality and scientific value in light microscopy, please read [Huisman et al. (2021) ArXiv.org](https://arxiv.org/abs/1910.11370).

> **Development is continuing!** Please contribute to the new V02-10 draft of the model. Click [**here**](Model/in%20progress/v02-10) for a shortcut to the model directory. To create an issue, click on "Issues" above, the "New Issue" button, and select whether you are submitting a proposed new feature/element or want to propose a change to elements of the current version of the model.
ver

# What is the LiMi-Model?

The [Light-Microscopy (LiMi) Model](https://quarep.org/working-groups/wg-7-metadata/limi-model/) (Figure 1) is a tiered system of specifications (Figure 3) that fullfills the requirements delineated in the Image Acquisition component of REMBI and captures: 

1. MICROSCOPE HARDWARE Specifications
2. IMAGE ACQUISITION Settings
3. CALIBRATION AND PERFORMANCE Procedures and metrics

<p align="center">
  <img src="https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/blob/master/Graphics/Figure-1_v03_MM+model elements.png" title="Figure 1: Image Metadata versus Microscopy Metadata">
</p>

**Figure 1: Imaging Experiment Workflows and Microscopy Metadata**

# Proposed Suite of 4DN-BINA Extensions of the OME Data-Model
To facilitate future adaptation and expansion of the guidelines, the proposed 4DN-BINA-OME model is organized on the basis of the core vs. extension ontology concepts. As such the model consists of the following four components (see Figures 2 and 3):

1. A proposed revision of the OME Core Model
2. A 4DN-BINA-OME Basic extension
3. A 4DN-BINA-OME Advanced + Confocal extension
4. A 4DN-BINA-OME Calibration extension

<p align="center">
  <img src="https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/blob/master/Graphics/4DN-BINA-OME%20CORE%2BCALIBRATION%2BBASIC%2BADV%2BCONF%20EXTENSION_Instrument_v04.png" title="Figure 2A: OME Image Core ontology vs. 4DN-BINA-OME Extensions">
</p>

<p align="center">
  <img src="https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/blob/master/Graphics/4DN-BINA-OME%20CORE%2BCALIBRATION%2BBASIC%2BADV%2BCONF%20EXTENSION_Image_v05.png" title="Figure 2B: OME Image Core ontology vs. 4DN-BINA-OME Extensions">
</p>

**Figure 2: OME Image Core ontology vs. 4DN-BINA-OME Extensions**

In addition to extending the [OME data model](https://docs.openmicroscopy.org/ome-model/5.6.1/developers/model-overview.html) and maintaining full-compatibility with it, the main advance provided by the 4DN-BINA-OME guidelines is to posit the subdivision of imaging experiments among a set of five Tiers representing increasing imaging and analytical complexity levels. As a consequence, these guidelines not only provide an OME-based comprehensive list of metadata key-value pairs that should be recorded, but also details which subset of the full list should be recorded depending on the specific Tier the experiment belongs to. In so doing the guidelines lie the foundation for the birth of a microscopy data standard that could serve the same purpose the Encode guidelines serve in the genomic community.

In order to foster the wide usability of the guidelines, the proposal aim at providing detailed explanations of why these values matter. Finally, in order to aide their adoption by software developers, the guidelines are expressed in the Extensible Markup Language (XML) Schema Definition ([XSD](https://www.w3.org/XML/Schema)) format that can be utilized to generate code for both traditional databases and other software utilizing the data model.

# Tier System Proposal

<p align="center">
  <img src="https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/blob/master/Graphics/Figure-3_v06_REVISED.png" title="Figure 3: Tier System">
</p>

**Figure 3: Tier System**

# Repository content and documentation
The proposed Microscopy Metadata guidelines are available as follows:

1. An .xsd file providing the XML-schema for the proposed OME extension.
2. A .graphml providing an rendering of the INSTRUMENT Specifications and IMAGE ACQUISITION Settings sections of the model using the Entity-Relationship (ER) formalism. In order to open the file you can use the [yED application](https://www.yworks.com/products/yed).
3. A PDF version of the same ER schema.
4. A .xsl worksheet providing a comprehensive list of metadata key-value pairs that should be recorded for each tier, which can be found [here -->](https://docs.google.com/spreadsheets/d/16IQl-K8UIStsdlkNzJTA7LzMCan9qyS3KKcmEJ5wu28/edit?usp=sharing)
