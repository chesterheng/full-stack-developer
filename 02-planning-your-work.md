#### CHAPTER 2: Planning Your Work
==================================

1. Identifying Requirements

* Workshops are one of the most common ways of eliciting requirements. 

  * Workshops involve getting a bunch of people together and running activities, with the hope of getting some useful information out of them. 
    * The people from outside your team who attend a workshop are often referred to as stakeholders; these are the people who have an interest in what you’re building. 
      * For a news web site, this might include people like the editors, or for an online store, it might include the marketing team and buyers. 
      * It can also include people from outside your organization; in an e-commerce example, the backend systems might include the suppliers you work with. It also probably includes your end-users.
- The format of these workshops varies depending on who the stakeholders are and what phase of the project you’re in. Early on, it is common to initiate a discovery phase to understand the problem you’re trying to solve, rather than jumping straight to a solution. Some may think this is anti-agile, but it’s important to do just enough to avoid starting your journey in the wrong direction. You do not need to fully understand the problem space and fully define your solution before starting to build.
- Workshops in the discovery phase might involve a large group of stakeholders, getting everyone together in a room to define the problem that needs solving. 
- The stakeholders might not agree on what the problem is, but by eliciting all of their thoughts you should be able to pull out some common themes that will allow the delivery team to identify the challenge, and define a set of steps to hopefully overcome it.

This is referred to as the double-diamond model. 
- Explore problem space
- Refine problem definition
- Explore solutions
- Define solution details

- In this form of double-diamond model, you get everyone together to explore the entire problem, and then the team that is responsible for devising a solution refines it into the actual work that needs to be done to solve the problem at a high level. 
- First, you identify the general shape of the problem space by first exploring the breadth of it, and then drilling down into any detail and unanswered questions. 
- Then, the second converge-diverge diamond is followed, with first identifying possible solutions, and then eliminating inappropriate ones and defining the actual specifications and details for each part of the solution. 
- Remember that your job is to actually come up with the solution; stakeholders might understand their problems best, but not necessarily the best way technology can help them. This is where the double-diamond model can help, as it involves stakeholders to get the relevant information from them to design an appropriate solution, but a core group (often just the most senior members of the team) then refines that into what actually gets built. 
- There are many other techniques that make use of the double-diamond model, and many other models and ways of running workshops to gather requirements, but this is one example.

The field of User Experience (UX) has grown out of a mixture of the academic field of human-computer interaction with the traditional role of visual and interaction design, and many UX teams follow a user-centered design approach, which puts the user at the heart of the requirements-gathering process. A user experience practitioner is a very powerful ally during a requirements elicitation process. 

Many of the most successful organizations out there put user needs first and have teams with engineering and UX practitioners working side by side. 

Often the lines of those roles blur, and some UX practitioners contribute to the engineering, or developers take part in the UX processes, increasing team effectiveness through reducing communication overheads.

These forms of requirement gathering are known as qualitative research—that is, they focus on abstract facts and information and how humans feel. 

Another way of eliciting requirements comes from a method called quantitative research, where raw data is analyzed to discover information. 

Quantitative data gathering is most effective when your product is in front of a user, and can give stakeholders a great deal of comfort as compared to qualitative research, which can often be driven by “gut feelings” or other subjective information. 

On the flip side, humans are not rational beings, and many will trust their gut over statistics!

There is a definite science behind the analysis of quantitative data, and it’s important not to underestimate it. Statistics is a complicated subject, and it is easy to apply an inappropriate form of data analysis, or misinterpret the results, leading to bad decisions.

When working with users, quantitative data is much easier to gather than qualitative, so quantitative data can become more helpful later on in the development of a product when there are many real world users of your application. 

Continuous delivery is a technique that encourages releasing early and often, and for teams that practice continuous delivery, the use of quantitative data can become much more effective as it allows for collecting data whilst parts of a new feature are beng developed. This is discussed further in later chapters.

The most common form of quantitative data comes from using analytics systems, which report on how users interact with your product, but it can also come from elsewhere in your organization. For example, if building a tool to be used in a call center, looking at the data such as the average wait time can prove enlightening when it comes to discovering what requirements you might need to consider in your product.

2.2 Defining the Work

2.3 Tracking the Work

2.4 Continuous Improvement

2.5 Prioritization & Estimation

2.6 Managing Bugs

2.7 Continuous Delivery

2.8 Summary

Effectively planning your work before you do it increases your effectiveness, as it ensures you properly understand the problem you’re trying to solve. 

Historically, this planning was done formally with a large amount of definition up front, but in many situations that has been replaced by agile methodologies.

Agile methodologies focus on only planning what is actually needed right now, leaving you free to plan or re-plan other parts of your project in a way that reacts to change.

Planning starts with defining a backlog—a prioritized list of what the team will be building—and these items should be structured so that they are not purely technical to allow for them to be prioritized in line with the organization’s goals. 

Items of work then move through a workflow where additional detail can be added, perhaps by stakeholders in other disciplines such as UX, adding elements such as visual design, until finally it is deployed to your end users. 

Two major agile techniques are Scrum and Kanban, which take different approaches to tracking and managing work. 

Both Scrum and Kanban encourage teams to reflect on their workflows and update them often to ensure they meet the unique needs of that team. 

Where they differ is in how they allow prediction of when future work may be delivered, with Scrum using story points to determine a velocity, and Kanban using the average time of previous feature delivery.

In addition to planning new work, you must also manage bugs that occur during development, perhaps as a feature is being developed, or potentially hidden until later. 

These bugs can still be treated as backlog items, but capture their requirements in a different way.

Continuous delivery and continuous integration are two distinct but related approaches to managing the engineering work to enable the process of delivering a feature. 

Continuous delivery applies automation to make it easy for a backlog item to transition through the different stages—from idea to realized and deployed system— and continuous integration is how developers coordinate changes onto one shared codebase.
