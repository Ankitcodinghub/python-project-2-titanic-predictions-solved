# python-project-2-titanic-predictions-solved
**TO GET THIS SOLUTION VISIT:** [Python Project 2-Titanic Predictions Solved](https://www.ankitcodinghub.com/product/python-project-2-titanic-predictions-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94240&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Python Project 2-Titanic Predictions Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Training from Disaster – This assignment will use the data from the Kaggle Titanic competition:

https://www.kaggle.com/c/titanic/overview

The goal is to be able to predict whether a passenger is likely to survive the Titanic or not.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
To do this exercise, we will have to do data cleaning to prepare the data. This means you may

</div>
</div>
<div class="layoutArea">
<div class="column">
have to create a variety of variables to help learn to predict whether a given passenger on the

</div>
</div>
<div class="layoutArea">
<div class="column">
Titanic was able to survive. There is a ton out on the web (including here) about this dataset, as

</div>
</div>
<div class="layoutArea">
<div class="column">
it’s popular among those just coming up to speed on machine learning classification models.

</div>
</div>
<div class="layoutArea">
<div class="column">
After satisfying the project requirements, feel free to play around and use what you learned in

</div>
</div>
<div class="layoutArea">
<div class="column">
class to join the Kaggle competition!

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Project requirements:

1. Download the titanic data from Blackboard. 2. Below is the data dictionary for the data. Variable Definition Key

</div>
</div>
<div class="layoutArea">
<div class="column">
survival

pclass

sex

Age

sibsp

parch

ticket

fare

cabin

embarked Port of Embarkation C = Cherbourg (France), Q = Queenstown (Ireland), S = Southampton (England)

</div>
</div>
<div class="layoutArea">
<div class="column">
Survival 0 = No, 1 = Yes

Ticket class 1 = 1st, 2 = 2nd, 3 = 3rd Sex

Age in years

# of siblings / spouses aboard the Titanic # of parents / children aboard the Titanic Ticket number

Passenger fare

Cabin number

</div>
</div>
<div class="layoutArea">
<div class="column">
3. Look at the data and see if there are any summary statistics that might give you some insights.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4. Data Cleaning and Feature Engineering

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Sadly sci-kit learn will only let use numeric or boolean variables for analysis, so let’s transform some of our variables to address that.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
<ul>
<li>Create booleans for each of the embarkment points.</li>
<li>Create a boolean for is male.</li>
<li>Create a boolean for whether someone has a cabin.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
You may want to use One Hot Encoding for this.

Moreover, some of our ages are missing, so let’s enter the missing values as 100 for now.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Some other feature engineering that you may want to perform can be found in this tutorial:

<a href="https://triangleinequality.wordpress.com/2013/09/08/basic-feature-engineering-with-the-titanic-data/">Basic Feature Engineering with the Titanic&nbsp;Data</a>

5. Creating an accurate model:

We have studied many ways to analyze data this semester. The titanic data is a classification problem.

<ul>
<li>Divide the data into a training set and a test set.</li>
<li>Pick three classification algorithms. Build a model for each of these methods.</li>
<li>Train your algorithm on the training set. Test the model’s accuracy on the test set</li>
<li>Look at the accuracy metrics (as discussed in class) for each algorithm
Can you improve the model?
</li>
</ul>
<ul>
<li>Use regularization and/or ensemble methods to see if you can improve the accuracy of your
model
</li>
<li>Use cross validation to see if that can improve the accuracy of the model.
Visualization – For the methods that you are able to show visualizations (i.e. decision trees), include these in your report.

Hand in: All python code.

An in depth analysis of your methodology that includes: Why you chose the model.

Which models were more accurate?

How did you determine accuracy?

Methods to improve accuracy.

How did you test your model?

And anything else….

You will be graded on the completeness of your analysis. Think in terms of your company boss handing you a dataset and asking for an analysis of company performance. What would you need to say to keep your job???

*****Extra Credit (add 3 percentage points to your grade!! I asked you to apply three different machine learning algorithms to create a model for this dataset. Explain your process, with code, in a Jupyter notebook.

/
</li>
</ul>
</div>
</div>
</div>
