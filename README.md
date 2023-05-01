Download Link: https://assignmentchef.com/product/solved-cind119-assignment-final-project
<br>
Your task in this project is to work with a team of data scientists and solve a problem based on a given dataset for an organization.  There are three datasets available for this project. These datasets are described at the end. You will have to choose <strong>only one </strong>of the dataset for analysis for your project. Your team will consist of up to a maximum of 2 students and each team will submit one project report. In your project, you will perform the following steps on the selected dataset:

<ol>

 <li>Data Preparation.</li>

 <li>Predictive Modeling/Classification:

  <ol>

   <li>Classification using Decision Tree.</li>

   <li>Classification using Naive Bayes.</li>

   <li>Compare the results of the 2 techniques on original and filtered data.</li>

  </ol></li>

 <li>Conclusions and Recommendations</li>

</ol>

Describe your results in your project report for each of the above steps. These steps are further explained in the sections below. You can use any tool of your choice for this project, such as SAS, Python, R, Weka, etc. <strong>Note that the final project report to be submitted will not include any information about code or the tools (specially no screenshots of tools) but the actual results and description of the analysis in the form of text, tables and charts</strong><strong>. </strong>

<h1>Data Preparation</h1>

The first and foremost step of data mining process is to understand the data and identify the research question(s).  Below are some suggestions to explore and understand datasets:

Look at the attribute type; e.g., nominal, ordinal or quantitative.

Find any missing values.

Find max, min, mean and standard deviation of attributes.

Determine any outlier values (records) for each of the attributes or attributes under consideration (min, max, std. dev, scatter plots, box plots or others can be used).

Analyze the distribution of numeric attributes (normal or other). Plot histograms for attributes of concern and analyze whether they have any influence on the class attribute.

Which attributes seem to be correlated? Which attributes seem to be most linked to the class attribute?.

Which attributes do you think can be eliminated or included in the analysis? This can be a subjective decision or an objective decision based on a statistical method.

Determine whether the dataset has an imbalanced class distribution (same proportion of records of different types or not) and do you need to balance the dataset.

Determine whether you need to handle missing values or transform any attributes (e.g., by normalizing the attributes, discretizing numeric attributes to categorical attributes, etc.).

<strong> </strong>

<strong>Note that it is not necessary to perform all of the above steps, you can decide to perform one or more steps as you deem appropriate.</strong> For example, if you judge that there are no outliers in a dataset then you do not need to apply any method to remove outliers. Similarly, if there are no missing values then there is no technique needed to fix them, or avoid any step that is too difficult to implement for you. Finally, describe your findings for data preparation in your report.




<h1>Predictive Modeling (Classification)</h1>

Apply the classification algorithms, Decision Tree and Naïve Bayes, which you studied in the course on your dataset after data preparation phase.

You will predict the class attribute by using each classification algorithm.

Determine the right strategy for dataset split: simple train-test set split, or 10-fold cross validation. <em>Choose only one strategy; e.g., train-test set split.</em>

Understand the output of your algorithms as much as possible; e.g., which attributes are used by decision tree to make the decision.

Determine your performance measures (accuracy, true positive, false positive, etc.).

Identify which algorithm performs well out of the two by using true positive, false positive and accuracy measure.




Describe results of predictive modeling in your report. Explain your interpretation of output of each of the algorithm in your report (e.g., explain decision tree). Explain how you determined the best performing algorithm.




<h2><strong>How to Compare Your Classification Models </strong></h2>




In order to evaluate and compare machine learning models with different features, a known approach is to create a baseline model first. This can be done by training a classification algorithm (e.g., decision tree) on the training set using the entire feature set (all attributes) and evaluating its performance using the selected metric (such as accuracy, true positive rate, and false positive rate) on the test set. Second, you need to train the same classification algorithm on your selected features and evaluate its performance on the validation set (or test set) using the same selected metrics as before. Similarly, you will repeat these two steps for the second classification algorithm—Naïve Bayes.  <strong>Finally, you would compare the performance of different trained models by using the selected metrics. </strong>This would give an indication whether your selected features (or parameters) have increased or decreased the performance of trained models.




<h1>Conclusion and Recommendations</h1>

State your major findings from different sections. State your recommendation to the company that they can put into place to solve their problem.




<h1>Tools</h1>




Two Python notebooks are attached with this project description. They will serve as a guide for you on how to analyze these datasets using Python. Two tutorials use two different types of Python packages to analyze data. Both tutorials are only tested using Google’s Colab, it is recommended to run them on Colab only. Upload the given notebook files (.ipynb) on Colab and start experimenting.

