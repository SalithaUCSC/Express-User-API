# Express-User-API

## Express JS API deployed on Heroku Cloud Platform

### Deployment Steps
*Heroku CLI must be installed to continue these steps*
1. Go into project folder
2. Hit **git init** to initialize.
3. Hit **git add .** to add all files to GIT.
4. Hit **git commit -m "add project"**.
5. Hit **heroku create ap_name** to create a new app. If heroku asks login details, give them.
6. Hit **git push heroku master**.

### API END POINTS

```
GET  ALL USERS       https://ex-rest-api.herokuapp.com/api/users
GET  SINGLE USER     https://ex-rest-api.herokuapp.com/api/users/id
POST ADD USER        https://ex-rest-api.herokuapp.com/api/users
POST UPDATE USER     https://ex-rest-api.herokuapp.com/api/users/update/id
POST DELETE USER     https://ex-rest-api.herokuapp.com/api/users/delete/id
```
