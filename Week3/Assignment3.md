Link to Github Repo : [https://github.com/hiteshK03/MLOps_Assignment](https://github.com/hiteshK03/MLOps_Assignment)  

## Preprocessing & Feature Engineering
* Normalize, method: "minmax"
* Polynomial features
* Trignometry features
* Fix imbalance
* Feature selection

## Comparison between top 5 models

| Model | Initial F1 Score | FIne-tuned F1 Score |
|:-----:|:----------------:|:-------------------:|
|   et  |      0.7410      |        0.7472       |
|  ada  |      0.7150      |        0.5724       |
|   rf  |      0.6860      |        0.8478       |
|  gbc  |      0.6779      |        0.8019       |
|  knn  |      0.5670      |        0.6336       |

## Plots
![conf_matrix](https://user-images.githubusercontent.com/45922320/126683729-82aca098-b1e0-439a-b10f-e0c6146c7c95.png)
![download](https://user-images.githubusercontent.com/45922320/126683739-2ebee625-c0c7-4a08-91c2-634a689a0cbf.png)

## Evaluation on unseen data
* Accuracy  : 0.9993
* Precision : 0.7358
* Recall    : 0.8478
* F1-Score  : 0.7879
