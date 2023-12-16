This page was developed as the final project of [Dr. Emorie Beck](https://psychology.ucdavis.edu/people/edbeck)'s course [Data Cleaning and Management](https://emoriebeck.github.io/psc290-data-FQ23/), taught at University of California, Davis in the Fall quarter of 2023.

## Background

This project aims to create a comprehensive pipeline for validating the Sleep Acceptance Scale (SAS), an instrument designed to evaluate people's acceptance of sleep problems. The data for this project come from adults between 18 and 59 living in Brazil who were surveyed online using REDCap.

Here I do not discuss in depth the results of the analyses as it is expected to be developed in a future publication in a scientific journal. What will be show in this project are the analyses' code and outputs that usually do not fit into a traditional scientific publication. 


## Motivation

There are two main goals that I wish to achieve with this project. First, it is to make the data analysis phase of this research project transparent and accessible to the reader. Further, it is aimed to be a "living" document, where the readers can make suggestions or critics  to improve the quality of the work. I also hope that by sharing the code and outputs in an online book format, researchers with limited or no knowledge of R programming can 

Although this document was designed to be accessed independently of the formal journal publication, it can also serve as supplementary material to the manuscript. To create a fully reproducible manuscript would be challenging because the co-authors of this research project do not work with R. With this document at least the data analysis can be shared in a reproducible format.

## Approach

Thanks to a suggestion from Dr. Emorie, this project was redesigned to the format of a HTML [Quarto book](https://quarto.org/docs/books/). This format allows to easily combine multiple `.qmd` documents into a single manuscript. Each "chapter" in this book correspond to a different step of the analysis. In this way, the scripts can be executed independently or bundled in a single file.

To create this product first I created a new project in RStudio using the Quarto book template. Then different `.qmd` files were created for each step of the analysis and saved in the general folder of the project. Additionally, a sub folder for the data was created, containing the raw data, the cleaned data from step 1, and intermediate outputs saved to optimize the rendering of the document.

The project was also made as a [Github repository](https://github.com/marwincarmo/sas), available publicly. Once finished, the book was hosted as a website on Github Pages, available at <https://marwincarmo.github.io/sas/>
