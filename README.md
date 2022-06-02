# halos_pipeline

## Data Generation

IllustrisTNG data access (cosmology simulation): https://www.tng-project.org/data/

Data specifications: https://www.tng-project.org/data/docs/specifications/

Data generation notebook: https://colab.research.google.com/drive/1L58I-5zWCC9hbedW0yhg-1VZ2qCWMEPy?usp=sharing

Features of dark matter halos: 
- **mass**: proportional to dark matter particle counts
- **velocity dispersion**: standard derivation of velocities
- **comoving radius** in ckpc/h
- **Group_M_Crit200, Group_M_Crit500, Group_M_Mean200, Group_M_TopHat200**: total mass enclosed in a sphere
- **Group_R_Crit200, Group_R_Crit500, Group_R_Mean200, Group_R_TopHat200**: comoving radius of a sphere
## Machine Learning Pipeline
Pipeline notebook: https://colab.research.google.com/drive/15GyKvV69agKNrIueeXUud86wk3nhfiqg?usp=sharing

Use one or multiple features of halos to predict **velocity dispersion**

Currently using sklearn PolynomialFeatures with Lasso regularization 

Goal: - Find a proper model to use some features of halos (that are easier to get) to predict other features of halos (that are harder to generate)

- Compare the predictions from different models

- Visualization

## Relevant Paper

https://arxiv.org/pdf/2010.15123.pdf
