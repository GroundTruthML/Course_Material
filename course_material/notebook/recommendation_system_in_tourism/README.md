# Tourism Recommendation System — Notebook and Data Guide

The public notebook folder contains three learning notebooks:

- 01_Data_Playground.ipynb
- 02A_Cosine_Similarity.ipynb
- 02B_Collaborative_Filtering_Audited.ipynb

These files are useful for reading and reviewing the analysis. They are **not currently a one-click Colab path**: the notebooks expect source and prepared data files that are not included in this repository, and the setup has not been validated in hosted Colab.

## Required data

The analysis uses the INCULTUM tourism and review data. Obtain it from the official Zenodo record: https://zenodo.org/records/10934854 . Review its CC BY-SA 4.0 license and attribution requirements before reuse.

The notebooks expect the original CSV files in a folder named assets/raw_incultum and prepared files under assets/baseline_data. In particular, the recommendation notebooks use items.csv, categories.npy, users.npy and events.npy; Notebook 01 also reads the raw source files and the country GeoJSON. Follow each notebook's data-loading cells and experiment-specific rules. Ratings recorded as zero mean missing or invalid; they are not dislikes.

The prepared arrays used in the project were produced by case-specific preparation steps and are not distributed here. Results from different experiments use different populations and rules; do not compare their scores as if they were one experiment. The notebooks do not establish that a traveller saw, visited or benefited from a recommendation.

## Opening the notebooks

Browse the notebook files in this folder on GitHub. Before running one, obtain the source data, create the expected folder structure, and inspect the setup and license notes above. A fully guided hosted execution path will be added only after its data preparation and run order are implemented and checked.
