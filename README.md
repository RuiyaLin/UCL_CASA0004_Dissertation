## Overview
All data and code for this project are located in the **code/ directory**.

## Notebooks:

- **key code.ipynb**: Contains the main analysis and algorithms. The visualizations (e.g., charts and maps) in this version may differ from the final report (e.g., in colors, border thickness, etc.).

- **Update code.ipynb**: This is the final and definitive version of the code. It was used for the last update and produces the visualizations as they appear in the final dissertation.

## Data
The data used in this study is stored in the **code/data/ directory**.

Due to the large size of the data files, they have been uploaded to GitHub using Git LFS (Large File Storage).

It is recommended to either:

- 1）Run git lfs pull in your terminal after cloning the repository to fetch the data files, or

- 2）Download the data directly from the Google Drive folder：https://drive.google.com/drive/folders/1GDrZYi0WNYrwtZcTyn39zcut2CvDyWu6?usp=sharing

Path Configuration: Please ensure to update the file paths within the code to match your local directory structure if necessary.

## Pre-computed Results
The **code/results/ directory** contains pre-computed output from the algorithms to save time.

The greedy algorithm has a long runtime (over 30 minutes). Therefore, its results are provided here for convenience.

- **greedy_1_unlimited.csv**: Results where the expansion cap for each hospital was set to equal the total maximum capacity.

- **greedy_2_dp2.csv**: Results where the expansion cap for each hospital was set according to the Second Development Plan.
