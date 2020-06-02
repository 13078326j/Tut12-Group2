# Call Management Centre Information System: Report
### Group 2 - Syed Aziz, Sahil Chowdhury, Ivan David, Jesslyn Iskandar, Adem Deojee
#### Information Systems Development Methodologies Project
---
## Table of Contents 

1. [Executive Summary](#executive-summary)
2. [Problem Definition](#problem-definition)
    1. [Empathy Maps](#empathy-maps)
    2. [Stakeholders](#stakeholders)
    3. [Assumptions](#assumptions)
    4. [Point of View Statements](#point-of-view-statements)
    5. [Design Thinking Principles Approach](#design-thinking-principles-approach)
    6. [Methodologies](#methodologies)
    7. [Reflection](#reflection)
    8. [How Might We Statements](#how-might-we-statements)
3. [Our Propososed Solution](#our-proposed-solution)
    1. [Solution Backlog](#solution-backlog)
    2. [Project Tasks](#project-tasks)
4. [Solution Models](#solution-models)
    1. [Use Case Diagrams](#use-case-diagrams)
    2. [Activity Diagrams](#activity-diagrams)
    3. [Class Diagram](#class-diagram)
    4. [Collaborative Diagrams](#collaborative-diagrams)
5. [Conclusion](#conclusion)
    1. [Competitve Advantages](#competitive-advantages)
    2. [Possible Effect of Project Failure](#possible-effects-of-project-failure)
<a name="Executive Summary"/>
<a name="Problem Definition"/>
<a name="Empathy Maps"/>
<a name="Stakeholders"/>
<a name="Assumptions"/>
<a name="Point of View Statements"/>
<a name="Design Thinking Principles Approach"/>
<a name="Methodologies"/>

<a name="Reflection"/>
<a name="How Might We Statements"/>
<a name="Our Proposed Solution"/>
<a name="Solution Backlog"/>
<a name="Project Tasks"/>
<a name="Solution Models"/>
<a name="Use Case Diagrams"/>
<a name="Activity Diagrams"/>
<a name="Class Diagram"/>
<a name="Collaborative Diagrams"/>
<a name="Conclusion"/>
<a name="Competitive Advantages"/>
<a name="Possible Effects of Project Failure"/>

## Executive Summary
#### Purpose of the report 
A major travel company performs sales of holiday packages. Currently they offer services through their in-house call management centre (CMC). With this, Relationship Managers from the company are able to provide information on particular travel packages as well as perform sales to their end-customers and potential customers.

This report analyzes and evaluates the Call Management Center's program by creating a new improved information system for a major travel company. 
This aims to translate raw data into usable information which will be used by Call Management Center to make decisions. The report also displays how the implementation of the new information system will address the problems within the travel company through various UML diagram designs and solutions. At last the report indicates the main benefits of the proposed solution ,specifically better customer satisfaction as well as improved sales rates, on the other hand the possible effects of project failure are noted such as extra resource costs and missed opportunities if the project happens to fail.



## Problem Definition
Due to the high number of holiday packages and difficulty with effectively converting customers to purchase the current operational activities of the Call Management center. The problem includes:
* Unacceptable waiting time for customers
* Lack of customer information and inefficiency in redirecting customers to relationship managers who are capable of helping.
This has led to slow call rates, waste of organizational resources and a negative customer relationship. Customer intentions cannot be fully understood by relationship managers, which means that customers can be redirected or simply hanging up several times.

### Objectives 
The objective of this project is to deal with the current problems of the Call Management Center’s operations and propose an improved solution in the form of a new information system. The solution proposed will also allow the Call Management Center to handle the requests and calls from customers and relationship managers for sales of the holiday package. In addition, the new program would allow the travel company, due to improved analytical processes, to target potential customers or delay existing customers.

### Empathy Maps
#### Relationship Managers
![rms](https://github.com/13078326j/jesslyn-/blob/master/Empathy%20Map%20Relationship%20Managers.png "Relationship Managers")
#### Customers
![customers](https://github.com/13078326j/jesslyn-/blob/master/Empathy%20Map%20-%20Customer.png "Customers")
#### Company Owner
![company owner](https://github.com/13078326j/jesslyn-/blob/master/Company%20Owner.png "Company Owner")

### Stakeholders
* Relationship Managers - Employees of the travel company and they will use the system to automate their calls and perform sales of holiday packages.
* Customers - Will interact with the system when they call the company where they will be assigned to an appropriate relationship manager and customers will ask queries about their desired holiday package.
* Company Owner - Owner of the travel company and wants to develop an information system to enhance their Call Management Center(CMC).
* Airline Companies - Provides available ticket dates that the travel company can book for customers.
* Hotel/Resort Companies - Gives access of the available hotel/resort to the travel company so they can book based on customers desired hotel/resort.
* Telecommunication Provider - A type of communication service provider that the travel company uses. 

### Assumptions on stakeholders
1. The company owner made the decision to remake and improve the call management centre information system.
2. Relationship managers are incentivised to make sales in order to earn commission
4. Relationship managers with higher skills will get more matches with a customer to offer higher quality services. This might translate into more customers
5. When dealing with a customer, relationship managers must have knowledge about all the holiday packages thats on sale
6. Relationship managers must be persuasive so that they can sell more holiday packages and earn the customer's trust
7. Airline Companies and Hotel/Resort companies gives access of their information to the travel company to make reservations.

### Point Of View Statements
1. User: Customers enquiring about holiday packages   
   Need: To engage with Relationship Managers that are knowledgeable in desired package  
   Insight: Current system doesn't target matching between customers and suitable Relationship Managers  
   
2. User: End-Customers looking for best deal on a certain package  
   Need: To engage with Relationship Managers that can find the best possible deal on said package  
   Insight: Current system lacks ability to filter Relationship Managers through skill level and performance  
  
3. User: Relationship Managers who wish to make the most deals for the most commission\
   Need: To connect with customers on a personal level so they can build rapport\
   Insight: Current system does not profile customers and RMs in terms of their age, sex, culture or language proficiency

4. User: Customer wants to talk to a representative of the company as soon as possible and does not want to wait on hold\
   Need: An Interactive Voice Response unit and Automatic Call Distributer to handle their request\
   Insight: Current system poorly handles caller overflow and many customers hang up

5. User: Customer wants to get higher scores so that they are served first\
   Need: Getting a score from 1-10 based on the likelihood to purchase the product according to some pre-loaded criteria\
   Insight:Current system only serves customers with higher scores first and make the lower score customers wait.
   
6. User: Relationship Managers want to help as many customers as possible                   
   Need: To be assigned customers as efficiently as possible                           
   Insight: Current system ineffeciently assigns a customer to a relationship manager.
   
7. User: Relationship Managers who are having an outbound calling                  
   Need: Customer details, guidelines and script to improve services to end-customer\                       
   Insight: Current system lacks good quality services to end-customers.

8. User: Travel company                    
   Need: An information system to improve Call Management Center operations                     
   Insight: Current system does not provide adequate amount of assitance to relationship managers in serving their end-customer.
   
9. User: Relationship Managers want to help as many customers as possible                   
   Need: To be assigned customers as efficiently as possible                           
   Insight: Current system ineffeciently assigns a customer to a relationship manager   
   
### Design Thinking Principles Approach
1. Empathise: We must put ourselves in the minds of relevant stakeholders to identify their issues and thoughts. Utilise empathy maps to achieve this.
2. Define: We then define their issues by creating several P.O.V statements to aid our understanding of the problems. 
3. Ideate: In this stage we will brainstorm to create ideas through the use of H.M.W statements branching from the P.O.V statements.   Assumptions will also be decribed using team reflections.  
4. Prototype: Various models will be made to visualise the proposed system solution for the travel company. These include the use case, activity, class and collaborative diagrams.  
5. Test: Proposed logical solutions for the information system will be made sure that they satisfy the requirements and constant update iterations will also be made to continue agile development.
### Methodologies 
Agile scrum methodology was used to work on this information systems development project. It is a methodology that relies on incremental development. Usually each iteration consists of 2-4 week sprints where each sprints goal is to build the most important features of the system;  to come out with a potentially delieverable product. Additional features are able to be built in based on stakeholder and customer feeback in betweens sprints.

Other project management methods emphasize on building an entire product in one iteration from start to finish, however agile scrum methodology focuses on using several iterations of a product that provide stakeholders with highest value in the least amount of time.

Agile Scrum also has several benefits. It encourages products to be built faster as each set of  goals has to be completed within its sprint time frame. Additionally it helps the project team to focus on current sprint objectives and increases productivity.



### Reflection
The project started with understanding the assignment case study and the first stage of design thinking (empathy). Based on the discussion topic, we identified the stakeholders with and involed in the implementation of a call routing system for the travel company. 

For the key stakeholders who we felt will be most impacted and have the most insight on the changed processes, we have developed empathy maps. For customers, relationship managers and company owner, our empathy maps are created. We have provided corresponding POV (point of view) statements along with our empathy maps, which have identified the needs and perspectives of stakeholders with regard to the call system.

We have been able to define the issue in step 2 of the Design Thinking process through the empathy maps and POV statements. We have found that it is crucial for customers to minimize the waiting time for calls and to be matched with a Relationship Manager that is suitable for their needs and queries. It is essential for relationship managers to be well suited for their customer requirements.

#### Assumption outside the project specification
1. All insights made towards the existing (old) system are assumed based on the requests made in the discussion topic
2. Assume that the initial 10 minute profile questionnaire for relationship managers is adequate enough for a strong base 
3. The development of the software is outsource to external company
4. Assume a strong economy, without major recession.
5. Assume that economic policy developments are not unexpected to make our service redundant or undesirable.
6. End-customers will be available for testing during the time they agree to do so.
7. The cost of the project will remain the same as the initial cost.
8. Different departments must provide licence funding as needed.
9. Project will follow agile methodology throughout execution.
10. Training rooms for relationship managers will be available at the training center as needed.
11. The scope of the project will not change as soon as the stakeholders sign the scope statement.
12. Relevant stakeholders will attend weekly meeting for discussions.
13. There is a sub-system that matches with relationship manager and customer
14. Different departments will provide licence funding, as necessary.
15. Internally, training is carried out without any additional costs.
16. The project will follow the principles and criteria of team governance.
17. Project servers arrive configured as expected.
18. The correct number of handheld devices arrives without delays at the target delivery date.

#### How Might We Statements
1. How might we ensure customers can engage with relationship managers that are knowledgeable for their desired package?  
2. How might we ensure customers can engage with relationship managers to find the best deals from the holiday package?
3. How might we find a way to connect with customers on a personal level to build a rapport?
4. How might we minimise customer's call waiting time to not let customers hang up when waiting on hold?
5. How might we find a new way to make the system equal without serving customer based on scores?
6. How might we ensure relationship managers avoid only focusing on improving their ranking?
7. How might we improve the current system to assign customers with relationship managers efficiently?
8. How might we improve the relationship between customer and relationship manager?
9. How might we improve customer's phone call experience?
10. How might we find a way to improve relationship managers performance and knowledge about the holiday package?
11. How might we ensure relationship managers profile is kept up to date? 
12. How might we ensure relationship managers skills is kept up to date? 
13. How might we ensure customer's satisfaction in purchasing the holiday package or phone call is achieved?
14. How might we find a way that the system works efficiently?
15. How might we find a way to make customer's wait time be enjoyable?

Applying this design thinking to this project’s initial stages, allows us to better understand the scope of the project and our design objectives and our commitment to the needs and wants of our stakeholders. Phases 1 and 2 of design thinking provided us with a framework for the prototyping and modelling phase of our project. Knowing our priorities helped us to build up and manage our backlog that is dealt with GitHub issues.

## Our Proposed Solution

### Solution Backlog
Backlogs are sorted by priority from highest to lowest.
#### Product Solutions 
<table>
  <tbody>
    <tr>
      <th>Deliverable</th>
      <th>User Stories</th>
      <th>Completion</th>
    </tr>
    <tr>
      <td>Automatic call routing and dynamic call flow control system</td>
      <td><a href="https://github.com/13078326j/Tut12-Group2/issues/9">#9</a></td>
      <td><li> - [ ] </li></td>
    </tr>
    <tr>
      <td>Customer and Relationship Manager Skill Score Calculator</td>
      <td><a href="https://github.com/13078326j/Tut12-Group2/issues/9">#9, <a href="https://github.com/13078326j/Tut12-Group2/issues/7">#7, </a> <a href="https://github.com/13078326j/Tut12-Group2/issues/11">#11</a></td>
      <td><li> - [ ] </li></td>
    </tr>
    <tr>
      <td>Profiler Tool and its applications (target list, script/guideline provider, etc.)</td>
      <td><a href="https://github.com/13078326j/Tut12-Group2/issues/9">#9, <a href="https://github.com/13078326j/Tut12-Group2/issues/19">#19, </a><a href="https://github.com/13078326j/Tut12-Group2/issues/10">#10, </a><a href="https://github.com/13078326j/Tut12-Group2/issues/6">#6, </a><a href="https://github.com/13078326j/Tut12-Group2/issues/5">#5, </a><a href="https://github.com/13078326j/Tut12-Group2/issues/7">#7</a></td>
      <td><li> - [ ] </li></td>
    </tr>
     <tr>
      <td>Interactive Voice Response Unit</td>
      <td><a href="https://github.com/13078326j/Tut12-Group2/issues/12">#12, </a><a href="https://github.com/13078326j/Tut12-Group2/issues/12">#8</a></td>
      <td><li> - [ ] </li></td>
    </tr>
  </tbody>
</table>

#### Project Tasks
<table>
  <tbody>
    <tr>
      <th>Deliverable</th>
      <th>Issue Link</th>
      <th>Assigned to</th>
      <th>Completion</th>
    </tr>
    <tr>
      <td>Business Report</td>
      <td><a href="https://github.com/13078326j/Tut12-Group2/issues/2">#2</a></td>
      <td><a href="https://github.com/ademdeojee">@ademdeojee</a>
      <td><li> - [x] </li></td>
    </tr>
    <tr>
      <td>Use Case Diagram</td>
      <td><a href="https://github.com/13078326j/Tut12-Group2/issues/13">#13</a></td>
      <td><a href="https://github.com/13078326j">@13078326j</a>
      <td><li> - [x] </li></td>
    </tr>
    <tr>
      <td>Class Diagram</td>
      <td><a href="https://github.com/13078326j/Tut12-Group2/issues/21">#21</a></td>
      <td><a href="https://github.com/Syed-Aziz">@Syed-Aziz</a>
      <td><li> - [x] </li></td>
    </tr>
    <tr>
      <td>Activity Diagram</td>
      <td><a href="https://github.com/13078326j/Tut12-Group2/issues/16">#16, </a><a href="https://github.com/13078326j/Tut12-Group2/issues/15">#15</a></td>
      <td><a href="https://github.com/13773357">@13773357</a>
      <td><li> - [x] </li></td>
    </tr>  
    <tr>
      <td>Collaborative Diagram</td>
      <td><a href="https://github.com/13078326j/Tut12-Group2/issues/17">#17, </a><a href="https://github.com/13078326j/Tut12-Group2/issues/18">#18</a></td>
      <td><a href="https://github.com/Ivydude10">@Ivydude10</a>
      <td><li> - [x] </li></td>
    </tr>
  </tbody>
</table>

## Solution Models

### Use Case Diagrams
![Use Case Diagram](USE%20CASE%20DIAGRAM4-Page-2.png)
### Activity Diagrams
#### Customer
![Activity Diagram](https://github.com/13078326j/Tut12-Group2/blob/master/activity%20diagram%20iterative%204%20customer.png)
#### Relationship Manager
![Activity Diagram](https://github.com/13078326j/Tut12-Group2/blob/master/activity%20diagram%20iterative%205%20rm.png)
### Class Diagram
![Class Diagram](https://github.com/13078326j/Tut12-Group2/blob/master/Class%20Diagram%20Iterative%204.png)
### Collaborative Diagrams
#### Customer
![](https://github.com/13078326j/Tut12-Group2/blob/master/CollabDiagram%20v3.png)
#### Relationship Manager
![](https://github.com/13078326j/Tut12-Group2/blob/master/CollabDiagram%20v3-1.png)

## Conclusion
### Competitive Advantages
#### Increased Call Efficiency
The implementation of an updated automatic call routing system with dynamic flow control will allow for a faster and more efficient way of handling customers inbound and outbound calls. This means that now more customers will be interacted with in a shorter timespan, which provides an advantage over competitors as more potential clients can be reached per day over a competitor. This leads to more market influence and sales over time.
#### Better Customer Interaction, Satisfaction, Retention, and Sales Rate
The creation of both the skill score system and profiler tool will not only provide a customer satisfaction and sales benefit over competitors, but will also improve the satisfaction of sales employees who get commission. The questionnaire will be a very small 10 minute time investment which will will allow for the profiling system to match RMs with the right customers. The pre-existing social and cultural traits that the employee and customer have in common, in partnership with the automatically provided target list, product knowledge, script, and guidelines, will substantially increase the chance of sale and customer retention. Furthermore, the skill score and customer score system will create better opportunities and higher sale chance with high priority customers, as they will be preferenced by the system. 
#### Improved Relationship Manager Performance
The addition of a RM scoring system will incentivise the employees to work harder and smarter. As they increase their skill score, the quality and volume amount of customers will increase due to their high priority, thus allowing for more commission. The repeated evaluation of their performance will always keep them striving for more. This will lead to more sales and profit in the long run.
### Possible Effects of Project Failure
#### Extra Resource Costs
As the costs of developing and undertaking a project are quite high, especially concerning resources linked to employees and equipment, a failure in the end product regarding stated requirements and business needs is disastrous for the call management centre as potential profits will be lost and funds will be wasted for no significant gain.
#### Missed Opportunity
The travel company’s business requirement of improving the operations of the in-house call management centre through the development of an information system linking the most suitable Relationship Managers to customers, may become a missed opportunity for success as if the project fails, the team would have to backtrack to fix the issues. However, this may not be possible if the requirements change drastically, as is common in modern business environments, thereby causing a loss in resources and financial gain.
#### Loss of Developers
If the project to improve the call management centre were to fail, the travel company’s Information Technology and Systems Development team may suffer significantly as many of the talented and skilled employees may not tolerate failure as it can make their career record appear deficient, causing them to leave the company and search for more successful teams. 
#### Decrease in Innovation & Advancement
Another possible effect of project failure includes the loss of future success as innovation and technological systems advancements would significantly reduce. As teams realise their project has failed, extra resources and focus will be unfortunately applied to improve the project, contributing to draining of these assets from important areas.
#### Employee Erosion
The organisation itself and its members may also suffer dramatically if the call management centre project were to fail regarding employee confidence, motivation, team relations, and acceptance to required change. Employees may second-guess every decision, constantly reminded of failure, blaming and bickering over responsibility for the failure, and hesitation due to increased fear of the unknown.
