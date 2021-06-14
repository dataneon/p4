# Brain Sticker

## Github repos
- https://github.com/dataneon/brainsticker-backend
- https://github.com/dataneon/brainsticker-frontend

## Deployments
- Frontend: http://brainsticker-frontend.surge.sh/
- Backend: https://brainsticker.herokuapp.com/ (see end points such as `/notes/` and `canvases`)

## Description
Brain Sticker is a full-stack app that allows users to brainstorm by sticking notes to a canvas. The notes can created, read, updated, and deleted. The user is able to save their sessions to their accounts.

## Tech stack
### Frontend
- React
### Backend
- Django
### Database
PostgreSQL

## User Stories
- As a user, I want to receive up-to-date, relevant data about the location(s) I input.
- As a user, I want an intuitive design.
- As a user, I want a nice-looking application that is not crowded.
- As a user, I want to be able to save my sessions. 
- As a user, I want to move, edit, and delete notes.

## Screenshots of usage
![screenshot of user sign-up or log-in page](https://i.imgur.com/R4joXny.png)
Users can sign up or log in if they have already made an account.

![screenshot of user dashboard](https://i.imgur.com/uP7PxLY.png)
The dashboard when a user is logged in

![screenshot of sticky notes on a canvas](https://i.imgur.com/x0VJ33g.png)
Sticky notes displayed for a given canvas

![Screenshot of note edit page](https://i.imgur.com/ePZ6dva.png)
User can edit the content of a note or delete a note.

![Screenshot of canvas edit page](https://i.imgur.com/NprZY7X.png)
User can edit the canvas or delete a canvas.


## Installation
First `git clone` the backend: https://github.com/dataneon/brainsticker-backend

- Revert to commit `7e8214ff52`
- Install psql
- Run `pipenv shell`
- Run `psql -U postgres -f settings.sql`
- Run `python3 manage.py makemigrations`
- Run `python3 manage.py migrate`
- Run `python3 manage.py runserver`

Then `git clone` the frontend: https://github.com/dataneon/brainsticker-frontend

- Revert to commit `c26d5646`
- CD into `frontend`
- Run `npm i`
- Run `npm start`

## Thank you
Huge thank you to Tarric Sookdeo for his blog posts on user authentication:
- https://blog.devgenius.io/django-react-authentication-part-1-d351726b284d
- https://blog.devgenius.io/django-react-authentication-part-2-ea626688165e

Thanks to my instructors and classmates without whom I couldn't have made this project.
