# Financial-Well-being-survey-study
This is my presentation about the National Finanacial Well-being Survey

![image](https://user-images.githubusercontent.com/74316333/99918044-98bc3880-2d14-11eb-9390-48670dd9bb20.png)

# Introduction
<details>
  <summary>Key facts and proposed hypothesis</summary>
  
•The survey that I have analyzed for my project was developed in 2017 by the Consumer Financial Protection Bureau.<br/>

•The total number of respondents in the survey is 6,394, with the main study being fielded in late 2016.<br/>

•The main hypothesis that i will be testing in my research is that financial literacy is a better predictor of financial well being than income.<br/>
</details>


# Key dependent variable
<details>
  <summary>Financial well being</summary>
  
The key dependent variable that I will be observing is the Financial well being score.<br/>

Developed by the CFPB with the help of experts and consumers.<br/>


Represented as a number between 0-100, the scale does not have a clear cut-off point for good and bad scores, and extreme values are rare.<br/>

  ![image](https://user-images.githubusercontent.com/74316333/99919731-7976d880-2d1f-11eb-984f-42c4b9b8ab3b.png)<br/>


![image](https://user-images.githubusercontent.com/74316333/99919879-5e589880-2d20-11eb-8fd8-896877fba873.png)<br/>


</details>

# Key policy variables
<details>
  <summary>Financial literacy and income</summary>
 
# Financial literacy
For this research three key fiancial literacy variables were used that are encompassed in the CFPB.<br/>
  •Financial skill scale score<br/>
  
  Financial skill scale was developed by the CFPB.<br/>
  
  Mesures knowdledge about making financial using 10 questions in the survey.<br/>
  
  Has a scale of 0-100, with extreme scores being rare.<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99920732-b6de6480-2d25-11eb-932e-d279f363a412.png)<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99920769-03c23b00-2d26-11eb-828e-2bfb78d75cfb.png)<br/>
  
  •Lusardi & Mitchell financial knowledge skill scale score<br/>
  
  Measurement of financial literacy developed by Annamaria Lusardi and Olivia S. Mitchell.<br/>
  
  Has a scale between 0-3, and measures knowledge in regards to: Interest rates, Inflation and Risk diversification.<br/>

  ![image](https://user-images.githubusercontent.com/74316333/99920940-446e8400-2d27-11eb-8541-7f9b16678aa5.png)<br/>

  •Knoll & Houts financial knowledge scale score<br/>
  
  Developed by Melisaa A. Z. Knoll and Carrie R. Houts.<br/>
  
  The purpose of the scale is to measure financial knowdledge using psychometric techniques, that allow for “the comparison of financial knowledge across studies, populations, and programs.” <br/>
  
   The score is derived from 20 questions<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99921376-49810280-2d2a-11eb-839a-c803eadbdd35.png)<br/>
  
# Income<br/>

For this research income will be measured by the Household income variable from the CBPF survey.<br/>

The values are presented in an integer form, with values ranging from 1 (less than 20,000$) to 9 (150,000$ and more).<br/>

![image](https://user-images.githubusercontent.com/74316333/99921585-96b1a400-2d2b-11eb-9165-52fba054b8d4.png)<br/>

![image](https://user-images.githubusercontent.com/74316333/99922831-d7f98200-2d32-11eb-945a-19440d28d010.png)<br/>

</details>

# Other variables
<details>
  <summary>Variables that will be accounted for in the model</summary>

Other variables that will be accounted for in both models:<br/>
  
  •Highest educational attainment<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99922121-05dcc780-2d2f-11eb-9d4f-076e8276dd84.png)<br/>
  
  •Ethnicity<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99922197-800d4c00-2d2f-11eb-9476-ee6b6807e2f5.png)<br/>
  
  •Age group<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99922254-e72b0080-2d2f-11eb-9102-bbd2b9ded43a.png)<br/>
  
  •Gender<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99922288-21949d80-2d30-11eb-933c-094e8a355392.png)<br/>
  
  •Highest parental educational attainement<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99922331-57d21d00-2d30-11eb-8508-2de9c439042d.png)<br/>
  
  •Highest educational attainement in the household<br/>

