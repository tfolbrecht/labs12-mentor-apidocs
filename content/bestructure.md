---
weight: 80
title: Backend App Structure
---

# Backend App Structure

Blah blah blah this is why we did it this way

```shell

# backend src structure
.
├── controllers
│   ├── api.js
│   ├── auth.js
│   ├── experiences.js
│   ├── index.js
│   ├── invitations.js
│   ├── matches.js
│   ├── meetings.js
│   ├── menteeProfiles.js
│   ├── mentorProfiles.js
│   ├── notifications.js
│   ├── organizations.js
│   └── users.js
├── database
│   ├── dbConfig.js
│   ├── dev.sqlite3
│   ├── helpers
│   │   ├── db.js
│   │   ├── experiences.js
│   │   ├── invitations.js
│   │   ├── matches.js
│   │   ├── meetings.js
│   │   ├── menteeProfiles.js
│   │   ├── mentorProfiles.js
│   │   ├── notifications.js
│   │   ├── organizations.js
│   │   └── users.js
│   ├── migrations
│   │   ├── 20190501184840_organizations.js
│   │   ├── 20190501190520_users.js
│   │   ├── 20190501192222_mentorprofiles.js
│   │   ├── 20190501192227_menteeprofiles.js
│   │   ├── 20190501192238_experiences.js
│   │   ├── 20190501192245_matches.js
│   │   ├── 20190501192314_notifications.js
│   │   ├── 20190501192316_meetings.js
│   │   └── 20190502095546_invitations.js
│   └── seeds
│       ├── 000-cleanup.js
│       ├── 001-organizations.js
│       ├── 002-users.js
│       ├── 003-mentors.js
│       ├── 004-mentees.js
│       ├── 005-experiences.js
│       ├── 006-matches.js
│       ├── 007-notifications.js
│       ├── 008-meetings.js
│       ├── 009-invitations.js
│       └── 999-final.js
├── middleware
│   ├── authenticate.js
│   ├── authorize.js
│   ├── generateToken.js
│   ├── passport.js
│   └── serverMiddleware.js
├── routes
│   ├── auth.js
│   ├── experiences.js
│   ├── index.js
│   ├── invitations.js
│   ├── matches.js
│   ├── meetings.js
│   ├── menteeProfiles.js
│   ├── mentorProfiles.js
│   ├── notifications.js
│   ├── organizations.js
│   └── users.js
├── server.js
├── tests
│   ├── auth.test.js
│   ├── experiences.test.js
│   ├── meetings.test.js
│   ├── menteeProfiles.test.js
│   ├── mentorProfiles.test.js
│   ├── notifications.test.js
│   ├── orgs.test.js
│   └── users.test.js
└── validators
    ├── api.js
    ├── auth.js
    ├── experiences.js
    ├── index.js
    ├── matches.js
    ├── meetings.js
    ├── menteeProfiles.js
    ├── mentorProfiles.js
    ├── notifications.js
    ├── organizations.js
    ├── roles.js
    └── users.js

9 directories, 81 files
```