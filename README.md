# Document_Classifier_And_Text_Extractor
Introduction
Document image classification is an important step in Digital Libraries and other document image analysis applications. There is great diversity in document image classifiers: they differ in the problems they solve, in the use of training data to construct class models, and in the choice of document features and classification algorithms. We survey this diverse literature using three components: the problem statement, classifier architecture, and performance evaluation. We emphasize techniques that classify single-page typeset document images without using OCR results. Developing a general, adaptable, high-performance classifier is challenging due to the great variety of documents, the diverse criteria used to define document classes, and the ambiguity that arises due to ill-defined document classes.


Procedural Aspects under Modelling:
As part of this project, we were trying to solve 2 problem statements (i.e) Document(forms) Classification and Document fields Extraction. Three different components of a document classifier include:

1.	Problem Statement: The problem statement for a form classifier has two aspects: the document space and the set of classes. The former defines the range of input forms, and the latter defines the output that the classifier can produce.

2.	The Classifier Architecture: Different classification algorithms such as Feedforward Neural Network, Resnet, VGG were applied on the trained data set in order to capture the features from the images and classify accurately on the unseen data.

3.	Evaluation Metrics: Performance evaluation is a critically important component of a document classifier. It involves challenging issues, including difficulties in defining standard data sets and standardized performance metrics, the difficulty of comparing multiple document classifiers, and the difficulty of separating classifier performance from pre-processor performance.

Technology Used:
•	Tesseract – Batch files,
•	Google Vision API- Single files
•	FNN, ResNet50, VGG15.
•	Tkinter

Benefits:
•	By testing many samples, we discovered that Google Vision API is much better to use for text extraction.
•	Gives Bounding box, by which we can get coordinates around text, to retrieve it.
•	Can access information extracted from image in the csv file.
•	User can easily get attributes from csv file.
•	User can get all the text extracted neatly on notepad.

Drawbacks:
•	With tesseract the text extraction wasn’t up to par level.
•	Tesseract fails to give the bounding box, which is essential in getting text back to append into the csv file.
•	With our project we are successfully extracting text and appending the text with respect to their categories into the csv file.
•	For to append there is a only limitation that, user has to select attributes in decided format only, otherwise the function will append wrong attributes.

Challenges:
•	Faced challenges in appending the attributes extracted with the help of Google Vision API- Bounding Boxes.