You can also use SAS of this data analysis using some of the labs we have provided you earlier in the course.

If you are taking other courses in this program, then R can be use as well.

You can also use GUI tools like Weka. Tutorial 2 uses its Python package. You can also use it by installing as a software application (https://www.youtube.com/watch?v=TF1yh5PKaqI)  In short, choice of tools is yours.

<strong> </strong>

<h1>Datasets</h1>

Select only one of the following datasets for your group and solve the problem for this company described for a particular dataset below.

<h2>Dataset for Churn</h2>

Customer churn or customer attrition means the loss of customers for a company.  The problem for customer churn is that the company would like to know in advance which customers would churn in near future. You are a member of a team of data scientists and the task of your team is to help this company in characterizing customer churn through data analytics methods. This dataset has 21 attributes including a binary class attribute about churn. The descriptions of the attributes are given below:




<ol>

 <li><strong>State:</strong> Customer’s state.</li>

 <li><strong>Account Length:</strong> Integer number showing the duration of activity for customer account.</li>

 <li><strong>Area Code: </strong>Area code of customer.</li>

 <li><strong>Phone Number: </strong>Phone number of customer.</li>

 <li><strong>Inter Plan: </strong>Binary indicator showing whether the customer has international calling plan.</li>

 <li><strong>VoiceMail Plan:</strong> Indicator of voice mail plan.</li>

 <li><strong>No of Vmail Mesgs: </strong>The number of voicemail messages.</li>

 <li><strong>Total Day Min:</strong> The number of minutes the customer used the service during day time (continuous quantitative data type).</li>

 <li><strong>Total Day Calls</strong>: Discrete attribute indicating the total number of calls during day time. <strong> Total Day Charge:</strong> Charges for using the service during day time (continuous data type).</li>

 <li><strong>Total Evening Min:</strong> The number of minutes the customer used the service during evening time.</li>

 <li><strong>Total Evening Calls:</strong> The number of calls during evening time.</li>

 <li><strong>Total Evening Charge:</strong> Charges for using the service during evening time.</li>

 <li><strong>Total Night Min:</strong> Number of minutes the customer used the service during night time.</li>

 <li><strong>Total Night Calls: T</strong>he number of calls during night time.</li>

 <li><strong>Total Night Charge:</strong> Charges for using the service during night time.</li>

 <li><strong>Total Int Min:</strong> Number of minutes the customer used the service to make international calls.</li>

 <li><strong>Total Int Calls: </strong>The number of international calls.</li>

 <li><strong>Total Int Charge:</strong> Charges for international calls.</li>

 <li><strong>No of Calls Customer Service:</strong> The number of calls to customer support service.</li>

 <li><strong>Churn:</strong> Class attribute with binary values (True for churn and False for not churn).</li>

</ol>




<h2>Bank Marketing Dataset</h2>

This dataset refers to the problem of telemarketing for a bank. The dataset is collected from a Portuguese bank and the bank wants to have an effective telemarketing strategy to sell long-term deposit accounts (e.g., bonds, saving accounts, etc.).  These marketing campaigns were based on phone calls and multiple contacts were often needed to determine whether a customer would subscribe to a long-term deposit account. Your team of data scientists will help this bank in  determining such customers and devising an effective telemarketing strategy by applying data analytics method on the given dataset.







<ul>

 <li><strong>– Age:</strong> Age of the customer (numeric).</li>

 <li><strong>– Job: </strong>Type of job (qualitative).</li>

 <li><strong>– Marital:</strong> Marital status (qualitative).</li>

 <li><strong>– Education:</strong> Education of the customer (qualitative).</li>

 <li><strong>– Default:</strong> Shows whether the customer has credit in default or not (qualitative).</li>

 <li><strong>– Balance:</strong> Average yearly balance in Euros (numeric).</li>

 <li><strong>– Housing:</strong> Shows whether the customer has housing loan or not (qualitative).</li>

 <li><strong>– Loan:</strong> Shows whether the customer has personal loan or not (qualitative/categorical).</li>

 <li><strong>– Contact:</strong> Shows how the last contact for marketing campaign has been made (qualitative)</li>

 <li><strong>– Day: </strong>Shows on which day of the month last time customer was contacted (numeric).</li>

 <li><strong>– Month:</strong> Shows on which month of the year last time customer was contacted (qualitative).</li>

 <li><strong>– Duration:</strong> Shows the last contact duration in seconds (numeric).</li>

 <li><strong>– Campaign:</strong> Number of contacts performed during the marketing campaign and for this customer (numeric).</li>

 <li><strong>– Pdays:</strong> Number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted). <strong>15 – Previous:</strong> Number of contacts performed before this campaign and for this client (numeric).</li>

 <li><strong>– Poutcome: </strong>Outcome of the previous marketing campaign (qualitative).</li>

 <li><strong>– Y</strong> – Class attribute showing whether the client has subscribed a term deposit or not (binary: “yes”,”no”)</li>

