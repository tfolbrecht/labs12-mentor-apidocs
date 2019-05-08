---
weight: 79
title: Fronend App Structure
---

# Frontend App Structure

Blah blah blah this is why we did it this way


```shell
# Frontend src structure
.
├── actions
│   ├── auth.js
│   ├── experiences.js
│   ├── index.js
│   ├── invitations.js
│   ├── matches.js
│   ├── meetings.js
│   ├── mentees.js
│   ├── mentors.js
│   ├── notifications.js
│   ├── organizations.js
│   └── users.js
├── components
│   ├── ExperiencesComponents
│   │   ├── ExperienceCard.js
│   │   └── ExperienceList.js
│   └── MeetingsComponents
│       ├── MeetingCard.js
│       ├── MeetingsForm.js
│       └── MeetingsList.js
├── constants
│   ├── actionTypes.js
│   └── config.js
├── containers
│   └── MeetingsContainer.js
├── history
│   └── index.js
├── index.js
├── pages
│   ├── AdminPanel
│   │   ├── AdminPanel.js
│   │   ├── Application
│   │   │   ├── Application.js
│   │   │   ├── ApplicationRes.js
│   │   │   └── ProfileInfo.js
│   │   ├── Assignment
│   │   │   ├── Assignment.js
│   │   │   ├── MapView.js
│   │   │   └── Recommended.js
│   │   ├── MentorApplications.js
│   │   ├── MentorAssignment.js
│   │   └── ProfileForms.js
│   ├── HomePage
│   │   ├── 404
│   │   │   ├── index.html
│   │   │   └── index.xml
│   │   ├── css
│   │   │   └── style.min.66d2a2d57ed39ba1b6d523fef1f7b51c4c3825c5a7c299e4df07ea49e5ff92a1.css
│   │   ├── favicon.png
│   │   ├── features
│   │   │   ├── noun_3d modeling_1885342.svg
│   │   │   ├── noun_branding_1885335.svg
│   │   │   └── noun_The Process_1885341.svg
│   │   ├── images
│   │   │   ├── logo-mobile.svg
│   │   │   ├── logo.png
│   │   │   ├── logo.svg
│   │   │   ├── undraw_businesswoman_pc12.svg
│   │   │   ├── undraw_hang_out_h9ud.svg
│   │   │   └── undraw_taking_notes_tjaf.svg
│   │   ├── index.html
│   │   ├── js
│   │   │   └── scripts.min.bf1e1f7ae8e03db5f012356e825843facdff51c0a559cb0d27fe2bbe1db405c2.js
│   │   └── tags
│   │       ├── index.html
│   │       └── index.xml
│   ├── HomePage.js
│   ├── MeetingsPage.js
│   ├── NotificationButton.js
│   ├── Notification.js
│   ├── NotificationsView.js
│   ├── OrganizationRegister.js
│   ├── StudentProfile.js
│   ├── UserLogin.js
│   └── UserRegistration.js
├── reducers
│   ├── auth.js
│   ├── experiences.js
│   ├── index.js
│   ├── invitations.js
│   ├── matches.js
│   ├── meetings.js
│   ├── mentees.js
│   ├── mentors.js
│   ├── notifications.js
│   ├── organizations.js
│   └── users.js
├── routes
│   └── index.js
├── serviceWorker.js
└── store
    └── index.js

21 directories, 71 files
```