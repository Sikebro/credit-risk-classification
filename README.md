# credit-risk-classification
module 20 challenge

<h2>Background</h2>
<p>In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.</p>

<h2>Instructions</h2>
The instructions for this Challenge are divided into the following subsections:
<ul>
<li>Split the Data into Training and Testing Sets</li>
<li>Create a Logistic Regression Model with the Original Data</li>
<li>Write a Credit Risk Analysis Report</li>
</ul>

<h2>Split the Data into Training and Testing Sets</h2>
Open the starter code notebook and use it to complete the following steps:
<ol>
<li>Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.</li>
<li>Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.</li>
<li>Split the data into training and testing datasets by using train_test_split.</li>
</ol>

<h2>Create a Logistic Regression Model with the Original Data</h2>
Use your knowledge of logistic regression to complete the following steps:
<ol>
<li>Fit a logistic regression model by using the training data (X_train and y_train).</li>
<li>Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.</li>
<li>Evaluate the model’s performance by doing the following:</li>
<ul>
<li>Generate a confusion matrix.</li>
<li>Print the classification report.</li>  
</ul>
<li>Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?</li>
</ol>

<h2>Write a Credit Risk Analysis Report</h2>
<p>Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.
Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:</p>
<ol>
<li><strong>An overview of the analysis:</strong> Explain the purpose of this analysis.</li>
<li><strong>The results:</strong> Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.</li>
<li><strong>A summary:</strong> Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.</li>
</ol>

<h1>Credit Risk Analysis Report</h1>
