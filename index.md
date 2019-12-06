# Development Procedure

# Product Backlog Item Generation
Product Backlog Items are represented by Github Issues with the “Needs Project” label, or other labels and identification methods as agreed to by the Scrum Team.

The Product Owner maintains this list and maintains an understanding of the priority of the Issues with a method of their choosing. They or their delegate refine the contents of the Issues, such that important, valuable, and time-sensitive Issues are selected first for upcoming Sprints and are appropriately detailed in a way that the Scrum Team finds useful.

Product Backlog Item generation and refinement is an on-going process that is independent of the development process described below.

# Development Sprint Process
Sprints are executed sequentially, and immediately following the last Sprint, unless other scheduling or strategic needs dictate otherwise. Sprints are comprised of four meetings, and the flow of a Sprint follows this pattern whether the work done is successful or not.

Sprints are timeboxed, with an acceptable range between one and four weeks. The duration of the Sprint defaults to two weeks, but may be adjusted during the Sprint Planning meeting if necessary.

During the Sprint, all Sprint Backlog Items will be completed, documented as necessary, and validated by Quality Assurance testing. Quality Assurance validation and backend work (database, architecture, etc) are not a separate phases or secondary concerns; rather, they must be accounted for when planning the Sprint.

The output of a Sprint is a complete and releasable iteration of the product. If any Sprint Backlog Items remain incomplete by the end of the Sprint, they are put back into the Product Backlog and may be addressed in future Sprints.


## Conduct Sprint Planning meeting
1. The Lead Developer or their delegate makes a new Github Project for the Sprint named "Sprint #" with the Sprint number in the appropriate repository
2. The Development Team moves Issues into the Sprint Project in the "To Do" column as a result of/during the Sprint Planning meeting. These Issues will make up the Sprint Backlog

## Work through Sprint Backlog
1. The Lead Developer or their delegate creates a new next_release branch or merges master into an next_release branch. All new work for the Sprint is done in this next_release branch
2. The Development Team assigns Sprint Issues to Developers. The Development Team self-organizes and self-determines who gets what issues to work on. Issues may be unassigned and/or reassigned at any time at their discretion
3. The Development Team conducts Daily Scrum meetings
4. The Developers move Issues through the Github Project columns
   1. Move Issues to the "Doing" column when started
   2. Move Issues to the "Done" column when complete
   3. Assign "Done" Issues to QA or impartial Developers for validation. Validation at this stage is a unit test to ensure that the changes made perform as expected by redressing the original Issue and determining if the problem has been solved or feature has been added as described
   4. Move validated issues to the "Validated" column

## Finish out the Sprint	
1. The Scrum Team conducts a Sprint Review meeting
2. The Lead Developer or their delegate merges the next_release branch into the current_version branch
3. The Scrum Team conducts a Sprint Retrospective meeting

# Determine if a release is necessary
1. The Director of Development or their delegate assign a version number to the proposed release using the Semantic Versioning format as described by semver.org, as appropriate to the situation
2. The Lead Developer or their delegate build a Release Candidate in Github from the current_version branch
3. Quality Assurance and the Developers conduct release validation. Release Validation may be tracked either as Issues in the next Sprint, or parallel to the  Sprint depending on resources and strategy
   1. The Director of Development or their delegate creates or reuses Release Validation procedures for representative client types, which include but are not limited to: ENT, BCA, and Baker
   2. The Lead Developer or their delegate procures or updates a database for each client type and makes them available for use
   3. The Lead Developer or their delegate conducts relevant migrations on each database
   4. Quality Assurance conducts validation on each database based on Release Validation procedures. They may assign validation tasks or procedures to Development Team members as needed
4. Director of Development or their delegate signs off on validation stating that all Release Validation procedures were completed satisfactorily and that the release is stable
5. The Lead Developer or their delegate merges the current_version into master branch
6. The Director of Development or their delegate notifies clients and internal employees of the release

# Roles

## Organizational Roles

### Developer
Developers perform work on projects, which may include coding, database work, design and UI work, and data manipulation. For the purposes of this process, no distinction in title is made between these different specialties.

### Lead Developer
The Lead Developer is in charge of the operations of the development team. They or their delegate assign tasks, monitor task progress, dictate and enforce code standards, and report to the Director of Development.

### Quality Assurance
Quality Assurance assures that work completed by the development team is functional and performs as desired. They do this by testing the code and its frontend either manually, or with automated testing scripts.

Quality Assurance may delegate or request delegation of validation tasks to Developers if needed.

### Director of Development
The Director of Development oversees the strategic operation of the development team. They draft new standards, research emerging technologies, and ensure order. The Director of Development or their delegate signs off on release validation once it is complete if the validation status is satisfactory and stable.

## Scrum Roles
Scrum only specifies and makes use of three roles: Development Team, Product Owner, and Scrum Master. These three roles together are collectively referred to as the Scrum Team. 

### Development Team
The Development Team is comprised of any individual that will contribute work to the Sprint. This includes not only development, but quality assurance, documentation, consultants, backend engineering, database architecture, and so on. The roster of the Development Team is based entirely on the content and needs of the Sprint.

To that end, the Development Team is self-organizing. Only the Development Team determines what work and in what quantities it can do, what members it has, and how work is distributed to its members. 

Throughout this document, "Development Team" refers to this specific role within Scrum, while "development team" refers to the organizational grouping of Developers, Lead Developer, Director of Development, and Quality Assurance.

### Product Owner
The Product Owner controls the Product Backlog, and therefore the product direction and strategy. Their goal is to maximize value for the product by ordering the Product Backlog Items by value, either to Xtract Solutions or to our clients. They may delegate the task of ordering and refining the Product Backlog to the Development Team, but the Product Owner remains responsible for its contents and orderly execution. 

The Product Owner or their delegate often interfaces with clients directly, producing new Product Backlog items based on their feedback and projected desires.

### Scrum Master
The Scrum Master oversees the execution, adherence, and efficiency of the Scrum process. They are the source of truth for Scrum, as well as an impartial mediator when problems need to be resolved that stand in the way of work within the Scrum process.

The Scrum Master officiates or attends Scrum meetings to ensure that they remain within their timebox, and are both positive and productive.

# Supporting Tools, Processes, and Services

## Github

### Issues
TBD
	
### Projects
TBD

### Repositories
TBD

### Labels
TBD

### Releases
TBD

### Wiki
TBD

## Slack
TBD

## Gmail
TBD

## Scrum

### Overview
TBD

### Roles
TBD

### Meetings
Sprint Planning
TBD

Daily Scrum
TBD

Sprint Review
TBD

Sprint Retrospective
TBD
