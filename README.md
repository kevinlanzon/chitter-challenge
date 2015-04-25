Chitter Challenge
=============

[Makers Academy](http://www.makersacademy.com/) Week 4 challenge - Build a Twitter Clone

This weeks challenge was to build a Twitter clone that will allow the users to post messages to a public stream. 

###Features

- Users can sign up to the service
- Users can log in
- Users can log out
- Users can post a message
- Users can see all posts in reverse chronological order

###Notes

- Users sign up to chitter with their email, password, name and a user name
- The username and email are unique.
- Posts have their user handle.
- Bcrypt used to secure the passwords.
- DataMapper and postgres used to save the data.
- Users don't have to be logged in to see the posts.
- Users can only post if logged in.
- On users' own home page, they can see their own posts and search for others'.

###Technologies Used

- Ruby
- Rspec
- Sinatra
- PostgreSQL
- Bcrypt
- DataMapper

How to clone this repo
----
```sh
git clone git@github.com:kevinlanzon/chitter-challenge.git
```

How to run tests
----
```sh
run rspec
```
