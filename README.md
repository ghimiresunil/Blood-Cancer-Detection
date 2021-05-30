# Blood Cancer detection
![Leukemia_vs_normalproject](https://user-images.githubusercontent.com/40186859/120111632-69d6c180-c192-11eb-9822-9981da9a26fd.png)

## Introduction

Just over a month ago, I did what seemed like a small research at first: a mine Convolutional Neural Network (CNN) revealed something I did not expect. Yet the more I researched, the more I noticed that I had witnessed the beginnings of a break in the base of CNN architecture and a first hint of a brand-new form of CNN.

The project i.e. Detection of Blood Cancer is the result of approximately a month of research I have done to build the latest form of CNN architecture. I have never imagined it to take this long, but I've learned vastly more than I ever felt imaginable, and in fact, what I have done now touches almost existing types of blood cells and quite a bit besides.

According to the Leukemia & Lymphoma Community, one adult in the U.S. is infected with blood cancer around every 3 minutes and an approximate number of 174,250 individuals in the U.S. are predicted to have leukemia, lymphoma, or myeloma in 2018. The projected reported diagnoses in 2019 was about 61,780 and the rate of current cases of cancer is 3.5%, according to the National Institute of Cancer. As for the acute leukemia, the individual died within a few months if the treatment is not performed in a specific period. And identifying cancer in the early stages is very important for managing this type of cancer or any other type of cancer. It takes more time and effort to do the detection process by technicians manually and it costs more with the help of the instrument.

## Aims

The purpose of this research is to improve our ability to examine the different architecture of CNN and operating processes focused on the identification of blood cancer and acquire information about the specific parameters and hyperparameters that make up a complete system.

## Objectives
The project objectives are:

* Getting the information by proper research
* Build a system that can automatically diagnose cancer from the image of a blood cell.
* Able to visualize the model summary of the CNN architecture
* To configure and reconfigure the model made by the aggregation of the blood cell images

It has certainly taken me a month to come to terms with the conclusions I have reached. And while I hope I have put into my research and project will make it easier for others. Some of the research strategy guide for finding quality research are listed below:

* Consider the scope of my topic
* Locate background information 
* Identify information needs
* Analyze and adjust research strategy

To maximize my knowledge regarding blood cancer detection is one of the most rewarding benefits of eLearning provided by IEEE which helps me to find most desirable knowledge about detecting cancer using CNN architecture also provides best knowledge on model summary along with weights, bias, backpropagation, input, hidden and output layer, flattening layer, pooling layer, activation function and fully connected layer.

For me what has always been most important is the actual process of research. For I know of nothing exciting as to glimpse for the first time some new and basic truth.

## Reflection of Research Project

Some of the key achievement while doing blood cancer detection I have found existing methods for diagnosis and they are listed below:

* Medical history and physical examination: A record of the symptoms and problems that a person has experienced in the past. The personal background of the families of a individual tends to detect leukemia.
* Complete blood count (CBC): Blood is collected, and the number of RBCs, WBCs, and platelets examined under a microscope.
* Bone marrow aspiration: Bone marrow is extracted from the breastbone with a
needle. The extracted sample is examined under a microscope to look for irregular cells.
* Cytogenetic analysis: To help identify individual chromosomes, cytogenetic testing takes the blood or bone marrow. It shows chromosome abnormalities while help diagnose and identify the leukemia type. Typically reports are accessible in 3 weeks’ time.
* Immunohistochemistry: In immunohistochemistry, the blood sample of the cells produces unique antibodies and the difference of color can be seen under the microscope that allows to determine which kinds of cells are present.


While doing this project I have found before CNN there are several algorithms that people used for image classification. People used to create images features and feed them into some classification algorithm such as SVM. Some algorithms also used image-level pixel values as a vector of features. For example, you may be able to train an SVM with 784 features in which each
feature is the pixel value for an image of 28 × 28. The automated attribute extractors from the image can be thought of as CNNs. Although we lack a lot of spatial contact between pixels if we use an algorithm with a pixel vector, a CNN essentially utilizes neighboring pixel knowledge to analyze the picture by convolution first and only using a predictive layer at the end. Yann le cun first proposed this definition for digit classification in 1998, in which he used a single layer of convolution. It was later popularized in 2012 by Alex net which used multiple layers of convolution to achieve state of the art on the net of photos. So, henceforth make them am algorithm
of choice for challenges of image classification.

Following are the expertise I have gained as a researcher:

* The segmentation method has been proposed using color-based clustering to acquire the nucleus region and cytoplasm filed from stained images of blood smears. The SVM classifiers are introduced with the correct characteristics and the results are satisfactory.
* Automatically distinguish white blood cells (WBCs) from peripheral blood images and recognize five forms of WBCs they are eosinophil, basophil, neutrophil, monocyte, and lymphocyte. Eosinophil and basophil from other WBCs are first detected with a granularity attribute by SVM. The other three forms are then identified using CNN to extract features, and they are random forest to distinguish certain WBC.

![block_diagram_blood_cancer](https://user-images.githubusercontent.com/40186859/120111561-19f7fa80-c192-11eb-98b5-9d566d8549b8.png) <br>
*Figure  01: Block Diagram*
