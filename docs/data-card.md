# Data Card: Iris 

This Data Card documents the dataset used for Iris exploratory data analysis project.
It follows the general transparency goals of Google's Data Cards Playbook:
Describe dataset provenance, composition, intended use, limitations, and considerations not apparent from the data.

## Dataset Summary

| Item | Description |
| --- | --- |
| Dataset | Iris |
| Curated dataset | iris |
| Observations | 150 flowers |
| Species | Setosa, Versicolor, Virginica |
| Measurements | sepal length, sepal width, petal length, petal width |
| Unit | centimeters |
| Grain | one flower 

This Data Card documents the dataset used by the
Iris exploratory data analysis project.

It follows the general transparency goals of Google's
Data Cards Playbook:
describe dataset provenance, composition,
intended use, limitations, and considerations
not apparent from the data.

## Dataset Summary

| Item | Description |
| --- | --- |

| Dataset | Iris |
| Curated dataset | iris |
| Observation |150 flowers 
|
| Species | Setosa,
Versicolor, Virginica |
| Measurements | sepal length, Sepal Width, petal legth, petal width |
| Unit | centimeter |
| Grain | one flower |
| Primary use here | exploratory data analysis | 

## Purpose

The Iris dataset provides measurements of iris flowers from three species.

This curated dataset is commonly used for data exploration, visualization, and introductory data analysis because it contains a small set of clear numeric variables.


## Provenance

The Iris dataset is based on measurements used in R. A. Fisher's classic iris classification study.

This project uses the Iris dataset obtained through the Seaborn dataset collection and saved locally as `data/raw/iris.csv`.

## Dataset Composition

The dataset contains 150 observations representing individual iris flowers.

The variables used in this project are:

- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species`

The dataset includes three iris species:

- Setosa
- Versicolor
- Virginica

## Intended Use

The dataset is appropriate for:

- education
- exploratory data analysis
- visualization
- introductory statistical analysis
- supervised machine-learning experiments
- demonstrating reproducible analytical workflows

In this repository, the dataset is used to demonstrate exploratory data analysis with interactive distributions and relationships between numeric variables. 


## Additional Exploration


Other reasonable analytical questions include:

- predicting iris species from flower measurements
- comparing sepal measurements across species
- comparing petal measurements across species
- studying relationships between sepal length and sepal width
- studying relationships between petal length and petal width

## Limitations

The dataset is small and contains measurements from only three iris species, so results should not automatically be generalized to all flowers or plant species.

Results should therefore not automatically be generalized to:

- all iris species
- all flower populations
- different growing conditions
- future samples
- other plant species

The Iris dataset is small, and relationships between measurements may differ across species.

A predictive relationship observed in this dataset should not be interpreted
automatically as a causal relationship.

## Representation Considerations

The dataset contains observations from three iris species.

Because the dataset is small and includes a limited set of flower measurements, results may not represent all iris populations or other plant species.

Comparisons across species should be interpreted carefully because some measurements may differ naturally by species.

## Experiment-Specific Use

This project uses the Iris dataset for exploratory data analysis.

The primary numeric variables are:

- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`

The project examines individual distributions and relationships between selected numeric variables.

## Project Data Processing

The project:

1. loads the Iris dataset
2. observes the available columns
3. validates the selected variables
4. selects numeric flower measurements 
5. explores distributions 
6. compares relationships between selected variables

## References

- [Iris Dataset](https://archive.ics.uci.edu/dataset/53/iris)
- [Seaborn Example Datasets](https://github.com/mwaskom/seaborn-data)
- [Data Cards Playbook](https://pair-code.github.io/datacardsplaybook/)
- Data Cards convention: Pushkarna, Zaldivar, and Kjartansson (2022), *Data Cards: Purposeful and Transparent Dataset Documentation for Responsible AI*

---

[◄ Back to Home](index.md)
