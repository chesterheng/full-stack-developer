#### CHAPTER 2: Planning Your Work
==================================

1. Identifying Requirements

* Organise Workshops
  * Gather Stakeholders: People from outside your team have an interest in what you’re building  
  * Technique: Double-diamond model
    * Discovery phase: Explore problem space and Refine problem definition
      * Involve a large group of stakeholders to identify the general shape of the problem space by first exploring the breadth of it, and then drilling down into any detail and unanswered questions.
    * Explore solutions and Define solution details
      * Tecnical team to identifying possible solutions, and then eliminating inappropriate ones and defining the actual specifications and details for each part of the solution.

* Take part in the UX processes
  * Technique: Quantitative research
    * Raw data is analyzed to discover information.
    * Focus on abstract facts and information and how humans feel. 
    * Use analytics systems, which report on how users interact with your product, but it can also come from elsewhere in your organization. 
      * For example, if building a tool to be used in a call center, looking at the data such as the average wait time can prove enlightening when it comes to discovering what requirements you might need to consider in your product.

2.2 Defining the Work

Once what a product needs to do has been discovered, it’s important to define that work. This definition works as both a method of communicating to the wider team what needs to be done and a way of ensuring that the problem is truly understood to the point where a solution can be expressed in code.
Within many teams, the user story has become almost synonymous with agile, although there are many other ways of documenting a requirement, and user stories can be used in non-agile settings too.
Chapter 2 planning Your Work
17
Chapter 2 planning Your Work
User stories frame a new feature from the point of view of a user, and are commonly expressed in the form:
As someone
I want to do something
So that I can achieve something.
Other popular techniques include hypothesis-driven development, the famous functional requirement document, or even more ad-hoc approaches such as free text on the back of an index card.
It’s very easy to write bad user stories. Take for example:
As a user
I want to register for an account
So that I can check out quicker next time.
This type of requirement will often come from someone inside the business, not a user, and is then retrofitted onto a user. Do users really care about checking out quicker? Maybe for a site they use a lot, but not for those that are accessed infrequently. Be
wary of requirements that have been retrofitted onto a user; they are often not actually plausible, and can result in wasted effort. Framing user stories correctly can change your approach, and help better meet the desired goals. The above user story may be more reasonably expressed as:
As the business
I want users to register for accounts
So that I can gain more insight into my customers, and research shows that customers with accounts are more likely to return to the site.
Retrofitting often happens when it is hard to write the “so that” part of a user story.
If it’s hard to write that line, the value may not be obvious and needs more definition. The second user story here can be more easily challenged, and be subjected to wider discussion with the rest of the organization. For example, does the value added here outweigh the cost of adding more friction to the checkout process? Also, the definition of what data to capture is different between the two stories.
Another sign of a poorly defined user story is one that simply says, “As a user.” Most users have different needs, and in the first story above, the statement doesn’t apply
to all users—only users that are likely to return to the site. When building for users,
18

it’s important to have good understanding of who your users are and the differences between them. Very few systems have only one type of user. It is common practice to develop “personas” that represent typical users and to give them identities to make it easier to understand their behavior.
Sometimes a user story is hard to define because it covers a wide range of related technology and user journeys. These types of user stories can often be converted into “epics,” which are user stories that have been broken down into (or are being broken down into) a number of smaller, more granular user stories. Epics often appear very early on, when an idea first comes around. For example, if you’re building a brand new e-commerce web site, an epic might exist in this form:
As a customer,
I want to purchase an item from the web site,
So that I can have that item delivered to me and I can enjoy it.
This can then be broken down into smaller user stories based on the different mechanisms of purchasing something. For example, user stories might emerge around searching the catalogue to find an item to purchase, or different ways of paying for an item. These individual user stories can be much easier to reason through and prioritize. For example, if you potentially have users outside your country, you will often need to build in an address finder, or have shipping cost calculators for those countries, but such functionality can be deprioritized to focus on the local market first and then picked up at a later date. Trying to tackle a user story that is too large can cause problems, as
it is harder to see what has been missed, and can cause unnecessary work as it brings unnecessary features along with it.
Bill Wake proposed the mnemonic INVEST to remember the important characteristics of a good user story.
• Independent • Negotiable
• Valuable
• Estimatable • Small
• Testable
Chapter 2 planning Your Work
19

