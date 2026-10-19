# Ali Darvish

I build AI projects in Python, across machine learning, deep learning and computer
vision, and I'm currently learning NLP. I like problems where the hard part is
getting the evaluation right: keeping test data truly unseen, choosing metrics that
match the real problem, and being clear about what a model cannot do.

## Projects

### [Diabetes readmission prediction](https://github.com/alidarviish/diabetes-readmission)
Predicts which diabetic patients will be readmitted to hospital within 30 days, from
about 100,000 visits. Train and test are split by patient to avoid leakage, results come
with calibration and bootstrap ranges, a bias check shows the model is weaker for
patients over 70, and each prediction comes with reasons a clinician can read.
`Python` `scikit-learn` `pandas`

### [Vehicle classifier](https://github.com/alidarviish/vehicle-classifier)
8-class vehicle image classifier built on a Swin-Tiny vision transformer, with a
confidence threshold that sends uncertain images to manual review.
`PyTorch` `computer vision`

### [Iran earthquake pipeline](https://github.com/alidarviish/iran-earthquake-pipeline)
Downloads every M4+ earthquake in Iran since 2000 from the USGS API, cleans it, stores it
in SQLite, and builds charts, maps and an analysis of aftershock sequences.
`Python` `pandas` `SQLite` `matplotlib`

### [Credit card fraud detection](https://github.com/alidarviish/fraud-detection-project)
Fraud detection on data where only 0.17% of transactions are fraud: model comparison,
scaling and depth experiments, and a threshold search for a stacking ensemble that
never touches the test set.
`Python` `scikit-learn` `XGBoost`

### [Skills Manager](https://github.com/alidarviish/skills-manager)
A command-line app for managing people and their skills, with JSON storage.
Started as a single script, later refactored into modules with tests and CI.
`Python` `pytest` `GitHub Actions`

## Tools

Python · pandas · NumPy · scikit-learn · XGBoost · PyTorch · SQLite · matplotlib ·
pytest · Git · GitHub Actions
