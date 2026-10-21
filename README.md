
<table align="right" width="500">
  <tr>
    <td>
      <img src="Graphics/Figure 1_REMBI color_update.png" alt="Description" width="500" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <em>Figure 1: The different aspects of Microscopy Metadata.</em>
    </td>
  </tr>
</table>

The **[Light-Microscopy (LiMi) Model](https://quarep.org/working-groups/wg-7-metadata/limi-model/)** of metadata specifications originally arose as a **global community initiative** led by the [4D Nucleome](https://www.4dnucleome.org/) Imaging Working Groug and the [BINA](https://www.bioimagingna.org/qc-dm-wg) Quality Control and Data Management Working Group and is now maintained and revised under the [governance](https://doi.org/10.5281/zenodo.20733501) of [QUAREP-LiMi](https://quarep.org/working-groups/wg-7-metadata/limi-model/).
 
For more information about **LiMi-Model**, please read [Hammer et al., (2021) Nature Methods](https://doi.org/10.1038/s41592-021-01327-9), which was featured on the **Nature Methods FOCUS ISSUE** on [Reporting and reproducibility in microscopy](https://www.nature.com/collections/djiciihhjh). 

> **Learn More!** If you are a newby and you want to learn more about the importannce of metadata and quality control to ensure reproducibility, quality and scientific value in light microscopy, please read [Huisman et al. (2021) ArXiv.org](https://arxiv.org/abs/1910.11370).

> **Development is continuing!** Please contribute to the new V02-10 draft of the model. Click [**here**](Model/in%20progress/v02-10) for a shortcut to the model directory. To create an issue, click on "Issues" above, the "New Issue" button, and select whether you are submitting a proposed new feature/element or want to propose a change to elements of the current version of the model.
ver

# What is the LiMi-Model?

<table align="right" width="450">
  <tr>
    <td>
      <img src="Graphics/4DN-BINA-OME%20CORE%2BCALIBRATION%2BBASIC%2BADV%2BCONF%20EXTENSION_Instrument_v04.png" alt="Description" width="450" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <em>Figure 2: The LiMi-Model Basic extension.</em>
    </td>
  </tr>
</table>

The [Light-Microscopy (LiMi) Model](https://quarep.org/working-groups/wg-7-metadata/limi-model/) (Figure 1) is a tiered system of specifications (Figure 3) that fullfills the requirements delineated in the Image Acquisition component of REMBI and captures: 

1. MICROSCOPE HARDWARE Specifications
2. IMAGE ACQUISITION Settings
3. CALIBRATION AND PERFORMANCE Procedures and metrics

To facilitate future adoption and revision, the LiMi-Model is organized in four components (see Figures 2 and 3):

1. A proposed revision of the [OME data model](https://docs.openmicroscopy.org/ome-model/5.6.1/developers/model-overview.html)
2. A 4DN-BINA-OME Basic extension
3. A 4DN-BINA-OME Advanced + Confocal extension
4. A 4DN-BINA-OME Calibration + Performance  extension

<br clear="right" />

# Tier System Proposal

<table align="right" width="450">
  <tr>
    <td>
      <img src="Graphics/Figure-3_v06_REVISED.png" alt="Description" width="450" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <em>Figure 3: The LiMi-Model tier system.</em>
    </td>
  </tr>
</table>

A significant advance provided by the LiMi-Model is the subdivision of imaging experiments among a set of three Tiers representing increasing imaging and analytical complexity levels. As a consequence, the LiMi-Model not only provides a comprehensive list of metadata fields that should be recorded, but also details which subset of the full list should be recorded depending on the specific Tier the experiment belongs to. 

<br clear="right" />


# Repository content
The LiMi-Model is available for imaging and research scientists and for research software engineers as follows:

1. An Extensible Markup Language (XML) Schema Definition (**[XSD](https://www.w3.org/XML/Schema)**) representation.
2. An **[Entitiy Relationship diagram](https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model)** representation in .graphml, PDF and .png formats.
4. A **Spreadsheet representation** in .xls format.
