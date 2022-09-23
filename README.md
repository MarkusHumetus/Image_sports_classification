# [Hackathon of Talent Squad II (Barcelona-September 2022)](https://nuwe.io/dev/challenges/talent-squad-data-science-ii)

## Project Aims

The purpose of this project is to classify images from a test dataset into three different classes/labels according to which sport correspond. A training set of labelled images is provided. Organisation set two main goals:

1. Increase samples of images for training.

2. F1-score macro for the predictions.

Evaluation will be based on the f1_score from predictions of the dataset and the groundtruth (900), code quality (200) and documentation (100). (maximum puntuation 1200).

## Methodology

1. Load and Check initial images to homogenize formats, confirm its availability, check class distribution.

2. Build and train Convolutiona Neuronal Networks / CNNs. An initial screening of different pretrained models which are the base model (initial layers) of the CNN. 

3. Select the best model/s and study deeper with image augmentation, fine tunning by unfreezen last layers of base pretrained model,...

4. Increase training set of images by web scrapping. Images have to be validated: format, dupplicates and right labelling if considered representative (if not discarded).

5. Compare performance of best model with the extended set of training images.

6. Load models & wheights to make predictions with test set of images and get the scoring metrics. 

7. Report results and conclusions.

## Tools

* Python
* Git & Github
* [Jupyter Notebook](https://github.com/MarkusHumetus/Image_sports_classification/blob/main/main_Notebook.ipynb)
* Visual Studio Code
* Libraries: Pandas, Numpy, Seaborn, Matplotlib, Sklearn, Keras, Tensorflow, Selenium, OpenCV, Pillow, bing_image_downloader, 

## Getting Started

1. Clone this [repo](https://github.com/MarkusHumetus/Image_sports_classification) (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Use [requirements.txt](https://github.com/MarkusHumetus/Image_sports_classification/blob/main/requirements.txt) to check all installed dependencies in the working environment. 
3. Check and adapt the paths to the working directories according where files are stored.
4. Run the Jupyter Notebook as administrator. Otherwise, permision conflict will arise when opening image files.

## Project Status

[Finished]

Project was completed and submitted for competition in 23rd of September 2022.

## Results & Conclusions

* The maximum __f1 macro score__ obtained in the classification of the test images was __0.905__. 

* Best results were obtained with __Xception__ and __InceptionResNetV2__ pretrained models with the augmented training set of images.

* No improvements were observed when leaving last 10% layers of the pretained Xception model to be trained again.

* Increase the number of training images didn't improve the performance. On the contrary, it slightly worsen the results. It may be due the increase of 'noise' or variance in the training images. ON the other hand, the feed of new images can be biased by the selection of them. The more images and people who validate them, the less biased will be the training set. 

* As forseen, the __missclassifications occurs between__ the two most similar sports: __baseball and cricket__. 


The [best model as json file](https://github.com/MarkusHumetus/Image_sports_classification/blob/main/Im%C3%A1genes-data-science-ii/output/Xception_pretrained_aug.json) and its [wheigts as h5 file](https://github.com/MarkusHumetus/Image_sports_classification/blob/main/Im%C3%A1genes-data-science-ii/output/Xception_pretrained_aug.h5)  are uploaded on this repository. In the notebook, there is plenty of examples, how it can be loaded and tested with the test data.

## Contact

If you have any comment, doubt, proposal,... don't hesitate to contact me by email to marc.humet.datascience@gmail.com

If you are interested in my professional profile, please feel free to look at my [project's portfolio](https://github.com/MarkusHumetus) and my linkedin page:

[![LinkedIn][linkedin-shield]][linkedin-url]


[linkedin-url]: https://www.linkedin.com/in/marchumetmontada/

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555


## Acknowledgments

Thanks to the following organisations for the set up of such event which give the junior data scientist oportunities to learn, do networking and hopefully reach a first job in the data field.

![Barccelona_Digital_Talent](https://barcelonadigitaltalent.com/app/uploads/sites/3/2020/02/BDT-1.1-POSITIU_2-01.jpg)

![Mobil_World_Congress](https://challenges-asset-files.s3.us-east-2.amazonaws.com/companies/MWC_card.png)

![Nuwe](https://elreferente.es/wp-content/uploads/2021/12/LOGO_LETTERS_MONO-3.png)