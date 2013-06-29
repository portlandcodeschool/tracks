# Test rubrics for the various goals

## How we will test

Rather than require you all to go at the same pace we will separate this track into sections which will be tested at whatever pace you desire. You will also work with your group and have a separate time to show off your work and get review.

There are 3 chunks comprised of 4 sections each. If you did one section each day you would finish in 3 weeks. Most will do one test every other day and a group test once every other week.

### Project demo

Group tests will be administered on any day Monday..Thursday during either the morning or before 3pm in the afternoon. Project demos will take about 30 minutes. This test is a demonstration of an entire chunk of goals (4 sections). These can be arranged by putting your group's names on the signup sheet. Bring something to take notes.

Groups will present a demo of a small project they are creating. Demos should be 10-20 minutes in length and should be recorded by the presenters. Groups can be any size. The project presented should **not** be the same as the project in the Hartl book. Code should be uploaded to Github and will be reviewed after the presentation.

### Time trials

The individual time trials will only cover one section at a time and will take about 10 min per person. These can be arranged by putting your name on the sign-up sheet for the day.

Exams for each section will be 6 minutes long. The first 3 minutes will be spent on a time trial, while the second 3 minutes will be spent showing off your work on the project.

By no means are all the things in the rubric meant to be done in 3 minutes.

## Standards

We are working to become professional programmers. As such, the following is the bare minimum for every project and bit of code we present from here on out.

* Code accomplishes the goal
* Tests are included and correct
* Code contains comments that are accurate and concise
* Code is formatted according to a standard community style guide
* Code is presented professionally (no misspellings, nothing offensive in commit messages)
* Projects have a README and/or setup scripts
* Output is visually pleasing

## General guidelines

* 4\. Accomplishes the goal with accuracy and flair. Follows the style-guide and looks professional and idiomatic. Significant extras are demonstrated. Tests are included wherever possible.
* 3\. Accomplishes the goal correctly and simply. Follows the style-guide and looks professional. Student does not attempt further features. Tests are included wherever possible.
* 2\. Accomplishes the goal or at least comes extremely close. Follows the style-guide for the most part but may need some nitpicks. Student does not attempt further features. Tests are included but may not cover all the cases.
* 1\. Barely accomplishes the goal or comes close. Does not follow the style-guide very closely and code does not look professional. Tests are incorrect or not present.
* 0\. Student does not accomplish the goal. Tests are missing, style is poor, or there are many spelling errors or syntax errors.

## Chunk 1

### Section 1

* Be able to create sinatra projects from scratch
* Be able to use ERb and template interpolation in Sinatra

Points:

* 4\. All standards are followed. Should include aspects such as modular sinatra, reloaders, testing, rack middlewares, or something else extraordinary. Template does not contain any complicated logic and uses helpers where needed. Template may be in HAML or some other templating language.
* 3\. Most standards are followed. Project created including all necessary files. ERb template is rendered correctly with instance variables in the right place.
* 2\. Standards are attempted. Project created and loads in the browser.

### Section 2

* Be able to create Rails projects quickly
* Be able to deploy to heroku

* 4\. All standards are followed. Should include additional aspects such as bootstrap, extra documentation, logic in /lib, or something else extraordinary.
* 3\. Most standards are followed. Rails project is interesting but there is little attempt to go farther.
* 2\. Standards are attempted. Rails project is created and deployed to heroku. Loads in a browser but is very basic or unattractive.

### Section 3

* Be able to use scaffold generators
* Be able to use migrations to change the database

* 4\. All standards are followed. Should include additional aspects such as `respond_with`, tests, some model logic, or something else extraordinary. Project is up on heroku.
* 3\. Most standards are followed. Project is to spec but nothing special is present. Project is up on heroku.
* 2\. Standards are attempted. Project is up on heroku.

### Section 4

* Be able to create static controllers in Rails
* Be able to write tests in rspec

* 4\. All standards are followed. Should include additional aspects such as capybara, model specs, or something else extraordinary.
* 3\. Most standards are followed. Project includes extensive tests.
* 2\. Standards are attempted. Project is up on heroku. Tests are present though simple.

## Chunk 2

### Section 5

* Memorize the Ruby idioms that we use in Rails

* 4\. All standards are followed. Should include additional aspects such as more complicated flash cards, examples of idioms being used in real rails projects, flash cards from other open source projects or from the style-guide, or something else extraordinary.
* 3\. Most standards are followed. Student shows at least 20 flash cards with advanced topics that may have come from the style-guide or some other open source project. Simple ruby project is created showing off some idioms.
* 2\. Standards are attempted. Student shows at least 20 flash cards. Simple ruby project is created showing off some idioms.

### Section 6

* Be able to use bootstrap with Rails
* Be able to write CSS in SCSS

* 4\. All standards are followed. Should include additional aspects such as exploring another css framework, using the asset pipeline for compression, using coffeescript, using haml, using gems to pull in asset collections and installing them correctly, or something else extraordinary.
* 3\. Most standards are followed. Uses the correct bootstrap gem, updates the layout and can use the scaffold generator to created themed models.
* 2\. Standards are attempted. Bootstrap is included in the public folder or an assets folder. Student uses SCSS.

### Section 7

* Be able to create and edit migrations
* Be able to CRUD a model and see its attributes in the database

* 4\. All standards are followed. Should include additional aspects such as knowledge of correct AQI methods, use of rake tasks that include models, postgres, a NoSQL database, or something else extraordinary.
* 3\. Most standards are followed. Should be able to explain what's happening, and some basics about SQL such as indexing or joining. Might include some scopes or defaults.
* 2\. Standards are attempted. Project contains migrations and student can use AQI to access models but may not be using anything fancy.

### Section 8

* Be able to create forms using Rails
* Be able to show validation messages in forms

* 4\. All standards are followed. Should include additional aspects such as using other form builders like SimpleForm, generating forms automatically with bootstrap styles, using lambdas for validation.
* 3\. Most standards are followed. Able to create forms and show validation messages.
* 2\. Standards are attempted. Forms are simple or do not use form_for correctly. Validation messages are unstyled or incorrect.

## Chunk 3

### Section 9

* Be able to use authentication
* Be able to use helper functions in views

* 4\. All standards are followed. Should include additional aspects such as using OmniAuth or Devise to hook into an OAuth provider such as Github, a full capybara test suite, or something else extraordinary.
* 3\. Most standards are followed. Authentication is working correctly and the user model is written to the database. Sessions are being used correctly. Unit tests are present and correct but a whole capybara suite may not be present.
* 2\. Standards are attempted. Authentication is working but tests are missing or there is no evidence of using helpers.

### Section 10

* Understand authorization vs authentication
* Be able to CRUD a model through the controller without a scaffold

* 4\. All standards are followed. Should include additional aspects such as
* 3\. Most standards are followed.
* 2\. Standards are attempted.

### Section 11

* Memorize the steps to create a relationship between two models
* Understand what a `join` is in SQL

* 4\. All standards are followed. Should include additional aspects such as
* 3\. Most standards are followed.
* 2\. Standards are attempted.

### Section 12

* Be able to respond to js requests from controllers
* Memorize the common functions from the ActiveRecord Query Interface

* 4\. All standards are followed. Should include additional aspects such as
* 3\. Most standards are followed.
* 2\. Standards are attempted.