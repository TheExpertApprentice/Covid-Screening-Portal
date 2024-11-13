---

# Step by Step Visual Guide

## 1. Create a Health Screening Form

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





## 2. Set Up SharePoint Site

### Objective

Establish a centralized platform for storing screening responses and managing access control.

#### Action

Create a SharePoint site named "COVID-19 Self Screening Portal."

> **Appendix A:** SharePoint List Column Names
> - **Title:** An identifying name for the portal e.g., “Covid screening system”
> - **Fullname:** The complete name of the individual undergoing screening.

