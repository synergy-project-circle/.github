# Circle

## Summary

The goal of this project is to Socialfy the admin’s posts on announcements and events, providing an app where `admins` and `employees` can comment and react to posts.

## Long term vision

Circle will be a social media app where employees can share their personal interest with other employees on their spare time. The app will only feed `work` related posts during `work` hours, and then switches to `urgent` work-related posts and `personal` posts during non-working hours.

## Contributors

| Name                | Description |
| ---                 | ---         |
| Kim Joshua Villanueva | Founder    |
| Jessie Tarrosa      | Co-Founder  |
| Reymod Razote       | Co-Founder  |
| Ervin Benez         | Co-Founder  |
| Rodolfo Rivera      | Co-Founder  |

## Tech Stack

| Category              | Technology                                         |
| ---                   | ---                                               |
| Frontend              | ReactJS/TS (Material-UI, Scss, ReactQuery)         |
| Backend               | NodeJS/TS (Express)                                |
| Database             | MongoDB                                           |
| Hosting (Frontend & Backend) | Render                                  |
| Storage              | Firebase storage                                  |
| Auth Service         | Google Auth (Firebase Auth)                        |

## Specifications

### Frontend

| Access level | Actions |
| ---          | ---     |
| All          | Allowed to sign in and sign up through Google authentication |
|              | Allowed to see announcements and events           |
|              | Allowed to add/edit/remove personal reacts on posts and comments |
|              | Allowed to add/edit/remove personal comments      |
| Admin        | Allowed to add/edit/remove announcements and events and set their level of urgency |
|              | Allowed to moderate users by disabling/deleting a user's comment |
| User         | Allowed to update personal work hours             |

### Backend

| Access level | Actions |
| ---          | ---     |
| All          | Check if authentication is within the organization |
|              | Feed users within the organization announcements and events |
|              | Add/edit/remove personal reacts on posts and comments |
|              | Add/edit/remove personal comments                  |
| Admin        | Add/edit/remove announcements and events and set their level of urgency |
|              | Moderate users by disabling/deleting a user comment |
| User         | Update personal work hours                         |

## Technical Specifications

[Model collection](https://www.notion.so/Model-collection-1e14c172804045358f2a48c9c96114b4?pvs=21)

[API collection](https://www.notion.so/API-collection-37a7ce06a9484b66a6839c515f3a2d54?pvs=21)
