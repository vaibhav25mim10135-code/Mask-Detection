# Mask-Detection😷
## This program helps to detect whether a person is wearing a 😷 mask or not.
### Features:-
*  Face Detection & Classification: Identifies human faces in video streams and classifies them into categories such as mask or nomask.
*  Real-Time Processing: Provides instant detection and feedback, often integrated with surveillance systems for continuous monitoring.
### Tools/Technology used:-
* Google Colab
* Anaconda Prompt
* Python(.py/.ipynb)
### Steps to install:-
* Install dataset the custom dataset on yolo-11s that i have created through label studio , dataset is named as 📁 data.zip.
* Open Google Colab and open a new notebook
* If you have nvidia gpu then execute the first code in colab
* Upload the data.zip file in google colab <img width="1918" height="1078" alt="img2" src="https://github.com/user-attachments/assets/3253a5bd-9950-4382-84f4-06bf049ae01a" />
* Unzip the data.zip with given code 
* Split the images in training and validation
* Install ultralytics
* Configure training
* Train model  <img width="1915" height="915" alt="train" src="https://github.com/user-attachments/assets/64bb0a13-b7be-4eb0-bb29-a1b1ba736490" />
* Test model  <img width="1915" height="922" alt="train2" src="https://github.com/user-attachments/assets/faf3035b-f58e-4379-934a-3c79c5139b0f" /> <img width="1918" height="1078" alt="Screenshot 2025-11-23 184843" src="https://github.com/user-attachments/assets/977b7218-c022-4ff4-84d2-7602fedef39d" />
* Deploy Model
* Download your model  <img width="1918" height="1078" alt="Screenshot 2025-11-23 185127" src="https://github.com/user-attachments/assets/e2dfaa47-327c-4051-9458-2eebe3f675f5" />  <img width="1918" height="692" alt="Screenshot 2025-11-23 185550" src="https://github.com/user-attachments/assets/710dd9f3-a641-4bd9-a1b8-92c5f2df606f" />
* Save the model.zip and extract it in a folder.

### Run the project:-
* Extract the model.zip file  in a folder.
* Install anaconda distribution installer and after installation open anaconda prompt
* Create a new python environment <img width="1490" height="757" alt="Screenshot 2025-11-23 190636" src="https://github.com/user-attachments/assets/a2339909-bb56-4d6c-bff6-94d92e0931eb" />
* Activate the python environment that you have created.
* If you have nvidia gpu then you can install Gpu-enabled pytorch by executing given code , this will take few minutes to install.
* Copy the location of the folder where model.zip has been installed. <img width="1918" height="1078" alt="img3" src="https://github.com/user-attachments/assets/9e65881f-b1a2-4a79-9a8a-0282ed19388e" />
* Using cd command with directory location to move to the given directory.
* Download yolo_detect.py from my github respositry : https://github.com/vaibhav25mim10135-code/Mask-Detection.git
* Move yolo_detect.py into folder you extracted model.zip
* Execute the model using code given based on items you are present with like images , video or live streaming devices. <img width="1917" height="1078" alt="img4" src="https://github.com/user-attachments/assets/3c12a049-9502-4d1d-8e3a-eb7b98e828e6" />

### Instruction for testing
*  Make sure setup enviorments and download & install anaconda prompt is done properly.
*  You may create your own dataset from label-studio just like me.<img width="1918" height="1078" alt="Screenshot 2025-11-22 094748" src="https://github.com/user-attachments/assets/a0c95966-cd03-4c47-a2ca-29cc77ae57a5" />
*  Make sure to follow all steps.
*  For more details you can see Proper_Mask.ipynb file.






