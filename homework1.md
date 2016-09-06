<p align=center><b>HOMEWORK 1</b></p>
Submitted by <br>

|First Name|Last Name|Student ID|
|----------| --------|----------|
|AVINASH RATNAVEL MAHARAJ |       RATNAVEL      |    107143926    |
|CHIRAG                   |       KAMAT         |    107164851    |
|SHAM PRASAD              |       PS            |    106595940    |
|PRATIMA                  |       SHERKANE      |    107162787    |
<h3>ANSWER 1  -  ESSENTIAL DIFFICULTIES</h3>
<p align="justify">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspAccording to Brooks, essential difficulties are difficulties that occur because of inherent or intrinsic nature of the software.
Brooks states that 
</p>
>“The essence of a software entity is a construct of interlocking concepts: data sets, relationships among data items, algorithms, and invocations of functions. This essence is abstract in that such a conceptual construct is the same under many different representations. It is nonetheless highly precise and richly detailed.” 

<p align="justify">
(Definition from No Silver bullet article).  According to Brooks, 80% of difficulties in software systems arise due to Essential 
difficulties. From the article “No Silver Bullet” , we can understand that software systems are inherently complex and have lot of 
requirements and lot of constraints. So these inherent behaviours of the software systems produce many difficulties for making and
maintaining software. Let us consider an example of a Health Care System. The software team would have developed the software and would
have given the software to the client for testing. After seeing that, client may request lot of changes to the requirement. This is one of the main essential difficulties. As stated in the lecture, customers will not know when to request for changes. If the changes stated by
the customers are more, then it is difficult for the software team to redesign the software. Another example can be, software designed
for one state may not be used in other state because the rules and environment change. We should consider all this inherent difficulties in mind before developing software.</p>

<h3>ANSWER 2  -  ACCIDENTAL DIFFICULTIES</h3>
<p align="justify"> According to Brooks, “Accidental Difficulties are those difficulties that attend its production today but are not inherent”.
According to him, these difficulties account for only smaller part- may be 20% of the difficulties. Some people have understood this definition in a different way. Some people thought that accidental difficulties are difficulties that occur by chance. But what Brooks actually meant about accidental difficulties is that : “The use of technique A for benefit B unfortunately introduced problem C into the process of software development” (According to the lecture).We can understand that some new tools or techniques that were produced to solve some problems would actually introduce some other new problems. But these problems account only for 20%. He also says that a single technique could not increase the order of magnitude. It could be achieved only by combining multiple techniques and industry wide enforcement and discipline. Let us consider an example of introducing a new framework for development. The new framework would actually have advantages and can be faster but unfortunately the new framework itself can have some problems that will be introduced into our system. For example, the new framework will not support windows XP, but we would have used that environment for a very long time which makes it very hard for us to adapt to the new ones </p>

<h3>ANSWER 3 - TYPES OF ESSENTIAL DIFFICULTIES</h3>
<p>
</p>


- **Complexity** :
Nowadays the software systems have become more complex because of the widespread use of it and also because these systems have become more powerful. Very big software systems actually have lot of states and became more complex. In software engineering, abstraction is very difficult because every software will have its own modules. So each time we develop a software, we must develop the modules according to that product’s requirements. For example, a banking application is very much different from a health care application and hence we cannot create abstractions that are related to each other in most cases. This may cause some problems such as product flaws, delays etc. </p>

- **Conformity** :
Anything might happen in a company during the process of software development. There might be change in requirement, a new process might have to be implemented or the whole structure of the organisation could change. For example, let us consider a company that produces multiple softwares to its clients. The CEO of the company may change the rules of the company, which may affect the development process. Integrating new software with the existing old system (legacy system) becomes difficult sometimes. From the lecture, we clearly understand that that there is no plan for this change. The changes can happen at any time and we must face it as it happens. We must have some system in place to accomaodate the changes without having too much trouble.

- **Changeability** :
Clients or customers request for many changes to software developers because their requirements change frequently. More than manufacturing a software product, pressure to change it is greater for the software team. For example, let us consider a health care system. The software would have been completely built according to the initial requirements. After the review, the customers or clients may request multiple changes which may make our software developers to completely remodel the system. The clients actually are not aware about the time or circumstances on when to place a change request. It usually becomes difficult for the software developers if the changes are made during later stages. In other fields, this change is not easy. Consider a building built in downtown by a said company. The customer cannot make any big design or structure changes to the building because it will incur huge costs. But in software systems, clients ask us to change the systems frequently as modifications to the system can still be considered and most of the time it is feasible to implement the changes albeit at rather high costs. 

- **Invisibility** :
When the requirement is given, it is very difficult to imagine the outcome of the software by the software developer. It is important that the software developer understand the problem thoroughly. There are UML diagrams that can be laid out , which will help the software developer to visualize the software. There are mainly 13 different types of diagrams used. It is very difficult to state the problems using these diagrams. Although some kind of visualization is given to them, it is difficult for the developer to physically see a software - it is rather invisible due to its high level of complexity.  For example, let us consider a software designed for a restaurant. First we must gather all requirements from the customer and then we try to visualize the outcome of the software. Generally before coding, the software team first designs all these diagrams and tries to visualize the software. It is very important because if the software developer does not understand the problem properly then the resultant software will be completely different from that of the customer needs.

<h3>ANSWER 4 - WHY NO SILVER BULLET?</h3>
<p align="justify">Brooks defines silver bullet as “A single technique or technology that by itself can deliver one order-of magnitude improvement to some aspect of software development” (Lecture). From the definition we can understand that silver bullet is something that can improve the software system atleast by one order of magnitude. Even a small improvement is considered to be huge. He feels that there is no single technology that can improve the productivity of the software system. According to him, there is no magical cure for the problems faced during manufacturing a software product. That is why he says that there is no silver bullet. Brooks goes on to argue that the methodologies such as high-level languages, time sharing, OO analysis, design and programming have provided breakthroughs in attacking accidental difficulties, however, there is still no silver bullet because these techniques haven't met the deadline of 10 years or a target of a 10 times improvement in the production of software.</p>

