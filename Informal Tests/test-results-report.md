# TEST RESULTS REPORT (SPANISH)

A testing protocol was designed that consists of 9 steps:

1.  The user can create a new account from the “login” window.

2.  The user in the login window is able to recover their password. Assuming you already have an account created.

3.  The user logs in from the login window.

4.  El usuario  crea  una  nueva  orden de servicio.

5.  The user creates a new service order.

6.  The user returns to the main menu and accesses the service order history.

7.  The user accesses the workshop metrics.

8.  The user returns to the main menu and accesses the account settings menu.
 
9.  The administrator creates a new user from the settings menu of their account.

To achieve a more realistic and accurate approach to the failures that may occur during the implementation of the tests, these were carried out within the normal conditions of an ordinary work day and different types of users were taken, both administrative staff and operatives.
 
Four criteria were taken to catalog the different types of errors that could occur during the flow journey, errors on the part of the user, design errors or functionality of the prototype, factors such as the total travel time in the flow were also taken into account and personal observations.

## Individual results
It was tested on four different users who currently work in the automotive industry, in the small to medium-sized workshop sector. We classify them as administrative users (office workers, owners or customer service workers) and operational users (workshop managers or technicians). Below are the results for each user:

### User 1 (Administrative):

![User 1 results](https://atsuro0.s-ul.eu/30rGDTvy)

**Failed steps:**

**Step 1:** User error
**Comment from the test applicator:** User tried to fill out their information on the login screen instead of accessing the "create new account" window

**Step 2:** User error
**Comment from the test applicator:** Flow too complex for the user to understand, the instructions related to the recovery code to reset the password were not clear enough.

**Step 5:** Design error
**Comment from the test applicator:** Unintuitive design for the user, it is not clear where the requested action is going to be performed.

**Additional comments:**

**Step 4:**  The user did not fill out the "service required" field, he did not see it in the process of opening the new order.

### User 2 (Operative):

![User 2 results](https://atsuro0.s-ul.eu/VHkIvh1b)

**Failed steps:**

**Step 5:** Design error
**Comment from the test applicator:** Flow too complex for the user to understand, the instructions related to the recovery code to reset the password were not clear enough.

### User 3 (Administrative):

![User 3 results](https://atsuro0.s-ul.eu/ZBn3WFrq)

**Failed steps:**

**Step 5:** Design error
**Comment from the test applicator:** Flow too complex for the user to understand, the instructions related to the recovery code to reset the password were not clear enough.

### User 4 (Operative):

![User 4 results](https://atsuro0.s-ul.eu/5dvpXhbU)
**Failed steps:**

**Step 5:** Design error

**Comment from the test applicator:** Flow too complex for the user to understand, the instructions related to the recovery code to reset the password were not clear enough.

## Critical improvement points

**Step 1:** Upon first launch of the app, ask the user if they already have an account, if they select no then send them directly to the account creation screen.

**Step 2:**  Better explaining the process on each screen is currently somewhat ambiguous and it is expected that each user already knows the standard password reset process.

**Step 5:**  Abandon the progress markers feature and replace it with another button with the words “close service order.” This with the aim of creating a simpler and easier to understand flow for new users.

## Improvement points under consideration:

**Step 4:** Consider renaming the VIN field to "Serial Number" to make it less ambiguous. Move location to "service required" field since 3 out of 4 users skipped it.

**Step 6:** Returning to the main menu requires pressing the house symbol in the navigation bar, consider changing it to a button labeled "return to main menu" to be more consistent with the rest of the application.

**Step 7:**  Consider changing terminology in the “metrics” function in the menu.

**Step 9:** The "Add new employee" option is somewhat ambiguous. Use clearer terminology such as "Create employee account".

## General Results

![General Results](https://atsuro0.s-ul.eu/PWApidvx)

An increase in errors is evident during Steps 1, 2 and 5 in general. Most of these errors could be classified as "user errors", with points for improvement that should be taken into account. On the other hand, in Step 5, a design error is identified that is considered critical and requires a solution, since it affects one of the main functions of the software, preventing proper handling of the application. Although several of the Steps without errors were completed satisfactorily, there are significant observations that could be discussed with the development team to improve the quality of the software.

## Satisfaction survey results and user feedback comments:  
  
In addition to the test, a survey was conducted among the users at the end of it to find out what they thought about the prototype. A scale of 1 to 5 was used, 1 meaning “I disagree” and 5 “I strongly agree.”. The results are as follows:

### I would use this app frequently

![Pregunta  1](https://atsuro0.s-ul.eu/phXYXpdl)

### I feel like this app is unnecessarily complex

![Pregunta  2](https://atsuro0.s-ul.eu/i27vRQ4r)


### I think this app is easy to use

![Pregunta  3](https://atsuro0.s-ul.eu/CgPJu4bB)

### I think that the functions of this application are very well integrated

![Pregunta  4](https://atsuro0.s-ul.eu/wImDbtTZ)

### I think there are many inconsistencies in the application

![Pregunta  5](https://atsuro0.s-ul.eu/RsGUmkx2)

### I imagine that most people would learn to use this application very quickly.

![Pregunta  6](https://atsuro0.s-ul.eu/BwwZFRcj)

### I felt that the app was very uncomfortable or strange to use

![Pregunta  7](https://atsuro0.s-ul.eu/NUiu73WC)

### I needed to learn many things before I can start using this application

![Pregunta  8](https://atsuro0.s-ul.eu/B0NN4ANo)

### Do you have any suggestions for anything you think could be improved in the app?

![Pregunta  9](https://atsuro0.s-ul.eu/6aoLqHmS)
Only one user left us a suggestion about a function to take photos of the vehicles when opening the order as a car inventory. It is a good proposal and would be worth considering for future versions.

Analyzing the results of the survey, in general, the users understood the flow of the application with a certain mastery during the time the test lasted, only two of them told us that some parts are somewhat friendly and confusing. We could relate this to Step 5, which was confusing for all users.
