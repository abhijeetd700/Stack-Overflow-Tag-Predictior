# Stack-Overflow-Tag-Predictior

**All the relevant CODE & conclusions is available in ipynb notebook**<br/>

**Description:-**
Stack Overflow is the largest, most trusted online community for developers to learn, share their programming knowledge, and build their careers.<br/>
Stack Overflow is something which every programmer use one way or another. Each month, over 50 million developers come to Stack Overflow to learn, share their knowledge, and build their careers. It features questions and answers on a wide range of topics in computer programming.The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers in a fashion similar to a wiki or Digg.<br/>
 Based on the type of tags assigned to questions, the top eight most discussed topics on the site are: Java, JavaScript, C#, PHP, Android, jQuery, Python and HTML.

**Problem Statement:-**<br>
Suggest the tags based on the content that was there in the question posted on Stackoverflow.<br/>

**Business Objectives and Constraints:-**<br/>
* Predict as many tags as possible with high precision and recall.
* Incorrect tags could impact customer experience on StackOverflow.
* No strict latency constraints.

**Data:-**
Refer: https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data
<br>
All of the data is in 2 files: Train and Test.<br />
<pre>
<b>Train.csv</b> contains 4 columns: Id,Title,Body,Tags.<br />
<b>Test.csv</b> contains the same columns but without the Tags, which you are to predict.<br />
<b>Size of Train.csv</b> - 6.75GB<br />
<b>Size of Test.csv</b> - 2GB<br />
<b>Number of rows in Train.csv</b> = 6034195<br />
</pre>
The questions are randomized and contains a mix of verbose text sites as well as sites related to math and programming. The number of questions from each site may vary, and no filtering has been performed on the questions (such as closed questions).<br />
<br />

