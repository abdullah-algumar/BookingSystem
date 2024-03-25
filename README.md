# Booking System

### Project:

BookingSystem using django rest and React

# Install and Run

### Install React & Django repos:
`git submodule update --init --recursive`

### Create a environment file in the BASE_DIR named .env and put the informations:

```
touch .env
```

```
DEBUG=True
SECRET_KEY=<secret-key>
POSTGRES_DB=<db-name>
POSTGRES_USER=<db-user>
POSTGRES_PASSWORD=<db-password>
DATABASE_HOST=<db-host>
DATABASE_PORT=5432
```

# Run with Docker

## on the main folder of project run this command

`docker-compose up -d --build`

# Running

- http://127.0.0.1:8000 is the Django app
- http://127.0.0.1:3000 is the React app


### Backend APIs docs find here:

- http://127.0.0.1:8000/redoc
- http://127.0.0.1:8866/swagger 
 