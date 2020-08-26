# Projects

Hello! I'm a new graduate from the University of Georgia (UGA), where I majored in Management Information Systems and Finance and attained a Certificate in Applied Data Science. I'm excited to apply my classroom learnings into tangible projects, whether it be in a corporate work setting or taking on new projects, where I will be converting raw data into actionable decisions and insights. The number of projects on my profile will grow as I continue to practice and learn more about the field of Data Science.

<h2>Project Descriptions</h2>

<h3>AdaBoost Classifier Implementation (August 2020)</h3>
<p>
   Using <a href="https://github.com/random-forests/tutorials/blob/master/decision_tree.ipynb" target="_blank">Google Developers' Decision Tree</a> code as my foundation for building stumps (1 level Decision Trees), I created an AdaBoost Classifier from scratch using basic Python functions. I added onto Google's code with many helper functions, a Stump class to keep track of each stump and its split criterion, and an AdaBoost class that is used to fit and predict new instances.
</p>

<p>At the bottom of the Jupyter Notebook, I tested the classifer using a rare dataset from Kaggle – Titanic: Machine Learning from Disaster. In the Jupyter Notebook, I achieved 76% accuracy when predicting new instances of the Titanic dataset. However, when replicating, the accuracy won't always be the same, since AdaBoost creates new datasets, emphasizing rows with incorrect classifications from the previous dataset, with (presumably) different records to create new stumps. This results in different criterion splits, and in turn, different results/predictions.
</p>

<h3>AR(p) Time Series Implementation (June 2020)</h3>
<p>
   In efforts to solidify my learnings of different ML topics, I enjoy implementing new topics that I learn using simple Python functions. In this project, I created a basic Autoregressive Time Series model using Apple stock prices in order to predict the next value(s). I used the Durbin-Levinson algorithm to create a psi matrix, which is used to make predictions.
</p>

<h3>Feature Selection Algorithm (April 2020)</h3>
<p>
   In this project, I created a forward selection algorithm that can be generalized to many different datasets. The goal is to evaluate different machine learning models using the wrapper (greedy) method of variable selection. This shows which subset of features performs best in a given dataset.
</p>

<p>
  The high-level logic of the code is as follows:
</p>
<ol>
  <li>Clean the dataset if needed.</li>
  <li>Evaluate each predictor variable individually against the response variable using some quality of fit measure (in my code, it's R&sup2; cross-validated).</li>
  <li>Store the best performing individual variable in a list (best subset of variables) and add on new variables to try to improve the quality of fit. The variable that improves the model the most will be added onto the best subset of features list. This process gets repeated until all of the variables are in the model.</li>
  <li>After the forward selection process is over, the N* (optimal number of variables) is calculated by finding the subset of variables that achieved the highest cross-validated R&sup2; value.</li>
</ol>

<p>I wrote the program using a 3L Neural Network and the AutoMPG dataset found off of the UCI ML Repository.</p>
  
  
<h3>Slickdeals Sentiment Analysis (Late Nov. 2019)</h3>
<p>
  Who doesn’t like a good deal? I certainly do, so I’ve decided to build and implement a natural language model that deciphers whether a product is worth buying on <a href="http://slickdeals.net" target="_blank">slickdeals.net</a>. For those not familiar, Slickdeals is a website that serves as a platform for people to share products that they find on the internet that are priced well below their manufacturer suggested retail price (MSRP). These items can be made up of many types of product categories, including groceries, video games, electronics, clothing, home appliances, and much more.
</p>

<p>
  For each of the products, there is a very active, well-informed community that posts their opinions about the products and talks about whether the product is worth buying. The goal of this project is to apply sentiment analysis to create an effective machine learning model and generate understanding about an effective way to combine English lexicon and data science to generate a modern day solution for online shopping.
</p>
  
<h3>NBMBAA Job Postings Web Scrape, Text Analysis, and Visualization (Late Sep. 2019)</h3>
<p>The <a href="https://nbmbaa.org/conference/" target="_blank">National Black MBA Association (NBMBAA) Conference</a> is an annual career fair where top-tier companies attend to recruit a diverse group of students from universities all around the country.</p>

<p>A group of UGA MBA students attend each year, and this project is designed to help these students get a convenient view of all the <a href="https://careersuccess.nbmbaa.org/jobs/?keywords=&event_id=4070&sort=" target="_blank">job postings</a> on the website as well as analyze the text on the postings to get insight on the verbiage being used by companies in their job descriptions. The goal here is so that students can tailor their resumes based on these keywords to match job descriptions and bypass a potential <a href="https://www.topresume.com/career-advice/what-is-an-ats-resume" target="_blank">ATS screening</a>.
</p>

<p>Additional documentation for more details on the project and my methodology is included in the project folder.</p>

<h3>MBA 2020 Student Profiles (Early Sep. 2019)</h3>
<p>While working at the MBA Career Management Center at my school, a director was wondering if there was a way to extract the names, number of years of work experience, and company for each student in the profile book (named "Terry_2020_FTMBA_ProfileBook_v4.pdf" in the MBA 2020 Student Profiles folder) without having to go through each student and manually inputting his/her information into an Excel spreadsheet, since this would be banal and time-consuming.</p>

<p>After cleaning, maniuplating, and reshaping the MBA 2020 student profile data, I created a program that effectively organized the raw text and vizualized the necessary information. Included in the folder are the PDF file and student roster list that I was given, the .txt file that I worked with throughout, the program I wrote, and the final output in .csv format. </p>
