# Project Management on GitHub using Agile Methodology

Agile methodology is a project management methodology that is used to manage software development projects. It is based on the iterative and incremental development of the project. It is a flexible methodology that allows the project to be adapted to the changes that may occur during the development of the project. In Agile, Quality and Time are fixed, but flexibility should be allowed with the Scope.

## Agile Manifesto
- ##### Individuals and interactions over processes and tools
- ##### Working software over comprehensive documentation
(however, documentation should be developed whenever needed.)
- ##### Customer collaboration over contract negotiation
- ##### Responding to change over following a plan

## Agile Principles
Agile methodology is based on the following software development principles:
- Satisfy The Customer \
Customer satisfaction by early and continuous delivery of valuable software.
- Welcome changing requirements, even in late development.\
Our goal is to deliver a solution that creates real value for the customer. We value responding to changes over following the plan, Agile processes harness change for the customer's competitive advantage.
- Deliver working software frequently (weeks rather than months).\
Shorter timescale perferred. Most Agile teams use 2-4 cycles or iterations.
- Close, daily cooperation between business people and developers.
- Projects are built around motivated individuals, who should be trusted.
- Face-to-face conversation is the best form of communication (co-location).
- Working software is the primary measure of progress.
- Sustainable development, able to maintain a constant pace.
- Continuous attention to technical excellence and good design.\
We should never compromise quality to meet project deadlines.
- Simplicity—the art of maximizing the amount of work not done—is essential.\
We should strive to create the simplest software solution (that meets the users’ expectations) that helps facilitate the outcomes expected for the solution. We should not over-engineer or stuff it with features that end up unused. We should not  opt for an easy solution now instead of a better approach that would take longer or what is usually  referred to as “Technical Debt”, as it will result in costly rework later and it defeats the  purpose of creating value for users and customers.
- Best architectures, requirements, and designs emerge from self-organizing teams.
- Regularly, the team reflects on how to become more effective, and adjusts accordingly.


## Agile concepts
- ### Epics
An epic is a large body of work that can be broken down into a number of smaller stories,in our case `issues` in GitHub. Epics often encompass multiple teams, on multiple projects, and can even be tracked on multiple boards.
Epics are almost always delivered over a set of sprints. As a team learns more about an epic through development and customer feedback, user stories will be added and removed as necessary. That’s the key with agile epics: Scope is flexible, based on customer feedback and team cadence
#### Note:
`Epics` are not the same as `Milestones`. `Milestones` are used to group issues into sprints. `Milestones` collectively manage and track progress on groups of issues and prioritise them. `Milestones` are issues grouped by a deadline or delivery time. In an Agile workflow, the development team pulls from the backlog as opposed to a manager pushing work onto the developers. The goal is to keep the backlog as small and as organized as possible.
- ### Stories
A story is a description of a feature told from the perspective of the person who desires the new capability, usually a user or customer of the system. A story is a small unit of work that delivers some value to the customer.
A story can be also broken down to its essential bits using a set of ordered Tasks that will eventually give the completion of the story itself as their final product. In our team we refer to this process as "breaking down a story".

The difference betweeen `Epics` and `Stories` is that `Epics` are the big picture of the project, while `Stories` are the smaller pieces of the project that are needed to complete the `Epics`. `Epics` are usually broken down into `Stories` and `Stories` are broken down into `Tasks`. `Epics` are usually delivered over a set of `Sprints`. As a team learns more about an `Epic` through development and customer feedback, `Stories` will be added and removed as necessary. That’s the key with agile `Epics`: Scope is flexible, based on customer feedback and team cadence. Keep in mind, If you can break a user story further into multiple stories, then it should be considered as an epic and not a user story.

#### Story points and Velocity
_Story points_ are used to estimate the effort required to complete a user story. The effort is measured in story points, which are an abstract measure of effort.

_Velocity_ is the number of story points that a team can complete in a sprint. Velocity is a measure of the team’s ability to deliver work. It is calculated by adding up the story points of all the completed stories in a sprint. Velocity is used to estimate how long it will take to complete a project. The higher the velocity, the faster the team can complete the project. The lower the velocity, the longer the project will take to complete.

