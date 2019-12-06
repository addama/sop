# Development Standard Operating Procedure

# 1. Process Overview

# Software development at Xtract Solutions follows the Agile Scrum framework, using Github as the source code repository. Software code is incrementally changed over short cycles of development, called Sprints, which are periodically bundled into a Release. Sprints contain one or more Product Backlog Items which represent individual features or fixes. Releases represent a set of features and fixes that will be delivered to clients. All code changes are made using Git (the protocol) and Github (the repository hosting service utilizing the protocol) to ensure revision history is maintained. 

# 1.1. Agile Methodology

# Agile is a methodology, an abstract mindset, that specifically emphasizes continuous improvement, collaboration, and efficiency in software development. This can be actualized, practically, by valuing worker skills and well-being over deadlines, shorter more manageable release cycles, and providing avenues for change rather than remaining rigid.

# 1.2. Scrum Framework

# While Agile is an abstract description of how things should be done, Scrum is a concrete implementation of those values into an actionable process. 

# Scrum relies on steady and frequent iteration, in the form of Sprints, to progressively add new features and fixes to a product. Sprints last between one and four weeks, and always end with a stable and releasable version of the product.

# Scrum has three roles and four meetings. Nothing else we do is considered Scrum if it is not those three roles and four meetings. Scrum meetings are timeboxed, which mean that they must occur, but must not exceed a pre-calculated amount of time. If more needs to be discussed after this timebox ends, the individual members may reconvene on their own to continue.

# 1.2.1. Product and Sprint Backlog

# The Product Backlog is a permanent list of needed or wanted features and fixes, prioritized by the Product Owner or their designee, contributed to by clients as well as Xtract Solutions employees. These items are then selected by the Development Team to build the Sprint Backlog. When these Sprint Backlog Items have been satisfactorily completed, they are removed from the Product Backlog. This process continues until there are no more Product Backlog Items, or the product is otherwise exhausted or terminated.

# 1.3. Git and Github

# Git is an industry-standard protocol for interacting with distributed (or hosted) repositories of well-maintained data. Central to Git is the idea of commits, which represent a change or set of changes to the structure or content of the data inside any given repository. These commits are tracked sequentially and record the author, the date and time the changes were made, and what was changed.

# Github is a hosting service provider that hosts Git repositories on a centrally located server that is accessible from the internet. This enables multiple people to work on, download, and view repositories with a centrally located source of truth rather than a distributed "web of truth" that must be viewed as a whole to understand all of the changes and status of a system.

# 1.3.1. Use of Github

# 1.3.1.1. Issues

# 1.3.1.2. Projects

# 1.3.1.3. Labels

# 1.3.1.4. Releases

# Releases are stable snapshots of the software, and its peripherals as required, that may include new functionality, bug fixes, and other changes deemed necessary by Xtract Solutions. 

# Releases are represented by a Release Number, which logically encodes the amount and intensity of the changes made since the last release. Release numbering follows the SemVer 2.0.0 numbering scheme as is applicable and strategically relevant.

# 1.3.1.4.1. Semantic Versioning Number

# As described on the SemVer website, version numbers follow this pattern:

# Given a version number MAJOR.MINOR.PATCH, increment the:

# * MAJOR version when you make incompatible API changes,
# * MINOR version when you add functionality in a backwards compatible manner, and
# * PATCH version when you make backwards compatible bug fixes.

# 2. Roles

# Roles can be expressed as coming from two separate hierarchies: those roles mandated by Scrum, and those mandated by business needs. These roles necessarily overlap, but represent distinct responsibilities to both Scrum and the general operation of the business. 

# 2.1. Scrum Roles

# Scrum mandates three roles: Development Team, Product Owner, and Scrum Master. These are the only roles with responsibilities within the Scrum process, and supercede organizational roles within it.

# 2.1.1. Development Team

# The Development Team is comprised of any individual that will contribute work to the Sprint. This includes not only developers, but quality assurance, documentation, consultants, backend engineers, database engineers, and so on. The roster of the Development Team is based entirely on the content and needs of the Sprint.

# To that end, the Development Team is self-organizing. Only the Development Team determines what work and in what quantities it can do, what members it has, and how work is distributed to its members. 

# Throughout this document, "Development Team" refers to this specific role within Scrum, while "development team" refers to the organizational grouping of Developers, Lead Developer, Director of Development, and Quality Assurance.

# 2.1.2. Product Owner

