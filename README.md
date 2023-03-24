## This is our submission for the event Brain Dead, an event of Revelation'23. Revelation'23 is the offcial technical fest of the Department of Computer Science and Technology, IIEST Shibpur.<br/> 
## Here, we've solved two problems:<br/> 
  Problem Statement 1 : Analyze Placement Data<br/> 
  Problem Statement 2 : Detecting Emotional Sentiment in Cartoons<br/> 

## Please download the notebooks to view its contents as there is an issue with viewing Colab Notebooks on the GitHub website. But downloading works fine.

## Problem Statement 1 : Analyze Placement Data<br/> 

**Challenge Description:**

In this challenge, you are supposed to analyze the placement records of the students of a MBA college.

The dataset includes secondary and higher secondary school percentages and specializations. It also contains degree specialization, work experience, and the salary offered to the students. Your main task is to analyze the factors that affect the placement and salary of students.

Analyze the dataset and derive meaningful insights from the data.

Here are some examples that you might consider for your analysis:
- What are the factors affecting the placement of a student?
- Which degree specializations are in high demand in the industry?
- Does mba percentage matter in placement?

Present your analysis in a report. You can use charts, tables, and graphs to elaborate your analysis. **You are not required to create any prediction model for this problem statement.**

**Dataset Link:**

<a href="https://www.kaggle.com/datasets/revelation2k23/brain-dead-placement-data">Placement Data <sup>*</sup></a>

**Dataset Description:**

The dataset has 215 rows and 15 columns. Each row represents a student and his/her/their corresponding data.

The columns and their description: <br/>
:point_right:  **sl_no:** 		 Serial Number <br/>
:point_right: **gender:** 		Gender- Male='M',Female='F' <br/>
:point_right: **ssc_p:** 		Secondary Education percentage- 10th Grade <br/>
:point_right: **ssc_b:** 		Board of Education- Central/ Others <br/>
:point_right: **hsc_p:** 		Higher Secondary Education percentage- 12th Grade <br/>
:point_right: **hsc_b:** 		Board of Education- Central/ Others <br/>
:point_right: **hsc_s:** 		Specialization in Higher Secondary Education <br/>
:point_right: **degree_p:** 		Degree Percentage <br/>
:point_right: **degree_t:** 		Under-Graduation(Degree type)- Field of degree education <br/> 
:point_right: **workex:** 		Work Experience <br/>
:point_right: **etest_p:** 		Employability test percentage ( conducted by the college) <br/>
:point_right: **specialisation:** 	Post Graduation(MBA)- Specialization <br/>
:point_right: **mba_p:** 		MBA percentage <br/>
:point_right: **status:** 		Status of placement- Placed/Not placed <br/>
:point_right: **salary:** 		Salary offered by corporate to candidates <br/>

**If after downloading the dataset, there are only 10 columns, then select the drop-down marked with red in the figure below, and apply "Select All".**
![select-all](https://user-images.githubusercontent.com/128146627/226792332-9fa6a207-abdf-468b-9f73-b4f7617f0c69.png)


**Tools used for analysis:**

You are free to use any tool of your choice.
But preferred tools include:
- MS Excel
- Tableau/ PowerBI, etc
- Jupyter Notebook/ Google Colab, Matplotlib.


**Deliverables:**

A complete report of the methodology employed in your work.  The report should be concise. This report might include references, tables, figures, and results. The file format should be either a ppt or a pdf. If you are using tools like Excel, also mention the excel formulas that you used for the analysis.

**Marking criteria:**

Some of the metrics our team will use for evaluating your reports include:
- Writing Style, references, figures, etc. 
- Dataset exploration 
- Methods 
- Results of analysis 
- Discussion 

---


## Problem Statement 2: Detecting Emotional Sentiment in Cartoons

**Challenge Description:**

Social media platforms are widely used by individuals and organizations to express emotions, opinions, and ideas. These platforms generate vast amounts of data, which can be analyzed to gain insights into user behavior, preferences, and sentiment. Accurately classifying the sentiment of social media posts can provide valuable insights for businesses, individuals, and organizations to make informed decisions. 

To accomplish this task, a customized private cartoon dataset (original images) of social media posts has been provided, which contains labels for each post's emotion category, such as happy, angry, sad, or neutral.  

The task is to build and fine-tune a machine-learning model that accurately classifies social media posts into their corresponding emotion categories, using synthetic images. 

To achieve this, the following steps are required: <br/>
:star: Generate synthetic images using any image generation techniques (e.g., GAN, Diffusion Models, Autoencoder Decoder) to augment the dataset and increase its size. <br/>
:star: So for example, we use the images in the category of "happy" to synthetically generate similar images. Repeat the same for each category. <br/>
:star: Use the original and synthetic images to build a machine-learning model that accurately classifies social media posts into their corresponding emotion categories. <br/>
:star: Evaluate the performance of the model using appropriate metrics such as accuracy, precision, recall, and F1-score. <br/>
:star: Compare the performance of the model when trained on the original dataset only, the synthetic dataset only, and the combination of both. <br/>
:star: Analyze the results to determine the effectiveness of using synthetic images for improving classification accuracy. <br/>


The dataset consists of a diverse range of cropped cartoon face images. The data has been pre-processed and cleaned, but you can apply additional data cleaning or pre-processing techniques if necessary. You can use any machine learning or deep learning algorithm or technique of your choice to build and finetune your model, as long as it can accurately classify the posts into their corresponding emotion categories. 

Based on a previous study, The performance accuracy of the best classification algorithms for emotion detection is 0.906. Your goal is to beat this using your models, but your model should not be overfitting or underfitting.

To evaluate the performance of your model, you will be using standard evaluation metrics such as accuracy, precision, recall, F1 score, and confusion matrix. The submission with the highest evaluation score will be declared the winner. The top submissions will also be invited to present their solutions and insights to the community.

**Dataset Link:**

<a href="https://www.kaggle.com/datasets/revelation2k23/brain-dead-emotion-detection"> Emotion Data <sup>*</sup></a>


