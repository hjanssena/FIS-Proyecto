> # SECOND DELIVERY

>![UADY logo](https://github.com/hjanssena/FIS-Proyecto/blob/JPabloMartinez/Assets/Logo_UADY.png?raw=true)

---
### FMAT UADY
### Group A - FIS
### Edgar Cambranes Martínez
=======
### [Checklist]()
---
## Video presentation - Second delivery
- [HERE!](https://youtu.be/GJcCetrvJJE)

## TEAM

### SCRUM master
 - Hugo de Jesús Janssen Aguilar 
 
### Development team
 - Emiliano Contreras Gamboa 
 - Alejandro Magdiel Duran Varela
 - Capi Madera de Regil
 - Jose Pablo Martinez Martinez
 - Edwing Mauricio Molina Chim
 - Sofia Reyes Rodriguez 

## About Our Product - PitSTOP

<img src="https://github.com/hjanssena/FIS-Proyecto/blob/b3437fb56d8e14e01c90bac4d7f6ad1923f5de83/Assets/Logo_PitSTOP.jpg" width="500" height="500" border="50"/>

---

### Product evolution

The main idea of the product did not suffer many changes between the first and second installment, however, it was necessary to better define and refine the important aspects of it. Among the most relevant changes for our product were:

The data that will be saved for each service order was defined:

   - Service to be performed: Brief description of what the client requests, whether a diagnosis or a preventive service. It is an open field for the failure or service requested to be described in an understandable manner.

   - Type of service: It can be preventive or corrective, it will serve as a metric for the workshop to know what type of work it attends.

   - Reception date

   - Promised date and time: It is the time agreed with the client for the delivery of their vehicle.

The client and vehicle data were also defined, which are: Name and surname, address, telephone number, email, model and make of the vehicle, VIN and license plates.

In addition, a complete review of the requirements was made, resulting in a more compact and defined list, which considers the most important functions expected from the system.

### More information about

- [HERE!](https://github.com/hjanssena/FIS-Proyecto/tree/8bcf9cf14cb7ba1417732637ee52c1f7d38d323a/Product)


## Requirements

---

### Requirements evolution

During the course of this second delivery, we had to make numerous changes to both the functional and non-functional requirements. This was because we realized that the requirements we had defined in the first delivery were not well-defined. Moreover, many of them involved unnecessary implementations given the time constraints for this delivery. Consequently, we had to reevaluate the functional and non-functional requirements. 

We had to eliminate or modify many of the functional requirements, as we discovered that, when creating use cases, many of them were somewhat unnecessary. They didn't significantly contribute to the system's functionality, and we wouldn't be able to complete them by the final delivery deadline.Lastly, we narrowed down the non-functional requirements to those where compliance can be observed through the project's prototypes. 

**Comparison between old and new requeriments**

- [HERE!]() **PENDIENTE**

### Artifacts evolution

A series of use case specifications were developed where each functional requirement was described in terms of how a user would use it. Likewise, the use case diagram was improved from the one in the first delivery.

- [Use Case Diagram](https://github.com/hjanssena/FIS-Proyecto/blob/8bcf9cf14cb7ba1417732637ee52c1f7d38d323a/Artifacts/UML-Use-Case-Diagram.pdf)

- [Use Case Specifications](https://alumnosuady-my.sharepoint.com/:x:/g/personal/a14016364_alumnos_uady_mx/EYczFlZ-P7hMvsU24l4KoicBFqIizoKz6LvKhqTFET9rjQ?e=gYGnAi)

## Our video [Second delivery]

- [SECOND DELIVERY](https://youtu.be/GJcCetrvJJE) 

---

## Process

### About the process

For this second delivery, we have employed concepts from the incremental lifecycle, implementing them in small sprints while incorporating some features of the Agile SCRUM methodology. We can observe the incremental lifecycle in our project. For example, to complete the review and validation of requirements, we had to deliver an initial version. After receiving group feedback and making necessary adjustments, we had to update the requirements and create new artifacts. 

Regarding the use of the SCRUM Agile methodology, we did not utilize all its elements for our project, but only the features we considered relevant for our team's effective organization. The project was carried out in a series of sprints, which will be detailed later, as increments. However, daily team meetings were not conducted due to time constraints; instead, we opted for weekly meetings. We employed SCRUM roles (Product Owner, Scrum Master, and Development Team) for team organization. 

#### Learn more about the process
- [Process description!](https://github.com/hjanssena/FIS-Proyecto/blob/8bcf9cf14cb7ba1417732637ee52c1f7d38d323a/Roles%20%26%20Organization/Process%20description.md)
  
- [Process management!](https://github.com/hjanssena/FIS-Proyecto/blob/SegundaEntrega/Roles%20%26%20Organization/Process%20Management.md)

## Design (UI/UX)

We created a user interface [prototype](https://www.figma.com/file/QQ6kXK1QVzeRAKcwilSRc7/Untitled?type=design&node-id=0%3A1&mode=design&t=ySZoxSK7i5XqvvHG-1), which was made using [Figma](https://www.figma.com/).

- The first requirement states that the workshop administrator can log in/register with their email. According to our use case diagram, it specifies that login and registration can be done with email. Thus, we have enough information to propose a prototype interface allowing the user to register or log in, located in the section named "Sign In/Up."

- The second requirement indicates that the workshop administrator can grant access to the company's database to their employees. Our use case diagram specifies that it meets the requirement, so we can begin creating a prototype interface for the administrator to grant database access, located in the "Account and Configurations" section.

- The third requirement states that employees with database access should only have access to that and not to the administrator's configurations. This can be verified with the information in the use case diagram, allowing us to create an interface prototype for employees, where access to certain permissions is modified.

- The fourth requirement mentions that vehicles can be registered by providing specific data for the record, stored in the database. Our use case diagram and use case specification confirm this, allowing us to create a prototype interface in the "Menu" section under the name "New Order."

- The fifth requirement specifies the need for a screen displaying upcoming service deliveries. Our use case diagram provides detailed instructions, allowing us to create the prototype, already completed and located in the "Menu" section as "Main Screen."

- The next requirement discusses visualizing a history of repaired vehicles, including the data recorded during registration. This can be verified through the diagram and use case specification, detailing what the interface prototype should contain. The prototype is located in the "Menu" section under the name "Order History," and the data visualization is under "Order View."

- The penultimate requirement mentions marking buttons to indicate progress in the vehicle repair. This can be verified in our use case diagram, and the use case specification document outlines the steps for creating the prototype. It is located in the "Menu."

- The final functional requirement states that the workshop administrator can view performance graphs for their workshop. Our diagram and use case specification indicate that a prototype interface can be created, found in the "Menu" section with the name "Metrics."

### Artifacts where the requirements were verified
[Use Case Diagram](https://github.com/hjanssena/FIS-Proyecto/blob/SegundaEntrega/Artifacts/UML-Use-Case-Diagram.pdf)
[Use Case Specification](https://alumnosuady-my.sharepoint.com/:x:/g/personal/a14016364_alumnos_uady_mx/EYczFlZ-P7hMvsU24l4KoicBFqIizoKz6LvKhqTFET9rjQ?e=gYGnAi)
[Prototype Desing in Figma](https://www.figma.com/file/QQ6kXK1QVzeRAKcwilSRc7/Untitled?type=design&node-id=0%3A1&mode=design&t=ySZoxSK7i5XqvvHG-1)

---

### SKILLS

- [Specific skills!](https://github.com/hjanssena/FIS-Proyecto/blob/8bcf9cf14cb7ba1417732637ee52c1f7d38d323a/Skills/General-skills.md)
- [Generic skills!](https://github.com/hjanssena/FIS-Proyecto/blob/8bcf9cf14cb7ba1417732637ee52c1f7d38d323a/Skills/General-skills.md)