- ### Tasks
A task is a small unit of work that can be completed in a short period of time. A task is a concrete step that needs to be done to complete a story. A task is a small unit of work that delivers some value to the customer.
- ### Sprints/Iterations
A sprint is a set period of time during which specific work needs to be completed. Sprints are usually two weeks long, but can be longer or shorter depending on the team’s needs. Sprints are used to break down work into smaller, more manageable chunks. The outcome of a Sprint is usually a working piece of software that will be added to the main "trunk" of the project. We can think of it like an single entry in a release changelog. You will probably set a milestone that will eventually represent a new release to be published, and that milestone will be made of several sprints that will add feature over feature to your final product.
#### Sprint and story points
The team should estimate the effort required to complete each story in the sprint. User stories can be priorirised using MoSCoW, and then each story can be estimated using Fibonacci sequence (1, 2, 3, 5, 8, 13, 20, 40, 100). The total number of story points is the sprint capacity. Based on the sprint capacity, the team can decide how many stories they can complete in the sprint.

- ### Backlog
The product backlog is a centralized and prioritized list of PBIs(Product Backlog Items), and the authoritative source that drives the Development Team’s work. The product backlog is the single source of requirements for any changes to be made to the product. The product backlog is never complete. As new features are identified, they are added to the product backlog. As the product is released, the product backlog is constantly updated to reflect changes in the product and changes in the market.

The Product Owner is responsible for the product backlog and the team is responsible for delivering the value to the customer.
The Product Owner should capture request that contributes to the value delivered to the customer. Thus the product owner should verify requests before adding them to the backlog. The product owner should also prioritize the backlog based on the value delivered to the customer. The backlog should be short enough to be completed in a sprint. The backlog should also be short enough to be completed in a reasonable amount of time.

The Product Backlog is a dynamic document to respond to changes effectively. We add PBIs, remove them, break them down and re-prioritized them based on previous cycles’ feedback. Thus, the Backlog Refinement process is a repeated process throughout the lifecycle of the project. The purpose of the Product Backlog refinement process is to ensure that there is enough development-ready PBIs and orders in alignment with business priorities. Assigning tasks is not part of this.

Product Backlog Items are mainly Epics, Defects and User Stories. Tasks are part of user stories. Recording a BPI on the backlog is not a guarantee that it’ll be delivered. It is an option that the Agile team might consider in delivering value to the customer rather than a commitment.
    - #### Sprint Backlog
    Essentially, the backlog is a collection of stories that have to be finished and tested before the end of the Sprint. At the beginning of each Sprint the team will decide which stories have to be pulled out from the Global Backlog. Moreover, the stories that belongs to a Sprint should be ordered by their priority and tagged with a number of points, representing the complexity of the story itself.
    - #### Global Backlog
    The global backlog is a prioritised list of stories that has not been scheduled to be completed. As new work comes in, it gets added to the global backlog and it possibly gets an assigned priority and maybe a label. In an Agile workflow, the development team pulls from the backlog as opposed to a manager pushing work onto the developers. The goal is to keep the backlog as small and as organized as possible.

#### Issues order in the backlog
The order should be based on business priorities. We should keep the high priority defects/bugs and user stories (ready for development) at the top, while epics should be placed at the bottom as they require decomposing into user stories. Usually, bugs have the highest priority, as they are the most critical issues that need to be fixed as soon as possible. The next priority is the user stories, which are the most important features that need to be developed. The last priority is the epics, which are the most important features that need to be developed, but they are not ready for development yet. They need to be broken down into user stories first.
- ##### High priority
On the top of the priority list, PBIs are mainly in the form of user stories and defects that are ready for development.
- ##### Medium priority
At a medium level of priority come the PBIs that are well understood but yet to be discussed with the development team detailed further such as brief User Stories.
- ##### Low priority
At the bottom of the priority list are the epics that need further discussion to be better understood and broken down.

- ### Timeboxing
Timeboxing means allocating a fixed perid, called a timebox, whitin which planned work or activities occur based on the assigned priority. Once the duration is over, the work that has not been completed is rescheduled, prioritised and moved to the next sprint (timebox). So, the timebox never exetended to accomodate the work initially planned for completion that timebox. An iteration is a timebox. The iteration duration is fixed and user stories that are not completed within a particular iteration are returned to the backlog for reprioritisation and rescheduling. If the team is not able to complete the work within the iteration, they should not extend the iteration time to complete the remaining user stories, nor compromise quality by trying to squeeze the remaining work into the current iteration. Whatever user stories remains should be returned  to the product backlog for refinement.
The timebox duration is not estimated based on the effort required to complete the work. But instead, based on a point in time where we want to stop and reflect.

#### The timeboxing benefits:
- It enables moving from plan-driven to value-driven development.
- Defining and limiting the  amount of time dedicated to an activity
encourages the team to get work done  immediately and avoid any non value-add effort,
such as unnecessary documentation.
Timeboxing helps the Agile team  stay focused on the time box’s goal and
not get distracted, as they are aware  that the timebox can not be extended.

