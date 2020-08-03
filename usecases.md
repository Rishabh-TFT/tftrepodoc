# Use Case

Use case plays a significant role in the distinct phases of the Software Development Life Cycle. Use Case depends on ‘User Actions’ and ‘Response of System’ to the User Actions.

It is the documentation of the ‘Actions’ performed by the Actor/User and the corresponding ‘Behaviour’ of the System to the User ‘Actions’. Use Cases may or may not result in achieving a goal by the ‘Actor/User’ on interactions with the system.

In Use Case, we will describe **How a System will respond to a given Scenario?**. It is ‘user-oriented’ not ‘system-oriented’.

### It is ‘user-oriented’: 
We will specify ‘what are the actions done by the user?’ and ‘What the Actors see in a system?’.

### It is not ‘system-oriented’: 
We will not specify ‘What are the input given to the system?’ and ‘What are the output produced by the system?’.

The development team needs to write the ‘Use Cases’, as the development phase highly depends on them.

Use case writer, Team members, and the Customers will contribute towards the creation of these cases. For creating these, we need to have a development team assembled and the team should be highly aware of the project concepts.

After implementing the case, the document is tested, and the behavior of the System is checked accordingly. In a case the capital Letter ‘A’ denotes ‘Actor’, the letter ‘S’ denotes ‘System’.
Who uses ‘Use Case’ documents?

This documentation gives a complete overview of the distinct ways in which the user interacts with a system to achieve the goal. Better documentation can help to identify the requirement for a software system in a much easier way.

This documentation can be used by Software developers, software testers as well as Stakeholders.

## Uses of the Documents:

    Developers use the documents for implementing the code and designing it.
    Testers use them for creating the test cases.
    Business stakeholders use the document for understanding the software requirements.

### Types of Use Cases

There are 2 types.

They are:

    Sunny day
    Rainy day

### 1) Sunny day Use Cases

They are the primary cases that are most likely to happen when everything does well. These are given high priority than the other cases. Once we have completed the cases, we give it to the project team for review and ensure that we have covered all the required cases.
### 2) Rainy day Use Cases

These can be defined as the list of edge cases. The priority of such cases will come after the ‘Sunny Use Cases’.  We can seek the help of Stakeholders and product managers to prioritize the cases.
Elements in Use Cases

### Given below are the various elements:

**1) Brief description:** A brief description explaining the case.

**2) Actor:** Users that are involved in Use Cases Actions.

**3) Precondition:** Conditions to be Satisfied before the case begins.

**4) Basic Flow:** ‘Basic Flow’ or ‘Main Scenario’ is the normal workflow in the system. It is the flow of transactions done by the Actors on accomplishing their goals. When the actors interact with the system, as it’s the normal workflow, there won’t be any error and the Actors will get the expected output.

**5) Alternate flow:** Apart from the normal workflow, a system can also have an ‘Alternate workflow’. This is the less common interaction done by a user with the system.

**6) Exception flow:** The flow that prevents a user from achieving the goal.

**7) Post Conditions:** The conditions that need to be checked after the case is completed.
Representation

A case is often represented in a plain text or a diagram. Due to the simplicity of the use case diagram, it is considered to be optional by any organization

### Use Case Example:

Here I will explain the case for ‘Login’ to a ‘School Management System’.
**Use Case Name** Login
**Use case Description** A user login to System to access the functionality of the system.
**Actors** Parents, Students, Teacher, Admin
**Pre-Condition** System must be connected to the network.
**Post -Condition** After a successful login a notification mail is sent to the User mail id

**Main Scenarios** | **Serial No** |**Steps**
------------------ | ------------- | ------------------------------
Actors/Users	   |        1      | Enter username, Enter Password  
----------------   |        2      | Validate Username and Password	
----------------   |        3	   | Allow access to System
Extensions	   |        1a	   | Invalid Username, System shows an error message
----------------   |        2b     | Invalid Password
----------------   |        3c	   | Invalid Password for 4 times, Application closed


### Points to be noted

- Common mistakes that the participants do with Use Case is that either it contains too many details about a particular case or no enough details at all.
- These are textual models if required we may or may not add a visual diagram to it.
- Determine the applicable precondition.
- Write the process steps in the correct order.
- Specify quality requirement for the process.

##### How to Write a Use Case?

The points summarized below will help you to write these:

=> When we are trying to write a case, the first question that should raise is ‘What’s the primary use for the customer?’ This question will make you write your cases from the User’s perspective.

=> We must have obtained a template for the these.

=> It must be productive, simple and strong. A strong Use Case can impress the audience even if they have minor mistakes.

=> We should number it.

=> We should write the Process Step in its Order.

=> Give proper name to the Scenarios, naming must be done according to the purpose.

=> This is an iterative process, which means when you write them for the first time it won’t be perfect.

=> Identify the actors in the system. You may find a bunch of actors in the system.

**Example,** if you consider an e-commerce site like Amazon, there we can find actors like buyers, sellers, wholesale dealers, auditors, suppliers, distributors, customer care etc.

Initially, let's consider the first actors. We can have more than one actor having the same behavior.

**For Example,** both Buyer/Seller can ‘Create an Account’. Likewise, both ‘Buyer and Seller’ can ‘Search for Item’. So, these are duplicate behaviors and they need to be eliminated. Apart from using the duplicate cases, we must have more general cases. Hence, we need to generalize the cases to avoid duplication.

=> We must determine the applicable precondition.

### Use Case Diagram

Use Case Diagram is a pictorial representation of a user(s) Actions in a system. It does provide a great tool in this context, if the diagram is containing a lot of actors, then it is very easy to understand. If it is a high-level diagram, it won’t share a lot of details. It shows complex ideas in a fairly basic way.

#### Fig No: UC 01

[UC1](C:\Users\risha\Downloads\uc1.jpg)
School Login System

This is the Use case diagram of ‘Login’ case. Here, we have more than one actor, they are all placed outside the system. Students, teachers, and parents are considered as primary actors. That is why they all are placed on the left side of the rectangle.

Admin and Staff are considered as secondary actors, so we place them on the right side of the rectangle. Actors can log in to the system, so we connect the actors and login case with a connector.

Other functionality found in the system are Reset Password and Forgot password. They are all related to login case, so we connect them to the connector.
User Actions

These are the actions that are done by the user in a system.

**For Example:** Searching on-site, Adding an item to favorites, trying to contact etc.

#### Note:

  - **A System** is ‘whatever you are developing’. It can be a website, an app or any other software component. It is generally represented by a rectangle. It Contains Use Cases. Users are placed outside the ‘rectangle’.
  - **Use Cases** are generally represented by Oval shapes specifying the Actions inside it.
  - **Actors/Users** are the people who use the system. But sometimes it can be other systems, person or any other organization.
