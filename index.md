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
