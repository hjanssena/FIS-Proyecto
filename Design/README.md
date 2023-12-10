# Requirements correspondence

The requirements correspondence was based on the descriptions elaborated for the use case specifications of each functionality/component of the system, ensuring that the prototypes align correctly with the intended purpose for each functionality and meet the specifications outlined in each requirement.

## Functional requirements

### Requirement:
- **The workshop leader should be able to register in the system using an email the first time they log in.**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF1FIGMA(1).png?raw=true" alt="Image" width="190px"><img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF1FIGMA(2).png?raw=true" alt="Image" width="188px">

    - **Correspondence**: In accordance with the specified requirement, this pertains to an interface where the user can input their information to register within the system, subsequently utilizing this data to log in.

---

### Requirement:
- **The administrator will be able to register users so that they can access the company's database from the system. This will be done using the user's email and assigning a password.**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF2FIGMA.png?raw=true" alt="Image" width="190px">

    - **Correspondence**: The prototype represents an interface where the company administrator can input employee data to generate their system access. Essential information for entry includes the username, password, and email address.

---

### Requirement:
- **The administrators and users will be able to reset their passwords using their entered email address.**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF3FIGMA%20(1).png?raw=true" alt="Image" width="190px"><img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF3FIGMA%20(2).png?raw=true" alt="Image" width="193px">

    - **Correspondence**: When the administrator clicks the button, the interface is displayed, prompting them to enter the email associated with an already registered account. Subsequently, they will receive a verification code to establish the new password entered by the user.

        The prototype features the fields for entering this information and then returns to the login screen for the new login session.

---

### Requirement:
- **User accounts will not be able to access the functions of administrator accounts; for instance, they will not be able to register other users in the system.**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF4FIGMA.jpg?raw=true" alt="Image" width="1080px">
    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF4FIGMA2.jpg?raw=true" alt="Image" width="1080px">

    - **Correspondence**: The prototype displays a user interface with several options removed, as these are functions accessible only to company administrators, such as statistics and adding new employees.

---

### Requirement:
- **The system will have a database containing customers' personal data. It should be able to store the customer's name, phone number, address, and email, as well as their vehicle information (make, model, VIN number, license plates, and mileage).**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF5FIGMA.jpg?raw=true" alt="Image" width="179px"> <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF5FIGMA.png?raw=true" alt="Image" width="190px">

    - **Correspondence**: The prototype displays the cards on the main page of the application after logging in. From these cards, you can access the information described in the requirement, showcasing relevant customer data stored in the database.

---

### Requirement:
- **The software will have the capability to store business service orders created by users. Each order can include the type of service provided, the customer's name, the service date, the mechanic's name in charge of the order, the parts used, and the final cost.**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF6FIGMA.jpg?raw=true" alt="Image" width="179px"> <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF6FIGMA.png?raw=true" alt="Image" width="190px">
    - **Correspondence**: The prototype showcases an interface where you can input information related to the service order, corresponding to the details described in the requirement description. By registering the data, the service order can be located, as depicted in the second image, with the information already entered into the database.
    
---

### Requirement:
- **The user should have access to the account settings, where they can decide how they will receive notifications from the system in their inbox.**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF7FIGMA.png?raw=true" alt="Image" width="190px">

    - **Correspondence**: A switch-type button has been added to enable/disable notification options and manage their flow. This functionality can be accessed through the "Settings" button in the application menu.

---

### Requirement:
- **Users can mark service orders as completed when finishing the task. In this state, all entered data will be permanent and not modifiable by the user.**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF8FIGMA.jpg?raw=true" alt="Image" width="190px"> <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF8FIGMA.png?raw=true" alt="Image" width="190px">

    - **Correspondence**: Based on the requirement, a section was designed in the settings that are accessed through the account button where the settings button is selected where you can choose if you want to receive notifications and you can activate the type of notification that you require notify you on your device.

---

### Requirement:
- **The workshop leader will be able to view the following performance indicators in the system: the number of vehicles that entered, the reason for their entry, and total earnings.**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF9FIGMA.jpg?raw=true" alt="Image" width="142px"> <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF9FIGMA.png?raw=true" alt="Image" width="150px"> <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RF9FIGMA(3).jpg?raw=true" alt="Image" width="142px">

    - **Correspondence**: In the design you can see the metrics on how the workshop is going and only the administrator can have access to this section. These metrics should include the number of clients per month, profits and the type of service offered.

## **Non-functional requirements**

### Requirement:
- **The workshop leader will be able to view the following performance indicators in the system: the number of vehicles that entered, the reason for their entry, and total earnings.**

    - <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RNF1FIGMA.jpg?raw=true" alt="Image" width="200px"> <img src="https://github.com/hjanssena/FIS-Proyecto/blob/EmilianoContreras/Assets/RNF1FIGMA.png?raw=true" alt="Image" width="180px">

    - **Correspondence**: In accordance with the non-functional requirement, the Figma prototype was made with the measures required by an Android device so that it can be navigated comfortably and that it follows Android standards.


---

### Requirement:
- **The workshop leader will be able to view the following performance indicators in the system: the number of vehicles that entered, the reason for their entry, and total earnings.**

    - **Correspondence**: To make the design intuitive and easy to use, certain shapes were used for the buttons and icons, as well as the name that defines the functionality that each button fulfills, and this was reflected during the unit tests where it was tested how easy it was to It is easy to use and how intuitive it was.
