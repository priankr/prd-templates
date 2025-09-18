# Peter Yang's PRD Template

## Product/Feature Name

### **1. Header**

In the header, include:

1. **Links** to other essential artifacts like designs.
2. **Team** names of people who are working on this feature.
3. **Last updated** date.

**Header Example:**

**Links
- [Design]
- [Analytics]
- [Meeting Notes]

**Team
-** PM: TBD
- Design: TBD
- EM: TBD
- Analytics: TBD
- Marketing: TBD

**Last updated:** 5/10/24

### **2. Problem**

Always start your PRD with the customer problem you’re trying to solve. Answer these questions in a few sentences:

1. Who is the customer?
2. What is the customer problem?
3. How do we know that this is a problem?

**Problem Example:**

New users want to view topics that they're interested in when they first sign up for Pinterest.Today, all new users see the same feed of the most popular content. This content is dominated by a few categories like women's fashion and decor that don't align with the diverse interests of all new users (see appendix for research).

We want to test letting new users select topics during onboarding to personalize their feed.

### **3. Goals**

List one output goal for your feature and 2-3 input metrics to drive the output. Include non-goals and guardrail metrics when relevant.

**Goals Example:**

**Output:
-** Increase activation rate by 20% (% of sign-ups who return in 7 days).

**Inputs:
-** Users who visit topic selector screen.
- Who select a topic and how many topics they select.
- Who pin during their first session.

### **4. Solution**

Describe the solution and key milestones at a high level. Then, for each milestone:

1. List each feature as a user story and be concise.
2. Mark clearly which features are P0 and P1.
3. Highlight any open topics in the requirements for async discussion.
4. Consider including a wireframe or design to bring the feature to life.

**Solution Example:**

We want to test this topi in two milestones:
1. **M1:** Test topic selector in onboarding and personalize feed based on topics
2. **M2:** Test using age, gender, and language signals to personalize the topic selector

**M1: Test topic selector in onboarding flow and personalized feed based on topics**
Link To Design

Example:

| **P0** | **See topic selector during onboarding
-** As a new user signing up to Pinterest, I see a *“Pick 5 or more topics to personalize your feed”* screen after signing up with email or phone number.
- The screen shows a grid of the most popular topics and a button labeled *“Meet your home feed”* that is initially disabled.
- Once I select 5+ topics, the button activates and I can click it to visit my Home Feed.

Discussion
**-** Peter: How should we rank the topics? |
| --- | --- |
| **P0** | **Home feed with content from topics that I selected**

When I visit the home feed for the first time, I see popular and recent content from the topics I selected. |

### **5. Launch plan**

Define your launch plan (e.g., is it a staged rollout or an experiment?). For experiments, define the success criteria, eligibility, test, control, and ramp plan.

**Launch Plan Example:**

**Topic selector experiment
1. Success criteria:** Grow activation rate by 20% (% of sign ups who visit again in 7 days)
2. **Eligibility:** People who sign up for Pinterest on web and mweb
3. **Test:** Experience described above
4. **Control:** Existing onboarding experience without “topic selector” screen
5. **Ramp plan:** 50/50 experiment

### **6. Meeting Notes**

Take meeting notes directly in the PRD. This ensures that the latest discussions and decisions are captured in a single document.

**Meeting Notes Example:**

**Team sync – 5/10**

**1. Peter:** Why are we forcing users to select 5+ topics?
2. **Wendy:** Data science has research showing that users who select at least 5 topics tend to retain better.
3. **Bob:** Suggest A/B the minimum number of topics in a subsequent experiment.

### **7. Appendix**

Keep your PRD short and link to a lengthy appendix with relevant information, such as customer interviews, competitive research, and supporting data.


**View Original Template:** [Peter Yang PRD Template](https://creatoreconomy.so/p/my-prd-template-how-to-write-with-ai)

