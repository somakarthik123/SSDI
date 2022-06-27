# SSDI

Malignant, Benign Cancers Differentiation using Machine Learning

Term Project Report 

Group 4

Abstract		 	 	 							
A skilled dermatologist generally follows a step by step process, which starts with observation of suspected lesions by naked eye. Secondly, dermoscopy (magnifying lesions microscopically) and later biopsy.During this process a lot of time is consumed and the patient's cancer will advance to later stages . Furthermore, a correct diagnosis depends on the clinician's ability. The finest dermatologists are just 80% accurate at detecting skin cancer, according to research. In addition to these challenges, there aren't enough qualified dermatologists working in public healthcare internationally. Machine learning methods have become a focus of study and have been demonstrated to be effective in the early detection and prediction of skin cancer.

Introduction								
Now-a-days skin cancer has become a major threat to humans. Particularly there are two types of skin cancers: malignant and benign. These two cancers are very dangerous and many people are dying because of these cancers. These two cancers can be cured in the initial stage, but should be given the right medication. But many doctors get confused between these two skin cancers, So, in this project we had implemented a convolutional network that is capable of classifying these two skin cancers. We had created this Cnn with the help of computer vision(opencv) which will take input images and then give an numpy array as output. We had even used dropout layers that will help the model in case of overfitting. Batch Normalization layers are also implemented as they will decrease the chance of underfitting.
Convolutional neural networks have become very popular today, as they are like a model of human neural networks. They are very well known for image classification as they will be using convolution filters in order to classify images and the predictions are very better compared to other types of algorithms. So, in this project we try to use the concepts of CNN to predict distinguish the type of skin cancer by taking image as an input because using CNN we will be able to classify the image and we know the type of Cancer present, the main advantage of using CNN is it requires comparatively less number of connections are required. Now-a-days new types of skin cancer are being born, so it is difficult even for doctors to predict the type of skin cancer a patient is having, so there is a high requirement of using machines to know about the patient’s health condition (Type of cancer). In this project we had trained a model by providing input images of the two skin cancers (malignant and benign). We first imported the image data into the system using opencv with resolution (224,224,3) and then normalized and created a model and then trained to achieve weights. 

Project Team Details

 ● Introduction - Our team has seven software engineers. Our strength is the willingness to learn and the flexibility to work on the challenges in the direction of progress of the project.

 ● Team Profile 
     
Group Members
Programming Languages Known
Additional Skills
Individual Qualification and Strength
Karthik Soma
(801264905)
Java, JavaScript, MySQL
AWS
Management, Programming
Kiran Samatham
(801269579)
Python, Java, Android, MySQL, C, HTML, CSS
Angular JS
Programming, Documentation
Leela Santoshi Totapally
(801273358)
Java, JavaScript, MySQL, HTML, CSS
Spring Boot,
Angular
Documentation, Programming
Sai Swetha Gannamani (801252489)
Java, Python, JavaScript, SQL, R, C, C++, SpringBoot, HTML, CSS, PHP, Bootstrap
AWS
Design,
Programming
 
Srinivasa Sharanya Nallamothu
(801293767)
Java, MySQL, PHP, HTML, CSS
AWS
Organization, Programming
Sumanth Reddy Gurram
(801273351)
Python, Java, C, MySQL, HTML, CSS
Angular, Ionic framework
Presentation, Programming
Divyaja Teeneti
(801254186)
Python, Java, HTML, CSS
Angular
Programming, Design

 
    ● First meeting: We held our first zoom meeting on 31st May. 2022 


Project Proposal: 
As per the instructions received, the project proposal is submitted on canvas under assignment ‘TERM PROJECT PROPOSAL SUBMISSION LINK’ on 2nd June 2022.

Team Agreement:
1. Methods of communication - Email ( UNCC and personal emails) and instant messaging using WhatsApp. In case of an urgent communication, phone calls are welcome.
2. Expected response time - Within 24 hours, every team member should reply to the messages and e-mails.
3. Meeting attendance - Every team member must attend all planned meetings. In case of non-avoidable emergencies, meetings should be postponed to a date when everyone is available.
4. Running meetings - All the meetings should be held over zoom video call and meetings can be conducted on weekends to plan the tasks completion.
5. Meeting preparation - Each team member should discuss the tasks that have been completed by them and should plan regarding further tasks implementation.
6. Version control - We will be using GitHub for version control. No commits should be made into the main repository.
7. Division of work - Sumanth and Kiran will be working on collection of images and preprocessing the data. Leela and Karthik will be accountable for keras pre-processing. Divyaja and Sharanya are responsible for tensor flow implementation. Swetha will be responsible for code implementation.
8. Submission of work -  Swetha will be submitting the work once it has been reviewed.
9. Contingency planning- If a team member drops out, the project should be continued and if a team member does not contribute, it should be reported to the professor.

