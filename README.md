# Sleep-Apnea-Detection

Sleep apnea is a potentially serious sleep disorder in which breathing repeatedly stops and starts. If you snore loudly and feel tired even after a full night's sleep, you might have sleep apnea 
The main Types of Sleep Apnea
 <li>Obstructive sleep apnea:- the more common form that occurs when throat muscles relax.</li>
 <li>Central sleep apnea:- which occurs when your brain doesn't send proper signals to the muscles that control breathing.</li>
 <li>Complex sleep apnea syndrome:-which occurs when someone has both obstructive sleep apnea and central sleep apnea.</li>

<h1>PROBLEM STATEMENT</h1>
Detecting Sleep Apnea from raw physiological signals.
Building a model to automatically detect sleep apnea events from PSG data.

<h1>Methodologies Adopted</h1>
<li>Based on our literature survey we can see that thoracic, abdominal, SPO2, PPG(cardiac activity) and airflow signals were good parameters for the identification of occurrence of sleep apnea.</li>
<li>We are a 3-layer CNN with two ConvPool layers with a downsampling factor 10 followed by a convolutional layer. The model is trained on all the signal.</li>
<li>We have used Our Custom model for Training </li>
 <li>70% of the training set is used for training, the remaining 30% are used for model validation.</li>
 
 <h1>Results</h1>
 
 ![Screenshot 2022-06-08 at 9 09 27 PM](https://user-images.githubusercontent.com/91361896/172658975-f88b87ac-3b08-44f9-b8db-61a60c664225.png)

<h2>Tags</h2>
#sleepApnea #dreem #MachineLearning 
