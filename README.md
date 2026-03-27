# data-analytics-journal
personal log for tracking data analytics skills, formulas, and projects
## Learning Log March 2026
### Data Types
* Numerical
* String/Text
* Date
* Categorical

Example for a workout log:
* **150 lbs**: Numerical
* **"Great workout!"**: String
* **2026-03-27**: Date
* **Yoga**: Categorical

### Key Data Realizations 💡

* **Double purposes of numbers in data**: A number isn't always strictly **Numerical**. If you are calculating something like an average, then it's numerical; if you are using it to group people, it's **Categorical**. *Example*: Customer satisfaction ratings can both be treated numerically to get an average (e.g., 4.2 stars), OR the ratings can be used to group the data/people (i.e., 1 star vs 5 star ratings).
* **String vs. Categorical**: **Strings** are unique and "messy" (like notes), and they are variable. **Categorical** data uses specific "labels" (like workout types) to help with filtering; they are fixed to specific options (e.g., small, medium, large).
* **String** data can be *both* ID information as well as descriptive information.
* **Dates are Points, Durations are Measurements**: A **Date** is a point in time (When). You can subtract two dates to get a **Duration**, which is a **Numerical** value (How long).

## The 6 Phases of Data Analysis 🔄

I am using these phases as a roadmap to solve data-related problems.

1. **Ask** ❓: Define the business challenge. 
   * *Goal:* What is the specific question we need to answer?
2. **Prepare** 🏗️: Collect and store the data.
   * *Goal:* Identify which data sources are credible and relevant.
3. **Process** 🧹: Clean the data.
   * *Goal:* Fix inconsistencies (like "Excellent" vs "5") and handle missing values.
4. **Analyze** 🧐: Find patterns.
   * *Goal:* Use math and logic to see how variables relate to each other.
5. **Share** 📊: Visualize findings.
   * *Goal:* Build charts that tell a clear story to stakeholders.
6. **Act** 🚀: Take a data-driven step.
   * *Goal:* Use the final insights to solve the original problem.

---

## Reference Dataset: Fitness App Orders 📋

I am using this sample data to practice identifying types and issues.

| Order ID | Product Name | Quantity | Order Date | Customer Rating |
| :--- | :--- | :--- | :--- | :--- |
| 1001 | Wireless Earbuds | 2 | 2025-07-01 | 5 |
| 1002 | Smart Watch | 1 | 2025-07-05 | 4 |
| 1003 | Portable Speaker | 3 | 2025-06-28 | **Excellent** (Inconsistent) |
| 1004 | USB-C Cable | 5 | 2025-07-10 | 3 |
| 1005 | Hard Drive | 1 | 2025-07-12 | *[Blank]* (Missing) |

---

## Data Type Quick-Ref 🧪

* **Numerical:** `Quantity`, `Rating` (when cleaned)
* **Categorical:** `Product Name`
* **String:** `Order ID` (Unique identifier)
* **Date:** `Order Date`
* **Boolean:** (Planned) - e.g., `Goal_Reached?` (True/False)

  ---
  ## Data Analysis in Psychology & Social Science 🧠

As a graduate of a bachelor's in psychology, I can map the **6 Phases** to the research process:
It is similar to the **scientific method**. E.g., the Ask phase is like forming a hypothesis, while "Analyze" is where statistics such as t-tests or ANOVAs are used.
  
1. **Ask** ❓: Translating a behavioral theory into a measurable question.
   * *Example:* "Does a 10-minute mindfulness app session reduce self-reported anxiety scores?"
2. **Prepare** 🏗️: Identifying variables and sampling.
   * *Example:* Collecting Likert-scale responses from a diverse group of college students.
3. **Process** 🧹: Data cleaning and validation.
   * *Example:* Identifying "Outliers" (e.g., a student who finished a 20-minute survey in 2 minutes) and standardizing scores (Z-scores).
4. **Analyze** 🧐: Testing the hypothesis.
   * *Example:* Comparing the mean anxiety scores of the "App Group" vs. the "Control Group."
5. **Share** 📊: Communicating results visually.
   * *Example:* Creating a Bar Chart with error bars to show the significance of the findings.
6. **Act** 🚀: Applying findings to clinical or real-world settings.
   * *Example:* Recommending the app to be integrated into campus counseling centers.

---

## Psychology & Stats: Data Type Examples 🧪

| Data Category | Psychology/Research Example |
| :--- | :--- |
| **Numerical (Discrete)** | Number of therapy sessions attended. |
| **Numerical (Continuous)** | Reaction time in milliseconds on a cognitive task. |
| **Categorical (Nominal)** | Diagnostic category (e.g., MDD, GAD, ADHD). |
| **Categorical (Ordinal)** | Likert Scale (1 = Strongly Disagree to 5 = Strongly Agree). |
| **Boolean** | Diagnosis Met? (True / False). |
| **String** | Patient clinician notes or open-ended interview transcripts. |

---

## Psychology & Data Analysis 💡

* **Inconsistent Data** in psych often looks like "N/A" vs "No Answer" in a survey. Cleaning this is vital to ensure the *Validity* of the study.
* **Missing Data** is common in longitudinal studies. Deciding whether to use the "Mean" to fill the gap or remove the participant is a major ethical and statistical decision.
