# Agile Logbook

*Daily stand-ups, sprint planning, progress updates and retrospective notes.*

[Home & CV](README.md) | [Agile Team Charter](charter.md) | [User Stories and Tasks](user-stories.md) | [Product Backlog](product-backlog.md) | [Sprint Backlog](sprint-backlog.md) | **Agile Logbook** | [Full FundiShop Document](FundiShop_PRP370_Portfolio.md)

## Introduction

The Agile Logbook records the team's development activities throughout the FundiShop project. It provides a record of sprint planning, daily progress, challenges, decisions and lessons learned during development.

FundiShop is a service marketplace that connects homeowners with local service providers, known as Fundis. The project involves developing a web application with a React frontend, a Spring Boot backend and a MySQL database.

The logbook helps the team monitor progress, communicate problems, identify blockers and reflect on how the development process can be improved. It also provides evidence of individual and team participation in Agile activities.

## Evidence

Add screenshots or photographs of your actual daily stand-ups, Trello activity, sprint planning discussions and retrospective notes. Evidence should show dates and relevant project activities wherever possible.

![FundiShop Agile logbook evidence showing team progress and daily activities](images/logbook.png)

*Figure 1: FundiShop Agile logbook evidence showing team activities, progress and discussions, 2026.*

Additional evidence can be included below if available.

![Screenshot of FundiShop team daily stand-up records](images/logbook-standup.png)

*Figure 2: FundiShop daily stand-up and progress records.*

![Screenshot of FundiShop sprint retrospective notes](images/logbook-retrospective.png)

*Figure 3: FundiShop sprint retrospective and improvement actions.*

## Sprint Planning Record

Sprint planning is used to agree on the sprint goal and select product backlog items that the team believes it can complete within the sprint. The selected items are broken down into smaller tasks and assigned according to the team's capacity and responsibilities.

### Proposed Sprint Goal

Develop and improve the main FundiShop user workflow, including account access, Fundi discovery and the ability for homeowners to request and view bookings.

### Planning Activities

- Review the prioritised product backlog.
- Discuss the requirements for the selected user stories.
- Identify dependencies and technical requirements.
- Break larger stories into smaller development tasks.
- Allocate responsibilities to team members.
- Agree on the sprint goal and expected outcomes.

## Daily Stand-up Records

Daily stand-ups provide an opportunity for team members to communicate their progress, explain what they plan to work on next and identify anything preventing them from completing their tasks.

The following table provides an example of how daily stand-up information can be documented. Replace these examples with your team's actual meeting records.

| Meeting | Progress | Next steps | Blockers or issues |
|---|---|---|---|
| Day 1 | Review project requirements and identify the sprint tasks. | Begin work on assigned development tasks. | Clarification of requirements may be needed. |
| Day 2 | Work on the frontend and backend components. | Continue implementation and prepare for integration. | Check dependencies between frontend and backend. |
| Day 3 | Continue development of the selected features. | Connect frontend components to backend endpoints. | Investigate any API or database errors. |
| Day 4 | Review the current implementation and test functionality. | Fix identified issues and continue testing. | Resolve any integration problems. |
| Day 5 | Review progress against the sprint goal. | Complete outstanding tasks and prepare for sprint review. | Identify unfinished work for future planning. |

## Team Contributions

The team's agreed roles provide a structure for coordinating project activities. Actual task contributions should be confirmed using the Trello assignments and project records.

| Team member | Role | Responsibilities |
|---|---|---|
| Kabelo Moloko | Scrum Master | Support Agile activities, coordinate communication and help identify blockers. |
| Lisakhanya Mpahla | Product Owner | Clarify requirements, represent user needs and prioritise product features. |
| Christian Hakizimana | Backend Developer | Contribute to backend development, REST APIs, database operations and integration. |
| Muhammad Siddeeq Rabin | Frontend Developer / QA | Contribute to user interface development, frontend integration and testing. |

