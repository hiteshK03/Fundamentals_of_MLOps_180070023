Link to Github Repo : [https://github.com/hiteshK03/MLOps_Assignment](https://github.com/hiteshK03/MLOps_Assignment)  
Part1 commands :  
```bash
git clone git@github.com:hiteshK03/MLOps_Assignment.git  
cd MLOps_Assignment/  
mkdir data  
mkdir ../external_cache  
cd ../  
dvc init  
dvc cache dir ../external_cache  
dvc add data/creditcard.csv  
git add data/.gitignore data/creditcard.csv.dvc  
git commit -m "Add raw data"  
dvc remote add -d storage s3://mlopsassign/datastore  
git add .dvc/config  
git commit -m "Configure remote storage"  
dvc push  
git push origin main
```
For both experiments:
* Accuracy_score = 1.0  
* F1_score = 1.0  

![Screenshot from 2021-07-15 21-29-02](https://user-images.githubusercontent.com/45922320/125819511-1583898d-769c-42bd-bf19-bcc5383a7cd5.png)
