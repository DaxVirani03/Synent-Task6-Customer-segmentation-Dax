# Dax Virani - Mall Segmentation

Objective
- Segment customers using clustering techniques to reveal behavioral groups and profile segments.

Steps performed
- Load customer dataset and clean missing values
- Feature engineering and scaling
- Determine cluster count via elbow and silhouette analysis
- Fit KMeans and profile clusters with summary statistics and visualizations

Tools / Libraries
- pandas, numpy, scikit-learn, matplotlib, seaborn

Outcome (brief)
- Notebook outputs recommended cluster counts, cluster profiles, and visual plots useful for targeted marketing.

How to run

```bash
pip install -r requirements.txt
jupyter lab
jupyter nbconvert --to notebook --execute "Dax Virani - mall_segmentation.ipynb" --inplace
```

Notes
- Place the customer dataset (CSV) in the workspace before running.
- Author: Dax Virani
