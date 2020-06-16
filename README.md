# React Challenge

## Setup
1. Clone the repository
2. Enter the project and run `npm install`
3. Once dependencies have been installed, run `npm start`

At this point, a server should start running on port 3000 that will serve two
routes.

## Endpoints
- List of aliases: http://localhost:3000/aliases
- List of unmatched plans: http://localhost:3000/unmatched-plans
- List of potential matches: http://localhost:3000/potential-matches
- One alias: http://localhost:3000/aliases/:id
- One unmatched plan: http://localhost:3000/unmatched-plans/:id
- One potential match: http://localhost:3000/potential-matches/:id

## Goal
Create an interface that shows unmatched plans and a form that enables a user
to match that plan to one entry in the set of potential matches.
