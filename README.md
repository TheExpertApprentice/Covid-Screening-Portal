<div align="center">
  <h1>COVID-19 Self Screening Portal</h1>
</div>

<div align="center">
  <b><code>Insights on developing and managing a COVID-19 self-screening solution for workplace safety.</code></b>
</div>

<br>

<p align="center">
  <!-- COVID-19 Self Screening Portal Image -->
  <a href="LINK_TO_MORE_INFO">
    <img src="PLACEHOLDER_FOR_COVID_PORTAL_IMAGE.png" alt="COVID-19 Self Screening Portal">
  </a>
</p>

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
> - ![Microsoft Forms Icon](link_to_forms_icon.png) **Microsoft Forms:** For creating dynamic screening questionnaires.
> - ![Power Automate Icon](link_to_power_automate_icon.png) **Microsoft Power Automate:** For automating data collection, analysis, and alerting processes.
> - ![SharePoint Icon](link_to_sharepoint_icon.png) **SharePoint:** For secure and centralized storage of health screening records and management of access permissions.
> - ![Custom Integration Icon](link_to_custom_integration_icon.png) **Custom Integration:** For validating staff and student identities against the organization's database to ensure accurate tracking and reporting.

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

1. **Sign in and Create a New Form:**
    - Go to [Microsoft Forms](https://forms.microsoft.com) and sign in with your Microsoft account.
    - Click on ‘New Form’ to start creating your health screening questionnaire.

2. **Name Your Form:**
    - Provide a title for your form such as "COVID-19 Self Screening Portal".
    - Add a description below the title if necessary.

3. **Add Questions:**
    - Click on ‘Add New’ to insert your first question.
    - Select the type of question you want to add (e.g., choice, text, number, rating).
    - Type the question and provide hints below each question.

> Image Placeholder for Step-by-Step Guide

## Set Up SharePoint Site

### Objective

Establish a centralized platform for storing screening responses and managing access control.

#### Action

Create a SharePoint site named "COVID-19 Self Screening Portal."

> **Appendix A:** SharePoint List Column Names
> - **Title:** An identifying name for the portal e.g., “Covid screening system”
> - **Fullname:** The complete name of the individual undergoing screening.

