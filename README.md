# Stroke Analysis

**Background**: According to the CDC (https://www.cdc.gov/stroke/facts.htm), 1 in 6 cardiovascular disease related deaths are due to stroke. Someone dies of stroke every 4 minutes, and billions are spent on health care costs related to stroke each year. 

Our goal was to create a machine learning model that would predict the likelihood of stroke based on a given set of parameters, including known risk factors. We used the stroke prediction dataset from Kaggle (https://www.kaggle.com/fedesoriano/stroke-prediction-dataset) to examine possible models. Using pandas in jupyter notebooks, we evaluated the following models: KNN, Random Forest, Logistic Regression, SVM, Decision Tree, Gaussian Naive Bayes, Neural Networks, and Gradient Boosting. Jupyter notebooks for each model can be referenced, as the names of the model correspond with what was examined inside of the notebook. We ultimately selected the Gaussian Naive Bayes model as our best performing model (GaussianNaiveBayes_FinalModel.ipynb).

A tableau dashboard with a predictive questionnaire was created based on our dataset and model (StrokProdiction.twbx). This connects to our Gaussian Naive Bayes Final Model jupyter notebook via a Tabpy server.

Instructions:
1. Start Tabpy server(Use the command *pip install tabpy-server* in the command prompt to install the Tabpy and then type *Tabpy* to start the server)
2. Start Jupyter notebook and run the GaussianNaiveBayes_FinalModel.ipynb, which is the jupyter notebook with the final model.
3. Open up the Tableau workbook in Tableau Desktop and make sure you navigate to 

Help -->  Setting and Performance ---> Manage External Service Conenction
Type in the server as localhost and and port as 9004 and that is it, Tabpy is configured and you should able to run the predictive questionnaire dashboard



