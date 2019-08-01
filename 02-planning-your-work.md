#### CHAPTER 2: Planning Your Work
===================================

1. Identifying Requirements: Double-diamond model and Quantitative research
2. Defining the Work: User stories and a set of acceptance criteria
3. Tracking the Work: Scrum methodology

1. Identifying Requirements: Double-diamond model and Quantitative research

* Workshops are one of the most common ways of eliciting requirements. Workshops involve getting a bunch of people together and running activities, with the hope of getting some useful information out of them.

* Double-diamond model (Discover -> Define -> Develop -> Deliver)
  * Explore problem space and Refine problem definition
  * Explore solutions and Define solution details
  
* Quantitative research
  * Raw data is analyzed to discover information

2. Defining the Work: User stories and a set of acceptance criteria

* Senior or lead developers may be brought in early to help other team members (such as UX practitioners) understand any technical restrictions to that process, as well as identify alternative ways of solving a problem.

* User stories frame a new feature from the point of view of a user, and are commonly expressed in the form:
  * As someone
  * I want to do something
  * So that I can achieve something.

* Characteristics of a good user story (INVEST)
  * Independent: The story cen be achieved without any other user stories being done first.
  * Negotiable: The story can be changed or discarded at any point until work starts on it.
  * Valuable: High value/low cost items tend to be the highest priority, whereas low value/high cost items can be discarded.
  * Estimatable: The story is estimated with a value and cost to it.
  * Small: Subtle details are missed if the story is large.
  * Testable: Work done by a QA or automated tests within a team.

* A set of acceptance criteria and wireframes or visual assets

3. Tracking the Work: Scrum methodology

* The single most important thing is the backlog, which is a prioritized list of things to work on. 

* In Scrum, the development team works in fixed-length sprints and agrees at the start of the sprint how many items to accept from the backlog into the sprint. 

* By the end of every sprint, the development team should have produced a “potentially shippable increment” of the product, so value is being added on a regular basis.

* A product owner, who should be empowered to make decisions around the product being built and is responsible for building the backlog, and should be accessible to the development team.

* A Scrum Master, who is responsible for facilitating Scrum within the team and working with the product owner and stakeholders to produce a backlog, and who can facilitate removing impediments or “blockers” that stop work in the sprint and the development team itself. 

* A development team should be cross-functional and capable of doing all the work to deliver a backlog item within a sprint.

* A sprint starts off with a planning session. In the first half of the sprint planning session, the product owner and the development team negotiate which backlog items should be accepted into the sprint—the idea is that the team only accepts items it thinks it can complete in the sprint. 

* A “definition of ready”-defining what it means for a backlog item to have sufficient definition for a team to accept it.
* For a feature to be considered ready for development, the following things must be complete:
  * The product owner has prioritized it.
  * UX, product, and dev have developed and agreed upon acceptance criteria for it.
  * The development team has estimated it (or re-estimated, if the scope of the item has changed).
  * The technical lead is happy with the proposed approach, if it impacts the technical architecture.
  * If the feature involves any changes to administrator workflow, the administrators have been consulted.
  * If the feature requires any changes to the data schema, the data architect has reviewed it.
  * Any dependencies on external APIs have been identified.
  * If any new UI assets are needed, they have been identified.

* A “definition of done”—an agreement on what an item being completed actually means—is determined by the Scrum team. 
* For a feature to be considered done, the following must be complete:
  * The code should conform to the coding style guide.
  * All new code should have unit tests written against it, and all unit tests must pass.
  * The tech lead must have reviewed the impact on the cross-functional requirements of the product.
  * The code should have been written by a pair, or reviewed by a peer.
  * The UX designer and product owner should have seen the feature in the QA environment.
  * The tester should have exercised the functionality and smoke tested the product in the QA environment.
  * Browser-based automation tests should have passed in all supported browsers.
  * Any bug tickets identified by the manual QA should have been resolved.

* Estimation techniques known as “story pointing” and “velocity tracking” are used to help determine how much work a team can accept into a sprint—these are discussed in more detail in the Prioritization section.

* In the second half of the sprint planning session, developers break down the individual stories into tasks that make sense for that team. These tasks can often be things like “create acceptance criteria,” “produce wireframe,” or “add new API endpoint to backend.”

* While the sprint is in progress, each day should start with a daily standup, where the product owner, Scrum Master, and development team get together around the task board and discuss what they did the previous day, what they plan to do that day, and whether there is anything stopping them (blockers). Each person should be limited to one minute, and only one person should talk at a time. 

* The standup is referred to as such because standing (for those that can), as opposed to sitting, keeps the meeting short. 
* The standup is not intended to serve as an update for management, and only those who are part of the core team should talk, although others are allowed to observe.

* If any blockers are identified in the daily standup, they should not be solved in the meeting unless absolutely necessary. Instead, the Scrum Master should make a note of them and mark the corresponding item as blocked. After the standup, team members can discuss as a smaller group any actions that may be needed and allocate those appropriately in order to unblock the task.