</ul>




<h2>Credit Card Dataset</h2>




In order to provide loans to customers, a bank needs to make right decision in determining who should get the approval and who should not.  This dataset is the German Credit Data  that contains  20 attributes and the class attribute showing a good or a bad credit risk.  Your team of data scientists will need to  develop  a data analytics based strategy for the  bank managers  that can help them in making a decision about loan approval for the  prospective applicants/customers.







<ol>

 <li><strong>Creditability: </strong>The class attribute (qualitative)showing whether the credit rating is good or</li>

 <li><strong>Account Balance: </strong>Checking account status (1: &lt; 0 DM, 2: 0&lt;=…&lt;200 DM, 2 &gt; 200 DM, 4: No checking account), where DM= Deutsche Mark (qualitative attribute).</li>

 <li><strong>Duration of Credit (month):</strong> Duration of credit in months (numerical)</li>

 <li><strong>Payment Status of Previous Credit: </strong>Credit history (qualitative) 0: no credits taken, 1: all credits at this bank paid back   duly, 2: existing credits paid back duly till now, 3: delay in                      paying off in the past,  4:  critical account.</li>

 <li><strong>Purpose: </strong>Qualitative attribute showing the purpose of the loan (0: New car, 1: Used car , 2:</li>

</ol>

Furniture/Equipment, 3: Radio/Television, 4: Domestic Appliances  , 5: Repairs ,6: Education ,7: Vacation, 8: Retraining ,9: Business, 10: Others)

<ol start="6">

 <li><strong>Credit Amount: </strong>Numerical value showing the credit amount</li>

 <li><strong>Value Savings/Stocks: </strong>Qualitative attribute showing average balance in savings and stocks (1 : &lt; 100 DM, 2: 100&lt;= … &lt; 500 DM, 3 : 500&lt;= … &lt; 1000 DM, 4 : =&gt;1000 DM, 5:   unknown/ no savings account)</li>

 <li><strong>Length of current employment: </strong>Qualitative attribute showing length of employment (1 : unemployed, 2: &lt; 1 year, 3: 1&lt;=…&lt;4 years, 4: 4&lt;=…&lt;7 years, 5:&gt;=7years).</li>

 <li><strong>Instalment percent: </strong>Installment rate in percentage of disposable income (numerical) <strong> Sex &amp; Marital Status: </strong>Qualitative attribute showing gender and marital status (1: male :</li>

</ol>

divorced/separated, 2: female : divorced/separated/married, 3 : male: single, 4: male   :

married/widowed, 5 : female : single)




<ol start="11">

 <li><strong>Guarantors: </strong>(Qualitative) Guarantors and co-applicants: (1 : none, 2 : co-applicant, 3 :</li>

</ol>

guarantor)

<ol start="12">

 <li><strong>Duration in Current address: </strong>Qualitative value showing the duration in current address (1: &lt;= 1 year, 1&lt;…&lt;=2 years, 2&lt;…&lt;=3 years,  3:&gt;4years)</li>

 <li><strong>Most valuable available asset: </strong>Qualitative attribute showing valuable assets ( 1 : real estate 2 : savings agreement/ life insurance, 3 : car or other, 4 : unknown / no property)</li>

 <li><strong>Age (years): </strong>Numerical value showing age in years.</li>

 <li><strong>Concurrent Credits: </strong>Installment plans ( 1 : bank,  2 : stores, 3 : none )</li>

 <li><strong>Type of apartment: </strong>Type of housing ( 1 : rent, 2 : own, 3 : for free)</li>

 <li><strong>No of Credits at this Bank: </strong>Numerical value showing number of existing credits at the bank</li>

 <li><strong>Occupation: </strong>Job (Qualitative) (1 : unemployed/ unskilled – non-resident,  2 : unskilled – resident,</li>

</ol>

3 : skilled employee / official,  4 : management/ self-employed/highly qualified employee/ officer)

<ol start="19">

 <li><strong>No of dependents: </strong>Numerical value showing number of dependents</li>

 <li><strong>Telephone: </strong>Qualitative attribute for telephone number (1: yes, 2: No)</li>

 <li><strong>Foreign Worker: </strong>Qualitative attribute showing whether the person is the foreign worker or not (1:</li>

</ol>

yes , 2: no)