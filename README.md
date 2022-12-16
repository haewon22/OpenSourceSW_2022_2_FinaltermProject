<2022_2_FinaltermProject>
=========================
> Brain Tumor Classification
# • *Configuration instructions*
## Voting Classifier with
>* SVM
>* ExtraTrees
>* KNN
## Hyperparameter
```
KNeighborsClassifier(n_neighbors=1)
ExtraTreesClassifier(n_estimators=90, random_state=7, max_depth=19, max_leaf_nodes = 10000)
SVC(random_state = 1, kernel='linear', probability=True)
VotingClassifier(estimators=[ ('extra', extra_clf), ('KNN', knn), ('SVM', svm) ], voting='soft')
```
## Training Dataset
> MRI data
> * Glioma_tumor
> * Meningioma_tumor
> * No_tumor
> * Pituitary_tumor
# • *Operating instructions*
> 1. Download dataset
> 2. Run code
# • *Copyright and licensing information*
>* MIT License
# • *Contact information*
>* Name : 정해원
>* Student ID : 20221377
>* E-mail : haewon20430@cau.ac.kr