# The Product Owner controls the Product Backlog, and therefore the product. Their goal is to maximize value for the product by ordering the Product Backlog Items by value, either to Xtract Solutions or to our clients. They may delegate the task of ordering and refining the Product Backlog to the Development Team, but the Product Owner remains responsible for its contents and orderly execution. 

# The Product Owner or their designee often interfaces with clients directly, producing new Product Backlog items based on their feedback and projected desires.

# 2.1.3 Scrum Master

# The Scrum Master oversees the execution, adherence, and efficiency of the Scrum process. They are the source of truth for Scrum, as well as the orchestrator when problems need to be resolved that are standing in the way of work within the Scrum process.

# The Scrum Master officiates or attends Scrum meetings to ensure that they remain within their timebox, and are both positive and productive.

# 2.2. Organizational Roles
# 2.2.1. Lead Developer

# The Lead Developer is in charge of the operations of the development team. They or their designee assign tasks, monitor task progress, dictate and enforce code standards, and report to the Director of Development.

# 2.2.2. Director of Development

# The Director of Development oversees the strategic operation of the development team. They draft new standards, research emerging technologies, and ensure order. The Director of Development or their designee signs off on release validation once it is complete if the validation status is satisfactory for a release.

# 2.2.3. Developer

# Developers perform work on projects, which may include coding, database work, design and UI work, and data manipulation. 

# 2.2.4. Quality Assurance

# Quality Assurance (QA) assures that work completed by the development team is functional and performs as desired. They do this by testing the code and its frontend either manually, or with automated testing scripts.

# 3. Tools and Locations
# 3.1. Github
# 3.1.1. Github Issues
# 3.1.2. Github Wiki
# 3.2. Git
# 3.3. Xtract Solutions Documentation Site

# 4. Development Process
# 4.1. Requirements Generation and Refinement

# Requirements (user stories, issues, bug fixes, etc) can originate from anywhere inside the organization, or come from client feedback and request. No matter the origin, the Product Owner or their designee maintains these requirements as Product Backlog Items, and ensures their quality. 

# Requirements are entered and stored into Github in a relevant repository, which allows historical tracking of changes, as well as directly integrating with the development team's coding process. 

# The Product Owner or their designee endeavors to refine the Product Backlog Items as necessary to ensure they have the specificity and granularity required to express the work needed and the desired functionality. The Product Owner may delegate this process of refinement to the Development Team, but the Product Owner remains the controlling role for the Product Backlog's quality and ordering.

# This is an on-going process that happens independently of the development process described herein.

# 4.2. Sprint Execution 

# Sprints are executed sequentially, and immediately following the last Sprint, unless other scheduling or strategic needs dictate otherwise. Sprints are comprised of four meetings, and the flow of a Sprint follows this pattern whether the work done is successful or not.

# Sprints are timeboxed, with an acceptable range between one and four weeks. The duration of the Sprint defaults to two weeks, but may be adjusted during the Sprint Planning meeting if necessary.

# During the Sprint, all Sprint Backlog Items will be completed, documented as necessary, and validated by Quality Assurance testing. Quality Assurance validation and backend work (database, architecture, etc) are not a separate phases or secondary concerns; rather, they must be accounted for when planning the Sprint.

# The output of a Sprint is a complete and releasable iteration of the product. If any Sprint Backlog Items remain incomplete by the end of the Sprint, they are put back into the Product Backlog and may be addressed in future Sprints.

# 4.2.1. Sprint Structure

# 4.2.1.1. Sprint Planning Meeting

# The Sprint begins with the Sprint Planning meeting. The Sprint Planning meeting is a Scrum meeting, and is timeboxed to at most two hours per week that the Sprint will run.

# During the Sprint Planning meeting, the Development Team and Product Owner negotiate what Product Backlog Items will be completed in the upcoming Sprint. The Development Team seeks to select enough items to have a full but not hectic amount of work during the Sprint, and the Product Owner seeks to maximize the value of the final product by prioritizing the Product Backlog Items and suggesting higher-value alternatives to work being selected if any exist.

# During the Sprint Planning meeting, the Development Team and Product Owner endeavor to refine the Product Backlog Items into the specificity and granularity that they deem necessary to perform the work 

# When the Sprint Planning meeting is complete, the Sprint has officially begun. The work selected is compiled into a Sprint Backlog, which is worked down over the course of the Sprint.

# 4.2.1.2. Daily Scrum Meeting

# The Daily Scrum is a Scrum meeting that is timeboxed to 15 minutes. As its name suggests, it is a daily meeting held by and for the Development Team to discuss their internal work, process, concerns, etc. The Development Team may invite anyone else they may need to talk to at their discretion. The Scrum Master may sit in on the Daily Scrum to ensure that it remains under 15 minutes long, and that the meeting is productive and positive.

