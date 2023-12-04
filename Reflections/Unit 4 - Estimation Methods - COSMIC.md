# COSMIC FOR PitSTOP

## **Functional requirement "Password Reset"**

 the administrators and users will be able to reset their passwords using their entered email address. 

### **1. measurement strategy:** 

**Purpose:** measure the functionality of the component, to estimate the effort required for its implementation. 

**Scope:** component functionalities. 

**Functional users:** human operators users 

**Layer:** Application component for password recovery.  

### **2. Mapping:**    

From the login screen, the “forgot password” button is selected. The email associated with the account for which the password is to be recovered is entered, and an email with the verification code is sent. The code sent to the requester's email is entered, and it is verified that the code is correct. The new password is entered, and the password is entered again for verification. Once the password verification is complete, the user is returned to the login screen. 
<table>
    <tr>
        <th><b>Triggering Input</b></th>
        <th>"The user selects the option "Forgot password?"</th>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Interface prompting the user's email address</td>
    </tr>
    <tr>
        <td><b>Input</b></td>
        <td>Email address associated with the registered user account.</td>
    </tr>
    <tr>
        <td><b>Read</b></td>
        <td>Email address (check existence of the email address as a user)</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Sending mail with the verification code</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Interface requesting recovery code</td>
    </tr>
    <tr>
        <td><b>Input</b></td>
        <td>Verification Code</td>
    </tr>
    <tr>
        <td><b>Read</b></td>
        <td>Verification of the submitted code</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Error/Confirmation Message</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Interface for creating and confirming a new password</td>
    </tr>
    <tr>
        <td><b>Input</b></td>
        <td>New Password</td>
    </tr>
    <tr>
        <td><b>Read</b></td>
        <td>New password and verification that it is the same</td>
    </tr>
    <tr>
        <td><b>Write</b></td>
        <td>New password in the database</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Login Interface</td>
    </tr>
</table>

### **3. Measurement:**

Based on the **COSMIC** methodology, one **COSMIC** Functional Point was assigned to each subprocess (Input, Output, Read, or Write). This is based on the principle that **COSMIC** assigns one point to each data movement, resulting in a total of **14 COSMIC Functional Points**.

---

## **Functional requirement "Add settings"**

The user must have access to the account settings, where they can decide how they will receive notifications from the system in their inbox.  
 
### **1. measurement strategy:**

**Purpose Description:** To determine an accurate measure of the functional size of the requirement for the PitSTOP system. 

**Measurement Scope:** The entire system specified in the system requirement. In this case, it would be the account settings screen and the application configuration screen. 

**Functional Users:** Human operator users. 

**Layer:** Application component for application configuration. 

### **2. Mapping:**

- The user has access to the account settings screen. 

- From the account settings screen, the user selects the **"App settings"** option. 

- On the **"App settings"** screen, three options appear: 

    - **Notification badge:** The user selects whether they want the app to send notifications to their device inbox. 

    - **Push notifications:** The user displays on the screen the types of notifications that can be activated or deactivated from their inbox. 

        - **Push notifications (pending vehicles):** The user selects whether they want the app to send them a notification about pending vehicles. 

        - **Push notifications (new vehicle added):** The user selects whether they want the app to send them a notification every time a new vehicle is added. 

- The user can return to the account settings screen by selecting a button to return.


<table>
    <tr>
        <th><b>Triggering input</b></th>
        <th>The user selects the "App settings" option.</th>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>A menu of options is displayed on the screen. In this menu you will find "notifications badge" and "push notifications"</td>
    </tr>
    <tr>
        <td><b>Input</b></td>
        <td>The "notifications badge" option is activated</td>
    </tr>
    <tr>
        <td><b>Read</b></td>
        <td>Check Number of Notifications for Added Vehicles and Pending Vehicles</td>
    </tr>
    <tr>
        <td><b>Write</b></td>
        <td>In the user's database, it is enabled to show the number of notifications that have not been read</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Mark the "notifications badge" option as activated</td>
    </tr>
    <tr>
        <td><b>Input</b></td>
        <td>The "pending vehicles" option is activated</td>
    </tr>
    <tr>
        <td><b>Read</b></td>
        <td>Check the number of vehicles that are pending in the database</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Mark the "pending vehicles" option as activated</td>
    </tr>
    <tr>
        <td><b>Input</b></td>
        <td>The "New vehicle added" option is activated</td>
    </tr>
    <tr>
        <td><b>Read</b></td>
        <td>Check the number of vehicles added each time a new service order is opened in the database.</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Mark the "New vehicle" option as enabled</td>
    </tr>
    <tr>
        <td><b>Input</b></td>
        <td>The "notifications badge" option is disabled</td>
    </tr>
    <tr>
        <td><b>Write</b></td>
        <td>In the user's database, the number of notifications that have not been read is disabled</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Mark the "notifications badge" option as disabled</td>
    </tr>
    <tr>
        <td><b>Input</b></td>
        <td>The "pending vehicles" option is activated</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Mark the "Pending vehicles" option as disabled</td>
    </tr>
    <tr>
        <td><b>Input</b></td>
        <td>The "New vehicle" option is disabled</td>
    </tr>
    <tr>
        <td><b>Output</b></td>
        <td>Mark the "New vehicle" option as disabled</td>
    </tr>
