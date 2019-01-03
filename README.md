# questioner_APIs
APIs for the questioner challenge for Andela fellowship

The routes for all endpoints
--------------------------------------
GET /api/v1/meetups: this gets all the meetups

GET /api/v1/meetups/upcoming/all :  this gets all the upcoming meetups

GET /api/v1/meetups/:id : this gets a specific meetup identified by the id given

POST /api/v1/meetups : this create a new meetup

POST /api/v1/questions : this create a new questions

PATCH /api/v1/questions/:id/upvote : this upvotes a question

PATCH /api/v1/questions/:id/downvote : this downvote a question

GET /api/v1/questions/:id : this gets all questions for specific meetup identified by the id given

[![Build Status](https://travis-ci.com/Karlmusingo/questioner_APIs.svg?branch=master)](https://travis-ci.com/Karlmusingo/questioner_APIs)
