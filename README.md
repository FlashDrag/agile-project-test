# Project Management on GitHub using Agile Methodology

Agile methodology is a project management methodology that is used to manage software development projects. It is based on the iterative and incremental development of the project. It is a flexible methodology that allows the project to be adapted to the changes that may occur during the development of the project.


## Agile concepts
- ### Epics
An epic is a large body of work that can be broken down into a number of smaller stories,in our case “issues” in GitHub. Epics often encompass multiple teams, on multiple projects, and can even be tracked on multiple boards.
Epics are almost always delivered over a set of sprints. As a team learns more about an epic through development and customer feedback, user stories will be added and removed as necessary. That’s the key with agile epics: Scope is flexible, based on customer feedback and team cadence
#### Note:
`Epics` are not the same as `Milestones`. `Milestones` are used to group issues into sprints. `Milestones` collectively manage and track progress on groups of issues and prioritise them. `Milestones` are issues grouped by a deadline or delivery time. In an Agile workflow, the development team pulls from the backlog as opposed to a manager pushing work onto the developers. The goal is to keep the backlog as small and as organized as possible.
- ### Stories
A story is a description of a feature told from the perspective of the person who desires the new capability, usually a user or customer of the system. A story is a small unit of work that delivers some value to the customer.
A story can be also broken down to its essential bits using a set of ordered Tasks that will eventually give the completion of the story itself as their final product. In our team we refer to this process as “breaking down a story”.

The difference betweeen `Epics` and `Stories` is that `Epics` are the big picture of the project, while `Stories` are the smaller pieces of the project that are needed to complete the `Epics`. `Epics` are usually broken down into `Stories` and `Stories` are broken down into `Tasks`. `Epics` are usually delivered over a set of `Sprints`. As a team learns more about an `Epic` through development and customer feedback, `Stories` will be added and removed as necessary. That’s the key with agile `Epics`: Scope is flexible, based on customer feedback and team cadence. Keep in mind, If you can break a user story further into multiple stories, then it should be considered as an epic and not a user story.
- ### Tasks
A task is a small unit of work that can be completed in a short period of time. A task is a concrete step that needs to be done to complete a story. A task is a small unit of work that delivers some value to the customer.
- ### Sprints
A sprint is a set period of time during which specific work needs to be completed. Sprints are usually two weeks long, but can be longer or shorter depending on the team’s needs. Sprints are used to break down work into smaller, more manageable chunks. The outcome of a Sprint is usually a working piece of software that will be added to the main “trunk” of the project. We can think of it like an single entry in a release changelog. You will probably set a milestone that will eventually represent a new release to be published, and that milestone will be made of several sprints that will add feature over feature to your final product.
- ### Backlog
The product backlog is a centralized and prioritized list, and the authoritative source that drives the Development Team’s work. The product backlog is the single source of requirements for any changes to be made to the product. The product backlog is never complete. As new features are identified, they are added to the product backlog. As the product is released, the product backlog is constantly updated to reflect changes in the product and changes in the market.

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
Timeboxing means allocating a fixed perid, called a timebox, whitin which planned work or activities occur based on the assigned priority. Once the duration is over, the work that has not been completed is rescheduled, prioritised and moved to the next sprint (timebox). So  the timebox never exetended to accomodate the work initially planned for completion that timebox. An iteration is a timebox. The iteration duration is fixed and user stories that are not completed within a particular iteration are returned to the backlog for reprioritisation and rescheduling. If the team is not able to complete the work within the iteration, they should not extend the iteration time to complete the remaining user stories, nor compromise quality by trying to squeeze the remaining work into the current iteration. Whatever user stories remains should be returned  to the product backlog for refinement.

The timeboxing benefits:
- It enables moving from plan-driven to value-driven development.
- Defining and limiting the  amount of time dedicated to an activity
encourages the team to get work done  immediately and avoid any non value-add effort,
such as unnecessary documentation.
Timeboxing helps the Agile team  stay focused on the time box’s goal and
not get distracted, as they are aware  that the timebox can not be extended.


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
    - Add the due date of the sprint
2. Add the issues to the sprint:
    - Add the issues to the sprint by dragging them from the Scrum board to the sprint milestone. This will automatically add the issues to the sprint milestone.
    - Add the issues to the sprint by adding them to the sprint milestone.

- ### Projects
After adding our epics, stories and tasks we can go to our boards and check that they have been added. In this way, at the beginning of Scrum, we can add all our epics and user stories to our project backlog.
Projects are used to group issues into a project board. Projects are used to track progress on groups of issues and prioritise them. Projects are issues grouped by a project board.

#### CREATE SCRUM BOARD AND TASK BOARD::
1. Create a project board:
    - Add the title of the project board
    - Add the description of the project board
    - Add the columns of the project board
2. Add the issues to the project board

- ### Issues and Labels
Issues are the main element of GitHub. They can be used to track bugs, enhancements, tasks, or even user stories. Issues can be created by anyone (for public repositories), and are moderated by repository collaborators. Each issue contains its own discussion forum, can be assigned to a user, and can be labeled and milestoned.

Labels are used to categorize issues, pull requests, milestones, and projects. Labels can be applied to one issue at a time, and can be used to organize and search issues. Labels can be created at the repository or organization level, and can be shared across repositories.

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