</table>

### **3. Measurement:**

Based on the **COSMIC** methodology, a **COSMIC** Functional Point was assigned to each sub-process (Input, Output, Read or Write) based on the fact that in **COSMIC** each data movement is assigned a point, giving us a total of **14 COSMIC Functional Points.**

---

## Using COSMIC's standard formulas

**The total PIC is 14+19 =** 33

**Effort Required =** Size (number of CFPs) x Delivery Rate (hours per CFP)

**Effort required =** 33 (CFP) x 4 (hours per CFP)  

**Effort required =** 132 hours

**Cost per function point:** 340,000 / 22 CFP = $15,454.54

**Total Cost =** Size (CFP) x Cost Per Unit ($/CFP)  

**"Paswword reset" =** 14 CFP * $15,454.54 = $216,363.56

**"App settings" =** 19 CFP * $15,454.54 = $293,636.26

**Total Cost =** $509,999.82

**Sprint Duration Cost =** $254,999.91  

**Project Duration =** COSMIC Function Points / COSMIC Function Points Month

**Project duration =** 33 / 22 = 1.5 months to put both requirements into operation

---

### Associated costs (Allocation of salaries according to functions)

<table>
    <tr>
        <th><b>Name</b></th>
        <th>Experience</th>
        <th>Salary and roles</th>
    </tr>
    <tr>
        <td><b>Hugo de Jesús Janssen Aguilar</b></td>
        <td>Automotive engineer with team management experience. Technical skills in C#, MySQL, Unity, and development environments like Github.</td>
        <td>Serves as Scrum master and developer. Monthly salary of 80,000 MXN.</td>
    </tr>
    <tr>
        <td><b>Emiliano Contreras Gamboa</b></td>
        <td>Database management knowledge, technical skills in HTML, CSS, JavaScript, and PHP, English language proficiency B1. Familiar with software development environments like Github.</td>
        <td>Functions as a developer. Monthly salary of 40,000 MXN.</td>
    </tr>
    <tr>
        <td><b>Alejandro Magdiel Duran Varela</b></td>
        <td>Technical knowledge in Python, English language proficiency B2, basic knowledge of C language development, and basic understanding of software development environments like Github.</td>
        <td>Functions as a developer. Monthly salary of 40,000 MXN.</td>
    </tr>
    <tr>
        <td><b>Capi Madera de Regil</b></td>
        <td>Technical skills in Photoshop, Illustrator, Unity, and C# programming language, English language proficiency C1. Familiar with software development environments like Github.</td>
        <td>Serves as UI/UX designer and developer. Monthly salary of 50,000 MXN.</td>
    </tr>
    <tr>
        <td><b>José Pablo Martínez Martínez</b></td>
        <td>Knowledge of virtual community management, basic video editing skills, English language proficiency B2, basic knowledge of C language development, and basic understanding of software development environments like Github.</td>
        <td>Functions as a developer. Monthly salary of 40,000 MXN.</td>
    </tr>
    <tr>
        <td><b>Edwing Mauricio Molina Chim</b></td>
        <td>Knowledge of video editing, English language proficiency B2, basic knowledge of C language development, and basic understanding of software development environments like Github.</td>
        <td>Serves as UI/UX designer and developer. Monthly salary of 50,000 MXN.</td>
    </tr>
    <tr>
        <td><b>Sofia Reyes Rodríguez</b></td>
        <td>Knowledge in project management, English language proficiency B2, basic knowledge of C language development, and basic understanding of software development environments like Github.</td>
        <td>Functions as a developer. Monthly salary of 40,000 MXN.</td>
    </tr>
</table>

---

# Fundamentos 

- [Roles para el desarrollo de software:](https://projectcor.com/es/blog/roles-fundamentales-en-un-equipo-de-desarrollo-de-software/ )

- [salarios](https://mx.computrabajo.com/salarios/ingeniero-software)

- [hackerrank](https://www.hackerrank.com/research/developer-skills/2023)
 
- [sueldos](https://www.glassdoor.com.mx/Sueldos/scrum-master-sueldo-SRCH_KO0,12.htm#:~:text=El%20sueldo%20promedio%20de%20Scrum,de%20entre%20%2420%2C000%20y%20%2482%2C437.)
