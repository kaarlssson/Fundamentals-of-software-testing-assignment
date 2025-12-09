## Summary (Summarize the bug encountered concisely)

Typographical error in the "Create blank project" button text on the Project Creation page; displays "Create black project" instead.

## Steps to reproduce

1. Ensure the user is logged into GitLab.

2. Navigate to the Project Creation page: https://gitlab.com/projects/new

3. Observe the button text under the "Create blank project" option

## What is the current bug behavior?

The text displayed on the button/link intended for creating a blank project is "Create black project".

## What is the expected correct behavior?

The text on the button/link for creating a blank project should correctly display "Create blank project".

## Relevant logs and/or screenshots

URL: https://gitlab.com/projects/new#blank_project
![Image info](../Image/Bug_Project_create_blank.png)

## Possible fixes

Modify the relevant front-end code to say blank instead of black

## Whom do you report/ Assign To/ Tags

Assignee: Front-end Developer / UI Team
Tags: UI-Bug, Typo, ProjectCreation

## Priority

Minor
The bug is a cosmetic/typographical error that affects the user interface and professionalism. It is not blocking functionality but should be fixed asap.
