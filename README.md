## Essentials of Project Management

### Why do you need project management?  

__Scenario:__  You're working away on a project, writing software, adding and fixing features for a great new product.  __*Then*__ someone on the team wants to add a new feature, but it doesn't quite mesh with the rest of the product, or may not fit in the current timeline.

__Q: What can you do?__
+ Get organized. 
+ Plan ahead. 
+ Prioritize.  

__A: Project Management__ 

Project management helps you organize, understand, anticipate and react to changes in a plan or product.  Even if it's not your primary job, it will be somebody's job in your organization. 
Project management tools can help you understand how they think, help them plan, and keep everything running smoothly.  

There are several styles of project management:
+ Agile (used in small, flexible teams)
+ Waterfall (used for larger organizations, e.g. government)
+ Other 

Regardless of which style of project management you use, there are several common features and tools.

### Essential Features of Project Management

##### 1. Definition
*Q:* What is a project?  
*A:* An activity with a definite, measurable goal within a specified time frame.  

Example Mission Statements
+ Put a man on the moon by the end of the decade.  (JFK)
+ Create a way to post your resume online and track who visited it by the end of the year, or until you get a job.  Maybe 30 people would like to use it.  (Rasmus Lerdof, PHP creator)
+ Create an online music service for your friends to share music before festival season starts.

##### 2. Project phases
+ Start: 
    + Define the project.  
    + Create mission statement.
    + Get backing of key stakeholders.  
    + Obtain budget and resources.  
+ Middle: 
    + Many steps to do on most projects.  There may be multiple iterations (e.g. see *Agile*).  
    + Ramp up resources, get stuff done.  
+ End: 
    + Product release!  
    + Wind down resources, or reallocate to other projects.  
    + Plan for maintenance, product support after release. 
    + End-of-life planning (product will be replaced by a new version).  

##### 3. Define stakeholders, roles  
+ Stakeholders are anyone who has an interest in the project.  
    + Managers, funding sources
    + Customers (internal and external)
    + Engineers, sales, marketing, tech support
    + Contractors, vendors (hardware and software resources, infrastructure)
+ Roles
    + Software developer
    + Software tester
    + Customer representatives
    + Product owner, scrum master (helps define the product, keep it on track)
    + Managers, executives, administration, accountants  

Some roles may overlap, depending how things are organized.

##### 4. Resources, Schedule, Scope 
There are three main project variables to work with.
+ *Resources*: people, budget, software and hardware needed
+ *Schedule*: define time estimates, dependencies of different phases of project
+ *Scope*: what is included in each phase, and what is not

Some of these are defined early in a project.  For example, create a basic outline needed to obtain budget, resources and approval.  Once basic resources are approved, you have some leeway to allocate or rearrange them. 

The *Iron Triangle* or *Triple Constraint.*   You can trade off project variables. 

<img src="https://github.com/bfetler/project_management/blob/master/images/iron-triangle1.png" alt="iron triangle" />

Examples:
+ *If schedule is cut:* Cut the scope and do less work in less time, or add resources and do the same amount of work.  
+ *If resources are cut:* Increase the schedule and add time to get the same amount of work done.
+ *If time estimates are too short:* 
    + Increase the schedule (let the schedule slip).
    + Cut the scope, pushing some features out to the next release.

##### 5. Work Breakdown Structure
Define what the team will do.  Outline the project phases needed to have a viable product.
+ Brainstorm ideas (usually at the start of project or phase).
+ Define user stories, what customers want. May be broken into individual interactions:
    + Customer A
    + looking for item B
    + visits web page W
    + has possible choices C1, C2, C3
    + has possible outcomes O1, O2, O3
    + assign initial priority to user story (high, low, 1-5)
+ Break into doable pieces, work items.  Level of detail depends what you need.
+ Define dependencies.  *Example:* 
    + Item A must be done before Items B and C.
    + Items B and C may be done in any order, and do not depend on each other.
+ Rearrange work items, schedules.
+ Prioritize items and user stories.  Some items are required, have fixed schedule and dependencies, others are flexible.
+ Set time estimates for each item.
    + Don't forget time for writing and testing software, writing documentation.
    + Are time estimates accurate?  What is the error range?

Tools for defining work items, work flow:
+ whiteboard
+ post-its
+ project software (e.g. Pivotal Tracker, Microsoft Project)
+ rearrange user stories, priorities
+ planning documents, design review
+ email, talk to each other (human communication)
+ feature tracking, bug tracking (e.g. Bugzilla)
+ software source code tools: git, branching
+ get metrics: how complex each item, how long to complete

Once definitions are set:
+ Set milestones, major changes in scope.
+ Do high priority items first, the ones in scope for phase or project.
+ Move other items to a later phase or release.
+ May need to find critical path (picture), find Minimum Viable Product (MVP).
+ Be aware any of these may change.

##### 6. Different ways to manage projects
How to manage a project depends on the organization.
+ Big companies, government, 1000's of workers.  
    + Break into smaller teams
    + Teams communicate with each other at different phases.
    + Need organization.
    + Usually longer time frame. 
    + *Example:* Waterfall, lots of chained dependencies.
+ Small companies, startups.
    + Agile, iterative.
    + Small flexible teams.  
    + Several iterations to achieve viable product.
    + *Example:* Scrum
        + Monthly sprints (working product at end of each sprint).
        + Daily short standup meetings to resolve blocking issues.
        + Review feature backlog, burndown rate, priorities.  

All methods of project management need the following common items.
+ product definitions
+ testing
+ customer feedback
+ issue tracking, metrics

##### 7. Tips for productive meetings
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

##### 8. Project end
+ Release to customers!
+ Communicate well to stakeholders.
+ Get revenue.
+ Gather and monitor feedback.
+ Track unreleased features (for next sprint or release), bugs, unresolved issues.
+ Add fixes or patches as needed.
+ Plan for product end-of-life if needed.
+ Review lessons learned, retrospective.


### Summary

+ Clearly define project goals.
+ Make sure you have the resources and stakeholder support to do it.
+ Define resources, schedule, scope.
+ Set work items, time estimates, dependencies.
+ Prioritize.
+ Use software tracking, feature and bug tracking.
+ Build your dream.

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
+ Give management options.  Let them decide.
+ Keep learning.

__Note:__ These are notes for a future talk.  I'll try to keep it under an hour.
