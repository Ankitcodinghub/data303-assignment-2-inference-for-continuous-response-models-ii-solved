# data303-assignment-2-inference-for-continuous-response-models-ii-solved
**TO GET THIS SOLUTION VISIT:** [DATA303 Assignment 2-Inference for Continuous Response Models II Solved](https://www.ankitcodinghub.com/product/data303-assignment-2-inference-for-continuous-response-models-ii-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101401&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DATA303 Assignment 2-Inference for Continuous Response Models II Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Assignment Questions

Q1. In a 2015 article comparing technological advancement of hybrid electric vehicles (HEV) in different market segments, authors Lim et al. collected data on prices and other features for 154 HEV models (Lim et al. 2015. Technological Forecasting and Social Change. vol 97, pages 140-153). We will use regression analysis to explore the factors that influence price. The dataset is in the file hybrid_reg.csv and contains the following variables:

<ul>
<li>carid: Vehicle ID</li>
<li>vehicle: Make of vehicle</li>
<li>year: Model year</li>
<li>msrp: Manufacturer’s suggested retail price in 2013 (US dollars).</li>
<li>accelrate: Acceleration rate in km/hour/second</li>
<li>mpg: Fuel economy in miles/gallon</li>
<li>mpgmpge: Max of mpg and mpge (mpge is miles per gallon equivalent for plug-in HEVs to take into
account the all electric range, with mpge = 33.7∗driverange . batterycapacity
</li>
<li>carclass: Model class. C = Compact, M = Midsize, TS = 2 Seater, L = Large, PT = Pickup Truck, MV = Minivan, SUV = Sport Utility Vehicle</li>
<li>carclass_id: Index representing model class
The variables carid and vehicle are vehicle identifiers and will not be used in the analysis. Likewise carclass_id will not be used as it is a numerical form of the variable carclass and does not provide any additional information.
</li>
</ul>
a. (3 marks) Read the dataset into R. Prepare the data for analysis by adding the new variables below to the dataset. Give the number of observations in each year group of the new variable yr_group.:

<ul>
<li>yr_group: group year as follows “1997-2004”, “2005-2008”, “2009-2011”, “2012-2013”.</li>
<li>msrp.1000: convert msrp from US$ to US$1000 by dividing msrp by 1000.</li>
</ul>
<ol start="2">
<li>(3marks)Usetheggplot2packagetoplotmsrp.1000againsteachofthepredictorvariables,yr_group, accelrate, mpg, mpgmpge and carclass. Are there strong indications of non-linear relationships with any of the numerical predictors? If so, which ones?</li>
<li>(3 marks) Create pairwise scatterplots of the numerical predictors. Is there any indication of potential multicollinearity among these predictors?</li>
<li>(4 marks) Fit a linear model with all predictors (yr_group, accelrate, mpg, mpgmpge and carclass) included in the model. Calculate the VIF statistic for the predictors. To check for evidence of multicollinearity we will use a different threshold defined by</li>
</ol>
VIFmodel = 1 , 1−R2

where R2 is the R2 value for the model that includes all predictors. Using this threshold identifies model

predictors that have stronger relationships with other predictors than the response variable has. It is a more stringent way of identifying multicollinearity. If GV IF(1/(2×Df)) &gt; V IFmodel, then this is evidence of severe multicollinearity. Calculate V IFmodel for your fitted model. Is there evidence of severe multicollinearity? Are you surprised by the result?

<ol start="5">
<li>(3 marks) Fit a generalised additive model to the data including all predictors, using a smooth spline for each numerical predictor. Present the RSE, R2 and adjusted R2 values in a table.</li>
<li>(3 marks) Print the results for the significance of smooth terms in a table. Which of the numerical predictors have a significant non-linear effect on msrp.1000? Justify your answer briefly.</li>
<li>(4 marks) Perform a diagnostic check of regression assumptions and adequacy of basis functions for the model you fitted in part (e). What conclusions do you draw from your results? (Note: ensure your diagnostic plots fit on a single page).</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
model

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
h. (4 marks) Calculate and print a table of AIC values for the model in part (e) (Model 1) and each of the following models:

<ul>
<li>Model 2: excludes mpg only from Model 1</li>
<li>Model 3: excludes mpgmpge only from Model 1</li>
<li>Model 4: excludes mpg and mpgmpge from Model 1</li>
</ul>
<ol start="9">
<li>[3 marks] What do your results in part (h) indicate about whether both mpg and mpgmpge should be included in the model? Explain your answer briefly. What regression pitfall does this point to?</li>
<li>[2 marks] Are you surprised by your conclusions in part (i) given your findings in part (d)? Explain your answer briefly.</li>
<li>[3 marks] Calculate and print a table of BIC values for Models 1 to 4. Based on these results, which model would you choose as your preferred model? Explain your answer briefly.</li>
</ol>
2. Q2. (5 marks) Suppose we have a data set with five predictors:

<ul>
<li>X1 =GPA</li>
<li>X2 =IQ</li>
<li>X3 =Gender(0=female, 1=male)</li>
<li>X4 =Interaction between GPA and IQ</li>
<li>X5 =Interaction between GPA and Gender.
The response variable, Y , is starting salary after graduation (in thousands of dollars). Suppose we get the following regression coefficient estimates:

βˆ0 =5, βˆ1 =8, βˆ2 =0.2, βˆ3 =10, βˆ4 = 0.05, βˆ5 = 2
</li>
</ul>
<ol>
<li>(1 mark) Write down the estimated model equation in terms of Yˆ, X1, X2 and X3.</li>
<li>(3 marks) Which one of the following statements is correct and why? Show any working you do.
i. For a fixed value of IQ and GPA, males earn more on average than females provided that the GPA is high enough.

ii. For a fixed value of IQ and GPA, females earn more on average than males.

iii. The difference in expected salary between males and females increases as GPA increases.

iv. An increase in IQ by one point is associated with a reduction in expected salary, provided GPA is

high enough.
</li>
<li>(1 mark) True or False: Since the coefficient for the GPA:IQ interaction term is very small, there is
very little evidence of an interaction effect. Justify your answer.
</li>
</ol>
Assignment total: 40 marks

‘

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
