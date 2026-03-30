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

---
## Iteration: "Non-Linear" 🔄

Data analysis is rarely linear. It is an **iterative process**, meaning findings in later stages often require you to revisit earlier ones.

* **Feedback Loop:** You might reach the *Analyze* phase only to realize the data was pulled from a biased sample (back to *Prepare*), or that your survey question was poorly phrased (back to *Ask*).
* **Avoid "Shortcut" Traps:** The biggest mistake is rushing to an answer. Skipping steps or ignoring inconsistencies leads to "Type I" or "Type II" errors in your conclusions.
* **Continuous Growth:** Reviewing your work at each phase doesn't just improve the data—it improves your skills as an analyst.

### Psychology Connection: Iteration in Action 🧠
| If you find this... | ...Go back to this phase |
| :--- | :--- |
| Outliers that suggest participants didn't understand the task. | **Process** (to re-filter or investigate) |
| Results that don't answer the original hypothesis. | **Ask** (to refine the research question) |
| Missing demographic data needed for a sub-group analysis. | **Prepare** (to find additional data sources) |

---

# Course 1, Module 1: Foundations of Data Analytics 🏗️

## The Analytical Mindset 🧠
* **Analytical Skills:** Qualities and characteristics associated with using facts to solve problems.
* **Analytical Thinking:** The process of identifying and defining a problem, then solving it by using data in an organized, step-by-step manner.
* **Technical Mindset:** The ability to break things down into smaller steps or pieces and work with them in an orderly and logical way.
* **Data Analyst:** Someone who collects, transforms, and organizes data in order to draw conclusions, make predictions, and drive informed decision-making.

## Core Definitions 🔬
* **Data:** A collection of facts.
* **Dataset:** A collection of data that can be manipulated or analyzed as one unit.
* **Data Analytics:** The science of data.
* **Data Analysis:** The collection, transformation, and organization of data to draw conclusions, make predictions, and drive informed decision-making.
* **Data Science:** A field of study that uses raw data to create new ways of modeling and understanding the unknown.

## The Data Environment & Strategy 🌐
* **Data Ecosystem:** The various elements that interact with one another in order to produce, manage, store, organize, analyze, and share data.
* **Data Strategy:** The management of the people, processes, and tools used in data analysis.
* **Data Design:** How information is organized.
* **Data-Driven Decision-Making:** Using facts to guide business strategy.

## Problem-Solving Tools 🛠️
* **Context:** The condition in which something exists or happens. 
* **Root Cause:** The fundamental reason why a problem occurs.
* **Gap Analysis:** A method for examining and evaluating the current state of a process to identify opportunities for improvement.
* **Data Visualization:** The graphical representation of data.

---

## Applied Learning: Context vs. Root Cause 🔍
In my Psychology background, **Context** is the background that gives meaning to data, while a **Root Cause** is the specific factor we can change to solve a problem.

* **Scenario:** A spike in student anxiety levels in May.
* **Data:** Anxiety scores (Numerical).
* **As Context:** "Finals Week" explains why the scores are high. It provides the "Why" behind the trend.
* **As Root Cause:** If the problem is that students are failing, and the data shows they have four exams on the same day, the "Exam Schedule" is the root cause we can actually fix.

---

## Iteration & The Non-Linear Process 🔄
Data analysis is **iterative**. We often move back and forth between phases as we discover new information. Analysts must be willing to "loop back" to ensure quality.

| If you find this... | ...Go back to this phase |
| :--- | :--- |
| Outliers suggesting participants didn't understand the task | **Process** (to re-clean or investigate) |
| Results that don't answer the original hypothesis | **Ask** (to refine the research question) |
| Missing demographic data needed for a sub-group analysis | **Prepare** (to find additional data sources) |

# Course 1, Module 2: The Data Life Cycle 🔄

**Key Distinction:** The **Data Analysis Process** is about solving a specific problem (Ask, Prepare, Process, Analyze, Share, Act). The **Data Life Cycle** is about the management of the data itself from "birth" to "death."

## The Standard 6-Stage Life Cycle
1. **Plan:** Decide what data is needed and how it will be managed.
2. **Capture:** Collect data from various sources.
3. **Manage:** Store and maintain the data (tools and security).
4. **Analyze:** Use the data to solve problems or support goals.
5. **Archive:** Store relevant data for long-term future reference.
6. **Destroy:** Securely delete data and all shared copies.

---

## Industry Variations & Priorities 🏢
Different sectors emphasize different stages based on their specific goals:

| Organization | Priority | Unique Stages |
| :--- | :--- | :--- |
| **Finance** | Security & Compliance | *Qualify, Purge* |
| **USGS (Geological)** | Documentation | *Preserve, Metadata* |
| **Harvard (Research)** | Meaning & Context | *Visualization, Interpretation* |

### Psychology & Research Perspective 🧠
The **Harvard 8-Step Model** (Generation, Collection, Processing, Storage, Management, Analysis, Visualization, Interpretation) is most relevant to social science. 
* It emphasizes **Interpretation**—the crucial step of assigning human meaning to the statistical results.
* Unlike Finance, Research often omits "Purge/Destroy" because historical data is vital for longitudinal studies and validating past theories.

---

## The Universal Rule: Data Governance 💡
Regardless of the model, analysts must govern how data is handled so that it remains **accurate, secure, and available** to meet the organization's needs.

# Course 1, Module 2: The Data Analysis Process (The 6 Phases) 🗺️

While the **Data Life Cycle** manages the data's "life," the **Data Analysis Process** is the specific path used to solve a problem and find answers.

### 1. Ask ❓
* **Goal:** Define the problem and understand stakeholder expectations.
* **Key Task:** Identify the "Gap" between the current state and the ideal state.
* **Psychology Connection:** Similar to defining a research hypothesis—if the question is flawed, the data won't help.

### 2. Prepare 📑
* **Goal:** Identify and locate the data needed to answer the questions.
* **Key Task:** Ensure data is objective, unbiased, and credible.

### 3. Process 🧼
* **Goal:** Clean and refine data to ensure accuracy.
* **Key Task:** Remove outliers, fix errors, and transform data using **SQL** and **Spreadsheets**.

### 4. Analyze 📉
* **Goal:** Turn raw data into actionable information.
* **Key Task:** Use **Python**, **SQL**, and **Spreadsheets** to find patterns and draw conclusions.

### 5. Share 📢
* **Goal:** Interpret results and communicate findings.
* **Key Task:** Use **Data Visualization** to tell the "story" of the data so stakeholders can make decisions.

### 6. Act 🚀
* **Goal:** Put insights to work.
* **Key Task:** In this program, this culminates in a **Capstone Case Study**—a real-world project to showcase in my professional portfolio.

---

## The Certification Roadmap 🎓
This program is structured to master each phase individually:

1. **Ask:** *Ask Questions to Make Data-Driven Decisions*
2. **Prepare:** *Prepare Data for Exploration*
3. **Process:** *Process Data from Dirty to Clean*
4. **Analyze:** *Analyze Data to Answer Questions* & *Intro to Python*
5. **Share:** *Share Data Through the Art of Visualization*
6. **Act:** *Google Data Analytics Capstone: Complete a Case Study*

---

> **Analyst Tip:** The transition from **Analyze** to **Share** is where the "Psychology" of data happens—it's not just about the numbers, it's about how you help others understand and trust them.
