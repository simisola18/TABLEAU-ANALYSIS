# TABLEAU-ANALYSIS
Case Study: NHS Scotland Hospital Bed Availability for Cancer Treatment     
# INTRODUCTION
The COVID-19 challenges have put some strain on the operating model of NHS Scotland, which has led to ineffective operations in the healthcare sector. In order to improve how the NHS responds to patient treatments and plan their response times accordingly, a clear and strategic approach must be taken in order to successfully manage the treatment of cancer, specifically Urological Cancer.
# PART ONE
SECTION A: FORECASTING EVALUATION
In every life situation, human predicts the future based on the current or past incidents that occurred in society (Hyndman and Athanasopoulos, 2021). Forecasting is the process of adopting the historical trend or data to predict particular estimations for specific managerial or business trends. Four Key Questions that should be considered by the management at NHS
These questions include:
1. To what extent has the forecasting technique used operational indicators and inputs? As a consultant, the performance measure can be derived through key
operational indicators and inputs. It will enable NHS Scotland to determine Its performance and helps direct the forecasting technique in considering the operational indicators toward predicting the future trend for the organisation.
2. What is the level of automation integrated with the technique? Integrating automation to the model applied in forecasting techniques can enable NHS Scotland
to maintain a better predictive process or estimate future trends (Lightner, 2018). As a consultant, this is a key criterion to consider in the forecasting technique for NHS Scotland because automation helps projection to include machine learning, intelligent technologies, and artificial intelligence.
3. How does the technique create the variable and factors involved? there is a need to consider the process of identifying variables and factors involved in projecting future trends in the organisation for effective management of patients, staff, and hospitals to reduce the waiting time of cancer patients in hospitals.
4. Is this technique thoroughly effective for its purpose? The effectiveness of the forecast technique ensures the level of accuracy achieved in the process of determining the future trend or projection in NHS Scotland. Key metrics towards

