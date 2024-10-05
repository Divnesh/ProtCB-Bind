ProtCB-Bind - Protein-carbohydrate binding prediction using an ensemble of classifiers

To run the scripts found in the Notebooks you will need to download and update the Data files, i.e. the ETC_Dataset, SGD_Dataset and SVM_Dataset.
The files have been shared on Google Drive and can be accessed using the following link: https://drive.google.com/drive/folders/1rRX8CHkoookbwfocWhPChx_7OCzzbncN?usp=sharing

The predictor function is contained in the ProtCB-Bind notebook and svm, sgd and etc features as well as the labels to make predictions. 


The TS49_Test notebook produces the results of ProtCB-Bind on TS49 dataset and uses the probabilties calculated from StackCB-Embed and StackCB-Pred to create the ROC graph for the predictors.
TS88_Test notebook does same tasks for TS88 dataset


For futher information, please contact me on divnesh44@gmail.com