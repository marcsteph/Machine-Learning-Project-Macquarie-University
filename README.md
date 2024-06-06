# Classification of Living things 

Introduction

In the major project, you will be working with a specified dataset of images.  
You will then explore the data and try the statistical learning approaches that we have covered in this course to tackle the task associated with the dataset.  
The statistical approaches should cover both conventional machine learning (i.e. not deep learning), from the first half of the unit, and deep learning from the second half.  Which methods you choose are (mostly) entirely up to you;
a goal of the project is for you to explore the approaches you've been taught, or perhaps beyond those, in order to build a high-performing system.
We're specifying an image dataset as this is one of the types of data to which deep learning has been most extensively applied, as in the MNIST dataset used as a running example in the Geron textbook.
The image dataset will have an associated classification task.  
The goal of your statistical learning approaches is to build models that will perform well on that classification task.  To evaluate how well you do, we'll be using both a public test set and a private test set.  You'll have access to the public test set for the whole duration of the project, so you can see how well your system is performing.  The private test set, which will only be released at the end of semester for a limited period, is to see how well your system generalises to an unseen dataset.
The evaluation will be carried out as an in-class competition in Kaggle.

Project Task

For this, you'll be working with a dataset of images of living things.  Your task is to predict the category label of the living thing.  
A special feature of this year's major project is that you'll be predicting category labels at two different levels of granularity in the Linnaean taxonomy of living things, one more coarse-grained and one more fine-grained; see the dataset description for more details.  
There will correspondingly be two Kaggle competitions: one for coarse-grained classification and one for fine-grained.
We expect that, by default, you'll be developing your solutions under Google Colab.  
This dataset is available in Kaggle, although you can use whatever data you like to train your model.
For evaluation, there'll be a public test set and a private test set.  
For each of the two Kaggle competitions (coarse-grained, fine-grained) the images will be the same, but the labels necessarily different.  
The private test set will be released for a limited time in the last week of class.


As noted in the project Description, 

you'll be working with a dataset of living things.  The images have dimensionality of varying dimensionality, and are in colour.  There will be two versions of test data, where the images are the same, but the labels are different: one set of labels is coarse-grained and consists of 8 labels, and the other is more fine-grained and consists of 50 labels.
Below are 16 images, along with their coarse-grained labels. 
These labels come from the Class rank in the widely used Linnaean biological taxonomy; the 8 we are using are ['Aves', 'Reptilia', 'Mammalia', 'Arachnida', 'Magnoliopsida', 'Insecta', 'Liliopsida', 'Pinopsida'].  
The fine-grained labels come from the Family rank; you can find out the set of 50 labels we're using from the provided code stub.  
One example of a fine-grained label is Family Scolopacidae representing sandpipers (wading bird). Scolopacidae are part of Class Aves (broadly, birds).
