# OSM-A-B-Testing-Analysis
**Aim:** To check if the Tutorial impacts the User's Retention Rate, using A/B Testing Analysis.

**Dataset used:** OpenStreetMap (OSM) Users' synthetically generated Dataset

**Methods used:** A/B testing. Statistical analysis, Hypothesis testing, Segment analysis

**Stakeholders:** Product development team, Finance team, Marketing team

Statistical findings:

<img width="4451" height="3387" alt="Image" src="https://github.com/user-attachments/assets/866e8fe5-372c-4196-b9ca-5e4c3ddafc06" />

**Process:**
1. Pre-Test Research: Define the objective and collect data accordingly
2. Hypothesis Generation: Generate the guess (e.g, red color button vs green color button, which will work better?) 
3. Split Test Design: Split the data randomly into two groups: Control and Variant
4. A/B Testing: Performing hypothesis testing to develop statistical metrics that will support your assumptions.
5. Test Result Analysis: Analyse the test results by calculating their business impact.
6. Implement Winner: If your assumption is valid, apply changes to your product accordingly.

**Key Findings:** 
1. Retention rate for tutorial is 40.17%, and for no tutorial is 37.05%. Difference in **retention = 2.69%.**
2. The interval for retention difference is entirely positive. Suggesting the tutorial does improve retention.
3. With a p-value of 0.00687, it confirms that our retention difference is not a coincidence. Watching a tutorial does affect retention.
4. Also, **86.8%** as the statistical power shows a high probability of detecting the true effect.
5. After further classification, with an effect size of 0.0502, states that the difference exists but is negligible in practical terms.
6. Segment analysis shows that expert-level users contribute to a stronger tutorial effect, as compared to the new users.

**Limitations:**
1. Self-selection bias
2. Can't predict long-term.
3. The effect is negligible and will need more validation.

**Recommendations:**
1. Perform a Randomized Pilot test.
2. Apply targeted user rollout of tutorial.
3. Measure quality metric (e.g, user experience, edit quality, etc) along with retention.

Thank you.
