# Machine-Learning

## 🌍 Project Goal
The purpose of this project is to analyze the daily bike-sharing dataset from the UCI Machine Learning Repository and build predictive models that can help a bike-sharing company optimize operations.

## 📂 Folder Structure
- **`data/raw`**: Original, unprocessed data  

- **`data/processed`**: Cleaned and processed data  

- **`scripts/`**: R scripts and markdown files containing code

- : **`models/`**: Saved models as RDS files

## ⚙️ How to Start Working

### Clone the Repository
```bash
git clone https://github.com/anamasurquijo/Machine-Learning.git
```

### Make changes and push R scipts + updated data files. 
**Note: DO NOT push the .Rproj file as this will lead to incompatibility between package versions and local system versions** 
```bash
// to push your saved changes -> 
git diff
git status
git add <file-names>
git commit -m "Your commit message"
git push origin main

// to pull changes from upstream -> 
git fetch origin main
git merge
```