### ANSWER 5 - DIFFERENCE BETWEEN SOFTWARE ENGINEERING AND COMPUTER SCIENCE?
Software engineers share a similar relationship with Computer Scientists as what a chemical engineer shares with a chemist. Let’s take an example on the Chemistry side of things.  The chemist is involved in a lot of research work to see if he can convert salt water to potentially drinkable water. This is sort of an invention. Once this technique becomes successful, his part of the job is done. It is at this point, our chemical engineer comes into picture. A chemical engineer would then take this technique to apply it to salt water to produce “potentially shippable and viable” product. He has to consider various factors such as the following:
- **Scalability** – A chemical engineer is supposed to manufacture tons of gallons of drinkable water which should then be bottled and shipped to large metropolitan and cosmopolitan cities.  So, he is supposed to consider the quantity of water that needs to be collected from the salty water bodies and then scale it accordingly.
- **Budget** – A chemical engineer needs to look at the budget and then decide upon the costs incurred in processing the salt water and all the other process that’s involved in the conversion of salt water into drinkable water.
- **Demand and Supply** – A chemical engineer would look into the demand and supply ratio and produce drinkable water that’s actually needed by the people not overshooting the given budget.
With this example, we can get better insights at the relationship shared between software engineers (software engineering) and computer scientists (computer science).  Computer scientists would develop complex algorithms to solve a particular problem and Software engineer would pick up things that are developed by computer scientists to further develop a “potentially shippable, scalable” product.  As defined by __Daniel M. Berry__,
_“Software Engineering is that form of engineering that applies –_ 
  * _A systematic, disciplined, quantifiable approach,_*
  * _The principles of computer science, design, engineering, management, mathematics, and other disciplines.._
_to creating, developing, operating, and maintaining cost-effective, reliably correct, high-quality solutions to software problems."_

### ANSWER 6 - ABSTRACTIONS, CONVERSATIONS, SPECIFICATION, TRANSLATION AND ITERATION

**Abstractions**

Abstraction is one of the most important technique in software engineering. It is all about solving problems by developing abstractions that involves breaking down a problem into smaller parts until we can immediately solve it by an existing abstraction. It is about removing unnecessary details and keeping parts relevant to the project. Once the smaller parts are taken care of, we can synthesize the solution back up and solve the larger ones until an optimal solution is obtained. It is basically used to reduce complexity of systems and increase efficiency by identifying important features for representation. There is data abstraction – which is representation of data objects and Procedural abstraction – that is representation of instructions. Abstraction includes encapsulation, data hiding, inheritance and polymorphism. For example, if we have two functions that are performing the same task, we can combine it into a single function to get the desired result. We most of the time use abstractions that are created by others – sometimes we need to develop a product which involves certain function that have already been used before. Also, we most of the time use abstractions that are created by others.  In this case we use the already available abstractions and add our features to it. This way we get to save time as well as prevent ambiguity. Examples of where abstraction is used include architecture of systems, databases, programming languages, software framework and file systems.

 **Conversations**
 
Conversations play very important role in delivering a successful product. It involves having constant interactions with everyone involved in the project right from the beginning, to work as a team so as to keep everyone up to date on what’s happening, to come up with changes/ innovative solutions we think are better than earlier due to changes in demand of the product in the market or changes in the final deliverables. The key here is communicating effectively with people around us to make the project successful. The individuals involved here could be clients, domain experts, developers, designers, testers, marketers or the end users.  

**Specifications**

<p>Requirements and Specifications - both go hand in hand.</p>

**"Requirements Define Necessary Objectives (‘The What’) and Specifications Define How to Meet The Objectives (‘The How’)"** <sup>[1]</sup> 
 
As it is rightly said, establishing right requirements and specification is the first and one of the most important steps in software engineering. It is very important that we understand what has been specified already and build a project plan as best as we can do, as this lays a solid foundation to build a project. Not establishing them right might lead to problems that surface later in the development cycle causing more money and time to be spent in fixing the problems.
It is true that we might not have a clear picture of all the requirements and specifications at the start of the project and various requirements might evolve as the project progresses. That said, we must have a plan in place to handle new changes, overcome the challenges faced and incorporate solutions when necessary – in short facilitate incremental development.

A few specification types include Imperative, Declarative and Relational based on the way they are modeled. In particular, the specification phase involves various steps such as building the technical documentation, finalizing the software’s to be used, designing the project, preparing test plans and test cases, development lifecycles. The main points to be considered in this phase is to review if the details are right, complete, compatible, achievable and testable. Therefore, the importance of establishing good requirements and specifications is important.

**Translation**

Software engineering involves translation at every stage. The concept of a software product is translated to requirement specification. Specifications are then transformed into design which is then transformed into code and finally code is translated by compilers to give us the software end product. 

**Iteration**

A project works best when done iteratively; when the application/project is developed step by step. The clients’ needs keep changing, new elements need to be added, and problems need to be rectified. Hence we need to iteratively incorporate them by making modifications to designs and adding new functionalities instead of waiting till the very end of the project. A new version of the software is produced in each cycle of the model. The advantages of taking the iterative approach is: Having a much better end product since the defects are detected and rectified at an earlier stage, more attention is given to design and development than documentation in earlier stages. This phase works best when the project is big and major requirements are well defined. 

### **References**

1. Philosophe, "Requirements And Specifications"




