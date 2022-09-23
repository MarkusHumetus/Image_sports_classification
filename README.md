1. scrap images
2. convert images
3. validate and manually classify images for training
manipulate images
4. make neuronal net
5. train
6. check test


# [Hackathon of Talent Squad II (Barcelona-September 2022)](https://nuwe.io/dev/challenges/talent-squad-data-science-ii)

## Project Intro/Objective

The purpose of this project is to classify images from a test dataset into three different classes/labels according to which sport correspond. A training set of labelled images is provided. Organisation set two main goals:

1. Increase samples of images for training.

2. F1-score macro for the predictions.

Evaluation will be based on the f1_score from predictions of the dataset and the groundtruth (900), code quality (200) and documentation (100). (maximum puntuation 1200).



## Methodology

1. Load,  Explore and Transform dara (images&labels)
2. Construct different Convolutional Neuronal Networks and train them.
3. Screening classification by machine Learning.
4. Tunning of hyperparameters to optimize the chosen model.
5. Predict the status for the test data set (supplied without label) with the optimised model.

## Tools

* Python
* Git & Github
* Jupyter Notebook
* Visual Studio Code
* Libraries: Pandas, Numpy, Seaborn, Matplotlib, Sklearn, Keras, Tensorflow, Selenium, OpenCV, Pillow

## Getting Started

1. Clone this [repo](https://github.com/MarkusHumetus/Image_sports_classification) (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Use [requirements.txt](https://github.com/MarkusHumetus/Image_sports_classification/blob/main/requirements.txt) to check all installed dependencies in the working environment. 
3. Check and adapt the paths to the working directories according where files are stored.
4. Run the Jupyter Notebook as administrator. Otherwise, permision conflict will arise when opening image files.

## Project Status

[Finished]

Project was completed and submitted for competition in 23rd of September 2022.

## Results & Conclusions

The [best model as json file](https://github.com/MarkusHumetus/Image_sports_classification/blob/main/Im%C3%A1genes-data-science-ii/output/Xception_pretrained_aug.json) and its [wheigts as h5 file](https://github.com/MarkusHumetus/Image_sports_classification/blob/main/Im%C3%A1genes-data-science-ii/output/Xception_pretrained_aug.h5)  are uploaded on this repository. In the notebook, there is plenty of examples, how it can be loaded and tested with the test data.



## Contact

If you have any comment, doubt, proposal,... don't hesitate to contact me by email to marc.humet.datascience@gmail.com

If you are interested in my professional profile, please free have a look on my [project's portfolio](https://github.com/MarkusHumetus) and my linkedin page:

[![LinkedIn][linkedin-shield]][linkedin-url]


[linkedin-url]: https://www.linkedin.com/in/marchumetmontada/

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555


## Acknowledgments

Thanks to the following organisations for the set up of such event which give the junior data scientist oportunities to learn, do networking and hopefully reach a first job in the data field.

![Barccelona_Digital_Talent](https://barcelonadigitaltalent.com/app/uploads/sites/3/2020/02/BDT-1.1-POSITIU_2-01.jpg)

![Mobil_World_Congress](https://challenges-asset-files.s3.us-east-2.amazonaws.com/companies/MWC_card.png)

![Nuwe](https://elreferente.es/wp-content/uploads/2021/12/LOGO_LETTERS_MONO-3.png)