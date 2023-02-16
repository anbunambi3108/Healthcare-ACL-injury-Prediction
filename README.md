# Healthcare--ACL-injury-Prediction
To investigate the feasibility of using a deep learning–
based approach to detect an anterior cruciate ligament
(ACL) tear within the knee joint from MRI scan dataset.
Developing a neural network by using deep
convolutional neural networks (CNNs) and other
popular models to isolate the ACL on Magnetic
resonance images followed by a classification CNN to
detect structural abnormalities within the isolated
ligament.
# About the dataset
The dataset we used is KneeMRI dataset was gathered
retrospectively from exam records made on a Siemens
Avanto 1.5T MR scanner, and obtained by proton density
weighted fat suppression technique at the Clinical
Hospital Centre Rijeka, Croatia, from 2006 until 2014.
The dataset consists of 909 MRI's of either left or right
knees of dimension 231x231x3. Each volume record was
assigned a diagnosis concerning the condition of the
anterior cruciate ligament in a double-blind fashion, i.e.
each volume record was labelled according to the
ligament condition: 
- (0) healthy, 
- (1) partially injured or completely ruptured<br>
	of 683 and 226 images.
# Models Implemented
- Custom Convolutional Neural Network (CNN)
- AlexNet
- VGG16
- VGG19
- Inception V3
