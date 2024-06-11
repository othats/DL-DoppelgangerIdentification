
# Final Project: Doppelgänger Identification

This project involves building a neural network capable of identifying doppelgangers, using various techniques. We separated the project into different stages, each represented by a different notebook. 


## Project Structure

- [DatasetManipulation.ipynb](FINAL/DatasetManipulation.ipynb)

This notebook covers the preprocessing of the dataset used for training and testing the doppelganger identification models. It includes steps to ensure the uniformity of our data, so that all images become of the same size and resolution (256x256). For that we used the Viola-Jones Algorithm. Explanations of the steps taken are offered within the notebook. 

- [FinalProject.ipynb](FINAL/FinalProject.ipynb)

This is the main notebook for the project. It integrates the data loading, model training, evaluation and results analysis. We explore different model architectures, such as ResNet18 and MobileNetV3. Additionally, we experiment with triplet margin loss to improve the model's ability to distinguish between similar and dissimilar faces.

- [ModelApplication.ipynb](FINAL/ModelApplication.ipynb)

This final notebook focuses on applying the trained models to identify doppelgangers in old and new data. It includes steps for loading the trained models, making predictions, and visualizing the results. 


## Execution

If you want to execute the given notebooks, follow these steps: 

1. Clone the repository : `git clone https://github.com/othats/DL-DoppelgangerIdentification`

2. Install the required dependencies : `pip install -r requirements.txt`

3. Run the notebooks


## Authors

- [@ Luca Franceschi](https://github.com/LucaFranceschi01)
- [@ Julia Othats-Dalès](https://www.github.com/othats)
- [@ Alejandro Gonzalez](https://github.com/alejandrogonzalez14)


## Acknowledgements

 - Dataset courtesy of: C. Rathgeb, P. Drozdowski, M. Obel, A. Dörsch, F. Stockhardt, N. E. Haryanto, K. Bernardo, C. Busch, “Impact of Doppelgängers on Face Recognition: Database and Evaluation”, in Proc Intl. Conf. of the Biometrics Special Interest Group (BIOSIG), Darmstadt, Germany, September, 2021.