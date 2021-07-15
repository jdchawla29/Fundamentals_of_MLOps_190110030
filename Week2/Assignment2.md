## Link - 
https://github.com/jdchawla29/MLOps_Assignment.git

List of commands -
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

Values -

Bucket ss -