![image](https://user-images.githubusercontent.com/74316333/99922370-8819bb80-2d30-11eb-82a2-789f510951a3.png)<br/>

 •Region<br/>
 
 ![image](https://user-images.githubusercontent.com/74316333/99922593-a7fdaf00-2d31-11eb-8307-9c1b50891d74.png)<br/>
 
</details>

# Splitting the data and initial regression results
<details>
  <summary>Interaction between key variables</summary>
  
In order to make a predictive model, the data was split into two parts, 20% that would be used for model development and 80% for testing.<br/>

Key data for Financial literacy model<br/>

![image](https://user-images.githubusercontent.com/74316333/99923523-5efc2980-2d36-11eb-9b09-1a64107bf541.png)<br/>

Key data for the Income model<br/>

![image](https://user-images.githubusercontent.com/74316333/99923666-0a0ce300-2d37-11eb-84d1-7b82d51ff481.png)<br/>

# Full regression model
<details>
  <summary>All variables and key interactions included</summary>
  
![image](https://user-images.githubusercontent.com/74316333/99923032-16dc0780-2d34-11eb-973b-a57bd38c9c31.png)<br/>

</details>

</details>

# Visual analysis
<details>
  <summary>Visual representantation of expected prediction</summary>
  
Scatter plot for out-of-sample testing for the Financial Literacy model:<br/>

![image](https://user-images.githubusercontent.com/74316333/99925076-eb114f80-2d3c-11eb-9a3d-976a8a207b55.png)<br/>


Scatter plot for out-of-sample testing for the Income model:<br/>

![image](https://user-images.githubusercontent.com/74316333/99925198-74288680-2d3d-11eb-9704-cd8f53eda322.png)<br/>

</details>

# Statistical prediction
<details>
  <summary>Testing the goodness of fit</summary>

# Mean and correlation
<details>
  <summary>Testing the mean and correlation between models and actual values</summary>
  
  Correlation<br/>
  
  Financial literacy model:<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99925903-22cdc680-2d40-11eb-91e5-424b5137d8d3.png)<br/>
  
  Income model:<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99925935-3842f080-2d40-11eb-8b99-9b6b0674d089.png)<br/>
  
  Paired t-test for mean<br/>
  
  Financial literacy model:<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99925816-c2d72000-2d3f-11eb-9573-583dc08a1d64.png)<br/>
  
  Income model:<br/>
  
  ![image](https://user-images.githubusercontent.com/74316333/99925851-e732fc80-2d3f-11eb-9451-8953226418ac.png)<br/>
  
</details>

# Cross validation testing
<details>
  <summary>Cross validation testing with k=5</summary>

Root mean squared deviation:<br/>

Financial literacy model testing:<br/>

![image](https://user-images.githubusercontent.com/74316333/99926176-1007c180-2d41-11eb-9635-541c12520b35.png)<br/>

Income model testing:<br/>

![image](https://user-images.githubusercontent.com/74316333/99926191-2281fb00-2d41-11eb-8c3d-d833696f8f1b.png)<br/>

R-squared:<br/>

Financial literacy model testing:<br/>

![image](https://user-images.githubusercontent.com/74316333/99926218-40e7f680-2d41-11eb-81e8-784d058ef8e9.png)<br/>

Income model testing:<br/>

![image](https://user-images.githubusercontent.com/74316333/99926254-5ceb9800-2d41-11eb-86c9-1417fd897396.png)<br/>

</details>

# Randomized Cross validation testing
<details>
  <summary>Another Cross validation test after randomizing order</summary>
  
Root mean squared deviation:<br/>

Financial literacy model testing:<br/>

![image](https://user-images.githubusercontent.com/74316333/99926534-53aefb00-2d42-11eb-9060-eb931ffbc380.png)<br/>

Income model testing:<br/>

![image](https://user-images.githubusercontent.com/74316333/99926571-76411400-2d42-11eb-8991-3083649fd9a2.png)<br/>

R-squared:<br/>

Financial literacy model testing:<br/>

![image](https://user-images.githubusercontent.com/74316333/99926593-8c4ed480-2d42-11eb-819c-a96ec3687317.png)<br/>

Income model testing:<br/>

![image](https://user-images.githubusercontent.com/74316333/99926616-9c66b400-2d42-11eb-844b-6b52ad2391a0.png)<br/>

</details>
</details>

# Conclusion
<details>
  <summary>Practical significance</summary>
  
While there is no evidence to suggest a causal effects, the data does seem to show that financial literacy could be a better predictor of financial well being.<br/>

Further data analysis would be needed, one that analyzes data over a longer time perdiod.<br/>

Nonetheless, the research seems to show that financial literacy plays a larger role than previously believed in understanding financial well being.<br/>

</details>
