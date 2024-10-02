## ENIGMA Hippocampal Subfields Extraction and QC Protocol

![HIPPOCAMPAL SUBFIELDS](https://raw.githubusercontent.com/ENIGMA-git/ENIGMA-Subfields/main/images/Fig1.png "ENIGMA")

The hippocampal formation plays an important role in episodic memory, and is implicated in a variety of neurological and psychiatric disorders. Individual subfields of the hippocampus have been associated with distinct aspects of memory formation; for example, dentate gyrus granule cells and CA3/CA4 pyramidal cells are critical to declarative memory acquisition, whereas the CA1, subiculum and entorhinal cortex are involved in disambiguation during working memory processes. Until recently, delineation of these hippocampal subfields for further analysis depended upon laborious manual segmentation methods. A number of automated segmentation techniques, including the widely-employed FreeSurfer ‘-hippo-subfield’ algorithm, now offer the ability to efficiently detect hippocampal subregions using fully automated, noninvasive in vivo neuroimaging. The FreeSurfer algorithm employs Bayesian inferences from ‘prior’ probabilistic atlases to predict the location of hippocampal subfield voxels and has shown strong correlations with manual delineations. Basic information on the hippocampal subfield and amydala subnuclei tool can be found on the respective FreeWiki page: https://surfer.nmr.mgh.harvard.edu/fswiki/HippocampalSubfieldsAndNucleiOfAmygdala

ENIGMA has examined the test-retest and trans-platform reliability of the most recent FreeSurfer algorithm (version 6.0 and 7.1.1), with an aim to circulate standardized subregion segmentation protocols based on this algorithm. We are currently performing sub-region segmentation across a number of disease working groups, including ENIGMA-Major Depressive Disorder and ENIGMA-Epilepsy.

Protocols and QC Manuals:

- [The original QC script package for the developmental version of FS6.0 version, including its manual (as used for the original project in ENIGMA-MDD)](https://enigma.ini.usc.edu/website_downloads/Subfields/Subfields_QCpackage_original_FS6.0dev.zip)
- [An updated hippocampal subfields QC script package for FreeSurfer v6.0.0](https://enigma.ini.usc.edu/website_downloads/Subfields/Subfields_FS6.0.0.zip)
- [An updated hippocampal subfields QC script package for FreeSurfer v7.1.1](https://enigma.ini.usc.edu/website_downloads/Subfields/Subfields_FS7.1.1.zip)
- [The manual for both versions of the QC script package](https://enigma.ini.usc.edu/website_downloads/Subfields/Instructions_Subfields_FS6.0_or_FS7.1.1_version_1.0.pdf)

A more detailed description of the QC procedure with some background information can be found here: [PG Sämann et al., Human Brain Mapping, 2022](https://onlinelibrary.wiley.com/doi/full/10.1002/hbm.25326).

For further information, please contact Philipp G. Sämann \([saemann@psych.mpg.de](saemann@psych.mpg.de)\) and Eugenio Iglesias \([e.iglesias@ucl.ac.uk](mailto:e.iglesias@ucl.ac.uk)\).
