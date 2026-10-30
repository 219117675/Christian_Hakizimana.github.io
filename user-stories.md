# User Stories and Tasks

*Features written from the end user's perspective, broken down into tasks.*

[Home & CV](README.md) | [Agile Team Charter](charter.md) | **User Stories and Tasks** | [Product Backlog](product-backlog.md) | [Sprint Backlog](sprint-backlog.md) | [Agile Logbook](logbook.md) | [Full FundiShop Document](FundiShop_PRP370_Portfolio.md)

## Project Overview

FundiShop is a service marketplace designed to connect homeowners with local service providers, known as Fundis. The platform aims to make it easier for homeowners to find professionals, request services, arrange bookings and track their booking progress. Fundis can use the platform to manage their service requests.

User stories help describe the functionality from the perspective of the people who will use the system. Each story explains who needs a feature, what they want to do and why the feature is useful. The stories can then be divided into smaller development and testing tasks.

## Evidence

The evidence for this section should show the user stories and their related tasks as recorded on the FundiShop Trello board. Add a screenshot of the relevant Trello cards below.

![Screenshot of FundiShop user stories and their related tasks from Trello](images/user-stories.png)

*Figure 1: FundiShop user stories and related tasks recorded on the Trello board, 2026.*

## Draft User Stories and Tasks

The following examples illustrate how FundiShop functionality can be expressed as user stories and divided into manageable development tasks. Confirm the final wording, assigned members and completion status against the actual Trello board.

### User Story 1: User Registration

**As a** new user, **I want** to register for a FundiShop account, **so that** I can access the platform's services using my own account.

**Example tasks:**

- Create the registration form and input fields.
- Validate the information entered by the user.
- Connect the registration form to the backend API.
- Save valid user details in the database.
- Test successful registration and invalid input.

### User Story 2: User Login

**As a** registered user, **I want** to log in to FundiShop, **so that** I can access the features available to my account.

**Example tasks:**

- Develop the login interface.
- Validate the email and password fields.
- Connect login to the backend authentication logic.
- Display suitable messages when login fails.
- Test login using valid and invalid credentials.

### User Story 3: Find a Fundi

**As a** homeowner, **I want** to find local Fundis by their services, **so that** I can identify a suitable professional for my needs.

**Example tasks:**

- Create the Find a Fundi page.
- Display available Fundi profiles and trade categories.
- Retrieve relevant Fundi information from the backend.
- Show useful profile information to homeowners.
- Test the page with available and empty result sets.

### User Story 4: Create a Booking

**As a** homeowner, **I want** to request a booking with a Fundi, **so that** I can arrange help for a service I need.

**Example tasks:**

- Design the booking form.
- Capture the selected Fundi, date, time and job description.
- Connect the form to the booking API.
- Store the booking and its initial status.
- Test booking submission and validation.

### User Story 5: Track Bookings

**As a** homeowner, **I want** to view my bookings and their statuses, **so that** I can track the progress of my service requests.

**Example tasks:**

- Create the homeowner dashboard and booking summary.
- Retrieve bookings associated with the logged-in homeowner.
- Display booking dates, service details and statuses.
- Handle loading, empty and error states.
- Test that the correct bookings appear on the dashboard.

### User Story 6: Manage Booking Requests

**As a** Fundi, **I want** to view and manage incoming booking requests, **so that** I can respond to service requests from homeowners.

**Example tasks:**

- Develop the Fundi booking-management interface.
- Retrieve bookings associated with the Fundi's profile.
- Display relevant booking information and current statuses.
- Implement the permitted booking status updates.
- Test booking retrieval and status changes.

## Task Allocation

Tasks should be allocated according to the team's agreed roles, skills and availability. The table below is a planning template; the actual allocation must match the Trello cards.

| Team member | Agreed role | Example area of responsibility |
|---|---|---|
| Kabelo Moloko | Scrum Master | Support sprint coordination, track blockers and help the team follow its Agile process. |
| Lisakhanya Mpahla | Product Owner | Clarify user needs, prioritize requirements and help confirm acceptance criteria. |
| Christian Hakizimana | Backend Developer | Contribute to backend APIs, data handling and integration with the database. |
| Muhammad Siddeeq Rabin | Frontend Developer / QA | Contribute to user interfaces, frontend integration and software testing. |

These responsibilities describe the team's agreed roles, not proof that a specific task was completed by a particular member. Use the assigned members and task statuses shown in Trello when recording actual contributions.

## Reflection

When developing the FundiShop user stories, the main end users considered were homeowners and Fundis. Homeowners need a convenient way to find service providers, request bookings and track the progress of their requests. Fundis need a way to view incoming requests and manage their responses. These needs help guide the features included in the application and keep development focused on the people who will use the system.

The user stories use the format "As a..., I want..., so that..." to identify the user, the requested feature and its purpose. This format makes each requirement easier to understand and discuss. Stories should be small enough to implement and test, with clear acceptance criteria that explain what must happen for a feature to be considered complete. For example, a booking story can be tested by checking that valid booking details are submitted and that the new booking is associated with the correct homeowner and Fundi.

After defining a story, it can be broken down into tasks covering interface development, backend integration, database operations and testing. Breaking work into smaller tasks makes progress easier to track and helps team members understand what needs to be done. Task ownership and progress should be managed through the team's Trello board so that responsibilities and outstanding work remain visible.

One improvement I would make is to ensure that every story has specific acceptance criteria and a clear definition of completion. For example, the booking story should specify which fields are required, what happens when the submitted information is invalid, and which booking status is shown after a successful request. Writing user stories has helped me understand how to translate user needs into manageable development work and how planning, communication and testing contribute to building a useful system.

**Personal example to add before submission:** Describe one real user story or task from the Trello board that your team discussed, refined or had difficulty completing. Explain what you personally contributed and what you learned from that experience.

---

[← Agile Team Charter](charter.md) | [Product Backlog →](product-backlog.md)

*© 2026 Christian Hakizimana · 219117675 · CPUT Diploma in ICT · PRP370S/371S/372S*