- ### MoSCoW prioritization
MoSCoW prioritization is a prioritization technique that helps to prioritize the product backlog items.
MoSCoW prioritization is a representation of a User Story Criticality compared to other User Stories under consideration, this could be on the project as a whole or for a particular iteration.

It is a way to prioritize the product backlog items based on the following criteria:
- #### Must have
Guaranteed to be delivered in the current sprint. These are the most important features that need to be developed. `Must-Have` PBIs are non-negotiable and are guaranteed to be delivered within the iteration or project. There is no point in releasing the  solution on the end date without these items as they are necessary for it to work. Core functionality, as well as legal, safety and security related PBIs, are usually prioritised under `Must Have`.

- #### Should have
If there is some workaround  to achieve the goal of PBI, even if it is manual and painful, then we should  consider it as `Should Have` or `Could Have`. Categorising a PBI as a Should Have or Could  Have does not mean it won’t be delivered. Simply delivery is not guaranteed  within the current iteration.
These are the features that are important and add significant value to the product but not critical to the success of the product or vital. They should be delivered in the current sprint if possible, but if not, they can be delivered in the next sprint. The product still functions; however, a `should have` adds significant value if they are included. Performance improvements, minor defects fixes, or new functionality are a `Should Have` as without them, the product still works.

- #### Could have
`Could have` items are desirable but less crucial than `should have` items. Have small impact if left out of the current sprint. `Could-Haves` are not core to the product or solution. Compared with `Should-have`, they have a much smaller impact on the outcome if left out. Thus, `Could-Have` items provide the main pool of contingency since they would only be delivered in their entirety in a best-case scenario. When a problem occurs and the deadline is at risk, one or more `could-have` items are dropped.

- #### Won’t have
'Won't have` means that the Agile team has agreed that the PBI wouldn't be delivered.
- On the iteration level, it means that it won't be included in the current iteration, but it might be included later in  the project but in another iteration.
- At the project level, it means these PBIs won't make it to the deployed solution. We still record the `Won't have' PBIs  as they help clarify the project's scope and manage expectations. Some items will simply not make it into the deployed solution.

Documenting the `Won't have` PBIs helps to clarify the project's scope and manage expectations. Some items will simply not make it into the next iteration, release or final deployed solution.

#### Note:
It is not recommended that the percentage of `Must-Have` items exceeds 60% of the overall effort planned for the iteration. The percentage can be estimated based on the **story points** assigned to each PBI. For example, if the team has a capacity of 10 story points per iteration, then the maximum number of `Must-Have` items should be 6 (60% of 10)

Then, a reasonable contingency level - typically  around 20% should be `Could Have` effort. Creating a sensible pool of `Could-Haves` sets the correct expectations for the customer or product owner that these items may be delivered in their  entirety in a best-case scenario.
##### For example,
the Product owner proposed to have 5 PBIs/user stories (A, B, C, D, E) in the current iteration backlog. Team Capacity is 10 User Story Points per iteration. As the current team capacity is ten story points per iteration, a maximum of 6 story points could be `Must Have`, and at least 2 Story Points should be `Could-have`, what's remaining are by default `Should-Have`. Based on our prioritised list, `A` & `B` might be assigned a `Must Have`, `C` is a `should have`, and `D` is a `Could have`, while `E` is a `won't have` in this iteration.

Also each PBI/user story is assigned a story point value, for example, `A` is 3 story points, `B` is 2 story points, `C` is 1 story point, `D` is 2 story points, and `E` is 2 story points.

Now the development team has a prioritised list for PBIs to be completed within the iteration and can proceed with development. That prioritisation is relative to the remaining PBIs in the backlog. A PBI might be prioritised as `Won't have` in `iteration 1`, but later as `Must Have` in iteration two, if for example, it must be included in the release after `iteration 2`. Priority is always relative to the remaining PBIs.

- ### Information radiators
Information radiators are used to display the progress of a project, such as remaining user stories, current team velocity, user stories' status in the current sprint, the progress towards the next release, the count of open defects and so on. Information radiators usually show critical agile team information that reflects the work status and help the team better achieve their goal. Information radiators are real-time, updated, straightforward and understandable at a glance. Any team member can update the information presented on the Information Radiators. Information radiators usually show critical agile team information that reflects the work status and help the team better achieve their goal. The number of hours worked per team member is not critical information and should not be displayed on the information radiators.
Information radiators form can be:
- Boards(Planning Boards, Kanban boards, Team Board, etc.)
- Burndown charts
- Traffic lights
- Impediment Lists

