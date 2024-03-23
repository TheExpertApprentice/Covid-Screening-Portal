<div align="center">
  <h1>COVID-19 Self Screening Portal</h1>
</div>

<div align="center">
 <b><code>Insights on developing and managing a COVID-19 self-screening solution for workplace safety.</code></b>
</div>

<p align="center">
  <!-- COVID-19 Self Screening Portal Image -->
  <a href="LINK_TO_MORE_INFO">
    <img src="PLACEHOLDER_FOR_COVID_PORTAL_IMAGE.png" alt="COVID-19 Self Screening Portal">
  </a>
</p>
<br>

<div align="center">
 <b><code><a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&color=F39835F0&background=FFE66F00&vCenter=true&random=false&width=435&lines=+Stay+Safe,+Keep+Screening!" alt="Typing SVG" /></a></code></b>
</div>
<br>

<br>

<p align="center">
  <sup>
    <i>
      In the midst of challenges, we innovate for health and safety,<br>
      Building digital bridges to secure our communal well-being.<br>
      A portal designed, not just for screening, but for caring,<br>
      Embracing technology to protect against the unseen.<br>
      <a href="LINK_TO_PROJECT_STORY_OR_REFERENCE">Discover the Journey of Innovation: COVID-19 Screening Portal</a>
    </i>
  </sup>
</p>

<br>

<p align="center">
  <a href="LINK_TO_CONTRIBUTE">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?longCache=true" alt="Pull Requests">
  </a>
  <a href="LINK_TO_LICENSE">
    <img src="https://img.shields.io/badge/License-CUSTOM-lightgrey.svg?longCache=true" alt="Custom License">
  </a>
</p>

<p align="center">
  <!-- Social Media or Contact Links, if any -->
  <a href="YOUR_SOCIAL_MEDIA_OR_CONTACT_LINK" target="_blank">
    <img src="https://img.shields.io/twitter/follow/YOUR_SOCIAL_MEDIA_HANDLE.svg?logo=twitter">
  </a>
</p>

<div align="center">
  <sub>Created by
  <a href="LINK_TO_CREATOR_PROFILE">Your Name or Organization</a>
</div>

<br>

****



## Overview

The COVID Screening Portal was developed in 2021 to streamline the daily health screening process for employees at my organisation, ensuring a safe working environment during the pandemic.

## Problem

Prior to the portal, manual screening processes were time-consuming, prone to errors, and lacked a centralized system for tracking and analyzing COVID-19 for over 25,000 employees and students, excluding visitors, leading to potential health risks in the workplace. The cost of acquiring a new, off-the-shelf commercial solution was less realistic due to the financial constraints of the organization, compounding the need for an innovative and cost-effective approach to health screening.

## Solution

The portal automated the process for staff and students to do a self-daily health screening process prior to being granted access to the campus through custom forms and Power Automate workflows, enabling real-time symptom tracking, automated alerts for health anomalies, and data-driven decisions to maintain workplace safety. The solution was integrated with SharePoint for secure record-keeping and campus access management. It facilitated the identification of suspected positive cases through the questionnaire responses, alerting campus clinic administrators and security personnels for immediate follow-up. Additionally, the system incorporated a robust validation mechanism, ensuring access to campus facilities was conditionally granted based on the accurate verification of staff and student identities against the organization's database.

