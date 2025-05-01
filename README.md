I led the committee of 4 students in our Data Science I class to design, preprocess, test and implement a machine learning competition to predict a binary classification of "Academic Achievement" for our entire class of 108 students.

The 3 additional students on the committee were Allen Martin, Dhanush Kumar and Saptarshi De.

I performed the mock-run through of the competition that was used in grading students' submissions, and was the point of contact between our teacher Dr. Rizk, the TA's Rohan and Rounak, the rest of the committee, and the rest of the students in the class.
I also designed the competition template from scratch, modifying it later with highly involved contributions from Allen Martin, and I also was responsible for selecting the dataset that we used in the competition.
I performed preprocessing to the degree that the data was (mostly) ready to use for students: only requiring additional preprocessing of dropping of a single column, converting a single categorical variable, and imputation of 2 columns with missing values (and later scaling of the data).

The competition allowed students to select 2 from the following to performing binary classification: Support Vector Machines, Neural Networks and Random Forest.

Students were asked to not only write the necessary code, but also evaluate model performance through markdown cells in Jupyter.
Students grades in the competition were determined both by the accuracy of their best model as well as the length of time before their submission.


[Initially, the competition was going to predict mental health outcomes based on factors such as physical activity level, substance abuse, dietary habits and more. However, it became clear the data was synthetic when the heatmap revealed substance abuse and physical activity were the least correlated of all variables with the target of mental health disorder. Synthetic data does not mean it is inherently an issue, but given 1.) we could not determine how the synthetic data was arrived at, even by reaching out to the Kaggle author and 2.) the data firmly contradicted a large swath of literature about mental health, we decided not to select such a delicate subject if the conclusions students would reach could not be explained.]


