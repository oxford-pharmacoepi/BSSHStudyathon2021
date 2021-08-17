# BSSHStudyathon2021 8th September 2021, Oxford
*An international study characterising patients undergoing surgery for wrist arthritis and its outcomes*

There are 3 elements to this studyathon:
1. Appraising the literature for what is already known within systematic review (led by researchers from NDORMS and University of Leeds)
2. Assessing the outcomes of proximal row carpectomy - patient reported pain and hand function (led by Xpert clinics and Erasmus MC)
3. Characterising the patients proceeding to intervention for wrist arthritis, and assessing the serious adverse events associated with intervention (led by the OHDSI community)

*All 3 parts aim to contribute equally address the central research question and support each other through heterogeneity*

<img src="https://img.shields.io/badge/Study%20Status-Started-blue.svg" alt="Study Status: Started">

- Analytics use case(s): **Characterization**
- Study type: **Clinical Application**
- Tags: **OHDSI**
- Study lead: **Jenny Lane**
- Study lead forums tag: **jenniferlane** 
- Study start date: **1st July 2021**
- Study end date: **1st October 2021**
- Protocol:
- Publications: ** **
- Results explorer: 

# Cohort Diagnostics
If you are undertaking cohort diagnostics for the first time, you may need set up your environment using the instructions given in the [HADES installation guide](https://ohdsi.github.io/Hades/rSetup.html). To run the study you will need to load the package, enter the RProj, and build it. Once built, you will need to open the extras/CodeToRun.R file and enter your database connection details, where you want to save your results locally, and so on (see instructions in the file). In this same file you can then run the study, view the results locally in a shiny application, and share your results.

## Requirements
Please note prior to running (and as detailed in the file Extas/CodetoRun.R), you may also need to install packages in order for packages to run including: 
```From CRAN:  
- devtools
- dplyr
- ggplot2
- SqlRender
- DatabaseConnector
- parallel
- rJava  
From github:  
- OHDSI/FeatureExtraction@v3.1.0
- OHDSI/Andromeda@v0.4.0
- OHDSI/OhdsiSharing@v0.2.2
- edward-burn/CohortDiagnostics; branch = DiagAi
``` 
*Note, we suggest using the branch of cohort diagnostics from the edward-burn account rather than the OHDSI one so as to ensure consistency in results set (the OHDSI cohort diagnostics package continues to be developed - the version on Ed´s github is just a recent fork from the main OHDSI repo).*   

## Sharing Results
The output is contained in a .ZIP file within the `Output`folder, in the `Export` directory.
We recommend centres review the blinded results in their personal shiny app prior to sharing within OHDSI. We then invite centres to share the results with us via the SFTP server. To share these via the OHDSI SFTP you will need a key file which you will need to be sent separately. To get this please contact jennifer.lane@ndorms.ox.ac.uk.

We look forward to working with you!

