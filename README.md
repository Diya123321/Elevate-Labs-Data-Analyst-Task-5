# Elevate-Labs-Data-Analyst-Task-5
<br>
I have this time worked on Data Visualisation of the most famous dataset of all time "Titanic Dataset" colllected from "Kaggle.com".I tried to gain insights from it as much as possible.It was great working on this dataset 
 as it was a bit easy to visualise it and imagine it .<br>
 **All Insights I gained From the Dataset plot by plot**
<br>
<b>Basic Insights are</b><br>
The dataset contains 418 rows and 12 columns, representing passengers and their features.<br>Columns include: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked.<br>
Age, Cabin, and Embarked contain missing values.<br>

Cabin has many missing entries, possibly due to lower-class passengers not being assigned cabins.<br>

Data types show a mix of categorical (Sex, Embarked, Pclass as int but categorical), numeric (Age, Fare), and textual (Name, Ticket).<br>
Age ranges from 0.42 to 80 years. Mean ~29.7, suggesting a young to middle-aged population.<br>

Fare ranges widely from 0 to over 500, indicating a large disparity in ticket prices.<br>

Most passengers have 0 siblings/spouses and 0 parents/children onboard.<br>
About 38% survived and 62% did not, showing class imbalance in the dataset.<br>
Most passengers are in 3rd class.<br>

There are more males than females.<br>

Most passengers embarked from Southampton (S).<br>


<b>Insights from Histograms</b><br><br>
<b>Age Distribution</b><br>

The age distribution is slightly right-skewed, with the majority of passengers aged between 20 and 40 years. There are fewer children and elderly passengers.<br>

<b>Fare Distribution</b><br>

The fare distribution is heavily right-skewed, indicating that most passengers paid lower fares, with a few outliers who paid significantly more (likely 1st-class passengers).<br>

<b>SibSp and Parch<br></b>

Most passengers traveled alone or with one family member. A few passengers had large families aboard, which is rare and may indicate group bookings.<br><br>
<b>Insights from Boxplots</b><br><br>
<b>Age vs. Passenger Class (Pclass)<br></b>

Passengers in 1st class tend to be older on average than those in 2nd and 3rd classes. This may reflect socioeconomic status.<br>

<b>Fare vs. Sex<br></b>

Females generally paid higher fares than males, especially with a few female passengers showing very high fare outliers (possibly cabins or suite fares).<br>

<b>Age vs. Survival<br></b>

Survivors tend to be slightly younger than non-survivors, although outliers exist in both groups. The median age for survivors is lower.<br>
 <b>Insights from Pairplot</b><br><br>
,b>Fare and Survival Relationship</b><br>

In the pairplot, we observe that higher fare-paying passengers had a greater chance of survival, especially those clustered at lower age levels (young 1st-class women and children).<br>

<b>Age and Parch/SibSp</b><br>

Passengers with more siblings/spouses or parents/children tend to be younger. These passengers are more likely to be in families.<br>

<b>Clear Separation in Survival Patterns</b><br>

Some clusters (e.g., high Fare and low Age) appear to correlate with a higher likelihood of survival, showing a pattern of class-based rescue bias.<br>
<b>Insights from Scatterplots</b><br><br>
<b>Age vs. Fare by Survival</b><br>

Survivors (especially females) are mostly in the low-to-mid age range and paid higher fares, forming a visible upper-left cluster in the plot.<br>

<b>SibSp vs. Parch by Survival</b><br>

Passengers with 0 to 1 family members had a slightly higher survival chance. Those with many family members (e.g., 4+ SibSp or 3+ Parch) rarely survived.<br>
