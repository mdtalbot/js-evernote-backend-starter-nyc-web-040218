### Welcome!

This is the back end for Tinynote, a simple note-taking app that I built using React and a Rails starter template provided by my coding bootcamp. For the front end, see https://github.com/mdtalbot/tinynote-frontend.  

### Motivation

This app was created mostly just to sharpen my React skills, as well as help me delve further into Semantic UI. The fact that it also helps keep me organized is a bonus.

### Libraries and Frameworks Used

* [Ruby on Rails](https://rubyonrails.org/)
* [React](https://reactjs.org/)
* [Semantic UI](https://react.semantic-ui.com/)
* [Moment](https://momentjs.com/)
* [PostgreSQL](https://www.postgresql.org/)

## Features

- [x] Allows users to create, read, update, and delete notes.
- [x] Contains a search bar for easy retrieval of notes from the database.
- [ ] (WIP) Sorts notes by the date they were created or date they were updated.

## Installation


Clone the source locally:

```sh
$ git clone https://github.com/mdtalbot/tinynote-backend/
$ cd tinynote-backend
```

Install the `bundler` Gemfile:

```sh
$ gem install bundler
```

Install project dependencies:

```sh
$ bundle install
```

Create the database:

```sh
$ rails db:create
```

Apply migrations to the database:

```sh
$ rails db:migrate
```

(Optional) Seed the database:

```sh
$ rails db:seed
```
This will create a few notes filled with standard lorem ipsum placeholder text.

Start the server on port 4000:

```sh
$ rails s -p 4000
```

*Once the server is running, make sure to also clone, install, and run the front end, found at http://www.github.com/mdtalbot/tinynote-frontend*. Installation instructions for the front end are found in that repository's README.
