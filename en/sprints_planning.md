# Overall sprint planning

Make a sprint plan for the whole project.

1. Make time boxes the length of each sprint.
   - Each sprint should generally be two weeks long. Use one-week sprints if the scrum team is inexperienced.
   - If there are public holidays during a sprint, adjust the sprint so that there are at least eight business days.
   - Sprints should ideally start on the same day of the week, as this creates a predictable rhythm.
   - Sprints should not start on Mondays for the following reasons.
       - The team will take time to warm up again after the weekend.
       - In Japan, many public holidays are held on Mondays, so starting sprints on Mondays leaves the schedule prone to disruption.

1. Create a product backlog.
  1. Establish stories based on the functional requirements.
     - Statements like "Make it possible to do X" or "Incorporate Y" are better than simply "Do Z". They decrease the readability of the list but are easier to picture.
     - Large stories that cannot be completed in one sprint should be split according to the [story splitting cheat sheet](./story_splitting.md).
  1. Estimate the story points of each story. 
     - Stories must be split into small enough segments for the team to handle on their own (they must, at minimum, fit into one sprint).
     - It is useful to set criteria like the following to determine whether stories need to be split, although this depends on the development team.
       - A story should be split if it is likely to be larger than 13 points.
       - A story should be split if it is likely to take longer than 2-3 days.
  1. The dependency relationships between stories should be considered when deciding and rearranging the priority order.
  1. Tests that are not included in stories based on functional requirements should be treated as separate stories.
     - This does not need to be done for all tests in the project, only the tests planned for phases that appear in the overall sprint plan.

1. Create a sprint backlog.
  1. Determine the velocity of the development team (the number of story points that will be handled in each sprint).
      - If the development team is inexperienced (contains members who are working on Scrum for the first time), the team’s velocity is likely to be low in the early sprints and then gradually increase. Consider this when deciding on the velocity of each sprint.
  1. Move tasks from the product backlog to the sprint backlog to fit the velocity of each sprint.

1. Check that this schedule is compatible with the master schedule.
  - For contract development, the following events are milestones.
    - Reviews by internal parties outside the scrum team
    - Client reviews
    - Exchange of deliverables with other teams
    - Testing of connectivity with other systems
  - Before each sprint (at least one sprint prior), check that the necessary stories are being finished.
    - The key to success in development is to keep a safety period between the scheduled completion time and the time of the milestone in the master schedule.
    - If a safety period is not possible, either the task is being started too late or the schedule is unrealistic. 

[Example of a plan created for a real project](./examples/OverallSprintPlan_ProjectExample.xlsx?raw=true)

## Points of caution for contract development

> **Note**: In waterfall development, a written project plan is usually used to plan projects. While sprints are planned as described in this document instead, some points in the project plan used for waterfall development are still necessary.
>
> Consider the overall sprint plan to be equivalent to the development schedule in a project plan. 

If the project as a whole is in waterfall model and sprints are only used for part of the project, care is needed when planning. With that said, the points requiring caution are basically the same as those that need to be considered when creating a schedule in waterfall model.

If these points are not taken into account when making the schedule, a simple failure to meet the estimates will require a report to the leaders or a new plan, and there is a high risk of a vicious cycle where work is repeatedly being rescheduled.

1. It is important for progress to occur as planned, as the situation is judged according to the plan.
  - Do not expect the same velocity from start to finish. It is common for velocity to decrease after starting.
    - Velocity usually increases not as a result of the team becoming familiar with operating methods but for reasons such as gaining a deeper understanding of the requirements or design or becoming familiar with the development technology.
    - The degree to which velocity increases can be predicted by the gap between the knowledge and skills of the development team members and the knowledge and technical skills required for the project.
      - Taking measures to reduce this gap will increase velocity.
2. Since the three parameters of a project are period, scope and cost, in cases where the period and scope are fixed (such as lump-sum contracts), the focus needs to be on controlling cost while completing the project.
  - When checking that the schedule is compatible with the master schedule, make sure there is a buffer at the end of the phases.
     - The buffers used for real projects vary considerably, from 20% to 100%.
     - Like plans in waterfall model, the size of the buffer should be decided based on the characteristics of the project.
