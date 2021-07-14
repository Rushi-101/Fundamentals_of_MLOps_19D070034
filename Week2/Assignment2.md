Link to the repo for Assignment 2 : https://github.com/Rushi-101/MLOps_Assignment

Created the above repository
1. dvc init
2. dvc add data/creditcard.csv
3. git add data/creditcard.csv.dvc data/.gitignore 
4. git commit -m "Add raw data"    
5. dvc remote add -d storage s3://mlopsassign1/datastore 
6. dvc push
7. git push origin main

### Decision Tree Classifier
Accuracy score : 0.9991573329588147
F1 score : 0.889697186224832

### Random Forest Classifier
Accuracy score : 0.9994382219725431
F1 score : 0.9173850891195552

### Screenshot of Amazon S3 bucket
<img src="https://github.com/Rushi-101/Fundamentals_of_MLOps_19D070034/blob/main/images/mlopsassign1 bucket.png">
<img src="https://github.com/Rushi-101/Fundamentals_of_MLOps_19D070034/blob/main/images/Folders inside bucket.png">
