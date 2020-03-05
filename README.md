# Eplileptic Seizure Prediction Papers

## Datasets

* ![CHB-MIT Scalp EEG Database](https://physionet.org/content/chbmit/1.0.0/)
* ![TUH EEG Seizure Dataset](https://www.isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml#c_tusz)
* ![Bonn dataset](http://epileptologie-bonn.de/cms/front_content.php?idcat=193&lang=3&changelang=3)
* ![UCI Epileptic Seizure Recognition Data Set](https://archive.ics.uci.edu/ml/datasets/Epileptic+Seizure+Recognition), is a restructuring of the Bonn dataset
* ![American Epilepsy Society Seizure Prediction Challenge - Kaggle 2014](https://www.kaggle.com/c/seizure-prediction/data)
* ![epilepsyecosystem.org](https://www.epilepsyecosystem.org/) was first available as Kaggle contest data of ![Melbourne University AES/MathWorks/NIH Seizure Prediction competition](https://www.kaggle.com/c/melbourne-university-seizure-prediction) in 2016
* ![Freiburg dataset](http://epilepsy.uni-freiburg.de/freiburg-seizure-prediction-project/eeg-database), discontinued, data can be purchased from ![European Epilepsy Database](http://epilepsy-database.eu/)

## Papers

* ![Cook et al. 2013: Prediction of seizure likelihood with a long-term, implanted seizure advisory system in patients with drug-resistant epilepsy: a first-in-man study](https://www.thelancet.com/journals/laneur/article/PIIS1474-4422(13)70075-9/fulltext)
* ![Tsiouris et al. 2018: A Long Short-Term Memory deep learning network for the prediction of epileptic seizures using EEG signals](https://www.sciencedirect.com/science/article/abs/pii/S001048251830132X?via%3Dihub)
* ![Abdelhameed et al. 2018: Semi-Supervised Deep Learning System for Epileptic Seizures Onset Prediction ](https://ieeexplore.ieee.org/document/8614216)
  * train a Convolutional Autoencoder
  * use the trained Encoder, input the features/latent space representation into a Bidirectional LSTM for classification
  * uses CHB-MIT dataset

