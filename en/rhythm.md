# Sprint execution

This document defines how to execute each sprint.

## Prerequisites

- The people involved are the product owner (or product manager), scrum master and development team.

## Sprint workflow

1. Hold a [sprint planning meeting](#sprint-planning-meeting) before starting the sprint.
1. Carry out [daily work](#daily-work).
1. Carry out [product backlog refinement](#product-backlog-refinement) during the sprint.
1. Conduct a [sprint review](#sprint-review) at the end of the sprint.
1. Conduct a [sprint retrospective](#sprint-retrospective) at the end of the sprint.

## Sprint planning meeting

### Pre-preparations

1. Close the sprint before the last one.
1. Create a new sprint and move the previous stories, which could not be closed, to the new sprint.
    - Do not simply move the stories but recreate them as stories indicating the actual situation. 
    - New stories may occur in this process.
    - For example, remaining confirmation tasks could be handled by creating the story "Confirmation of sprint XX" and transferring the tasks there. 

### Part 1

Participants: Product owner (or product manager), scrum master, development team  
Duration: 2 hours (for a two-week sprint)

1. The schedule of the new sprint is announced by the product owner and input. 
   - Sprints should generally be two weeks, or one week for an inexperienced scrum team.
1. The development team indicates story points that will be covered in this sprint. This should generally be the same as the results of the previous sprint.
1. The scrum team sets objectives to be accomplished during the sprint (sprint goals).
1. The development team selects the stories necessary to accomplish the sprint goals according to the backlog and inputs them in the sprint backlog.

### Part 2

Participants: Scrum master, development team  
Duration: 2 hours (for a two-week sprint)

1. Allocate a manager for each story.
1. Create specifications and a checklist for each story. Ask the product owner (or product manager) about any points you are unsure of in any story.
1. Decide on the content to be demonstrated for each story at the sprint review.
1. The story managers indicate all of the tasks that are needed in order to complete each story in the sprint backlog, based on the check results (around 15 minutes).  
Reference: [Criteria for good tasks: **SMART**](./smart_tasks.md)
1. Once the tasks are set, check that there are no issues in any tasks and enter estimated times for each task.
    - Each task must be small enough to complete in one day.
        - If experience indicates that around five hours of work can be completed with no overtime, this is the ideal amount of work per day converted into real time.
        - Therefore, any task that takes longer than five hours needs to be divided up.
1. If the time required for a task cannot be estimated and other work depends on this task, the task should be added to impediments, rather than adding a buffer to the time estimate.
1. Look at the total estimated time and judge whether the work can be completed during the sprint. Consult the product owner (or product manager) if there is a risk that it cannot be completed.

## Daily work

1. Hold [daily scrums](./daily_scrum.md).  
    - These documents presume that these will be held in the morning, but they can be held at any time.
    - Even if they are not held in the morning, daily scrums need to be held at the same time and in the same place every day.
1. Open the Kanban and move today’s tasks (indicated at the daily scrum) to "Doing".
1. Each pair discusses their tasks, decides which tasks will be done by each member and which will be done together and then begins working on their tasks.
1. Move each task to "Done" when it is completed.
1. If any tasks are still in "Doing" at the end of the work day, update the working time and remaining time and return the tasks to "ToDo".   
    - Make sure not to leave any tasks in the "Doing" lane at the end of the work day.


## Product backlog refinement

Participants: Product owner (or product manager), scrum master, development team  
Duration: Around 5 hours in total throughout the sprint period (for a two-week sprint)

The stories for the next 2-3 sprints need to be refined. Do not refine later stories,
as it is difficult to picture them, which means that they may need to be changed.

1. Add stories. Follow the instructions for creating product backlog in the [overall sprint plan](./sprints_planning.md) when adding stories.
1. Revise existing stories and add more details. Check whether the revisions based on the [story splitting cheat sheet](./story_splitting.md) are sufficient.
1. Revise the priority order of the stories.
1. Check that each story is ready.
    - At minimum, the backlog expected to be executed in the next sprint should be ready.
    - If the stories are not ready, talk to the team about preparing them during the previous sprint or revise the completion conditions.


## Sprint review

Participants: Product owner (or product manager), scrum master, development team  
Duration: 2 hours (for a two-week sprint)

### Pre-preparation

- Display the screen where the demonstration will be performed, along with the backlog and Kanban.

### Review

1. Announce that a review is being conducted for sprint X.
1. Provide a demonstration for each story.
1. Ask for any opinions.
    - A representative records any opinions in the minutes. When there are no more opinions, proceed to the next step.
1. Instruct the minute-taker to read the minutes aloud.

### After the review

- The minute-taker adds opinions from the review to the backlog and/or bugs.

## Sprint retrospective

Participants: Product owner (or product manager), scrum master, development team  
Duration: 1.5 hours (for a two-week sprint)

1. Hold a [sprint retrospective](./retrospective.md).

### After the retrospective

- Add points to try to the project wiki.