System Requirements:
We will need at least 16 GB of RAM, but we would recommend using 32 GB. When multitasking, less than 16 GB can be problematic. CPU: Because it provides High Performance, processors above Intel Corei7 7th Generation are encouraged.



Programming Languages:
We have used python programming language in order to implement this project.  

Tools and Environments

Jupyter Notebook:
It is an interactive web based application that is used for different workflows in machine learning and data science. It can also be used offline on a local computer without any internet access.

Tensorflow:
The Maths behind Ml and Deep learning are very complicated as they include differential equations. We can use Tensor flow which makes all the required calculations in the learning process. This contains the Keras package which helps in creating Models.
Keras:
It helps in creating required models. We can even include Dropout layers and Batch Normalization layers by using this framework. It also contains ImageData augmentation
Image Data Generator:
It helps in creating new data from old data (i.e) This will make the image flip, rotate, change its orientation etc.
OpenCV: 
It helps in taking an image as an input and form a matrix having all the pixel values of the image. Computer cannot read images as humans did but it can read by using Pixel values.Using opencv we can convert Images to Numpy arrays . This is the most important framework for projects that deals with images as input.

Text Files
No text files are produced in this project.

 User Manual
   Dependencies:
Install Jupyter notebook - Installing the classic Jupyter Notebook interface
Install TensorFlow - https://www.tensorflow.org/install
Install Keras using the instructions provided in https://keras.io/
Install OpenCV https://docs.opencv.org/4.x/d5/de5/tutorial_py_setup_in_windows.html
Install Git https://github.com/git-guides/install-git
Install Numpy https://numpy.org/doc/
Install Matplotlib https://matplotlib.org/stable/index.html
Check if all dependencies are installed successfully on your system
Steps to run on the local environment:
1. Clone the GitHub repository onto the local machine.
2. Open Jupyter notebook and navigate to the cloned repository.
3. Select the python file and run it.

S.No
Task
1
Collection of Data Set based on the features required.
2
Collection of data images of both benign and malignant.
3
Data pre-processing
4
Importing data using open cv.
5
Importing Keras, Tensor flow packages and Training the model.
6
Observing overfitting,  underfitting and validation accuracy.
7
Implementing batch normalization and dropout layer.
8
Training the model and observing both train accuracy and validation accuracy.
9
Updating the model with required changes


Report1
Functionalities Implemented
Planned stories
Completed stories
Planned Stories for next sprint
Collection of Data Set 
Collection of data images of both benign and malignant.
Data pre-processing
Importing data using open cv.
Importing Keras, Tensor flow packages and Training the model.
1,2,3,4,5
1,2,3,4,5
6,7,8,9


Report 2:
Functionalities Implemented
Planned stories
Completed stories
Planned Stories for next sprint
Observing overfitting,  underfitting and validation accuracy.
Implementing batch normalization and dropout layer.
Training the model and observing both train accuracy and validation accuracy.
Updating the model with required changes
6,7,8,9
6,7,8,9
none















Sample Run			 			
				

				
		
				
			
			 			
				
					

				
			
		
		
			
				
					

				
			
			 		
		
				
				
Conclusion and Future work:
					
In conclusion, it was determined from the above - mentioned observations that this model had attained a test accuracy of 77 percent, the highest one to date, and could thus be used for medical purposes to distinguish between malignant and benign skin cancers with ease. This aids medical professionals who struggle to differentiate between the two types of skin cancer. This study can assist doctors in spotting skin cancer and providing the right treatment to their patients. Without this initiative, the patient's health might go worse if the wrong prescription is used. So, this initiative is beneficial.
The project aimed to make it possible to access the model's programming code so that the programming expert may investigate it further. The capability to download the trained model and create business-level applications.

				
			
		



				
			
		


