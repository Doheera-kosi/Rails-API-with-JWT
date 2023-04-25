# User Login and Signup with JWT Authentication 

> This application focuses on user login and sign up and authorizing/authenticating them with JWT (JSON Web Tokens).

## Pre-requisite

Before you get started, you will need the following:

* Ruby installed on your machine
* PostgreSQL installed on your machine
* Basic knowledge of Ruby on Rails

## Setup

To get started, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/your-repository.git
   ```

2. Navigate to the repository directory:

   ```
   cd your-repository
   ```

3. Install the necessary dependencies:

   ```
   bundle install
   ```

4. Set up the database:

   ```
   rails db:create && rails db:migrate
   ```

5. Start the Rails server:

   ```
   rails server
   ```

6. Open your web browser and navigate to `http://localhost:3000` to view the application.

## Ruby version

This application was developed with Ruby version 3.1.1 and Rails version 7.0.4.3

## System dependencies

This application has the following system dependencies:

* Ruby
* Rails
* PostgreSQL

## Configuration

1. Clone the repository to your local machine.
2. Navigate to the root directory of the project and run `bundle install` to install all necessary gems.
3. Make sure PostgreSQL is running on your machine.
4. Run `rails db:create` to create the PostgreSQL database.
5. Run `rails db:migrate` to migrate the database schema.
6. Run `rails db:seed` to populate the database with seed data (optional).

## Database Creation

To create the PostgreSQL database:

```
rails db:create
```

This will create the development and test databases defined in the `config/database.yml` file.

Note: make sure PostgreSQL is running on your machine before running this command.

### Database initialization

To initialize the database with the necessary tables and seed data, run the following command in your terminal:

```
rails db:migrate
```

## Usage

Once the application is running, you can use the following endpoints to create, authenticate, and authorize users:

- `POST /users` - create a new user with a username, password, and age
- `POST /login` - authenticate a user with a username and password and receive a JWT token
- `GET /auto_login` - authorize a user with a JWT token

Note that the `/auto_login` endpoint is protected and requires a valid JWT token to access.

Then, navigate to `http://localhost:3000` in your browser to view the application.

### How to run the test suite

To run the test suite for this application, run the following command in your terminal:

```
rails test
```

### Services

This application requires no additional services to run.

### Deployment instructions

To deploy this application to a server, follow the standard deployment process for Ruby on Rails applications.

## Conclusion

This repository provides a simple example of how to implement user authentication and authorization with JWT in a Ruby on Rails application. It is just one approach and may not be suitable for every application, but it serves as a starting point for building more complex systems.