# TODO List App (Ruby on Rails + SQLite)

This is a simple TODO list application built with Ruby on Rails and SQLite. The app features a modern UI and is ready for further extension, including React JS frontend integration.

## Features
- Add, edit, delete, and mark tasks as completed
- Responsive, Material Design-inspired UI (Materialize CSS via CDN)
- SQLite database for easy local development

## Requirements
- Ruby 3.2+
- Rails 8+
- Node.js & Yarn (for JS dependencies)

## Setup Instructions
1. **Install dependencies:**
   ```sh
   bundle install
   yarn install # if using Yarn for JS packages
   ```
2. **Setup the database:**
   ```sh
   rails db:setup
   ```
3. **Start the Rails server:**
   ```sh
   rails server
   ```
4. **Visit the app:**
   Open [http://localhost:3000/tasks](http://localhost:3000/tasks) in your browser.

## Stack
- Ruby on Rails (API & server-side rendering)
- SQLite (default dev database)
- Materialize CSS (CDN)

## Migrating to React Frontend
You can migrate the frontend to React JS for a modern SPA experience. Recommended approaches:
- Use [Vite](https://vitejs.dev/) for a modern React setup, or
- Use the [`react-rails`](https://github.com/reactjs/react-rails) gem for classic integration.

## Development Notes
- To customize styles, edit `app/assets/stylesheets/application.css`.
- To add React, set up your preferred JS bundler and create React components in `app/javascript`.

## License
MIT
