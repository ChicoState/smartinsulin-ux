# Phase II: Refining interaction and designing wireframes

---

## Introduction
In Phase II, the team focused on improving how users interact with the app and how well the design supports real-world diabetes management. The app is intended to help people living with Type 2 diabetes, as well as their caregivers, by connecting to a Bluetooth-enabled insulin pump and providing real-time health information. This round of work concentrated on refining wireframes and testing early designs through cognitive walkthroughs and informal user feedback.

The walkthroughs revealed important issues that needed to be addressed. Users struggled with certain steps in the onboarding and setup process, especially when asked to configure insulin settings or interpret glucose data. Some features lacked clear labels or guidance, which made it harder for users to know what action to take next. One caregiver, for example, could not get past the first screen because there was no text-to-speech support available. In other cases, users hesitated when trying to review bolus history or respond to a high glucose alert, due to poor layout and limited feedback from the system.

In response, the team redesigned several screens to make task flows easier to follow and to provide more immediate feedback and reassurance. Navigation paths were adjusted to match how users think about the tasks they need to complete. Button labels and screen headings were rewritten to remove ambiguity. Accessibility improvements were also added, including support for screen readers and clearer visual indicators.

This phase was valuable because it confirmed what was working and, more importantly, what needed to change. The updated designs now better reflect how people actually use the app, especially in high-stakes or time-sensitive situations. The result is a clearer, more supportive experience that helps users manage diabetes with greater confidence and fewer obstacles.

---

## Methods

Our primary research method used during this sprint was the cognitive walkthrough. The specific details of this method were outlined in assignment x12 Cognitive Walkthrough, and can be used to replicate this method. Two (n=2) external users put themselves in the shoes of our personas and attempted to follow through the associated scenarios using our wireframes. At each step of the attempted walkthrough, they answered the following two questions: 1) Will the user know what to do at this step? and 2) If the user does the right thing, will the user know that they did the right thing and is making progress toward the goal? This method is meant to simulate user feedback and identify design issues (such as lack of feedback or clear labeling) for further improvement.

The software engineering (SE) team solicited informal feedback from the software engineering class (roughly n=35) during their presentation. Both the UI/UX and SE teams worked together to generate the following question: If you know someone who manages diabetes, what challenges have they faced with current diabetes management technologies?

---

## Findings

During this phase, we used two main research methods: (1) cognitive walkthroughs and (2) informal feedback from users and caregivers. Both gave us important insight into how people actually use the app and where things break down. It helped us better understand what users need, especially when managing or supporting someone with Type 2 diabetes.

From the walkthroughs, it became clear that the setup process needs to be more supportive. People often got stuck when asked to enter things like the bolus rate, mostly because they did not know what those terms meant. This told us we needed to explain these things better, especially for caregivers who are involved but may not have a medical background. We also noticed that users weren’t always sure if they had done something correctly like saving a setting or responding to an alert because the app didn’t give clear confirmation. Navigation could be confusing too. Some users had trouble finding scheduled doses or bolus history, and the final setup screen left people hanging with no clear next step.

The informal feedback added another layer of understanding. One caregiver who uses text-to-speech couldn’t get past the home screen because there was no support for it something we hadn’t fully considered even though most phones offer built-in audio features. Caregivers also told us they needed emotional reassurance. They didn’t just want numbers; they wanted to know their loved one was okay. Even a simple message like “All vitals are stable” would make a big difference.

We also found that some of the language in the app felt too clinical. People weren’t familiar with certain terms, and that made parts of the app feel intimidating. We realized we need to simplify language and give explanations where it matters. Another key thing we heard was that users expected the app to notify them when something was wrong without having to check it constantly. That made it clear how important proactive alerts really are.

---

## Conclusions

The Cognitive Walkthrough identified a persona/scenario that we had neglected to fully address. The persona of Tyler, a parent monitoring his child with diabetes, requires the functionality of a monitoring account, which we had not accounted for when we built out our wireframes. Initially, we had thought of implementing a monitoring dashboard accessible through the hamburger menu sidebar of the app, but determined that to be a less effective implementation of the monitoring functionality goals. We have elected to add an “add monitoring account” button in several locations in the app (including within the workflow of the creation of a primary account). The monitoring account will then be accessed through a username and password sign-on, like a primary account, but will not prompt the user to go through first-time device setup.

Cognitive Walkthroughs also identified other areas of the application, such as settings, that require additional building out. The Tyler persona Cognitive Walkthrough identified several areas of the application where additional labeling and feedback would improve user interactions.

The Cognitive Walkthrough of the James persona, a visually impaired user, while not directly useful in feedback, did bring to our attention a lack of detail to our knowledge of the functionality of text-to-speech and screenreader services. We intend to explore that functionality on multiple smartphones and make revised notes for future user interaction and feedback conducted by non-visually impaired external users attempting to test functionality for visually impaired users.

---

## Caveats

Our external evaluators do not live with diabetes (to our knowledge) and thus their feedback focuses more on the interface as a whole, rather than the diabetes-specific features.

Furthermore, we are a team of three novices who are not working full-time on this project, and thus the wireframes that were reviewed for the cognitive walkthroughs were not as comprehensive as those likely to be developed in a professional setting.

With regards to the James persona, as noted in the conclusion of this report, none of our team have experience utilizing text-to-speech or screen-reader tools. Further research is required to ensure that the correct care be given to the compatibility of our app with such tools.

---