Chapter 2 planning Your Work
An independent user story is one that is achievable without any other user stories being done first. This means that you can reprioritize your stories at any point, by moving them up or down your backlog in response to any changes in your organization.
Negotiability means that a story can be changed, rewritten, or discarded at any point until work starts on it. For example, if a story is proposed that has significant technical implications, it should be possible for developers to challenge that story and determine if there’s a simpler way of implementing it that still satisfies the business needs.
A user story must be valuable for it to make any sense. Stories that call for busywork, or fun technical items (for example, trying out a shiny new technology) but actually deliver no value to the organization have no worth as stories, so should not be on the backlog. Some teams go further than simply requiring a story to be valuable and assign “value points” to an item, which are an abstract concept similar to story points that can help with prioritizing items. High value/low cost items tend to be the highest priority, whereas low value/high cost items can be discarded. This is why user stories must
also be estimatable. If a user story isn’t estimatable, it is difficult to prioritize. It is also indicative of an underlying issue with the story. If something isn’t estimatable, it may be because a story is not clear or defined enough. This also usually means it’s not clear or defined enough for a team to be able to implement it.
Small is another important characteristic of a user story. Many teams will define a rule of thumb for how large a story can be. Teams running in sprints will often declare a story must be small enough to complete in a single sprint, and others will use a different rule of thumb based on what they feel comfortable with. When a story is large, it is easier to miss subtle details within it, which can lead to wasted effort, and it also becomes harder to realize parts of that story that might have value sooner, as instead the whole story must be defined. Anecdotally, large stories cause the biggest issues in delivery teams.
The final requirement of INVEST is that a user story must be testable. If a story is
not testable, it means there’s no way of figuring out if what the team has implemented
is correct, or if it has the right impact. Testability here often refers to the work done by
a QA or automated tests within a team, but is becoming more widely used to refer to a way of measuring the impact of delivering that feature on an organization (and therefore checking that the story did have value). When a requirement isn’t testable, it’s often due to a lack of clarity on what it is supposed to do and how it is supposed to behave. A lack of testability can also mean that the value isn’t well-defined.
20

These requirements can sometimes be in conflict with each other. Often, to make a user story independent, you must make it quite large. This is especially true when you start building the foundation of a system. The first item you build might require you
to set up build tooling, or have dependencies on other systems—for example, a login system. Some teams choose to address this by communicating that there will be a “first story overhead” to the first item they build, or by having a “foundation sprint” to get things ready. There are challenges beyond this initial foundation stage, too. For example, if a group of related but independent stories presents itself, it is common for the first in this group to require a larger set of technical tasks, which then makes implementing the later stories easier. This can challenge the estimatability of stories, as the order in which they are done will change those estimates.
Another example occurs when the build of a minimum viable product (MVP) is underway. The MVP is the bare minimum a product must do to be useful or valuable, so by its very definition, the product does not have value until the MVP phase is written. All stories in the MVP therefore become dependent on each other, and an item by itself may not be seen as valuable (for example, why have the ability to browse a catalogue until you have a way of checking out?).
In these early stages, taking the mnemonic literally is difficult, although as a product continues beyond MVP into continuing or BAU (business as usual) development, it becomes much easier to stick to the principles, and doing so becomes a key enabler for continuous delivery.
When new stories are proposed, they do not always meet the requirements of INVEST immediately. A new story is often a placeholder to indicate more work is needed to identify the value, or discover enough information to make it estimatable. It is common to have an “ideas” or “discovery” phase of your planning process where these stories are refined before moving on to being a full-fledged part of your backlog.
Once the high-level definition of a requirement is complete and it appears on the backlog, it then becomes necessary to define the rest of the work needed to make it ready for the team to implement. The kind of definition required will vary between teams. Relatively immature teams will require more definition before moving to the next phase, whereas more mature ones can work with less detail. Getting the level of detail just right is tricky! Too much and you’ve wasted time and effort in over-specifying; too little and you risk re-work or the wrong feature being built.
Chapter 2 planning Your Work
21

Chapter 2 planning Your Work
As work progresses from the idea phase into production, it requires differing levels of detail. As a developer, you may have certain expectations about what you are given, meaning there are also often stages before the development stage (such as visual design) that must be completed. Since this definition happens inside your team, it’s necessary
to have good communication and clear expectations about what happens during each phase. Senior or lead developers may be brought in early to help other team members (such as UX practitioners) understand any technical restrictions to that process, as well as identify alternative ways of solving a problem.
As a developer, the most common level of definition required is a set of acceptance criteria, and often some wireframes or visual assets if there is a UI component involved. It is unhelpful, though, for these to appear suddenly in a perfectly polished form; it’s useful for the development team to have visibility on work that is coming their way, before it is fully defined.
The method of communicating this definition to the development team is important too, and depends heavily on the way the team likes to work. One effective method
of doing this is called behavior-driven development, which relies on a mixture of conversation and written record to establish these acceptance criteria. Behavior-driven development is discussed in more detail in the Testing chapter.
Verbal communication is a much richer method for humans to communicate
than written communication, and although definitions often come to developers from other roles on the team, that is not the only direction communication can flow. Asking questions—and, for other roles on the team, being available to answer those questions— is as crucially important as producing a good definition in the first place! There are many effective teams that use verbal communication over a written record, and although this often causes problems with scale, it can work very well. Remember the agile manifesto: “People over processes.”

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
