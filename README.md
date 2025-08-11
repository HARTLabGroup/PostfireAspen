# *Code for:* Limited conifer regeneration, but widespread regeneration of aspen seedlings following the Cameron Peak Fire, northwestern Colorado

## Description of the project

This repository contains all code for Limited conifer regeneration, but widespread regeneration of aspen seedlings following the Cameron Peak Fire, northwestern Colorado.

## Organization of the project

The project has the following structure:

-   *.gitignore*

-   *CITATION.cff*

-   citationstyle.csl : A [Citation Style Language](https://citationstyles.org/) file used to format references in the main text file.

-   Code: This subdirectory contains all code written for this project. In order for the code to work, the associated data (forthcoming on Dryad - <https://doi.org/10.5061/dryad.x3ffbg7zx>) should be stored in a subdirectory called `Data/Dryad`. The files should be run sequentially (i.e., *01-SpatialData.Rmd* then *02-SiteSelection ... 04-PostfireAspenRegen-MainText.Rmd).* For all R markdown files (.Rmd), the knit version is also included as a Microsoft Word document.

    -   *01-SpatialData.Rmd* : This code will download most of the data.

    -   *02-SiteSelection.Rmd*: This code was used to identify areas for randomly locating sample sites

    -   *03-StudyArea.Rmd*: This code was used to characterize the study area from existing geospatial data products.

    -   *04-IostfireAspenRegen-MainText.Rmd*: The code for reproducing the main text and results presented therein.

    -   *references.bib*: A BibTeX file containing all information for all references used in the project

    -   *Template.docx*: A Microsoft Word document used to a style template for generating the main text file.

-   Results: This subdirectory contains results generated for use in the main text or supplement.

    -   Figures: This subdirectory contains any figures generated for use in the main text or supplement.

-   *License.md*

-   *README.md*

-   *PostFireAspen.Rproj*

## License

This project is licensed under the Creative Commons Attribution 4.0 International - see the LICENSE.md file for details

## Citation

Please cite this work following the Citation.cff file
