# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

## Method

**Method:** Multi-Armed Bandit

**Why:** Multi-Armed Bandit is suitable because we want to test multiple approaches to helping FinWise trial users experience value after importing financial data. Instead of splitting traffic equally throughout the experiment, MAB dynamically allocates more users to the better-performing experience, helping us optimize activation while minimizing exposure to less effective variants.

_____

## Hypothesis + primary metric

IF we dynamically optimize the post-import experience using different guidance approaches, THEN more trial users will complete their first financial model within 7 days, BECAUSE personalized guidance and reduced friction will help users experience FinWise's core value faster.

**Primary metric:** Percentage of trial users who generate their first financial model within 7 days of successfully importing financial data., target: Achieve at least a 20% relative increase in first-model completion rate compared with the control experience, while keeping guardrail metrics within acceptable limits.

_Experiment: FinWise First Value Experience Optimization, Increase the percentage of trial users who generate their first financial model within 7 days of importing financial data, helping them experience FinWise's core value and potentially improving Trial-to-Paid Conversion Rate._

_Testing Three post-import experiences: A) Existing experience, B) Guided walkthrough to create the first financial model, and C) Instant financial insights preview with a CTA to create a model. A Multi-Armed Bandit will dynamically allocate more traffic to the better-performing variant. on FinWise trial users who successfully complete their first financial data import but have not yet generated their first financial model.. Current experience: After importing financial data, trial users are assumed to navigate independently to the Financial Modeling feature. Without clear guidance, some users may struggle to generate their first financial model and experience the product's value.._

_Predicted outcome: Trial users exposed to guided modeling or instant financial insights will achieve at least a 20% relative increase in first-model completion within 7 days compared with the control experience, as the Multi-Armed Bandit allocates more traffic to the better-performing variant.. If successful: Roll out the highest-performing post-import experience to all eligible trial users. Monitor whether increased first-model completion translates into improved Trial-to-Paid Conversion and long-term retention.. If unsuccessful: Analyze where users abandon the modeling journey, review completion time and user feedback, and investigate whether the friction comes from feature complexity, unclear financial insights, or insufficient perceived value. Use these findings to design a new experiment.._

_____

## Guardrail + read date

- **Guardrail:** Post-import abandonment rate must not increase by more than 5 percentage points compared with the control group.
- **Read date:** 28 days after experiment launch, after allowing 7 additional days for the final enrolled users to complete their first model.

_____
