### Data integrity
The accuracy, completeness, consistency, and trustworthiness of data throughout its lifecycle.

Data integrity can be compromised in lots of different ways. There's a chance data can be compromised every time it's replicated, transferred, or manipulated in any way.
- **Data replication**: The process of storing data in multiple locations. If you're replicating data at different times in different places, there's a chance your data will be out of sync. This data lacks integrity because different people might not be using the same data for their findings, which can cause inconsistencies.
- **Data transfer**: The process of copying data from a storage device to memory, or from one computer to another. If your data transfer is interrupted, you might end up with an incomplete data set, which might not be useful for your needs.
- **Data manipulation**: The process of changing the data to make it more organized and easier to read. Data manipulation is meant to make the data analysis process more efficient, but an error during the process can compromise the efficiency.
- **Other threats**: Data can also be compromised through human error, viruses, malware, hacking, and system failures.

### Data Constraints and Examples

As you progress in your data journey, you'll encounter many types of data constraints (criteria determining validity). The table below offers definitions and examples of data constraint terms you might come across.

| Data Constraint | Definition | Examples |
|---|---|---|
| Data type | Values must be of a certain type: date, number, percentage, Boolean, etc. | If the data type is a date, a single number like 30 would fail the constraint and be invalid |
| Data range | Values must fall between predefined maximum and minimum values | If the data range is 10-20, a value of 30 would fail the constraint and be invalid |
| Mandatory | Values can't be left blank or empty | If age is mandatory, that value must be filled in |
| Unique | Values can't have a duplicate | Two people can't have the same mobile phone number within the same service area |
| Regular expression (regex) patterns | Values must match a prescribed pattern | A phone number must match ###-###-#### (no other characters allowed) |
| Cross-field validation | Certain conditions for multiple fields must be satisfied | Values are percentages and values from multiple fields must add up to 100% |
| Primary-key | (Databases only) value must be unique per column | A database table can't have two rows with the same primary key value. A primary key is an identifier in a database that references a column in which each value is unique. More information about primary and foreign keys is provided later in the program. |
| Set-membership | (Databases only) values for a column must come from a set of discrete values | Value for a column must be set to Yes, No, or Not Applicable |
| Foreign-key | (Databases only) values for a column must be unique values coming from a column in another table | In a U.S. taxpayer database, the State column must be a valid state or territory with the set of acceptable values defined in a separate States table |
| Accuracy | The degree to which the data conforms to the actual entity being measured or described | If values for zip codes are validated by street location, the accuracy of the data goes up. |
| Completeness | The degree to which the data contains all desired components or measures | If data for personal profiles required hair and eye color, and both are collected, the data is complete. |
| Consistency | The degree to which the data is repeatable from different points of entry or collection | If a customer has the same address in the sales and repair databases, the data is consistent. |

Clean data + alignment to business objective = accurate conclusions <br>
Alignment to business objective + additional data cleaning = accurate conclusions <br>
Alignment to business objective + newly discovered variables + constraints = accurate conclusions 

Maintaining data integrity helps ensure a close alignment of data and business objectives because the data is likely to be accurate, complete, consistent, and trustworthy.

---

Types of insufficient data:
- Data from only one source
- Data that keeps updating
- Outdated data
- Geographically-limited data

Ways to address insufficient data:
- Identify trends with the available data
- Wait for more data if time allows
- Talk with stakeholders and adjust your objective
- Look for a new dataset

<details><summary>Consider the following data issues and suggestions on how to work around them.</summary>
  <h5>Data issue 1: no data</h5><ul><li>Gather the data on a small scale to perform a preliminary analysis and then request additional time to complete the analysis after you have collected more data. </li><li>If there isn’t time to collect data, perform the analysis using proxy data from other datasets. This is the most common workaround.</li></ul>
  
  <h5>Data issue 2: too little data</h5><ul><li>Do the analysis using proxy data along with actual data.</li><li>Adjust your analysis to align with the data you already have.</li></ul>

  <h5>Data issue 3: wrong data, including data with errors</h5><ul><li>If you have the wrong data because requirements were misunderstood, communicate the requirements again.</li><li>Identify errors in the data and, if possible, correct them at the source by looking for a pattern in the errors.</li><li>If you can’t correct data errors yourself, you can ignore the wrong data and go ahead with the analysis if your sample size is still large enough and ignoring the data won’t cause systematic bias. </li></ul>
  
