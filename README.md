This repository provides datasets, code, and resources to reproduce the experimental results described in the associated paper and its supplementary materials. The repository is structured into several directories, each serving a specific purpose. Users are encouraged to follow the instructions below to ensure accurate reproduction of the analyses.

data Directory:
This directory contains the training histories derived from four distinct datasets and their corresponding models. To reproduce the results presented in the paper (including those in the supplementary materials), download the required files and place them in the appropriate directories as specified in the code configurations. This setup will enable you to generate the related outcomes, such as performance metrics and visualizations.

tSNE Directory:
This directory includes the source code necessary to reproduce the results detailed in Section 2.3 of the supplementary materials. Execute the provided scripts to regenerate the t-SNE analyses and associated figures.

src Directory:
This directory houses the core implementation for generating idealized training loss curves. To utilize these scripts:

1. Input the training histories from the data directory.
2. Run the code to produce the idealized training loss data.
3. Apply the generated data for subsequent analyses, including ORI trends, ORI-AUC scores, and Q-Q plot evaluations.

Special Notes:
To ensure successful execution of the code, users may need to adjust file paths in the event of errors (e.g., due to differences in local directory structures). We recommend verifying all paths relative to your working environment prior to running the scripts.

Thank you for your interest in this repository. For any questions or issues, please refer to the paper or contact the corresponding authors.
