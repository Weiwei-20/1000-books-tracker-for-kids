# Project 1000 Books Tracker for Kids

## Objective
Reading is so much fun and so important for little minds. My husband and I have been reading to my son since he was born, every night before bedtime, and other times during the day. He learned so much from books and very interested in all kinds of subjects.

We recently joined our local library for 1000 books before kindergarten, and we also got a color book to track his progress, which is not that convenient and doesn't have a place to record the name of the book, etc. I always wanted to have something to record the books he really loves reading and why he loves it. Unfortunately, the library website doesn't have such a function to store the books we borrowed and read. Now it's a good time to develop something my son can track his reading progress, also make notes about which book he likes, so we have a favorite books list, future reading list, and so on, we can also share with other friends and families with their little ones.

## API Creation 

First, we are going to need to create an API using Spring that will handle our DB and interactions with it.

### Requirements
- [ ] Create a RESTful API with Spring Boot.
  - [ ] Endpoints for the following:
    - [ ] All `CRUD` operations for `book`s
      - [ ] Create endpoint
      - [ ] Read endpoint
      - [ ] Update endpoint
      - [ ] Delete endpoint
     
  - [ ] A database service layer for retrieving and storing `book`s from the database and interacting with the controllers.
  - [ ] Error handling
    - [ ] Resource not found
  - [ ] Integration testing suite
    - [ ] SmokeTests
    - [ ] HttpRequestTest
    - [ ] Application & WebLayer Tests
    
#### Relationships

Our user should be able to:
- access `book`s from the `categry` the book is on.


#### User Input Fields

Each entity should have fields the user can interact with:
- Change an `book`name.
- Should have ratings. 
- Should have comments with a way to add them.
- Have a way to delete an `book`.

## Single Page Application Front-end 

Next we will crate our front-end. It should be an SPA that uses JS to build out components that our users can interact with. Use modular JS to create reusable components.  This application should allow you to create new books, edit details about each of the items after they have been created, and delete items.

### User Interaction

Our users should be able to add new instances of 'book's as well as comments and ratings.

## Entities

### `book`

- title
- image
- author
- publisher
- publish year
- comments
- ratings
