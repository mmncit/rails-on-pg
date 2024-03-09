# Template for Ruby on Rails using PostgreSQL

## Description

This project is a Ruby on Rails application that utilizes a PostgreSQL database.

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Copy the `.env.example` file and rename it to `.env`.
4. Open the `.env` file in a text editor.
5. Replace the placeholder values with the appropriate values for your environment.
   - For example, if your PostgreSQL database username is `myuser` and password is `mypassword`, update the `DATABASE_USERNAME` and `DATABASE_PASSWORD` variables accordingly.
6. Save the `.env` file.

## Usage

### Apply database changes

```bash
bundle exec rails db:migrate
```

### Run the server

```bash
bundle exec rails server
```
