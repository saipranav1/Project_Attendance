Welcome D Sai Pranav !!
![Project Logo](https://user-images.githubusercontent.com/48133426/116291303-0a138200-a7b2-11eb-963c-5ead9628ec90.jpg)
This project involves building an attendance system which utilizes facial recognition to mark the presence, time-in, and time-out of employees. It covers areas such as facial detection, alignment, and recognition, along with the development of a web application to cater to various use cases of the system such as registration of new employees, addition of photos to the training dataset, viewing attendance reports, etc. This project intends to serve as an efficient substitute for traditional manual attendance systems. It can be used in corporate offices, schools, and organizations where security is essential.

This project aims to automate the traditional attendance system where the attendance is marked manually. It also enables an organization to maintain its records like in-time, out time, break time and attendance digitally. Digitalization of the system would also help in better visualization of the data using graphs to display the no. of employees present today, total work hours of each employee and their break time. Its added features serve as an efficient upgrade and replacement over the traditional attendance system.

## Scope of the project 🚀
Facial recognition is becoming more prominent in our society. It has made major progress in the field of security. It is a very effective tool that can help low enforcers to recognize criminals and software companies are leveraging the technology to help users access the technology. This technology can be further developed to be used in other avenues such as ATMs, accessing confidential files, or other sensitive materials.
This project servers as a foundation for future projects based on facial detection and recognition. This project also convers web development and database management with a user-friendly UI. Using this system any corporate offices, school and organization can replace their traditional way of maintaining attendance of the employees and can also generate their availability(presence) report throughout the month.

**The system mainly works around 2 types of users**
1. Employee
2. Admin

**Following functionalities can be performed by the admin: <br>**
• Login <br>
• Register new employees to the system <br>
• Add employee photos to the training data set <br>
• Train the model <br>
• View attendance report of all employees. Attendance can be filtered by date or employee. <br>

**Following functionalities can be performed by the employee: <br>**
• Login <br>
• Mark his/her time-in and time-out by scanning their face <br>
• View attendance report of self <br>

## Face Detection
Dlib's HOG facial detector.

## Facial Landmark Detection
Dlib's 68 point shape predictor

## Extraction of Facial Embeddings
face_recognition by Adam Geitgey

## Classification of Unknown Embedding 
using a Linear SVM (scikit-learn)

## Documentation 📰
[This](https://github.com/saipranav1/Project_Attendance/tree/master/Documentation) folder contains all the related documents with UML Diagrams. 
 
## How To Run ?
- clone it on your computer
- make a separate [python virtual environment](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) or use the default one already installed on your machine
- Download [this](https://drive.google.com/uc?export=download&id=1HzO-rnEqgkZ6tLt48yWhYgHk1_zOIYhf) file 
 - put it inside **``` \Attendance-System-Using-Face-Recognition\face_recognition_data ```** directory
- run **``` pip install -r requirements.txt inside \Attendance-System-Using-Face-Recognition ```** directory
- Run **``` python manage.py runserver ```** inside **``` \Attendance-System-Using-Face-Recognition ```** directory to run the project
- Enjoy !

## UI 💻
<img width="1920" height="1080" alt="Screenshot (323)" src="https://github.com/user-attachments/assets/625cf008-3aca-460b-a545-36807689b4b2" /><img width="1920" height="965" alt="Screenshot 2022-11-15 181546" src="https://github.com/user-attachments/assets/9afdc025-d9ab-46ce-900a-5a88b6c980a5" /><img width="1920" height="1080" alt="Screenshot (341)" src="https://github.com/user-attachments/assets/add77f57-0909-4b7e-8df7-0578ac160acf" />
<img width="1920" height="1080" alt="Screenshot (336)" src="https://github.com/user-attachments/assets/62096e97-24c3-46d5-8c3d-167f8e0fb335" />
<img width="1920" height="688" alt="Screenshot 2022-11-15 182246" src="https://github.com/user-attachments/assets/f5657778-675b-4d1d-87a6-907c05216e49" />
<img width="1920" height="1080" alt="Screenshot (333)" src="https://github.com/user-attachments/assets/537f0762-151a-4ced-a593-b0f12a4ebe89" />

<img width="1920" height="690" alt="Screenshot 2022-11-15 at 12-30-26 Screenshot" src="https://github.com/user-attachments/assets/bc7d06bd-9d41-4d3f-84f4-e10c3d44aed3" />
<img width="1920" height="1080" alt="Screenshot (325)" src="https://github.com/user-attachments/assets/8c3337aa-eb25-4ab4-8307-ecee7d3415ed" />
<img width="1920" height="1080" alt="Screenshot (324)" src="https://github.com/user-attachments/assets/cb5de0c0-d432-4983-b7c8-403d7288180b" />



 

## Thank You
- Author : [D Sai Pranav](https://github.com/saipranav1)