## Development Progress and Challenges

During the development of FundiShop, the frontend and backend components need to work together to support the main marketplace features. This requires communication between the React application, Spring Boot REST APIs and MySQL database.

### Technical Areas

- Developing and improving the React user interfaces.
- Implementing backend endpoints using Spring Boot.
- Connecting application features to the MySQL database.
- Testing user registration and login functionality.
- Implementing Fundi profiles and booking operations.
- Testing communication between frontend and backend.

### Example Technical Challenges

One possible integration challenge is ensuring that frontend requests can communicate correctly with the backend. For example, incorrect API endpoints, CORS configuration or unexpected response formats can prevent features from working as expected.

Another important area is ensuring that booking information is correctly associated with the homeowner and the selected Fundi. This requires correct backend relationships and database operations.

## Sprint Review

At the end of a sprint, the team should review the completed functionality and compare the results with the sprint goal. The review helps determine which items meet their acceptance criteria and which items need additional work.

| Review area | Details to record |
|---|---|
| Completed work | List the features and tasks completed and verified during the sprint. |
| Unfinished work | Identify tasks that remained incomplete and explain their status. |
| Testing results | Record the tests performed and any defects identified. |
| Feedback | Document feedback from the team and relevant stakeholders. |
| Next steps | Identify work that should return to the product backlog or be considered for the next sprint. |

## Sprint Retrospective

A sprint retrospective gives the team an opportunity to reflect on its working process and identify improvements for future sprints.

### What Went Well?

- Team members had defined responsibilities.
- The backlog provided a structure for organising work.
- Breaking features into smaller tasks helped make development manageable.
- Communication helped the team identify development issues.

### What Could Be Improved?

- Improve task estimation before committing to sprint work.
- Communicate blockers as soon as they appear.
- Allow sufficient time for frontend and backend integration.
- Keep Trello cards updated as tasks progress.
- Define clearer acceptance criteria before implementation begins.

### Suggested Improvement Actions

| Improvement | Action | Expected benefit |
|---|---|---|
| Task estimation | Discuss effort and dependencies before selecting sprint tasks. | More realistic sprint planning. |
| Communication | Report blockers and request help early. | Faster resolution of problems. |
| Testing | Test individual features before integrating them. | Fewer integration problems. |
| Trello updates | Update task status regularly. | Better visibility of team progress. |

## Personal Reflection

Maintaining an Agile logbook has helped me understand the importance of tracking development activities and reflecting on progress throughout a software project. It provides a structured way to record what the team is working on, the problems encountered and the decisions made during development. It also helps connect daily tasks with the larger sprint goal.

The development of FundiShop involves different components, including the React frontend, Spring Boot backend and MySQL database. Working across these areas requires coordination and regular communication. A feature may be implemented successfully in one component but still require additional work before it functions correctly as part of the complete application.

One important lesson is that technical challenges should be communicated early. Problems involving API communication, database relationships or frontend integration can affect other tasks if they are not identified in time. Regular progress discussions and updates to the task board can help the team identify these issues and decide how to address them.

As a backend developer, I have learned the importance of designing and testing backend functionality with the frontend requirements in mind. Backend endpoints must return the information expected by the user interface, while database relationships must correctly represent the application's data. This has strengthened my understanding of API development, integration and software testing.

For future sprints, I would improve task estimation, clarify requirements before implementation and allocate more time for testing and integration. I would also make sure that progress and blockers are recorded consistently. These improvements can help the team work more efficiently and deliver a more reliable FundiShop application.

**Personal evidence to add before submission:** Include one actual example of a task you worked on, a challenge you experienced, how you addressed it and what changed as a result. Also identify one retrospective action that you personally applied.

---

[← Sprint Backlog](sprint-backlog.md)

*© 2026 Christian Hakizimana · 219117675 · CPUT Diploma in ICT · PRP370S/371S/372S*
