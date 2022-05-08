# Not to do api server

This is a api server for the react not to do list.
The repo for the react not-to-do can be found here.

## How to use

- clone the repo `git clone`
- run `cd not-to-do-api`
- run `npm install`
- run `npm start`
  Note: you need to have nodemon installed globally. If you do not have it installed, run `npm install -g nodemon`

All the api has been written in the rest.http file

## APIs

All the api will follow the following URL:`{rootUrl}/api/v1/`

### Task API

all the task api will fowllow the following URL:`{rootUrl}/api/v1/tasks`

| #   | API | METHOD   | DESCRIPTION                                                   |
| --- | --- | -------- | ------------------------------------------------------------- |
| 1.  | `/` | `GET`    | fetch all the task from database                              |
| 2.  | `/` | `POST`   | send new task to add in the ßdatabase                         |
| 3.  | `/` | `PATCH`  | update task,i.e switch task item to not to do task            |
| 4.  | `/` | `DELETE` | send single or multiple task's id to delete from the database |

### User API

All the user api will follow the followinng URL:`{rootURl}/api/vi/urers/`

# react-not-to-do-api
