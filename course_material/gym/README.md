# Gym Marketing Case — Colab Learner Path

This folder contains the four learner notebooks for the Gym marketing case. The example data is synthetic.

## Start in Google Colab

1. Open **Notebook 01** from the Ground Truth ML case-study website, or open the notebook file here and choose **Open in Colab**.
2. Run the first setup cell. It connects Google Drive, clones this public course repository into My Drive/GroundTruth_Course_Material, prepares the compressed synthetic input tables and installs the pinned libraries.
3. Run the notebooks in order: **01 → 02 → 03 → 04**. Keep the same course folder in Drive so each notebook can use the outputs from the previous step.

The input package contains only the raw synthetic tables required to begin EDA and their data manifest. Notebook 01 creates the cleaned and analysis outputs used by later notebooks. The data generator (Notebook 00) is an internal preparation tool and is not part of the learner path.

## Notebooks

1. [01 — Data Readiness and EDA](notebook/01_data_readiness_and_eda.ipynb)
2. [02 — Basic Modeling](notebook/02_basic_modeling.ipynb)
3. [03 — Advanced Modeling](notebook/03_advanced_modeling.ipynb)
4. [04 — Member Scoring and Business Decision](notebook/04_member_scoring_and_business_decision.ipynb)

## Data and evidence boundaries

All records are synthetic teaching data. This case demonstrates a purchase-propensity workflow and a campaign-list decision; it does not estimate marketing lift or represent real members. The model scores and lists are reference outputs, not campaign instructions. No messages are sent and no appointments are booked.

## Environment and validation

Pinned Colab dependencies are listed in requirements-colab.txt. The setup cell uses Google Drive authentication and installs them into a dedicated runtime path. The notebooks have not yet been run end to end in an authenticated hosted Colab session; that remains a separate verification step.
