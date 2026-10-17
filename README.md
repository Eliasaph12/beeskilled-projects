# IPL Dataset Analysis – Data Science with Python

## Files
- `IPL_Dataset_Analysis.ipynb` — complete analysis notebook.
- `IPL_Project_Report.pdf` — five-minute project report.
- `Project_Completion_Certificate_Template.pdf` — editable/printable certificate template (not an official certificate).
- `requirements.txt` — Python dependencies.

## Dataset
Download the IPL Complete Dataset (2008–2020) from:
https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020

Place `matches.csv` and `deliveries.csv` in this folder. The notebook expects the standard columns from that dataset.

## Run
```bash
pip install -r requirements.txt
jupyter notebook IPL_Dataset_Analysis.ipynb
```
Run all notebook cells. The report describes the analysis and the notebook computes exact rankings from the dataset at run time.

## Upload to GitHub
Create a new repository on GitHub, then run these commands from this folder:
```bash
git init
git add .
git commit -m "Add IPL dataset analysis project"
git branch -M main
git remote add origin https://github.com/Eliasaph12/beeskilled-projects.git
git push -u origin main
```

