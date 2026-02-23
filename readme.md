# Data Science Lifecycle: Question → Data → Insight

## 1. Understanding the Lifecycle

### Starting with a Clear Question

Every data science task should begin with a specific and decision-focused question, not with a dataset or tools.

**A clear question:**

- Defines the real problem
- Identifies what needs to be measured
- Ensures the analysis is useful

**If we skip this step, we may:**

- Analyze irrelevant data
- Generate interesting but useless results
- Fail to support any real decision

So the question acts as a direction for the entire workflow.

### Data as Evidence (Not Just Numbers)

Data is not automatically correct or complete.
It is created by systems and people, which means it can contain:

- Missing values
- Bias
- Errors
- Incomplete records

Understanding the data involves:

- Knowing the source (database, logs, survey, API, etc.)
- Understanding what each column represents
- Checking whether the data can actually answer the question

This step ensures we are working with relevant and reliable evidence, not blindly running analysis.

### Insights Come from Exploration

Before making conclusions, we must explore the data using:

- Summary statistics
- Distributions
- Comparisons between groups
- Trend observation

At this stage we:

- Observe patterns
- Do not force explanations
- Do not jump to conclusions

An observation becomes an insight only when it is connected to the original question and helps in decision-making.

### Example:

**Observation:**

Users with longer loading time leave earlier

**Insight:**

Improving page load speed may reduce user drop-off

### How the Lifecycle Connects

The flow is:

**Question → decides → what data is needed → exploration → insight → decision**

Each step depends on the previous one.
If the question is wrong, everything that follows becomes meaningless.

-------------------------------

## 2. Applying the Lifecycle to a Project Scenario

### Project Context: Student Learning Platform
**Question**

*Why do some students stop using the platform after the first week?*

This question helps in:

- Improving student retention
- Designing better onboarding
- Increasing course completion

### Data Required

**Possible data sources:**

- User activity logs
- Login frequency
- Time spent per session
- Assignment submission records

**What the data represents:**

- Login frequency → engagement level
- Session duration → learning effort
- Feature usage → student behavior
- Last active day → drop-off point

**We would also verify:**

- Is the data complete?
- Are inactive users properly tracked?
- Is the time data accurate?

### Useful Insight for Decision-Making

A meaningful insight would be:

Students who do not complete their first assignment within 3 days are much more likely to become inactive.

This insight can lead to actions like:

- Early reminder notifications
- Guided onboarding
- Simplifying the first task

So the insight directly supports product improvement decisions.

----------------------------------------------------

### Key Takeaways

From this milestone, I learned to:

- Frame a clear and meaningful data question
- Treat data as evidence with limitations
- Perform exploration before making conclusions
- Convert observations into actionable insights

This approach ensures that future analysis and model building will be purpose-driven and aligned with real-world decisions.