![image](https://user-images.githubusercontent.com/74421758/147212712-c7f0263e-c40a-4cdb-b290-8adc2ec3499a.png)
  
</details>

### Proxy Data Examples

Sometimes the data to support a business objective isn’t readily available. This is when proxy data is useful. Take a look at the following scenarios and where proxy data comes in for each example:

#### Business Scenarios and Proxy Data Usage

| **Business Scenario** | **How Proxy Data Can Be Used** |
|-----------------------|--------------------------------|
| A new car model was just launched a few days ago and the auto dealership can’t wait until the end of the month for sales data to come in. They want sales projections now. | The analyst proxies the number of clicks to the car specifications on the dealership’s website as an estimate of potential sales at the dealership. |
| A brand new plant-based meat product was only recently stocked in grocery stores and the supplier needs to estimate the demand over the next four years. | The analyst proxies the sales data for a turkey substitute made out of tofu that has been on the market for several years. |
| The Chamber of Commerce wants to know how a tourism campaign is going to impact travel to their city, but the results from the campaign aren’t publicly available yet. | The analyst proxies the historical data for airline bookings to the city one to three months after a similar campaign was run six months earlier. |


#### Random sampling
A way of selecting a sample from a population so that every possible type of the sample has an equal chance of being chosen.

[Caluculating sample size](https://drive.google.com/file/d/1D_yQ1ph_I4F7D-5nVwx5iJ9YmbcO7-cC/view?usp=sharing)

Pre-cleaning activities help you determine and maintain data integrity and are important because they increase the efficiency and success of your data analysis tasks. One of the objectives of pre-cleaning activities is to address insufficient data. <br> If you know that your data is accurate, consistent, and complete, you can be confident that your results will be valid. Stakeholders will be pleased if you connect the data to business objectives. And, knowing when to stop collecting data will allow you to finish your tasks in a timely manner without sacrificing data integrity. Data analysts perform pre-cleaning activities to complete these steps.

---

#### Statistical power
The probability of getting meaningful results from a test. Statistical power can be calculated and reported for a completed experiment to comment on the confidence one might have in the conclusions drawn from the results of the study. It can also be used as a tool to estimate the number of observations or sample size required in order to detect an effect in an experiment.

#### Hypothesis testing
A way to see if a survey or experiment has meaningful results. 

Statistical power is usually shown as a value out of one. If a test is statistically significant, it means the results of the test are real and not an error caused by random chance. Usually, you need a statistical power of at least 0.8 or 80% to consider your results statistically significant.

#### Confidence level
The probability that your sample accurately reflects the greater population. Having a 99 percent confidence level is ideal but most industries hope for at least a 90 or 95 percent confidence level.

**Estimated response rate**: If you are running a survey of individuals, this is the percentage of people you expect will complete your survey out of those who received the survey.

A sample size calculator tells you how many people you need to interview (or things you need to test) to get results that represent the target population. To calculate sample size using an online calculator, it’s necessary to input the confidence level, margin of error, and population size. [Calculator](https://docs.google.com/spreadsheets/d/1kBTvnpH2qOLJx4XWjUG1v-GF4LPmOhequy_9VRyslJ8/template/preview). The calculated sample size is the minimum number to achieve what you input for confidence level and margin of error. If you are working with a survey, you will also need to think about the estimated response rate to figure out how many surveys you will need to send out.

---

#### Margin of error
The maximum amount that the sample results are expected to differ from those of the actual population. The closer to zero the margin of error, the closer your results from your sample would match results from the overall population. The more people you include in your survey, the more likely your sample is representative of the entire population. Decreasing the confidence level would also have the same effect, but that would also make it less likely that your survey is accurate. To calculate margin of error, you need three things: population size, sample size, and confidence level. [Calculator](https://docs.google.com/spreadsheets/d/1gdhfyA3_vMnQ1cDaGSCshXd5ezLtVPfLhxc9STGq6B8/template/preview).

#### Population
This is the total number you hope to pull your sample from.

#### Sample
A part of a population that is representative of the population.

#### Estimated response rate
If you are running a survey of individuals, this is the percentage of people you expect will complete your survey out of those who received the survey.

---

### Glossary Terms from Module 1

Terms and definitions for Course 4, Module 1

- **Accuracy:** The degree to which the data conforms to the actual entity being measured or described

- **Completeness:** The degree to which the data contains all desired components or measures

- **Confidence interval:** A range of values that conveys how likely a statistical estimate reflects the population

- **Confidence level:** The probability that a sample size accurately reflects the greater population

- **Consistency:** The degree to which data is repeatable from different points of entry or collection

- **Cross-field validation:** A process that ensures certain conditions for multiple data fields are satisfied

- **Data constraints:** The criteria that determine whether a piece of data is clean and valid

- **Data integrity:** The accuracy, completeness, consistency, and trustworthiness of data throughout its life cycle

- **Data manipulation:** The process of changing data to make it more organized and easier to read

- **Data range:** Numerical values that fall between predefined maximum and minimum values

- **Data replication:** The process of storing data in multiple locations

- **DATEDIF:** A spreadsheet function that calculates the number of days, months, or years between two dates

- **Estimated response rate:** The average number of people who typically complete a survey

- **Hypothesis testing:** A process to determine if a survey or experiment has meaningful results

- **Mandatory:** A data value that cannot be left blank or empty

- **Margin of error:** The maximum amount that the sample results are expected to differ from those of the actual population

- **Random sampling:** A way of selecting a sample from a population so that every possible type of the sample has an equal chance of being chosen

- **Regular expression (RegEx):** A rule that says the values in a table must match a prescribed pattern

---
