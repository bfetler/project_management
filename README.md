## Practical Software Project Management

### Why project management?  

__Scenario:__  You're working on a project, writing software, adding and fixing features for a great new product.  Everything is going well.   __*Then*__ someone on the team wants to add a new feature, but it doesn't quite mesh with the rest of the product, and may delay the current timeline for release.

__Q: What can you do?__
+ Get organized. 
+ Plan ahead. 
+ Prioritize.  

__A: Project Management__ 

Project management helps you organize, understand, anticipate and react to changes in a plan or product.  Even if it's not your primary job, it will be somebody's job in your organization. 
Project management tools can help you understand how they think, help them plan, and keep everything running smoothly.  

There are several common styles of project management:
+ Agile
+ Scrum
+ Lean
+ XP or Extreme Programming

These are generally known as agile methods.  There are many resources available for them online.  Common features include:
+ Small flexible teams.
+ Iterative product cycles, with a working product at end of each cycle.
+ Several iterations to achieve a viable product.
+ Interaction with customer representatives to define, test and evaluate.
+ Short meetings to resolve issues.
+ Review of features, bugs, priorities and scope.

Regardless of project management style, in practice they usually share some common definitions and methods.

### Common Methods of Project Management

#### 1. Definition
*Q:* What is a project?  
*A:* An activity with a definite, measurable goal within a specified time frame.  

Example Mission Statements
+ Put a man on the moon by the end of the decade.  (JFK)
+ Create a way to post your resume online and track who visited it by the end of the year, or until you get a job.  Maybe 30 people would like to use it.  (Rasmus Lerdof, PHP creator)
+ Create an online music service for your friends to share music before festival season starts.

#### 2. Project phases
+ Start: 
    + Define the project.
    + Create mission statement.
    + Get backing of key stakeholders.
+ Middle: 
    + Many steps or iterations on most projects.
    + Ramp up resources, get stuff done.
    + Release working software on each iteration cycle.
+ End:
    + Push to production, product release.
    + Reallocate resources to other projects.
    + Plan for maintenance, product support.
    + Reflect on lessons learned.

#### 3. Define stakeholders, roles  
+ Stakeholders are anyone who has an interest in the project.  
    + Managers, funding sources
    + Customers (internal and external)
    + Engineers, sales, marketing, tech support
    + Contractors, vendors (hardware and software resources, infrastructure)
+ Roles
    + Software developer
    + Software tester
    + Customer representatives
    + Product owner (helps define the product, keep it on track)
    + Managers, executives, administration, accountants  

Some roles may overlap, depending on team size and organization.

#### 4. Project Start
To obtain a budget and approval at the start of a project, one usually creates
+ Set of features desired in the product.
+ Set of features required to achieve a minimum viable product (MVP).
+ List of milestones, or major changes in scope, needed to create features.  Milestones may or may not be ordered or prioritized.
+ Initial time and resource estimates.

Once basic resources are approved, you may have some leeway to allocate or rearrange them. 

#### 5. Resources, Schedule, Scope 
There are three main project variables to work with.
+ *Resources*: people, budget, software and hardware needed
+ *Schedule*: define time estimates, dependencies of different phases of project
+ *Scope*: what is included in each phase, and what is not

The variables generally form a *Triple Constraint.*   You can trade off project variables, which may affect product quality. 

<img src="https://github.com/bfetler/project_management/blob/master/images/iron-triangle1.png" alt="iron triangle" />

Examples of trade offs:
+ *If time estimates are too short:* 
    + Cut the scope, pushing some features to the next phase (keep on schedule).
    + Increase the schedule and add more time (let schedule slip).
+ *If schedule is cut:*
    + Cut the scope and do less work in fewer iterations.
    + Add resources and do the same amount of work in fewer iterations.  
+ *If resources are cut:*
    + Increase the schedule and add more iterations to get the same amount of work done.
    + Cut the scope, pushing some features to the next phase (keep on schedule).
+ *If scope is increased:*
    + Add more iterations to increase schedule and get increased work done.
    + Add more resources within same schedule to get increased work done.

Trade offs using the triple constraint are usually considered:
+ At the project start.
+ When creating or adjusting different phases or sprints.
+ Within a phase or sprint to meet a deadline.