* At the end of the sprint, the sprint review occurs. As with sprint planning, this occurs in two parts. 
  * The first part is the demo, which is a chance for the team to show the completed work and the shippable increment to any stakeholders. 
  * The second is the sprint retrospective. The sprint retrospective is a chance for the team to look back at how the sprint went, and to identify any ways their processes can be improved to make the next sprint more successful. The retrospective must be as open and honest as possible, and is attended only by team members—other stakeholders are rarely invited. The Continuous Improvement section further on in this chapter discusses retrospectives in more detail.
  
* Within a sprint, it is common to have a burn-up (or burn-down) chart, which tracks the progress of the team within the sprint, and to indicate whether or not it’s likely that all the backlog items will be completed. The backlog as a whole can be tracked in this way, across sprints, to track progress towards any larger goals, or to help make estimates.

4. Continuous Improvement: Retrospective and Tackling technical debt

* The way your team goes about planning and tracking work should not be static. It should constantly evolve in response to how your team grows and changes. In Scrum, the end-of-sprint retrospective (or “retro”) was introduced as a way for the team to reflect on their work and how they improved. 

* The most common way to run retrospective is to look back to identify what went wrong, and then come up with actions to address those deficiencies.

* Regardless of how you run a retrospective, there are a few principles to take into account. 
  * One is known as the “prime directive” of retrospectives: regardless of what we discover, we understand and truly believe that everyone did the best job they could, given what they knew at the time, their skills and abilities, the resources available, and the situation at hand. 
  * The other key piece is that the team should feel that the retrospective is a safe place for them to engage in constructive discussion and suggest improvements. The substance of the discussion should also be available to stakeholders who are not in the room, so any potential improvements can be shared, and wider feedback acknowledged. 
  * Another important practice is to keep the retrospective focused on things that are under the team’s control. If a sprint went badly due to external factors (for example, company-wide redundancies, or a DDoS on the web site), although it can be cathartic to indulge in a complaint session, it’s not especially productive to do so.
  
* One possible format for a retrospective might be to start off by reflecting on any planned actions from the last meeting, seeing if any were completed, and determining which ones should be carried forward, if any. It’s then often useful to make a simple observation on how team members think the last sprint went, and see if there’s consensus and whether or not the feedback was positive.

* This can flag issues to talk about immediately; if not, it’s then a good idea to reflect back on individual factors from the previous sprint that influence what went well and what went badly. Once these specific events are identified, you can cluster them around themes and discuss what caused them to happen, before moving on and identifying ways to either make sure they continue (if they were good things), or avoid them happening again (if they were bad). Throughout the whole process, it’s key to make sure you’re reflecting on the good things that are worth celebrating and continuing, as well as the things to be improved.

* The [Retromat](https://retromat.org) is a tool that can generate activities within this framework, though you should make sure you adapt them for your team’s particular situation.

* Retrospectives are an important part of your team’s work, but it’s important that they aren’t the only time you reflect and practice self-improvement. Some teams have an area of their task board for sticky notes based on observations as they happen, and if some major event occurs, it’s okay to deal with it then and there rather than defer it to a retrospective. However you decide to do self-reflection and continual improvement on processes, you should make sure it works for your team.
 
* The retrospective is one method of self-improvement, but it’s not the only one. 

* Tackling technical debt is another way of self-improvement, and a key concern for any team. 

* It’s often tempting to place technical debt on your backlog as a thing to be solved, but it often never is, as it’s hard to explain its business value to your stakeholders, and it makes it hard to prioritize. There are two ways around this. 
  * The first is to ensure you express any technical items in the same form as any other user story. For example, if your tests take a long time to run, and you wanted to experiment with parallelization, it might be tempting to add a backlog item that says, “enable parallel test running.” Instead, you could say: As a developer, I want my tests to complete in under 60 seconds, So that I can make deployments quicker. This is clearly stated in language other stakeholders can understand, and can hopefully be prioritized by your product owner like any other work.
  * Another approach to tackling technical debt is to apply the Boy Scout rule: always leave the campsite cleaner than you found it. This time, our campsite is our codebase. Every time you work on a new feature, if you come across some technical debt, tackle it immediately rather than deferring it to later. 
  * Alternatively, if you know there is technical debt that needs solving, and there’s an upcoming feature that would benefit from that debt being solved, then simply build it into the estimate of that feature, as the two are linked.
  
* Some teams also have “tool time.” If there are common tools used by multiple teams, but your organization isn’t big enough for a dedicated platform team, then it is common to dedicate one dev per week for general maintenance tasks, like upgrading Jenkins, or other minor improvements. 

* If there are different teams in an organization, this can be cross-team work, so all teams benefit. The flipside is that it can then be hard for an individual team to prioritize, in which case each team donates one person for a set period to make improvements everyone can benefit from.

5. Prioritization & Estimation

6. Managing Bugs

7. Continuous Delivery



