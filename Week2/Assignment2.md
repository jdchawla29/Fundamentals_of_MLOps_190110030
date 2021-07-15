## Link - 
https://github.com/jdchawla29/MLOps_Assignment.git

## List of commands -
```bash
$ mkdir MLOps_Assignment
$ cd MLops_dvc
$ git init
$ git remote add origin https://github.com/jdchawla29/MLOps_Assignment.git
$ git branch -M main
$ dvc init
$ dvc add data/creditcard.csv
$ git add data/creditcard.csv.dvc data/.gitignore
$ git commit -m "Add data"
$ dvc remote add -d storage s3://mlops190110030assignment2/datastore
$ git add .dvc/config
$ git commit -m "Configure remote storage"
$ dvc push
$ git push origin main
```

## Values -

Decision Tree: "Accuracy": 0.9991924440855307, "F1-score": 0.7653061224489794

Random Forest: "Accuracy": 0.9996137776061234, "F1-score": 0.8735632183908045

## Bucket ss -

![AWS Console Screenshot](Screenshot%202021-07-16%20011535.jpg)
