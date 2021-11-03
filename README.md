# SCRUM backlog and board repository
This is the overall board for the SEP4 project.

## New User Stories
When creating new user stores, add an [Issue](https://github.com/jhviggo/sep4/issues/new) and set the label based on which team is responsible for completing it.
If you know which Sprint it belongs in, then add a Milestone with the given sprint name - otherwise just leave it blank.

If you want to specify what kind of issue it is (User Story, Task or Subtask) then you can also add that as a label.

## Linking to stories
When you create a merge request in you team repository, you can link directly to the issues with the prefix `GH-`, so issue 5 would be `GH-5`.

Please include this is your commit message, e.g.

`git commit`

```
Add new controller

GH-16

I added some cool features in the controller
```

## Sub-tasks
Github doesn't really have subtasks but you can link issues. If we want we can have labels for User Story, Task and Subtask
So in the subtasks you can add a new issue as shown below. When writing # and a number, you link to an issue. So this would be linked to issue 1
```
Task: add front page

Subtask of #1
...
```
## SCRUM board overview
The SCRUM board is under the project tab. It contains the backlog, where all issues are automatically added. The `To Do` board is meant to represent the current Sprint, so all current issues should be moved there in the beginning of a spring.

### Looking at the board
When you look at the SCRUM board you can filter using the search field. You can find all task with a given label, e.g. `Android` and issues in a given Milestone/Sprint.
