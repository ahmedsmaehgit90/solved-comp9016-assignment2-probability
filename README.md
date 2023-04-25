Download Link: https://assignmentchef.com/product/solved-comp9016-assignment2-probability
<br>
The purpose of this assignment is to assess the following <strong>LearningOutcomes</strong>:

<ul>

 <li>LO1 Appraise domain specific formalisms used in knowledge representation schemes.</li>

 <li>LO2 Compare and contrast current knowledge representation approaches integrated in systems relevant to AI.</li>

 <li>LO3 Select, apply and evaluate a knowledge representation scheme for a specified domain.</li>

 <li>LO4 Design and implement KR formalisms for a real-world data set.</li>

 <li>LO5Interpret,critiqueandcommunicatethesuitabilityofdatavisualisationtechniques used in conjunction with the design of KR formalisms and the analysis of the resulting output.</li>

</ul>

To that end, you are going to build upon the theory discussed in lectures and the practical work carried out as part the course.

<h3>1.1 PROBABILITY</h3>

<h4>1.1.1 PROBABILITY DISTRIBUTION TABLE</h4>

You have been studying hard on your latest assignment and asked your fellow students for some tips:

<ul>

 <li>Tip 1 “Study hard and you will do well, fail to do so and you will not”</li>

 <li>Tip 2 “Get plenty of rest and you will do well, fail to do so and you will not”</li>

 <li>Tip 3 “Set an an alarm and you will get up in time, fail to do so and you will not”.</li>

</ul>

You ask your fellow classmates which tips they adhere to and how frequently. After recording their responses you derive the following table:

Create a probability distribution table using appropriate variable names.

<h4>1.1.2 BAYESIAN NETWORKS</h4>

You have been given the following Random Variables:

<ul>

 <li>Fossil Fuels</li>

 <li>AI</li>

 <li>GlobalWarming</li>

 <li>Renewable Energy</li>

 <li>Traffic</li>

 <li>Employed</li>

</ul>

Construct a model of the world using these variables (Note: this is subjective but there should be a rationale behind your world view and your thought process articulated). Implement a Bayesian Network.

<ul>

 <li>Provide a visual depiction of the network • Detail the associated Conditional Probability Tables.</li>

 <li>Demonstrate querying the network.</li>

</ul>

Write a clear and concise description regarding Bayesian Networks, the utility of such and the associated pro’s and cons. Support this with examples where possible.

<h3>1.2 LEARNING: DEVELOPING AND EVALUATING A MODEL</h3>

“Naive Bayes is a simple technique for constructing classifiers: models that assign class labels to problem instances, represented as vectors of feature values, where the class labels are drawn from some finite set. There is not a single algorithm for training such classifiers, but a family of algorithms based on a common principle: all naive Bayes classifiers assume that the value of a particular feature is independent of the value of any other feature, given the class variable.” You will be implementing a Naive Bayes classifier and discussing the theory behind its operation from the perspective of probability, conditional independence, and Bayes theorem.

<h4>1.2.1 DATA</h4>

Choose an appropriate multivariate datasets with a limited number of classes from: <a href="https://archive.ics.uci.edu/ml/index.php">https:</a>

<a href="https://archive.ics.uci.edu/ml/index.php">//archive.ics.uci.edu/ml/index.php</a> Take a subset of data from the dataset:

<ul>

 <li>Compute the “Prior” probabilities for each of the classes.</li>

 <li>Compute the probability of evidence.</li>

 <li>Compute the probability of likelihood of evidences (numerator).</li>

</ul>

Articulate your understanding of each as applied to Bayesian networks. Tip: Demonstrate the suitability of a dataset or highlight why it is not suitable. Use appropriate visualisations to aid your rationale.

Write a clear and concise description regarding the dataset and its appropriateness for a Naive Bayes Classifier and probabilistic inference in general.

<h4>1.2.2 NAIVE BAYES LEARNER</h4>

Based onyour studying and reviewing of “learning.ipynb” implement the Naive Bayes learner and evaluate its performance for the selected dataset. Choose appropriate methodologies and/or variants in its utilisation. Present appropriate visualisations demonstrating its performance. Write a clear and concise description of the Naive Bayes Classifier considering the headings outlined: probability, conditional independence, and Bayes theorem

<h2>2 TIPS</h2>

<ul>

 <li><strong>Review </strong>“probability.ipynb”, “learning.ipynb” and ‘learning_apps.ipynb”.</li>

 <li><strong>TipforallParts</strong>: Do not provide masses of text lifted from the text/online or wikipedia. Be your own editor, focus on what is important and articulate that in a rationale way that is technically accurate. Demonstrating a capacity to explain complex topics in a clear and concise manner is indicative of a higher level of understanding and will be rewarded with an appropriate grade. Use results derived from experimental runs to back your claims and make sure your narrative is coherent and consistent.</li>

</ul>

<h2>3 SUBMISSION</h2>

You submission will contain:

<ul>

 <li>A 1500 word report <em>≤ </em>7 pages in “.pdf” format.</li>

 <li>A <strong>single </strong>“.py’ file</li>

</ul>

Prepare your submission by archiving it as a single “.zip” file using the following naming convention.

“A2_COMP9016_&lt;Surname&gt;_&lt;First name&gt;_&lt;Student Number&gt;.zip” e.g.

“A2_COMP9016_OReilly_Ruairi_R123456.zip”

<h3>3.1 WORD COUNT – 1500 WORD MAX</h3>

There are three distinct questions as part of this assignment Q1.1-Q1.3. In answering these it is important that you demonstrate an understanding of the underlying theory as applied in the context of your environment. There is a suggested word limit of 500 words per question, your ability to articulate your answer succinctly is indicative of a deeper understanding in itself. I <strong>highly recommend </strong>the use of well formatted tables for any experimental results and/or diagrams/visualisations if they aid the message you are trying to convey. Boilerplate text should be kept succinct and to the point.

Prepare your solution by the due date as a single “.pdf” file using the following naming convention.

“A2_COMP9016_&lt;Surname&gt;_&lt;First name&gt;_&lt;Student Number&gt;.pdf” e.g.

“A2_COMP9016_OReilly_Ruairi_R123456.pdf”

<h3>3.2 CODE SUBMISSION</h3>

A <strong>single </strong>“.py’ file should be prepared containing all code for questions 1.1-1.3. Encapsulate these in three individual functions called from the end of your submitted “.py” file. <strong>NB</strong>: Your code will be run from a “subdir” of the AIMA libraries (I have already provided a solution for importing these libraries from a parent directory – <a href="https://cit.instructure.com/courses/38151/files/707548?module_item_id=232253">see link</a> – I expect you to follow these guidelines).

Prepare your solution by the due date as a single “.py” file using the following naming convention.

“A2_COMP9016_&lt;Surname&gt;_&lt;First name&gt;_&lt;Student Number&gt;.py” e.g.

“A2_COMP9016_OReilly_Ruairi_R123456.py”