> **Technologies Used**
>
> - ![Microsoft Forms](https://img.shields.io/badge/Microsoft%20Forms-0078D4?style=for-the-badge&logo=microsoftforms&logoColor=white) **:** For creating dynamic screening questionnaires.
> - ![Power Automate Icon](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white) **:** For automating data collection, analysis, and alerting processes.
> - ![SharePoint Icon](https://img.shields.io/badge/SharePoint-0078D4?style=for-the-badge&logo=microsoftsharepoint&logoColor=white) **:** For secure and centralized storage of health screening records and management of access permissions.
> - ![Outlook](https://img.shields.io/badge/Outlook-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white) **:** For Access Alerts and reporting in case of positive case suspicions.

## Impact

The portal significantly enhanced operational efficiency by reducing screening times by **75%** and improved health guideline compliance by **90%**. It also enabled the organization to swiftly respond to potential health threats, ensuring the safety and well-being of all employees and students. Moreover, the system streamlined the management of campus access, effectively reducing the risk of COVID-19 transmission by automating the enforcement of health and safety protocols.

## Reflections and Learning Outcomes

This project highlights the importance of leveraging automation and data analytics in crisis management. The development and implementation of this Self Screening Portal did not only solve a pressing organizational challenge but also served as a valuable learning experienceIt honed my skills in developing intuitive user interfaces and automating complex workflows, contributing to my expertise in digital health solutions and reinforcing my commitment to leveraging technology for societal benefit.

## Conclusion

The COVID Screening Portal was pivotal in maintaining a safe workplace during the pandemic, paving the way for further innovations in health monitoring within the organization.

## Acknowledgments

I would like to give credit to the IT team and the VUT Clinic who collaboratively provided guidance, advice, collaboration, or feedback for improvement where necessary.

## Improvement

For organizational validation, the system grants access by authenticating staff or student numbers, thus ensuring a secure and reliable verification process. This required the implementation of a robust synchronization mechanism with the organization's HR and student databases to frequently update and maintain the accuracy of the user base. This critical feature ensured that only current employees and students could access campus facilities, enhancing the security and effectiveness of the health screening process. In addition, the integration of access control system could be beneficial.

---

# Step by Step Visual Guide

## Create a Health Screening Form

### Objective

Design a dynamic health screening questionnaire based on the SA National Health Question Bank.

#### Action Steps

> 1. **Sign in and Create a New Form:**
>     - Go to [Microsoft Forms](https://forms.microsoft.com) and sign in with your Microsoft account.
>     - Click on ***‘New Form’*** to start creating your health screening questionnaire.
>
> 2. **Name Your Form:**
>    - Provide a title for your form such as "COVID-19 Self Screening Portal".
>    - Add a description below the title if necessary.

> 3. **Add Questions:**
>    - Click on ***‘Add New’*** to insert your first question.
>    - Select the type of question you want to add (e.g., ***‘choice’***, ***‘text’***, ***‘number’***, ***‘rating’***).
>    - Type the question and provide hints below each question.
>    - Fill in the options if it’s a ***‘choice’*** question or set up response validation if it’s a ***‘text’*** question.
>    - Enable the ***‘Required’*** setting for each question by Toggling the switch to ensure that respondents cannot submit the form without answering all the questions. This is especially crucial for a health screening form to ensure that no important information is missed.
>    - Repeat this process to add all the questions necessary for the screening.
>    - Remember to use dropdown list to organise the options in question 9. Click on the ***'Choice'*** question type and then select the ***'...'*** or ***'More options'*** icon to change to ***'Dropdown'***. This will help in organizing the data effectively and preventing free-text variations.

> 4. **Customize Settings:**
>     - Click on the ***‘...’*** or ***'More form settings'*** (often represented by three dots or a gear icon) to access settings.
>     - Adjust settings for things like who can fill out the form, whether multiple responses are allowed, or if respondents can see summary results.

> 5. **Set Up Branching Logic (Important for question 2):**
>     - In your form, locate the question where you want to add branching. For example: ***"Are you a Staff/Student?"***
>     - Click on the ***'...'*** or ***'More options'*** icon on the bottom right of the question box and select ***'Add Branching'***.
>     - For each option in the question, determine the subsequent question that the respondent should be directed to. Based on the image:
>     - If the respondent selects ***"Staff,"*** they will be directed to the question asking for their ***"Staff number."***
>     - If ***"Student"*** is selected, the flow will take them to a different question to enter their ***"Student number."***
>     - And if they choose ***"Other,"*** they should be directed to provide their ***"Identification number."***
>     - Ensure that branching is set up correctly by clicking on the ***'Branching options'*** to review the pathways for each answer choice.
>     - Test the branching logic by previewing the form and selecting different options to see if you are taken to the correct subsequent question.
>     - Click on the ***'Required'*** toggle to make sure respondents must answer the question before proceeding, which is critical for gathering complete data sets.

> 6. **Design and Theme:**
>     - Use the ***‘Theme’*** option at the top of the form to choose a color scheme or upload a background image to align with your organization's branding.

> 7. **Review and Test:**
>     - Review your form for clarity and completeness.
>     - Send a preview link to yourself or a colleague to test the form’s functionality and ensure that all questions are correctly formatted and that branching logic works as intended.

> 8. **Share Your Form:**
>     - Once you are satisfied with the form, click on ***‘Share’*** at the top right.
>     - Choose how you want to distribute your form (link, QR code, email, or embed into a website).
>     - Copy the link or select the appropriate option to distribute the form to your intended audience.


## Screenshots of Questionnaire Creation

> ![Screenshot 1](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/1.png)
> ![Screenshot 2](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/2.png)
> ![Screenshot 3](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/3.png)
![Screenshot 4](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/4.png)
![Screenshot 5](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/5.png)

Now go back to question 2, and add branching logic as described in the Action Steps V above.

![Screenshot 6](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/6.png)

Proceed with other questions.

![Screenshot 7](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/7.png)
![Screenshot 8](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/8.png)
![Screenshot 9](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/9.png)
![Screenshot 10](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/10.png)
![Screenshot 11](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/11.png)
![Screenshot 12](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/12.png)
![Screenshot 13](https://github.com/TheExpertApprentice/Covid-Screening-Portal/blob/main/images/13.png)





## Set Up SharePoint Site

### Objective

Establish a centralized platform for storing screening responses and managing access control.

#### Action

Create a SharePoint site named "COVID-19 Self Screening Portal."

> **Appendix A:** SharePoint List Column Names
> - **Title:** An identifying name for the portal e.g., “Covid screening system”
> - **Fullname:** The complete name of the individual undergoing screening.

