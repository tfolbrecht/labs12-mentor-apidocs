---
weight: 17
title: Backend Errors
---

# Backend API Status Codes

<aside class="notice">This is not an exhaustive list and is subject to change!</aside>

The MentorMatchr API uses the following http status codes:

## /api/auth/

POST ROUTE /api/auth/login | Status Code
------------------| -------
success | 200
no user found | 404
no email | 400
no password | 400
wrong password | 401

POST ROUTE /api/auth/register | Status Code
-------------------- | ---------
on success | 201
no organization name | 400
no email | 400
no password | 400
user or organization already registered | 500

### /api/auth/github

UNDEF

### /api/auth/github/callback

UNDEF

## /api/experiences/
GET ROUTE /api/experiences
POST ROUTE /api/experiences
GET ROUTE /api/experiences/:id
PUT ROUTE /api/experiences/:id
DELETE ROUTE /api/experiences/:id

### /api/experiences/:id/remove

UNDEF

### /api/invitations/

UNDEF

### /api/invitations/:invitation_id

UNDEF

### /api/invitations/:invitation_id/github

UNDEF

### /api/invitations/:invitation_id/remove

UNDEF

## /api/matches/

UNDEF

### /api/matches/:id

UNDEF

### /api/matches/:id/remove

UNDEF

## /api/meetings/

GET ROUTE /api/meetings/ | Status Code
-------------------- | ---------
on success | 200 

POST ROUTE /api/meetings/ | Status Code
-------------------- | ---------
on success | 200
without notes | 201
without rating | 201
without notes and rating | 201
no match id | 400
no meeting date | 400
no location | 400

GET ROUTE /api/meetings/:id | Status Code
-------------------- | ---------
on success | 200 
if no such meeting | 404 

PUT ROUTE /api/meetings/:id | Status Code
-------------------- | ---------
on success | 200

DELETE ROUTE /api/meetings/:id | Status Code
-------------------- | ---------
on success | 200

DELETE ROUTE /api/meetings/:id/remove | Status Code
-------------------- | ---------
on success | 200

## /api/mentees/

GET ROUTE /api/mentees/ | Status Code
-------------------- | ---------
success | 200

POST ROUTE /api/mentees/ | Status Code
-------------------- | ---------
on success | 201
without interests | 201
without desired zip | 201
without application answers | 201
on fail without lambda_week | 404

GET ROUTE /api/mentees/:id | Status Code
-------------------- | ---------
on success | 200 
if no such meeting | 404 

PUT ROUTE /api/mentees/:id | Status Code
-------------------- | ---------
on success | 200

DELETE /api/mentees/:id | Status Code
-------------------- | ---------
on success | 200


## /api/mentors/

GET ROUTE /api/mentors/ | Status Code
-------------------- | ---------
on success | 200

POST ROUTE /api/mentors/ | Status Code
-------------------- | ---------
on success | 201

GET ROUTE /api/mentors/:id | Status Code
-------------------- | ---------
on success | 200
PUT ROUTE /api/mentors/:id | Status Code
-------------------- | ---------

DELETE ROUTE /api/mentors/:id | Status Code
-------------------- | ---------

## /api/notifications/

GET ROUTE /api/notifications/ | Status Code
-------------------- | ---------

POST ROUTE /api/notifications/ | Status Code
-------------------- | ---------

GET ROUTE /api/notifications/:id | Status Code
-------------------- | ---------

PUT ROUTE /api/notifications/:id | Status Code
-------------------- | ---------

PATCH ROUTE /api/notifications/:id | Status Code
-------------------- | ---------

DELETE ROUTE /api/notifications/:id | Status Code
-------------------- | ---------

DELETE ROUTE /api/notifications/:id/remove | Status Code
-------------------- | ---------


## /api/organizations/

GET ROUTE /api/organizations/ | Status Code
-------------------- | ---------

POST ROUTE /api/organizations/ | Status Code
-------------------- | ---------

GET ROUTE /api/organizations/:id | Status Code
-------------------- | ---------

PUT ROUTE /api/organizations/:id | Status Code
-------------------- | ---------

DELETE ROUTE /api/organizations/:id/remove | Status Code
-------------------- | ---------

## /api/users/

GET ROUTE /api/users/:id  | Status Code
-------------------- | ---------

PUT ROUTE /api/users/:id  | Status Code
-------------------- | ---------

DELETE ROUTE /api/users/:id | Status Code
-------------------- | ---------

DELETE ROUTE /api/users/:id/remove  | Status Code
-------------------- | ---------

GET ROUTE /api/users/current_user | Status Code
-------------------- | ---------
