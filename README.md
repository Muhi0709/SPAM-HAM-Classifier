### SPAM-HAM-Classifier

* Prediction.ipynb : main() function to be invoked to get the predicted labels
                (trained model/classifier is saved as "svm_classifier.sav",which i loaded for prediction)
                (also loads bagofwords.npy and lemma_dictionary.npy)
                (can be run independent of the Training.ipynb)

* Training.ipynb : training on the enron dataset is done and the "svm_classifier.sav" is saved.
                 (Also the tf-idf feature vectors,labels,lemma_dictionary and bagofwords are saved as npy files)


* Source code for checking accuracy of the trained classifier, results attached in Report.pdf

* svm_classifier.sav : trained classifier
* lemma_dictionary.npy : python dictionary for lemmatisation
* bagofwords.npy : python list of the unique word set generated from enron email set.
