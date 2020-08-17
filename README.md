# AI-PROJECT
RECOGNITION  OF FLOWER SPECIES

1.PROJECT DESCRIPTION

Artificial intelligence is an approach to make a  computer, a robot,or a product to think how smart human think.AI is a study of how human brain think,learn,decide and work,when it tries to solve problems.And finally,this study outputs intelligent software systems. The aim of AI is to improve computer functions which are related to human knowledge, for example,reasoning, learning,and problem-solving.

Automatic identification and recognition of flower species in environments such as forests,mountains and dense regions is necessary to know about their excistance.In recent years,plant species recognition is carried out based on the shape,geometry and texture of various plant parts such as leaves,flowers etc. Flower based plant species identification systems are widely used. While modern search engines provide methods to visually search for a query image that contains a flower, it lacks in robustness because of the intra-class variation among millions of flower species around the world. Hence in this proposed research work, a Deep learning approach using Convolutional Neural Networks (CNN) is used to recognize flower species with high accuracy. Images of the plant species are acquired using the built-in camera module of a mobile phone. Feature extraction of flower images is performed using a Transfer Learning approach (i.e. extraction of complex features from a pre-trained network). A machine learning classifier such as Logistic Regression or Random Forest is used on top of it to yield a higher accuracy rate. 
     
This approach helps in minimizing the hardware requirement needed to perform the computationally intensive task of training a CNN. It is observed that, CNN combined with Transfer Learning approach as feature extractor outperforms all the handcrafted feature extraction methods such as Local Binary Pattern (LBP), Color Channel Statistics, Color Histograms, Haralick Texture, Hu Moments and Zernike Moments. CNN combined with Transfer Learning approach yields impressive Rank-1 accuracies of 73.05%, 93.41% and 90.60% using OverFeat, Inception-v3 and Xception architectures, respectively as Feature Extractors on FLOWERS102 dataset.
      
 Flower species recognition based on flower identification remain a challenge in Image processing and Computer Vision community mainly because of their vast existence, complex structure and unpredictable variety of classes in nature. Because of these natural complexities,it is highly undesirable to perform normal segmentation or feature extraction or combining shape,texture and color features which results in moderate accuracy on benchmark datasets.Although some feature extraction techniques combining global and local feature descriptors reaches state of the art accuracy in classifying flowers,still there is a need for a robust and efficient system to automatically identify and recognize flower larger scale in complex environment.
       
2.LITERATURE SURVEY

2.1 Existing system and Proposed System

Existing system:
Flower species recognition based on flower identification remains a challenge in Image processing and Computer Vision community mainly because of their vast existence, complex structure and unpredictable variety of classes in nature.

Proposed System:
In proposed system it detects the character which is given as input, in whatever style the input text might be .In this project,wedevelop a model for flower recognition. We also present the algorithms for recognizing the characters which is given as the input and give the correct output from the user. In this recognition process there won’t be any wrong recognition of characters. Instead it recognizes the input and gives the correct output from the user, with high accuracy and in a less time while compared to existing system.

2.2 Feasibility Study:

Feasibility study a design stage for a projects that indicates whether a projects can be built with the available resources and knowledge successfully or not. Feasibility study also includes the users who will be benefited by using this project, the estimated cost and the profits that can be obtains by implementing this system, the adaptable changes. The changes in the system should not affect the pre-existing system.
The objectives of feasibility study include:
	The projects must be developed within the estimated cost and within the scheduled time.

	The project should be able to implement successfully by careful planning.

	The projects should be adaptable to changes.


2.3	Tools and Technologies Used:

	CNN
Convolutional Neural Network (CNN) is a picture acknowledgment and grouping calculation. A run of the mill CNN comprises of mix of convolutional, pooling what’s more, thick layers.

	OpenCV
OpenCV (Open Source Computer Vision ) is a library of programming capacities focused on ongoing PC vision .It contains different libraries and act like an Programming interface for PC’s to have a counterfeit vision.

	Tensor Flow
Tensor Flow is an open source man-made reasoning library which assists with making neural systems and furthermore can be utilized for Classification, Perception, Discovering and Forecast of information.

	Python 
Python is significant level programming language used to create PC applications or web applications. Python permits simple usage of libraries and has straightforward programming sentence structure with superior and productivity.

	Datasets
Datasets are assortment of information which the PC uses to prepare and learn the man-made consciousness framework. Datasets contains picture, CSV information, content, sound or logs what’s more, will be put away in Data distribution center or Data Lakes.

2.4	Software and Hardware Requirement

Software Requirements:

	  Front End: JavaScript

	  Programming Language: Python

	  Back End: Python with Tensorflow

	  Software: Google colaboratory

Hardware Requirements:

	  Processor: Core i3, 1GHz

	  RAM: 1GB or above

	  Hard Disk: 10GB or above

3.REQUIREMENTS

3.2.Functional Requirements:

The system has following functional modules:

1.Collecting dataset.

2.Building the convolutional neural network.

3.Training the convolutional neural network.

4.Classification of images as flower species or not.

3.3 Non-Functional Requirements:

•	Performance:

The  software makes use of advanced techniques for flower image identification,thus yielding the better accurate results.

•	Accessibility:

The software can be easily accessible by anyone. It can be made available to anyone who is in need of.

•	Portability:

The software is highly portable and can be used on desktop as well as laptop computers.

•	Reliability:

The software is very reliable tool for the prediction of flower images prevents possible manual errors and provide high accuracy.

•	Scalability:

The software is highly scalable because it is very easy  to add flower images and predict the presence of flower species.

4.SYSTEM DESIGN

4.1 Architecture Design

A system architecture is the conceptual model that defines the behavior, structure, and more views of a system. The  input training dataset  comprises of the dataset given by the user. This training dataset is given as input to the convolutional neural network. The convolutional network consists of many layers. The input passes through all the layers. Once  the training process is done testing dataset is given to the network to perform testing. Finally  the result is predicted whether the tumor is present or not.

4.2 Data Flow Design

A dataflow diagram(DFD) is graphical representation of the “flow” of data through an information system. DFDs can also be for the visualization of data processing.
DFD provides no information about the timing or ordering of processes, or about whether processes will operate in sequence or in parallel. Initially, data is pre-processed and then feature extraction is applied. The output from the feature extraction is then given to the classifier for classification. The input image to be checked for abnormalities is then pre-processed and result is input to the prediction process which compares the image with the results obtained after classification.


 







