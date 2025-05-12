# uda-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [UDA Assignment 1 Solved](https://www.ankitcodinghub.com/product/uda-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91110&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;UDA Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In this assignment you have been hired as an analytics consultant by JD power and Associates, who wants to perform a competitive analysis of the entry level luxury car market in the USA. Your job is to give advice/insights to these individuals based on the analysis of social media conversations. The detailed tasks are described below.

<ol>
<li>Write a scraper to fetch messages posted in Edmunds.com discussion forums. The scraper output should be a .csv file with the following columns: date and message (even though you will only use the messages in your analysis). Before you develop the scraper, carefully study one of the forums on Edmunds.com to understand the html as well as the threading structures.</li>
</ol>
&nbsp;

<ol start="2">
<li>Fetch around 5000 posts about cars from the Entry Level Luxury forum <a href="https://forums.edmunds.com/discussion/2864/general/x/entry-level-luxury-performance-sedans">https://forums.edmunds.com/discussion/2864/general/x/entry-level-luxury-performance-sedans</a></li>
</ol>
&nbsp;

The idea is to have multiple brands and models being discussed without one of them being the focal point. You can choose early or recent posts (do mention what you have chosen). Note that Edmunds changed its forum structure a few years ago, but left the early posts with the old structure. So you should choose either the oldest or newest posts.

&nbsp;

<strong>Task A:</strong> Once you fetch the data, test if the data support Zipf’s law. Plot the most common 100 words in the data against the theoretical prediction of the law. For this question, do not remove stopwords. Also do not perform stemming or lemmatization.

<em>Hint: Check </em><a href="http://www.garysieling.com/blog/exploring-zipfs-law-with-python-nltk-scipy-and-matplotlib"><em>http://www.garysieling.com/blog/exploring-zipfs-law-with-python-nltk-scipy-and-matplotlib</em></a>

&nbsp;

Task B: Find the top 10 brands from frequency counts. You will need to write a script to count the frequencies of words (stopwords should NOT be counted). Replace frequently occurring car <strong>models</strong> with <strong>brands</strong> so that from now on you have to deal with only brands and not models. You will need another script for this job. A list of model and brand names (not exhaustive) are provided in a separate file.

<strong>Task C:</strong> Calculate lift ratios for associations between the top-10 brands identified in Task A. You will have to write a script to do this task). For lift calculations, <strong>be sure not to count a mention more than once per post, even if it is mentioned multiple times in the post.</strong>

&nbsp;

<strong>Task D:</strong> Show the brands on a multi-dimensional scaling (MDS) map (use a Python script for MDS, there are multiple scripts available on GitHub).

&nbsp;

<strong>Task E:</strong> What insights can you offer to your client from your analyses in Tasks C and D

&nbsp;

<strong>Task F:</strong> What are 5 most frequently mentioned attributes or features of cars in the discussions? Which attributes are most strongly associated with which of these 5 brands? You DON’T have to do a sentiment analysis for this assignment.

&nbsp;

&nbsp;

<strong>Task G:</strong> What advice will you give to your client from Task F? For this assignment, you can assume that all sentiments are positive.

&nbsp;

<strong>Task H:</strong> Which is the most <strong>aspirational</strong> brand in your data in terms of people actually wanting to buy or own? Describe your analysis. What are the business implications for this brand?

&nbsp;

&nbsp;

<strong>Provide the following details in your python notebook:</strong>

&nbsp;

<ol>
<li>Which forum you chose (provide URL)</li>
<li>Which 10 brands you chose – provide the frequency table</li>
<li>Show all lift calculations in a table.</li>
<li>MDS map</li>
<li>State the 5 attributes you chose (again, a table is good here).</li>
<li>For task E, provide all details of your analysis – e.g., how you measured “aspirational” and how you found the most aspirational brand.</li>
<li>Advice/insights based on your analysis for your client.</li>
</ol>
&nbsp;
