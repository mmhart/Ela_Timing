Inoculation timing and isolate identity in arbuscular mycorrhizal fungi
Overview
This repository contains data and annotated analysis/figure-generation scripts associated with the study “Intraspecific variation outweighs inoculation timing in determining arbuscular mycorrhizal inoculant success” by Kuselah Tayaban and Miranda M. Hart (University of British Columbia Okanagan).

The study examines how inoculation timing and isolate identity affect establishment of introduced arbuscular mycorrhizal fungi (AMF), plant responses, and the resident AMF community. Three isolates of Rhizophagus irregularis (CC4, Cuba8, and DAOM197198) were compared under three inoculation strategies: inoculation before exposure to soil containing resident AMF (pre-soil), at exposure to resident soil (soil inoculation), or at both stages (repeated inoculation). Uninoculated controls were also included.

In a greenhouse experiment with Plantago lanceolata, inoculant detection and abundance were assessed using isolate-specific digital droplet PCR (ddPCR); plant growth and phosphorus responses were measured; and resident AMF communities were characterized with 18S rRNA gene amplicon sequencing. Samples were collected at two post-soil-exposure harvests for inoculant and plant measurements, and resident community composition was assessed at the later harvest.
Repository contents
Data
File	Description
Expt01_ddpcr_data.xlsx	ddPCR dataset used for analyses of introduced AMF detection and abundance in roots and soil.
Expt01_physio_data.csv	Plant physiological/response data for the experiment.
Expt01_qiime_metadata.csv	Sample metadata associated with community sequencing/QIIME analyses.
Timing_long1.csv	Long-format experimental data used in timing/isolate analyses and visualizations.


The descriptions above indicate the apparent role of each dataset based on its name and the associated manuscript; consult the files for exact columns, units, and coding.
Annotated scripts
The Annotated scripts/ directory contains Word documents with annotated analysis or plotting workflows:
File	Analysis or figure
Alpha_div_stats_plot.docx	Resident AMF alpha-diversity statistics and plots.
Mycorrhizal response_Plot_Stat...	Mycorrhizal/plant response plots and statistics (full filename as uploaded).
PCoA and SIMPER.docx	Community ordination (PCoA) and SIMPER analysis.
Permanova_Permadisp.docx	PERMANOVA and multivariate dispersion tests.
Plot Binomial Root and Soil.docx	Plots of inoculant detection/presence–absence in roots and soil.
Plot_GpGLM_Root_Soil.docx	Plots of root and soil inoculant abundance models.
Plots_soilchem_plantresponse.d...	Soil chemistry and plant-response plots (full filename as uploaded).
Rare_taxa_glm_figs.docx	Rare-taxon models and figures.
SoilP_soilpH_stats_figure.docx	Soil phosphorus and pH statistics and figures.
Stats Binomial Root and Soil.docx	Binomial models of inoculant detection in roots and soil.
Stats_CPGLM_Roots_Soil.docx	Abundance-model analyses for roots and soil.


These are annotated .docx documents, not executable .R files. Open them to inspect or extract the R code and explanatory notes. Two filenames above are abbreviated because only truncated names were visible in the supplied file listing.
Experimental design and treatment labels
- AMF isolates: CC4, Cuba8, DAOM197198 (all Rhizophagus irregularis).
- Inoculation strategies: pre-soil, soil inoculation, repeated inoculation; uninoculated control.
- Host: Plantago lanceolata.
- Experimental system: greenhouse pots containing a trap-culture-propagated AMF community originally derived from orchard soil.
- Measurements: isolate-specific ddPCR in roots and soil, plant biomass and phosphorus responses, soil chemistry, and resident AMF community sequencing.
Treatment labels may differ across individual source files or older scripts. Confirm levels and contrasts within each dataset and annotated workflow before running analyses.
Reproducibility
1. Download the data files and the Annotated scripts/ directory.
2. Open the relevant .docx file and inspect the documented R commands, required packages, input filenames, and working-directory paths.
3. Install the R dependencies identified in that document and update file paths to match your local copy.
4. Run the code, checking that treatment labels, units, and sample identifiers match the data files.
The manuscript reports analyses carried out in R 4.4.2, including generalized linear models, ddPCR presence/abundance analyses, and community analyses using vegan. This repository listing alone does not establish a complete computational environment or guarantee that each script will run without local path or package adjustments.
Sequence data
The manuscript identifies the associated raw sequence archive as NCBI BioProject PRJNA1464753. See the publication for molecular methods, primer details, and bioinformatic procedures.
Data availability and citation
For the study design, statistical methods, and interpretation, cite the associated manuscript (full publication details to be added upon acceptance/publication). If this repository is archived in Zenodo, cite the DOI displayed on the published Zenodo record containing these files; verify the archive and its contents before adding a DOI here.
Authors
- Kuselah Tayaban
- Miranda M. Hart (corresponding author), Department of Biology, University of British Columbia Okanagan, Kelowna, British Columbia, Canada — Miranda.hart@ubc.ca
License
See the repository's LICENSE file for the applicable terms. Confirm whether the license covers both code and data before reuse or redistribution.
