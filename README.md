# Rails Wikinimous

A simple wiki application built with Ruby on Rails where users can create, edit, and manage articles.

## Features

- Create new articles
- View a list of all articles
- Read individual articles
- Edit existing articles
- Delete articles

## Tech Stack

- Ruby on Rails
- Active Record (ORM)
- ERB (Embedded Ruby)
- Bootstrap & Font Awesome (for styling)
- Faker (for seed data)

## How It Works

The application follows RESTful conventions and the MVC architecture:

- **Model**: Article model with title and content
- **Controller**: Handles CRUD actions for articles
- **View**: Renders article data and forms dynamically

Articles are stored in a database and managed using Active Record.

## Setup

git clone <your-repo-url>
cd rails-wikinimous
bundle install
rails db:create db:migrate db:seed
rails server

Open in your browser:
http://localhost:3000/articles

## Learnings

- Implementing full CRUD with RESTful routes
- Using Active Record for database interactions
- Structuring a Rails app with MVC architecture
- Seeding databases with Faker
- Building dynamic views and forms

## Notes

This project was built to practice Rails fundamentals and RESTful application design.