# The Development Team may use this time to get clarification on Sprint Backlog Items by inviting the Product Owner, or the Product Owner's designee, and posing questions to them.

# 4.2.1.4. Sprint Review Meeting

# The Sprint Review meeting is a Scrum meeting that is timeboxed to at most one hour per week that the Sprint ran.

# Once the timebox for the Sprint is over, the Development Team, Product Owner, and any guests the Product Owner wishes to invite, convene to review the contents of the Sprint. During this meeting, the Development Team demos and outlines the work that they completed, as well as what was not completed, and they and the Product Owner decide which Sprint Backlog Items are complete. 

# The Product Owner may also wish to address changes to the Product or Product Backlog that occurred during the Sprint, as well as any new clients, bugs, or functionality requests.

# The Sprint Review attendees then may choose to discuss plans for what will go into the next Sprint in an effort to streamline the Sprint Planning meeting before it happens.

# 4.2.1.5. Sprint Retrospective Meeting

# The Sprint Retrospective meeting is a Scrum meeting that is timeboxed to at most one hour, plus 30 minutes per week that the Sprint ran. The meeting is held after the Sprint Review Meeting and before beginning the next Sprint with the Sprint Planning meeting.

# During the Sprint Retrospective meeting, the Development Team, Product Owner, and Scrum Master discuss how the work went during the Sprint, hoping to uncover and address any deficiencies, as well as highlighting good work and innovative ideas. 

# 4.3. Github Issue Management



# 4.4. Release Candidate

# 5. Glossary

# timeboxed


# Development Procedure

# Product Backlog Item Generation
Product Backlog Items are represented by Github Issues with the “Needs Project” label.

The Product Owner or their designee maintains this list and refines the contents of the Issues, and understands of the priority of the Issues with a method of their choosing such that important, valuable, and time-sensitive Issues are selected first for upcoming Sprints.

# Development Sprint Process

## Conduct Sprint Planning meeting
1. Make a new Github Project for the Sprint ("Sprint #") in the appropriate repository
2. Move Issues into the Sprint Project as a result of/during the Sprint Planning Meeting. These Issues will make up the Sprint Backlog.
3. Add all Sprint Issues to the “To Do” column

## Work through Sprint Backlog
1. Create a new next_release branch or merge master into next-release. All new work for the Sprint is done in the next_release branch.
2. Assign Sprint Issues to Developers. The Development Team self-organizes and 	self-determines who gets what issues to work on. Issues may be unassigned and/or reassigned at any time at their discretion
3. Conduct Daily Scrum meetings
4. Move Issues through the Github Project columns
  1. Move Issues to the Doing column when started
  1. Move Issues to the Done column when complete
  1. Assign Done Issues to QA or impartial Developers for validation. Validation at this stage is a unit test to ensure that the changes made perform as expected by redressing the original Issue and determining if the problem has been solved or feature has been added.
5. Move validated issues to the Validated column

## Finish out the Sprint	
1. Conduct Sprint Review meeting
1. Merge next_release branch into current_version branch
1. Conduct Sprint Retrospective meeting

# Determine if a release is necessary
1. Assign version number using the Semantic Versioning format as described by semver.org, as appropriate to the situation
2. Build Release Candidate in Github from the current_version branch
3. Conduct release validation
  1. Create or reuse Release Validation procedures for representative client types, which include but are not limited to: ENT, BCA, and Baker
  2. Procure or update databases for each client type and make them available for use by the Development Team
  3. Conduct relevant migrations on each database
  4. Conduct validation on each database based on Release Validation procedures
  5. Release Validation may be tracked either as Issues in the next Sprint, or parallel to the Sprint depending on resources and strategy
4. Director of Development or their designee signs off on validation stating the validation was completed satisfactorily and that the release is stable according to the information available to them
5. Merge current_version into master branch
6. Notify clients and internal employees to announce the release

# Roles

## Organizational Roles
Developer
: TBD

Lead Developer
: TBD

Quality Assurance
: TBD

Director of Development
: TBD

## Scrum Roles
Development Team
: TBD

Product Owner
: TBD

Scrum Master
: TBD

# Supporting Tools, Processes, and Services

Github
	Issues
	Projects
	Repositories
	Labels
	Releases
	Wiki
Slack
Gmail
Scrum
	Overview
	Roles
	Meetings
		Sprint Planning
		Daily Scrum
		Sprint Review
		Sprint Retrospective
