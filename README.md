A README documentation file which briefly describes the software and libraries used in your project, 
including any necessary references to supporting material. If your project requires setup/startup, 
ensure that your README includes the necessary instructions.

Softwares used:
1.Python 3.6 programming language 
2.Jupyter 
3.Anaconda package manager

Libraries: 
1. Numpy 
2. glob 
3. OpenCV
4. matplotlib 
5. Tqdm 
6. Pytorch and Torchvision
7. PIL(Python Imaging Library)
8. OS

Supporting materials: 
1. 	Dog dataset:https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip
2. 	Human dataset:http://vis-www.cs.umass.edu/lfw/lfw.tgz
3. 	Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." Advances in neural information processing systems 25 (2012): 1097-1105.
4.	LeCun, Yann, Yoshua Bengio, and Geoffrey Hinton. "Deep learning." nature 521.7553 (2015): 436-444.
5. 	Liu, Jiongxin, et al. "Dog breed classification using part localization." European conference on computer vision. Springer, Berlin, Heidelberg, 2012.
6.	He, Kaiming, et al. "Deep residual learning for image recognition." Proceedings of the IEEE conference on computer vision and pattern recognition. 2016.
7. 	Cuimei, Li, et al. "Human face detection algorithm via Haar cascade classifier combined with three additional classifiers." 2017 13th IEEE International Conference on Electronic Measurement & Instruments (ICEMI). IEEE, 2017.
8. 	https://neurohive.io/en/popular-networks/vgg16/ 
9. 	https://iq.opengenus.org/resnet50-architecture/ 
10.	https://medium.com/@erika.dauria/accuracy-recall-precision-80a5b6cbd28d#:~:text=Accuracy%20is%20an%20evaluation%20metric,True%20Positives%20and%20True%20Negatives.
11. 	Emami, Shervin, and Valentin Petrut Suciu. "Facial recognition using OpenCV." Journal of Mobile, Embedded and Distributed Systems 4.1 (2012): 38-43.


Setup:
1. Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/udacity/deep-learning-v2-pytorch.git
	cd deep-learning-v2-pytorch/project-dog-classification

2. Download the dog dataset.
   Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages.
   The dogImages/ folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the human dataset. 
   Unzip the folder and place it in the repo, at location path/to/dog-project/lfw.  
4. Make sure you have already installed the necessary Python packages 
   according to the README in the program repository.
5. Open a terminal window and navigate to the project folder. 
   Open the notebook and follow the instructions.

	jupyter notebook dog_app.ipynb