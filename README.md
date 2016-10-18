#Pairing

Find other people to pair with based on shared interests and skills

#Usage

To add people, go the People pag, To start and manage pairings, go to the Pairs page. 

##People Page
  - add person
    - email with fetch a gravatar
    - teaching and learning secions will help you in pairing them
  - generate a fake person
    - for testing
  - delete a person

##Pairs Page
  - generate pairs - generates pairs randomly, from unpaired people
  - clear pairs - all pairs become unpaired
  - save paris - save paris (records who paired with whom)
  - fullscreen - displays all pairs on one screen, good for projectors

##Person

  - select who to pair with
  - remove person from pair

#Installation and running
1. Install Meteor
2. Run `meteor`

#Deployment
1. use this heroku buildpack

  `test`

What is a buildpack? - It's a collection of scripts that prepares your code for execution by the Heroku dyno manager. Heroku's cedar stack has no default language/framework support, so we use a buildpack to determine/specify what kind of framework we wanted to build on. 

`https://github.com/jordansissel/heroku-buildpack-meteor.git`

What is cedar then? It's a polyglot environment, which means it has native support for many popular languages and frameworks. 
