# SpaceX Falcon 9 — Exploratory Data Analysis

A Python notebook exploring historical SpaceX Falcon 9 launch data to understand how launch characteristics relate to first-stage landing outcomes.

This project is part of the IBM Data Science Professional Certificate capstone learning pathway.

## Questions Explored

- How do landing outcomes differ by launch site?
- What relationship appears between payload mass and landing outcome?
- How do flight number and orbit type relate to mission results?
- How do landing outcomes change across the observed years?

## Workflow

1. Inspect and prepare the dataset.
2. Summarise distributions and missing values.
3. Explore launch sites, payload mass, flight number, and orbit type.
4. Visualise relationships using Matplotlib and Seaborn.
5. Prepare categorical variables for subsequent modelling.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, and Jupyter Notebook.

## Repository Contents

```text
.
├── spacex_launch_data_eda.ipynb
└── README.md
```

## Run the Notebook

Open the notebook in Jupyter:

```bash
jupyter notebook
```

Execute cells in order and review the notebook for its input data source. The repository does not currently include a separate requirements file or exported dataset.

## Interpretation and Limitations

This is exploratory analysis. Observed associations should not be interpreted as causal effects without further investigation. The results apply to the missions represented in the notebook's dataset.

## Related Work

- [SpaceX Data Collection](https://github.com/Slimjoey56/SpaceX-Launch-Data-Collection-and-Wrangling)
- [SpaceX SQL Analysis](https://github.com/Slimjoey56/spacex-launch-data-sql-analysis)
- [SpaceX Machine Learning](https://github.com/Slimjoey56/SpaceX-Machine-Learning-Prediction-Part-5-v1)

## Author

Jehosaphat Brobbey Impiani  
[GitHub](https://github.com/Slimjoey56)