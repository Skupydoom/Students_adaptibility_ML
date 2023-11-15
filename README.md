# Problem description:  
&emsp;A wide variety of educational courses are available on the Internet. Their popularity has increased significantly since the pandemic. Some are free, others have to be paid for. Short-term courses are acceptable, but there are also whole university programmes that last several years. These programmes can be quite expensive because the instructors have invested a lot of time in them. They require considerable effort on the part of the students.  
&emsp;Both the organizers of these programmes and the participants consider it unprofitable if students drop out in the middle of the course. It would be useful to assess a person's ability to complete a course on the basis of certain personal information. For example, one of the options could be a pre-course survey before payment. Several possible actions could be taken afterwards:
- Warn participants in advance if the course may be difficult for them;
- Enroll participants in a special group that receives special attention in terms of education. This may increase the likelihood of them completing the course;
- Offer a shortened or free demo version of the course before proceeding to the main programme.

# Dataset
&emsp;Here is a dataset containing personal information about online students. The goal is to predict their level of adaptability or, in other words, the likelihood of successfully completing of the course. The machine learning model should give a good result.  
&emsp;The dataset contains 13 descriptive columns and one target column, as follows:
1) "Gender": gender type;
2) "Age": age range of the student;
3) "Education Level" level of an educational institution;
4) "Institution Type": type of educational institution;
5) "IT Student": does a person study as an IT student;
6) "Location": is student location in town;
7) "Load-shedding": load reset level;
8) "Financial Condition": financial condition of family;
9) "Internet Type": type of network connection;
10) "Network Type": type of Internet used primarily in device;
11) "Class Duration": Daily class duration;
12) "Self Lms": institution’s own LMS availability;
13) "Device": device used primarily in classroom;

&emsp;Target column:
- "Adaptivity Level": the level of adaptability of the student.

The dataset is available on Kaggle.com: https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education/data  
The original research paper:  
Students' Adaptability Level Prediction in Online Education using Machine Learning Approaches or DOI: **10.1109/ICCCNT51525.2021.9579741**  

# The structure of the repo 
- A Jupyter notebook file "data_analysis.ipynb" with a comprehensive analysis of the data;
- The dataset "students_adaptability_level_online_education.csv";
- A script "train.py" that trains the final model and saves it to the binary file.
- ...