SECTION B: DATA ACCESS, CLEANING AND PREPARATION
As seen in the figure below, the various locations in NHS Scotland show a different pattern of times series. This is because most cities experienced horizontal and trend & seasonal with trends patterns in the referral and treatment of patients with urological cancer. NHS Highland experienced the lowest percentage of referrals treated but experienced a huge spike in numbers from 2020-2021 while NHS Grampian, NHS Lothian experienced a decrease in referrals during 2020-2021. This implies that some health boards experienced low referrals of these patients from 2015 to 2019 before the COVID-19 period. However, there was an increase in the rate of treatment from 2020 to date, as seen in most of the health boards of NHS Scotland. According to the health update of the Public Health Service (2022), updates reveal that over 141,572 adults were diagnosed with cancer treatment which correlates with the trends shown in the above figure on the increasing treatment of cancer in the NHS Scotland. Based on this, recommendations can be made to increase the accessibility to urological cancer treatment despite the pandemic in the health sector and also develop guidelines that can accommodate more treatment of urological cancer patients in the health center.
![image](https://github.com/user-attachments/assets/ccc13ff9-7c52-4d49-a78f-1c4ea607a9c7)
Table summary for the forecasted Time Series analysis 2012 to 2021
Health Board Pattern Identified Forecasting Method Mean Squared Error
NHS Highland Seasonal with Trend Pattern Regression Analysis 156.86
NHS Lothian Seasonal with Trend Pattern Regression Analysis 41.58
NHS Fife Seasonal with Trend Pattern Regression Analysis 74.05
NHS Lanarkshire Horizontal Pattern Moving Average Method 46.22

# Observation in the time series forecasting analysis of data with 2020 -2021
During the analysis of this data the aim was to get the best method to predict the number of referrals coming into the NHS Scotland’s system, three different methods were adopted for this analysis; the moving average method, Trend method, and Seasonality with Trend methods were used. The method which provided the lowest MSE is the one to be preferred to the management to predict the number of referrals and how resources can be allocated and managed efficiently.
NHS Highland gave 156.86 with the seasonal Trend pattern as the lowest MSE in theRegression analysis used. Likewise, NHS Lothian and NHS Fife have the same trend patterns
with the lowest MSE being 41.58 and 74.05 respectively. NHS Lanarkshire was the only health board analyzed that gave the moving average method as its lowest MSE with a value of 46.22 following a horizontal pattern.

# PART 2 BUSINESS INTELLIGENCE SYSTEMS - TABLEAU
Tableau Prep
The following data documents were uploaded into the tableau prep builder in order to give more information about 62 day standard cancer waiting times: names of the current hospitals, information about the health boards, geographical codes, and 62-day waiting standards for cancer waiting times recorded. The cleaning was done in different steps with the first step of merging the special health board and hb14 dataset by a union where 2 rows not needed were removed, followed by 3 different join functions; join1(right join), join 3(left join) and join 5(middle join) were the files were merged and cleaned to removed unwanted values and dates such as null values, fields with
QF and HBT were removed also, changing quarter to date format and renaming it as Time, adjusting my range of dates, filtering the cancer values to show for only urological cancer types etc. I then cleaned the data as seen in step 6 where HB and SHB fields were removed and postcode was split and cleaned. The final results of the cleaning steps can be seen in output where 8 rows remained of the cleaned data to be examined. The steps can be seen in the screenshots below.
Step One
![image](https://github.com/user-attachments/assets/be4c15c7-f9ea-4ac5-9920-d38e57cab47b)
Step Two
![image](https://github.com/user-attachments/assets/4e185752-2947-4af9-a4a1-7edae755be5d)
Step Three
![image](https://github.com/user-attachments/assets/d77e037c-aed7-4b25-9982-c08a2e85083f)
Step Four
![image](https://github.com/user-attachments/assets/777ef12c-3663-4bd2-8ed4-e4935c556b3b)
Step Five
![image](https://github.com/user-attachments/assets/f709d66a-bcff-42c0-afe4-a305d6b71b11)
Step Six
![image](https://github.com/user-attachments/assets/43541fc8-e081-4248-a3c7-8009405fbd67)
Step Seven:
![image](https://github.com/user-attachments/assets/f501320e-0477-4bca-ac6a-d7dcc8b7e9e5)
# Dashboard
Access Link:
https://public.tableau.com/app/profile/simi.oduba/viz/P2686827TABLEAUCWTDASHBOARD/P2686827TABLEAUDASHBOARD
![image](https://github.com/user-attachments/assets/e7f54949-9741-4a23-9495-54b7fa581307)
![image](https://github.com/user-attachments/assets/c869942c-41c2-4cdd-a0c2-97d714f2bcbd)
Scotland's percentage of referrals for various types of urological cancer is depicted in a time series chart..
![image](https://github.com/user-attachments/assets/2c036ee0-6f7e-4860-a372-dc247c8e25be)
Geographical map displaying the proportion of referrals treated at each hospital location in Scotland.
![image](https://github.com/user-attachments/assets/07095831-7ac2-4e38-9b36-36addb3c9b00)
Tree Map for the Health Board displaying the percentage of treated referrals for each health Board.
![image](https://github.com/user-attachments/assets/c6754a5a-ba03-4254-bc2f-ea9efe7c941e)
Table highlighting the proportion of referrals treated for each kind of cancer per quarter; 2012-2021.
![image](https://github.com/user-attachments/assets/cbf26480-4b60-4bd5-bf83-7840b8cebad9)
Dashboard of the overall data
# Explanation of Dashboard’s output of NHS Scotland
The dashboard displays a time series chart, a geographic graph, a tree map of the health boards, and a table of the percentage of referrals treated for cancer in NHS Scotland. The time series graph that was found showed that the percentage of referrals treated among all health boards of the NHS Scotland experienced a negative trend series pattern from a high referral rate of 93% in 2012Q1 and only experienced an increase of 71% between Q3 and Q4 of 2020 the peak of the Covid period after which it reduced again to the range of 60% by the last quarter of 2021. The geographical map indicated that mostly the Southern regions and the Eastern regions were the areas where a high number of referrals occurred, with the Western and Northern regions having the lowest records of referrals. All the regions had referrals above average with
the lowest referral rate being 51%. The health board treemap shows, with the help of the color gradient, the deepest red color with health board NHS Ayrshire and Arran with 93% has the highest number of referrals out of all the health boards with NHS Highland having the lowest referrals of 51% patients. This can help the management know which health boards to focus on and redistribute their resources accordingly.
The percentage of referrals that have received treatment is displayed in the highlighted Table. throughout the quarterly period from 2012 to 2021. It shows that show 3 health boards had a 0% referral rate for some quarters such as NHS Orkney, NHS Western Isles, and NHS Shetland while some health boards had 100% referral rates at certain quarters also including some who had 0% had at a point i.e NHS Western Isles, NHS Shetland, NHS Ayrshire and Arran, NHS Orkney. Some health boards also had missing values for certain quarters majorly NHS Orkney, NHS Western Isles, and NHS Shetland had few missing values. This denotes that there has been a low improvement in the number of treated patients in Scotland in the time series chart of the percentage of referrals treated. It implies that there is a need for developing a significant improvement in increasing the percentage rate of referral treatment in the hospital through increasing the facilities and funding package for the NHS in Scotland. Through this analysis, NHS Scotland has an overview of where the next phase of a strategy to be targeted i.e, providing facilities or funding that can increase the percentage of referred treatment in Scotland overall.

# PART 3: ETHICAL ISSUES IN BUSINESS INTELLIGENCE
# Legal
Governmental bodies or policies exist to guide the treatment of patients with cancer in NHS Scotland. Who is held liable for dates prescribed to patients who end up not getting treated or who is in charge of the consequences of the actions or inactions of the health system, is it the management or the NHS? Great care must be made towards the actions and systems implemented by the NHS so as to avoid suits or legal issues arising in regard to patient’s treatments and welfare.
# Ethics
Ethics is a critical aspect of business intelligence due to the involvement of data in decisionmaking in any situation (Kemparaj & Kadalur, 2018). For example, in the case of NHS, the body expects to secure the data on the treatment of referred cancer patients to enable the process effectively because there will be cases of disagreement in the output. There should be informed consent of data use to patients and ensure the integrity of the NHS Scotland as a whole. Sharing of data with other agencies should be questioned and monitored so patient’s records are not exploited.
# Privacy issues
In this aspect, the Privacy of the data should be given priority through standard confidential processes. For instance, the analysis for NHS Scotland on the percentage of referred treated above reveals a negative trend that needs to be private to prevent escalating among opposition political parties or citizens. It should be of note that the NHS Scotland’s data shouldn’t be shared with 3rd parties and abused, and the privacy of information shouldn’t be entirely generalized as patient’s information vary from individual to individual.

# References
Cancer survival statistics - People diagnosed with cancer during 2015 to 2019 - Cancersurvival statistics - Publications - Public Health Scotland
Eiselt H. A. & C. L. Sandblom, (2007). Linear Programming and its Applications. Springer-Verlag Berlin Heidelberg Publication.
Hyndman, R. J. and Athanasopoulos, G. (2021). Forecasting: principles and practice.Melbourne, Australia: OTexts.
Kemparaj V. M. & Kadalur, U. G. (2018). Understanding the principles of ethics in healthcare: a systematic analysis of qualitative information. Int J Community Med Public
Health, 5(8), 822-8.
Lightner, N. J. (2018). Advances in Human Factors and Ergonomics in Healthcare and Medical Devices. Proceedings of the AHFE 2018 International Conference on Human Factors and Ergonomics in Healthcare and Medical Devices. Springer.
Talha, K. B. (2022). Cancer survival rates in Scotland. Cancer survival rates in Scotland - TheLancet Oncology