#### Boards
Boards are commonly used information radiators in the Agile community.
The primary purpose of a board is to summarise team progress and the current status of the work progress for a particular iteration. In its simplest form, it comes with three primary columns `To Do`, `In Progress`, and `Done`. Usually, towards the end of a particular iteration, the Agile team starts planning for the next iteration, by agreeing on user stories to be included in the future iteration and their respective priorities.

#### Burndown Charts
The Burndown chart`s primary purpose is to show how quickly the development team burns through the user stories. The burndown chart shows the total effort remaining against the remaining time till the end of the iteration.

## GitHub tools
- ### Scrum board and Task board
The scrum board is a tool used to track the progress of a project. It is used to display the work that needs to be done, the work that is currently being done, and the work that has been completed.
- ### Milestones
Millstones are used to group issues into sprints. Milestones collectively manage and track progress on groups of issues and prioritase them. Milestones are issues grouped by a deadline or delivery time.
    - The issues can be the functionalities to be carried out for the next version and can be grouped in a milestone with the number of the next version and the release date.
    - In another structure, the issues can be user stories and tasks and can be grouped in a milestone with the current sprint and with the end date.
#### CREATE SPRINTS:
1. Create a milestone:
    - Add the title of the sprint
    - Add the description of the sprint
    - Add the due date of the sprint (standard iteration timebox is 2 weeks)
2. Assign the issues/userstories/PBIs to the sprint/timebox:
    - select the issues
    - click on the milestone button
    - select the milestone

- ### GitHub Project Boards
GitHub `Projects` are used to group issues into a **project board**, track progress on groups of issues and prioritise them. We can create project boards for specific feature work, comprehensive roadmaps, or even software release checklists.

#### CREATE Kanban Board with GitHub:
1. Create a project board:
    - Add the title of the project board
    - Add the description of the project board
    - Add the columns of the project board
        - Global Backlog
        Includes all the user stories and tasks that are not yet assigned to a sprint.
        - Sprint Backlog/To Do
        Includes all the user stories and tasks that are assigned to the current sprint/milestone.
        The user stories and tasks are prioritised in the sprint backlog based on the MoSCoW method.
        The user stories that are not realised in the current sprint are moved to the global backlog.
        - In Progress
        Includes all the user stories and tasks that are currently being worked on.
        - Done
        Includes all the user stories and tasks that have been completed.
2. Link the project board to the repository
3. Add the issues/PBIs to the project board
Place them in order of effort, based on the story points assigned to each issue in descending order.

- ### Issues and Labels
Issues are the main element of GitHub. They can be used to track bugs, enhancements, tasks, or even user stories. Issues can be created by anyone (for public repositories), and are moderated by repository collaborators. Each issue contains its own discussion forum, can be assigned to a user, and can be labeled and milestoned.

Labels are used to categorize issues, pull requests, milestones, and projects. Labels can be applied to one issue at a time, and can be used to organize and search issues. Labels can be created at the repository or organization level, and can be shared across repositories.

#### MoSCoW labels
MoSCoW labels are used to categorize issues, pull requests, milestones, and projects. Labels can be applied to one issue at a time, and can be used to organize and search issues.
- ##### Create labels for issues.
Must have, Should have, Could have, Won't have (optional)
- ##### Assign the labels to the issues.
If the issues are added to a `iteration`/`milestone`/`spint`/`timebox` - go to the `milestone`, select checkboxes of the issues and click on the `label` button and select the label. Make sure that you use a correctly balanced distribution of the labels, 60% `Must Have`, 20% `Could Have` and 20% `Should Have`.

#### CREATE EPICS, STORIES AND TASKS:
1. Create templates for issues:
Epic, Story, Task
2. Create labels for issues:
EPIC, STORY, TASK
3. Create a project boards:
Scrum board, Task board
4. Create a new issue:
    - For an epic we only need to put the title and description, we do not need to add an assignee or add them to a project.
    - For a story we need to add the title, link to the epic to which it belongs, add the description, acceptance criteria and tasks, assign the person in charge of following up on this user story and add it to the Scrum board.
    - For a task we need to add the title, link to the story to which it belongs, add the description, assign the person in charge of carrying out this task and add it to the task board.


## Credits:
- [CodeInstitute](https://codeinstitute.net/)
- https://www.topcoder.com/thrive/articles/project-management-on-github
- https://torre.me.uk/2019/03/28/using-github-as-project-management-platform/
