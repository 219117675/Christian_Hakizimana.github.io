# Product Backlog

*The prioritised list of features, improvements and requirements needed to develop the FundiShop service marketplace.*

[Home & CV](README.md) | [Agile Team Charter](charter.md) | [User Stories and Tasks](user-stories.md) | **Product Backlog** | [Sprint Backlog](sprint-backlog.md) | [Agile Logbook](logbook.md) | [Full FundiShop Document](FundiShop_PRP370_Portfolio.md)

## Project Overview

FundiShop is a web-based service marketplace that connects homeowners with local service providers, known as Fundis. The application is intended to help homeowners discover professionals, create service bookings and monitor booking progress. Fundis need to manage their profiles and respond to incoming service requests.

The product backlog organises the functionality required for the application. Each backlog item represents a feature, improvement or technical requirement. Items are prioritised according to their value to users, dependencies, risk and estimated effort. The backlog can be refined as the team learns more about the requirements.

## Evidence

The evidence for this section should show the actual FundiShop product backlog on Trello, including the relevant cards and their priority order.

![Screenshot of the FundiShop product backlog showing prioritised backlog items](images/product-backlog.png)

*Figure 1: FundiShop product backlog on Trello, showing prioritised product requirements, 2026.*

## Prioritised Product Backlog

The following table is a proposed backlog for FundiShop. The priority labels indicate suggested implementation order and must be checked against the team's actual Trello backlog.

| Priority | Backlog ID | Item | Description | User value |
|---|---|---|---|---|
| High | PB01 | User Registration | Allow new users to create accounts and provide the required details. | Enables users to access personalised platform features. |
| High | PB02 | User Login | Allow registered users to access their accounts securely. | Provides account access and supports role-based experiences. |
| High | PB03 | Role-Based Access | Distinguish between homeowners, Fundis and administrators. | Ensures users access features appropriate to their roles. |
| High | PB04 | Find a Fundi | Allow homeowners to view available Fundis and their trade categories. | Helps homeowners find suitable service providers. |
| High | PB05 | Fundi Profiles | Display details such as trade, biography, rates and service area where available. | Helps homeowners assess whether a Fundi suits their needs. |
| High | PB06 | Create a Booking | Allow homeowners to submit a booking request with a date, time and job description. | Creates the main connection between a homeowner and a Fundi. |
| High | PB07 | Booking Management | Allow Fundis to view requests and update permitted booking statuses. | Helps Fundis respond to and manage service requests. |
| High | PB08 | Homeowner Dashboard | Display a homeowner's bookings and their current statuses. | Allows homeowners to monitor their service requests. |
| Medium | PB09 | Fundi Dashboard | Provide Fundis with an overview of their profiles and booking requests. | Organises important information in one place. |
| Medium | PB10 | Booking Status Updates | Support relevant status changes, such as accepting, declining or completing a booking. | Improves communication about booking progress. |
| Medium | PB11 | Validation and Error Handling | Validate user input and show helpful messages when operations fail. | Improves reliability and user experience. |
| Medium | PB12 | Responsive User Interface | Ensure key pages remain usable across supported screen sizes. | Makes the application easier to use on different devices. |
| Medium | PB13 | Integration Testing | Test communication between the frontend, backend APIs and database. | Helps identify integration errors before release. |
| Medium | PB14 | Administrator Functions | Provide appropriate administrative access for managing platform information. | Supports platform administration. |
| Low / Future | PB15 | Reviews and Ratings | Allow homeowners to provide feedback about completed services. | Could help users evaluate service providers. |
| Low / Future | PB16 | Notifications | Notify users of relevant booking events. | Could improve awareness of booking updates. |

**Important:** This table is a proposed planning example, not proof that every listed feature is implemented or present on the team's Trello board. Remove, rename or reorder items to match the actual project backlog.

## How Priorities Were Considered

### High Priority

Core features that support the main marketplace workflow are proposed as high priority. Users need to access the platform, discover Fundis and create and manage bookings for FundiShop to deliver its primary purpose.

### Medium Priority

Features that improve usability, visibility and reliability are proposed as medium priority. Dashboards, validation, responsive layouts and integration testing help make the core functionality easier and safer to use.

### Low or Future Priority

Additional features such as reviews and notifications are proposed for later consideration because the main booking workflow can be developed without them. Their priority should be reviewed if user feedback or project requirements make them more important.

## Backlog Refinement

The product backlog should be reviewed regularly as development progresses. New requirements, testing results, technical dependencies and feedback can lead to changes in priority. Large items should be broken down into smaller stories that the team can estimate, implement and test.

Each item should have a clear description and, where appropriate, acceptance criteria. The team should also identify dependencies. For example, creating and tracking bookings depends on having the relevant user accounts, Fundi profiles and booking data available.

## Reflection

The purpose of the product backlog is to organise the features required for FundiShop and provide the team with a shared view of what needs to be developed. The proposed priority order places the main marketplace workflow first: users must be able to access the platform, find a suitable Fundi and request a service before additional features can provide their full value.

When deciding priorities, user value, dependencies, risk and effort should all be considered. Registration and login support access to personalised features, while Fundi discovery and booking functionality support the main purpose of the product. Features such as validation and integration testing are also important because errors in account handling or bookings can prevent the core workflow from working correctly. The final order should reflect the decisions recorded by the team rather than priority labels assigned only for this portfolio page.

The backlog can change during development as the team discovers missing requirements, identifies technical problems or receives feedback. Some items may need to be divided into smaller stories, while others may be moved to a later stage if they are not essential to the current project goals. Refinement helps ensure that the team works on the most valuable and achievable items first.

One potentially difficult prioritisation decision is choosing between adding extra features and improving the reliability of existing functionality. For FundiShop, a dependable booking process is central to the marketplace, so validating booking data and testing the connection between the frontend and backend should be considered alongside new features. The team's actual Trello discussions should be used to identify the specific item that was hardest to prioritise and explain how the decision was reached.

The product backlog connects to the user stories because each backlog item can be described from the perspective of a homeowner, Fundi or administrator. Those stories can then be divided into development and testing tasks and selected for a sprint. The Agile Team Charter supports this process by establishing team roles, communication expectations and working agreements. Together, these artefacts help connect user needs, planning, implementation and review.

**Personal example to add before submission:** Identify one real item on your Trello backlog that the team moved up or down in priority. Explain why the change was made, who contributed to the decision and what you learned from it.

---

[← User Stories and Tasks](user-stories.md) | [Sprint Backlog →](sprint-backlog.md)

*© 2026 Christian Hakizimana · 219117675 · CPUT Diploma in ICT · PRP370S/371S/372S*
