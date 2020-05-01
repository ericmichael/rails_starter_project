# Rails Starter Project

---

### Getting started

1. Clone the project.
2. Run `bundle install` to install the required dependencies.

### What's in the box?

This project is pre-configured for use with the following gems that you will need to fulfill the requirements, as well as some other optional features. *(The following links take you to helpful resources related to each gem.)*

- [RSpec](https://relishapp.com/rspec/rspec-expectations/docs/built-in-matchers) : test framework for testing source code through multiple types of tests

- [Cucumber](https://cucumber.io/docs/guides/10-minute-tutorial/) : test framework for acceptance testing

- [Devise](https://github.com/heartcombo/devise) : a complete MVC authentication solution

- [Factory Bot](https://devhints.io/factory_bot) : tool for building factories to create model fixtures

- [SimpleCov](https://github.com/colszowka/simplecov) : a code coverage analysis tool

- [Bootstrap](https://getbootstrap.com/) : toolkit with extensive prebuilt HTML/CSS/JS components and more

> All of these gems are ready to use, <u>except</u> for Devise. It has only been configured within the project settings - you must execute the necessary commands to install the Devise components.

### Project Requirements

**Build a to-do list app.**

- As a user of this app, you should be able to create to-do items which you can then mark as complete (or incomplete). You should also be able to edit these items, as well as delete them.
- Remember that you should only be able to access your own to-do list, and <u>never</u> anyone else's.

- Use Cucumber tests to ensure that you implement these features:
  - User should be able to sign up an account.
  - User should be able to log in and out of the app.
  - User should be able to view their to-do list.
  - User should be able to create a to-do item.
  - User should be able to edit a to-do item.
  - User should be able to mark an incomplete to-do item as complete.
  - User should be able to mark a complete to-do item as incomplete.
  - User should be able to delete a to-do item.

### Example

![Sample homepage when signed in](https://github.com/UTRGV-SOM/rails_starter_project/blob/master/rails_starter_project%20example.PNG)