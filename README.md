# Smart Insulin

Managing Type 2 diabetes can be tricky because patients need to take the right amount of insulin at the right time. If they take too much or too little, it can lead to serious health problems. Right now, many people rely on manual calculations or guesswork, which isn't always accurate.

Our project aims to make insulin delivery smarter and easier by using a Raspberry Pi (a small computer) and machine learning. Instead of relying on real-time sensors, we use historical data (past glucose and insulin records) to predict how much insulin a person needs. The Raspberry Pi will then control a small pump to automatically deliver the right amount of insulin (using water in our prototype).

Many individuals with Type 2 diabetes face challenges in determining the correct insulin dosage, as it depends on factors like food intake, physical activity, and overall health. Delays in administering insulin can result in dangerous fluctuations in blood sugar levels, leading to sudden spikes or crashes. Additionally, the risk of miscalculating the dosage, whether too much or too little, can cause serious health complications, making effective diabetes management both difficult and crucial.

---

## UX Team Members

* **Syd Ainsworth(https://github.com/UsabilityEngineering/ux-journal-5QU1D/tree/main/journal)** - (p01: Methods, Findings, Conclusions, Caveats) + (p02: Methods, Conclusions, Caveats)
* **Sri Ramani Thungapati(https://github.com/UsabilityEngineering/ux-journal-sthungapati/tree/main/journal)** - (p01: Methods, Findings, Conclusions, Caveats) + (p02: Findings, Conclusions)
* **Elizabeth E Rodriguez(https://github.com/UsabilityEngineering/ux-journal-babab0uille/tree/main/journal)** - (p01: Executive summary, Introduction, and Design Artifacts) + (p02: Wireframes, Executive summary, and Introduction)

---

# User-Centered Design Artifacts

* [Personas and Scenarios](personas/)
* [Sketches and Diagrams](sketches/)
* [Wireframes](wireframes/)
* [Prototype](#)

---

# Phase I: Analyzing Users, Competitors, and Initial Designs

**Executive Summary**

* **Understanding User Needs** – We identified that diabetes management goes beyond insulin delivery. Users need support in tracking food intake, mood, and overall well-being, making the system more than just a device.
* **More Than Just a Device** – Our system includes features like ChatGPT integration, allowing users to ask health-related questions such as “How much sugar is in a Pink Lady apple?”, helping them make informed dietary decisions.
* **Mood Diary for Tracking Well-Being** – A built-in mood diary allows users to log their feelings and health status, giving them a better understanding of how their mental and physical states impact glucose levels.
* **Competitor Analysis** – We researched existing insulin pumps and diabetes management apps, identifying gaps in automation, personalization, and user engagement that our system aims to improve.
* **Smarter Insulin Predictions** – Unlike traditional pumps, our machine learning model analyzes past data to predict insulin needs more accurately, reducing the risk of overdosing or underdosing.
* **Less Work for Patients** – By automating insulin delivery, we eliminate the need for manual calculations and adjustments, making diabetes management simpler and more stress-free.
* **Prototype is in Progress!** – We have purchased equipment and are actively building the system to control the insulin pump (simulated with water) using the Raspberry Pi.
* **Personalized for Each Person** – Our system is designed to learn from individual glucose patterns, making insulin delivery customized for each user rather than a one-size-fits-all approach.
* **A Step Toward Better Diabetes Care** – Through AI and automation, this project has the potential to enhance diabetes management, improving patient confidence, convenience, and overall health outcomes.

[Full phase I report](phaseI/)

---

# Phase II: Refining interaction and designing wireframes

**Executive Summary**

#### What Worked Well

* **Onboarding:** Sign In and Sign Up screens were clearly labeled and intuitive.
* **Progress Feedback:** Users received visual confirmation (screen transitions, success messages) when performing actions.
* **Dashboard Layout:** Users found glucose levels were easy to locate and understand.
* **Alert System:** Notification flow was recognizable and encouraged user response.
* **Navigation:** Setup steps used straightforward buttons and transitions.

#### Usability Issues Identified

* **Accessibility Concerns:**
  - A user found that the app’s navigation was difficult for our visually impaired persona, James, as it didn't fully support speech-to-text features. However, this issue was due to user error, as most devices offer these apps.
* **Bolus Rate Confusion:**
  - Our persona, Tyler (caregiver) was unsure how to adjust bolus settings for his daughter.
* **Setup Completion Ambiguity:**
  - Final setup screen lacked direction or confirmation on how to proceed to the dashboard.
* **Information Gaps:**
  - Our persona, Tyler  had difficulty adjusting insulin settings because of medical jargon and a lack of helpful explanations in the app.

#### Design Changes Based on Findings

* Introduced **tooltips and help icons** for bolus settings to assist caregivers.
* Updated **final setup screen** with a “Continue to Dashboard” button and success message.
* Clarified **error messaging** during login to help users identify incorrect credentials.
* Ensured **alert notifications** include confirmation and clear call-to-action (e.g., “Acknowledge,” “View Details”).

[Full phase II report](phaseII/)

---

# Phase III: Prototypes and User Testing

**Executive Summary**

!!!Put phase II Executive Summary here!!!

[Full phase III report](phaseIII/)
