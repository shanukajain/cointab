
## User Fetch Application

## Features

- fetching multtiple data
- SQL 
- store multiple data in database
- RDS of aws used
## Tech Stack

**Backend:**  nodejs | Express | MySQL

**Frontend:**  HTML | CSS | JavaScript


## Run Locally

Clone the project

```bash
https://github.com/shanukajain/cointab.git
```

```bash
  cd cointab
```

Install dependencies

```bash
  npm install
```
Start the server

```bash
  npm run server
```
## Environment variable
#### 
To run this project, you will need to add the following environment variables to your .env file

`password`
`port`
`admin_name`
## DEMO

### Frontend
https://cointabassigment.netlify.app/

### Backend
https://cointab-bvef.onrender.com

## API Reference

#### user

```http
  GET /user/
```
fetch 50 users

```http
  DELETE /user/
```

delete all the users

```http
  GET /user/read
```

return all user information


```http
  GET /user/search/?username=coinab
```

return all the users accoding to search
