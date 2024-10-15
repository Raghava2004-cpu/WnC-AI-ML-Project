# Raghava2004-cpu-WnC-AI-ML-Project
Roll No : 2304077 
Name : Raghava Ashok Vanapalli
Email Id : vanapallia.ug23.ec@nitp.ac.in

I'm from 2nd Year .. Still I didn't completed the Deep Learning . Currently I was Learning Ml .So I developed a model to recognize the numbers of MNIST data set using
the Logistic Regression ..

<h2>🚀 Project Steps</h2>
<ul>
  <li>📥 Fetching the MNIST Dataset</li>
  <li>🖼 Visualizing a Sample Digit</li>
  <li>⚙️ Preparing the Data for Training</li>
  <li>🔧 Building the Logistic Regression Model</li>
  <li>📊 Model Evaluation</li>
  <li>🔍 Model Insights</li>
</ul>






MNIST Dataset Classification with Logistic Regression
This project demonstrates the classification of the MNIST dataset (a large dataset of handwritten digits) using Logistic Regression. The goal is to classify digits (0-9) using machine learning techniques. I used scikit-learn, pandas, numpy, matplotlib, and seaborn to implement and visualize the results.

Importing Libraries.
The necessary libraries for data manipulation, visualization, and model building are imported.
<h2>Libraries Used</h2>

<p>
  <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python" style="width:60px; height:60px;"/>
  <img src="https://pandas.pydata.org/static/img/pandas_mark.svg" alt="Pandas" style="width🈯0px; height:60px;"/>
  <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="Seaborn" style="width🈯0px; height:50px;"/>
  <img src="https://matplotlib.org/_static/images/logo2.svg" alt="Matplotlib" style="width🈴0px; height:40px;"/>
  <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" alt="Scikit-learn" style="width🈯0px; height:40px;"/>
  <img src="https://numpy.org/images/logo.svg" alt="Numpy" style="width🈶0px; height:40px;"/>
</p>

<h2>Project Steps</h2>

<ol>
    <li>
        <strong>Fetching the MNIST Dataset:</strong>
        <p>I use the <code>fetch_openml()</code> function from <code>sklearn.datasets</code> to load the MNIST dataset. It is then converted into a pandas DataFrame for easy manipulation.</p>
    </li>
    <li>
        <strong>Visualizing a Sample Digit:</strong>
        <p>One of the images (in this case, the 56th image) is reshaped into a 28x28 grid and displayed using <code>matplotlib</code>.</p>
    </li>
    <li>
        <strong>Preparing the Data for Training:</strong>
        <p>The first 6000 samples are taken from the dataset and split into features (<code>x</code>) and labels (<code>y</code>), then further divided into training and test sets. I used only 6000 because actual MNIST dataset contain 70000 samples it was taking more time to train the model.</p>
    </li>
    <li>
        <strong>Building the Logistic Regression Model:</strong>
        <p>A Logistic Regression model is created using the multinomial approach and trained on the dataset.</p>
    </li>
    <li>
        <strong>Model Evaluation:</strong>
        <p>The model is evaluated using the test data, and accuracy score, confusion matrix, and classification report are generated.</p>
    </li>
    <li>
        <strong>Model Insights:</strong>
        <p>The model's intercepts and coefficients for a particular digit (like '1') are examined.</p>
    </li>
</ol>



<h2>Sample Output</h2>
<p>Below is an example of a digit from the MNIST dataset being visualized and classified:</p>
<img src="https://github.com/Raghava2004-cpu/PROJECTFILES/blob/e77e3d483cadc98e70ffd03419bedf4633ee93b7/Screenshot%202024-10-15%20200029.png" alt="Sample MNIST Digit Output" style="width:50%; height:auto;"/>


 

