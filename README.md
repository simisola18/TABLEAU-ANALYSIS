# TABLEAU-ANALYSIS
Case Study: NHS Scotland Hospital Bed Availability for Cancer Treatment     
INTRODUCTION
The COVID19 challenges have put some strain on the operating model of NHS Scotland,
which has led to ineffective operations in the healthcare sector. In order to improve how the
NHS responds to patient treatments and plan their response times accordingly, a clear and
strategic approach must be taken in order to successfully manage the treatment of cancer,
specifically Urological Cancer.
PART ONE
SECTION A: FORECASTING EVALUATION
In every life situation, human predicts the future based on the current or past incidents that
occurred in society (Hyndman and Athanasopoulos, 2021). Forecasting is the process of
adopting the historical trend or data to predict particular estimations for specific managerial or
business trends.
Four Key Questions that should be considered by the management at NHS
These questions include:
1. To what extent has the forecasting technique used operational indicators and
inputs? As a consultant, the performance measure can be derived through key
operational indicators and inputs. It will enable NHS Scotland to determine Its
performance and helps direct the forecasting technique in considering the operational
indicators toward predicting the future trend for the organisation.
2. What is the level of automation integrated with the technique? Integrating
automation to the model applied in forecasting techniques can enable NHS Scotland
to maintain a better predictive process or estimate future trends (Lightner, 2018). As a
consultant, this is a key criterion to consider in the forecasting technique for NHS
Scotland because automation helps projection to include machine learning, intelligent
technologies, and artificial intelligence.
3. How does the technique create the variable and factors involved? there is a need
to consider the process of identifying variables and factors involved in projecting future
trends in the organisation for effective management of patients, staff, and hospitals to
reduce the waiting time of cancer patients in hospitals.
4. Is this technique thoroughly effective for its purpose? The effectiveness of the
forecast technique ensures the level of accuracy achieved in the process of
determining the future trend or projection in NHS Scotland. Key metrics towards
3
P2686827
forecasting in the organisation require complete accuracy to employ a forecasting
technique.
Challenges/Implications of using the Forecasting Technique
Concerning challenges or implications, organisations experience these based on the
modalities involved in forecasting techniques. Some of these challenges/implications are
subjected to a dynamic situation of projective trends, which include the type of data, purpose
of data and so on. However, overall implications or challenges include selecting appropriate
forecasting techniques, maintaining the forecasting model employed, collating the exact data
type for forecasting, governmental policies and implications and economic conditions.
SECTION B: DATA ACCESS, CLEANING AND PREPARATION
As seen in the figure below, the various locations in NHS Scotland show a different pattern of
times series. This is because most cities experienced horizontal and trend & seasonal with
trends patterns in the referral and treatment of patients with urological cancer. NHS Highland
experienced the lowest percentage of referrals treated but experienced a huge spike in
numbers from 2020-2021 while NHS Grampian, NHS Lothian experienced a decrease in
referrals during 2020-2021. This implies that some health boards experienced low referrals of
these patients from 2015 to 2019 before the COVID-19 period. However, there was an
increase in the rate of treatment from 2020 to date, as seen in most of the health boards of
NHS Scotland. According to the health update of the Public Health Service (2022), updates
reveal that over 141,572 adults were diagnosed with cancer treatment which correlates with
the trends shown in the above figure on the increasing treatment of cancer in the NHS
Scotland. Based on this, recommendations can be made to increase the accessibility to
urological cancer treatment despite the pandemic in the health sector and also develop
guidelines that can accommodate more treatment of urological cancer patients in the health
center.
4
P2686827
The below is the time series showing all Health Board Percentage of Referrals Treated from
2012 to 2021 in Scotland.
SECTION C: TIME SERIES FORECASTING
The below figures present the time series of four major health boards which NHS Highland,
NHS Lothian, NHS Fife and NHS Lanarkshire that is based on forecasting analysis:
0
20
40
60
80
100
1 5 9 13 17 21 25 29 33 37
PERCENTAGE OF REFERRALS TREATED
PERIODS OF HIGHLAND
Time Series showing the Percentage of Referrals
Treated 2012 to 2021 (NHS Highland)
NHS Highland
5
P2686827
0
20
40
60
80
100
1 5 9 13 17 21 25 29 33 37
Percentage of Referrals Treated
Periods of Fife
Time Series showing the Percentage of Referrals Treated 2012 to
2021 (NHS Fife)
NHS Fife
6
P2686827
Time Series Forecasting for Each Health Boards
The following table present the pattern of the time series forecasting for the NHS Highland,
Lothian, Fife and Lanarkshire in Scotland and the time series forecasting:
SN Time Series Patterns
1 NHS Highland Cynical Trend Pattern
2 NHS Lothian Seasonal trend Pattern
3 NHS Fife Seasonal Trend Pattern
4 NHS Lanarkshire Horizontal Pattern
Forecasted Time Series from 2012 to 2021
0
20
40
60
80
100
1 5 9 13 17 21 25 29 33 37
Percentage of Referrals Treated
Periods of Lanarkshire
Time Series showing the Percentage of Referrals Treated 2012 to
2021 (NHS Lanarkshire)
NHS lanarkshire
0
20
40
60
80
100
1 5 9 13 17 21 25 29 33 37
PERCENTAGE OF REFERRALS TREATED
PERIODS OF HIGHLAND
Time Series showing the Percentage of Referrals
Treated 2012 to 2021 (NHS Highland) and its
Forecast
NHS Highland Seasonality with Trend
7
P2686827
8
P2686827
Table summary for the forecasted Time Series analysis 2012 to 2021
Health Board Pattern Identified Forecasting Method Mean Squared Error
NHS Highland Seasonal with Trend Pattern Regression Analysis 156.86
NHS Lothian Seasonal with Trend Pattern Regression Analysis 41.58
NHS Fife Seasonal with Trend Pattern Regression Analysis 74.05
NHS
Lanarkshire
Horizontal Pattern Moving Average Method 46.22
Observation in the time series forecasting analysis of data with 2020 -2021
During the analysis of this data the aim was to get the best method to predict the number of
referrals coming into the NHS Scotland’s system, three different methods were adopted for
this analysis; the moving average method, Trend method, and Seasonality with Trend
methods were used. The method which provided the lowest MSE is the one to be preferred to
the management to predict the number of referrals and how resources can be allocated and
managed efficiently.
NHS Highland gave 156.86 with the seasonal Trend pattern as the lowest MSE in the
Regression analysis used. Likewise, NHS Lothian and NHS Fife have the same trend patterns
with the lowest MSE being 41.58 and 74.05 respectively.
NHS Lanarkshire was the only health board analyzed that gave the moving average method
as its lowest MSE with a value of 46.22 following a horizontal pattern.
9
P2686827
Forecasted Time Series from 2012 to 2019 (Without 2020 and 2021)
0
20
40
60
80
100
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32
PERCENTAGE OF REFERRALS TREATED
PERIODS OF HIGHLAND
Forecasted Time series for NHS Highland
NHS Highland Seasonality with Trend
0
20
40
60
80
100
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33
Percentage of Referrals Treated
Periods of Lothian
Forecasted Time series of NHS Lothian
NHS Lothian Seasonality with Trend
10
P2686827
Table summary for the forecasted Time Series analysis 2012 to 2019 (Without 2020 and
2021)
Health Board Pattern Identified Forecasting Method Mean Squared Error
NHS Highland Seasonal with trend Regression Analysis 76.39
NHS Lothian Seasonal with trend Regression Analysis 42.64
NHS Fife Seasonal with trend Regression Analysis 63.97
NHS Lanarkshire Seasonal with trend Regression Analysis 23.28
Observation in the time series forecasting analysis of data without 2020 -2021
The forecast analysis followed the same trend on the actual time series with little difference
among the four health boards of NHS Scotland; Highland, Lothian, Fife, and Lanarkshire from
2012 to 2019. Three of the health boards had the same pattern with 2020&2021 and without,
which shows little to no changes in the trends in pattern referrals for the periods. While NHS
Lanarkshire was the only health board that had a pattern change while analyzing for 2020-
2021, it changed the pattern from horizontal back to seasonality with Trend. To get the best
MSE to analyse the forecast of the data, 3 different methods were adopted which are the
Moving Average, Seasonality with trend and trend were used in calculating the forecast, this
enables the analysis to adopt the best strategy in determining the forecast time series for the
following years examined and the one with the lowest forecast was picked as the best MSE to
predict the referrals for the NHS board.
The MSE of the health boards had lower values after analyzing compared to the data that
included the years 2020-2021 except for health board NHS Lothian which had a slight increase
in its MSE value of 1.06 when the data for 2020/21 was removed.
0
20
40
60
80
100
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32
Percentage of Referrals Treated
Periods of Lanarkshire
Forecasted Time Series of NHS Lanarkshire
NHS lanarkshire Seasonality with Trend
11
P2686827
SECTION D: LINEAR PROGRAMMING/LINEAR OPTIMISATION
Optimization mathematical modeling's function in NHS Scotland's staff-available bed
management
Optimisation modeling is a solution technique designed to cater to varieties of situations in
the health, business, education, governance, and other sectors. In the situation of managing
the available bed in NHS Scotland, modeling enables a sound decision regarding the
situation of NHS Scotland. It involves a mathematical process aimed at maximizing or
minimizing the complex situation in making sound and smart decisions. It aids in dispelling
questions about patient attrition rates and effective retention strategies. Also, to enhance the
quality and compliance of therapy while addressing scheduling issues. Major components to
consider in the case of NHS Scotland include decision variables (staffs’ time shift in
correlation to the occupancy of bed), result variable (Optimised Time Shift among Staff) and
uncontrollable variable.
Liner Programming on Problem Case on Staff Allocation in the NHS
Decision Variables
The key decision variables in the case of Tayside Hospital in Scotland include the staffs in
their time shift in correlation to the occupancy of bed. Therefore lets.
S1 = Staffs in period shift between 9:00 to 12:00
S2 = Staffs in period shift between 12:00 to 15:00
S3 = Staffs in time period shift between 15:00 to 18:00
S4 = Staffs in period shift between 18:00 to 21:00
S5 = Staffs in period shift between 21:00 to 24:00
S6 = Staffs in period shift between 0:00 to 03:00
S7 = Staffs in period shift between 03:00 to 06:00
S8 = Staffs in period shift between 06:00 to 09:00
S1= employees who commence work at 9am & work shifts (9am - Noon), (Noon to 3pm) &
(3pm to 6pm),
S2 = employees who commence work at 12noon & work shifts (Noon to 3pm), (3pm to 6pm)
& (6pm to 9pm),
S3 = employees who commence work at 3pm & work shifts (3pm to 6pm), (6pm to 9pm) &
(9pm to 12am),
12
P2686827
S4 = employees who commence work at 6pm & work shifts (6pm to 9pm), (9pm to 12am) &
(12am to 3am),
S5 = employees who commence work at 9pm & work shifts (9pm to 12am), (12am to 3am) &
(3am to 6am),
S6 = employees who commence work at 12am & work shifts (12am to 3am), (3am to 6am) &
(6am to 9am),
S7= employees who commence work 3am & work shifts (3am to 6am), (6am to 9am) & (9am
to Noon),
S8= employees who commence work at 6am & work shifts (6am to 9am), (9am to Noon) &
(Noon to 3pm).
Result Variable
Results (Optimised Time Shift among Staff) = O
Objective Function
O = S1 + S2 + S3 + S4 + S5 + S6 + S7 + S8
Uncontrollable Variables
S1 + S2 + S3 ≥ 22
S2 + S3 + S4 ≥ 30
S3 + S4 + S5 ≥ 16
S4 + S5 + S6 ≥ 4
S5 + S6 + S7 ≥ 5
S6 + S7 + S8 ≥ 18
S7 + S8 + S1 ≥ 36
S8 + S1 + S2 ≥ 28
S1 ≥ 0,
S2 ≥ 0,
Non-negative constraints: S3 ≥ 0, S4 ≥ 0, S5 ≥ 0, S6 ≥ 0, S7 ≥ 0, and S8 ≥ 0
13
P2686827
PART 2 BUSINESS INTELLIGENCE SYSTEMS - TABLEAU
Tableau Prep
The following data documents were uploaded into the tableau prep builder in order to give
more information about 62 day standard cancer waiting times: names of the current hospitals,
information about the health boards, geographical codes, and 62-day waiting standards for
cancer waiting times recorded.
The cleaning was done in different steps with the first step of merging the special health board
and hb14 dataset by a union where 2 rows not needed were removed, followed by 3 different
join functions; join1(right join), join 3(left join) and join 5(middle join) were the files were
merged and cleaned to removed unwanted values and dates such as null values, fields with
QF and HBT were removed also, changing quarter to date format and renaming it as Time,
adjusting my range of dates, filtering the cancer values to show for only urological cancer
types etc. I then cleaned the data as seen in step 6 where HB and SHB fields were removed
and postcode was split and cleaned. The final results of the cleaning steps can be seen in
output where 8 rows remained of the cleaned data to be examined. The steps can be seen in
the screenshots below.
Step One
14
P2686827
Step Two
Step Three
Step Four
15
P2686827
Step Five
Step Six
Step Seven:
16
P2686827
Dashboard
Access Link:
https://public.tableau.com/app/profile/simi.oduba/viz/P2686827TABLEAUCWTDASHB
OARD/P2686827TABLEAUDASHBOARD
Scotland's percentage of referrals for various types of urological cancer is depicted in a time
series chart..
Geographical map displaying the proportion of referrals treated at each hospital location in
Scotland.
17
P2686827
Tree Map for the Health Board displaying the percentage of treated referrals for each health
Board.
Table highlighting the proportion of referrals treated for each kind of cancer per quarter; 2012-
2021.
Dashboard of the overall data
18
P2686827
Explanation of Dashboard’s output of NHS Scotland
The dashboard displays a time series chart, a geographic graph, a tree map of the health
boards, and a table of the percentage of referrals treated for cancer in NHS Scotland. The
time series graph that was found showed that the percentage of referrals treated among all
health boards of the NHS Scotland experienced a negative trend series pattern from a high
referral rate of 93% in 2012Q1 and only experienced an increase of 71% between Q3 and Q4
of 2020 the peak of the Covid period after which it reduced again to the range of 60% by the
last quarter of 2021.
The geographical map indicated that mostly the Southern regions and the Eastern regions
were the areas where a high number of referrals occurred with the Western and Northern
regions having the lowest records of referrals. All the regions had referrals above average with
the lowest referral rate being 51%.
The health board treemap shows with the help of the color gradient the deepest red color with
health board NHS Ayrshire and Arran with 93% has the highest number of referrals out of all
the health boards with NHS Highland having the lowest referrals of 51% patients. This can
help the management know which health boards to focus on and redistribute their resources
accordingly.
The percentage of referrals that have received treatment is displayed in the highlight Table.
throughout the quarterly period from 2012-2021. It shows that show 3 health boards had a 0%
referral rate for some quarters such as NHS Orkney, NHS Western Isles, and NHS Shetland
while some health boards had 100% referral rates at certain quarters also including some who
had 0% had at a point i.e NHS Western Isles, NHS Shetland, NHS Ayrshire and Arran, NHS
Orkney. Some health boards also had missing values for certain quarters majorly NHS
Orkney, NHS Western Isles, and NHS Shetland had few missing values.
This denotes that there has been a low improvement in the number of treated patients in
Scotland in the time series chart of the percentage of referrals treated. It implies that there is
a need for developing a significant improvement in increasing the percentage rate of referral
treatment in the hospital through increasing the facilities and funding package for the NHS in
Scotland. Through this analysis, the NHS Scotland has an overview of where the next phase
of a strategy to be targeted i.e providing facilities or funding that can increase the percentage
of referred treatment in Scotland overall.
19
P2686827
PART 3: ETHICAL ISSUES IN BUSINESS INTELLIGENCE
Legal
Governmental bodies or policies exist to guide the treatment of patients with cancer in NHS
Scotland. Who is held liable for dates prescribed to patients who end up not getting treated or
who is in charge of the consequences of the actions or inactions of the health system, is it the
management or the NHS? Great care must be made towards the actions and systems
implemented by the NHS so as to avoid suits or legal issues arising in regard to patient’s
treatments and welfare.
Ethics
Ethics is a critical aspect of business intelligence due to the involvement of data in decisionmaking
in any situation (Kemparaj & Kadalur, 2018). For example, in the case of NHS, the
body expects to secure the data on the treatment of referred cancer patients to enable the
process effectively because there will be cases of disagreement in the output. There should
be informed consent of data use to patients and ensure the integrity of the NHS Scotland as
a whole. Sharing of data with other agencies should be questioned and monitored so patient’s
records are not exploited.
Privacy issues
In this aspect, the Privacy of the data should be given priority through standard confidential
processes. For instance, the analysis for NHS Scotland on the percentage of referred treated
above reveals a negative trend that needs to be private to prevent escalating among
opposition political parties or citizens. It should be of note that the NHS Scotland’s data
shouldn’t be shared with 3rd parties and abused, and the privacy of information shouldn’t be
entirely generalized as patient’s information vary from individual to individual.
20
P2686827
References
Cancer survival statistics - People diagnosed with cancer during 2015 to 2019 - Cancer
survival statistics - Publications - Public Health Scotland
Eiselt H. A. & C. L. Sandblom, (2007). Linear Programming and its Applications. Springer-
Verlag Berlin Heidelberg Publication.
Hyndman, R. J. and Athanasopoulos, G. (2021). Forecasting: principles and practice.
Melbourne, Australia: OTexts.
Kemparaj V. M. & Kadalur, U. G. (2018). Understanding the principles of ethics in health
care: a systematic analysis of qualitative information. Int J Community Med Public
Health, 5(8), 822-8.
Lightner, N. J. (2018). Advances in Human Factors and Ergonomics in Healthcare and
Medical Devices. Proceedings of the AHFE 2018 International Conference on Human
Factors and Ergonomics in Healthcare and Medical Devices. Springer.
Talha, K. B. (2022). Cancer survival rates in Scotland. Cancer survival rates in Scotland - The
Lancet Oncology