#### 6. Work Items
Define what the team will do in each phase or iteration.
+ Brainstorm ideas (usually at start of phase).
+ Define user stories, what customers want. May be divided into individual interactions:
    + Customer A
    + looking for item B
    + visits web page W
    + has possible choices C1, C2, C3
    + has possible outcomes O1, O2, O3
    + assign initial priority to user story (high, low, 1-5)
+ Break into doable pieces, work items.  Level of detail depends what you need and experience of the team.
+ Define dependencies.  *Example:* 
    + Item A must be done before Items B and C.
    + Items B and C may be done in any order, and do not depend on each other.
+ Rearrange work items, schedules.
+ Prioritize items and user stories.  Some items are required, have fixed schedule and dependencies, others are flexible.
+ Get time estimates for each item.
    + Estimates are based on past history or metrics.
    + Don't forget time for writing and testing software, writing documentation.
    + Are time estimates accurate?  What is the error range?

Tools for defining work items, work flow:
+ whiteboard
+ post-its
+ project software (e.g. Pivotal Tracker, Microsoft Project)
+ rearrange user stories, priorities
+ feature tracking, bug tracking
+ design review
+ email, talk to each other (human communication)
+ software source code tools: git, branching (features, tests, production)
+ get metrics: measure time to complete items (depends on complexity)

Once work items are known:
+ Do high priority items first, the ones in scope for phase or project.
+ Move other items to a later phase.
+ Be flexible. Be aware that priorities and definitions will often change.

#### 7. Different ways to manage projects
How to manage a project depends on the organization.
+ Small companies, startups:
    + Agile, iterative.
    + Small flexible teams.  
    + Several iterations to achieve viable product.
    + *Example:* Scrum
        + Monthly sprints (working product at end of each sprint).
        + Product owner is known as scrum master.
        + Daily short standup meetings to resolve blocking issues.
        + Review feature backlog, burndown rate, priorities.  
+ Big companies, government:
    + Break into smaller, agile teams.
    + Need organization, e.g. scrum of scrums.
    + Teams communicate with each other depending on phases.
    + Be aware of chained dependencies between teams and projects.
    + Usually longer time frame. 

All methods of project management need the following common items.
+ product definitions
+ testing
+ customer feedback
+ issue tracking, metrics

#### 8. Tips for productive meetings
Not all the steps below are necessary for every meeting, but they can lead to better productivity.  
+ What type of meeting is it?  
    + Announcements, design review, status reports?
    + Group meeting, one-on-one?
+ Create a written agenda, distribute beforehand.  Clearly state goals. 
+ Only invite those needed, but make sure necessary stakeholders are represented.  Do not waste others time.
+ Is one person presenting, or each team member?
+ Give everyone a chance to speak and give input, if needed.
+ Do not interrupt people.  Do not let people dominate the meeting.  
+ If topic gets off track, ask people to discuss it separately after the meeting.
+ Set a time limit of one hour or less, unless it's extraordinary.  People get bored, tired, need a break if longer.
+ Are decisions expected, or just a discussion?
+ Create action items.  Assign responsibilities to them, if possible.
+ Write up meeting minutes.
+ Follow up email with decisions made.

Hopefully this will avoid repeat meetings on the same topic with no decisions made.

#### 9. Project end
+ Push to production.
+ Communicate with stakeholders.
+ Get revenue.
+ Gather and monitor feedback.
+ Track unreleased features (for next sprint or release), bugs, unresolved issues.
+ Add fixes or patches as needed.
+ Plan for product end-of-life if needed.
+ Review lessons learned, retrospective.


### Summary

+ Clearly define project goals.
+ Make sure you have sufficient resources and stakeholder support.
+ Define resources, schedule, scope.
+ Set work items, time estimates, dependencies.
+ Prioritize.
+ Use software tracking, feature and bug tracking.
+ Build your dream.

Not every step above needs to be followed for every project, but hopefully some of the ideas will help you keep projects on track and be productive.

These tools are here to help you.  They also help managers track and understand what's going on.  

If you like, take a class on Project Management (usually 8-10 weeks).  Practice with the projects you have.  You can even get certified as a PMP (Project Management Professional).

### Back to Original Question

Given all of these tools, how would you respond to a new feature request, or any other change?
+ Get organized.
+ Look at resources, schedule and scope.
+ Talk to others, get ideas, input.
+ Plan where the new change will fit in your current product.
+ Assign it a priority. 
    + If possible, add it to a later phase.  
    + If needed in current phase, consider the impact on scope, schedule and resources.
+ Give product owner options to help them decide.
+ Keep learning.

