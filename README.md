# User Login and Signup with JWT Authentication 

> This application focuses on user login and sign up and authorizing/authenticating them with JWT (JSON Web Tokens).

### Pre-requisite

Before you get started, you will need the following:

* Ruby installed on your machine
* PostgreSQL installed on your machine
* Basic knowledge of Ruby on Rails

### Setup

1. Clone the repository to your local machine
2. Navigate to the project directory in your terminal
3. Run `bundle install` to install all necessary gems and dependencies
4. Create the database with `rails db:create`
5. Run the database migrations with `rails db:migrate`

### Ruby version

This application was developed with Ruby version 3.1.1 and Rails version 7.0.4.3

### System dependencies

This application has the following system dependencies:

* Ruby
* Rails
* PostgreSQL

### Configuration

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

### Usage

Once you have completed the setup, you can start the server by running:

```
rails s
```

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

### Conclusion

This README provides an overview of the necessary steps to get the user login and sign up functionality working with JWT authentication. If you have any questions or issues, please refer to the code or consult the Ruby on Rails documentation.