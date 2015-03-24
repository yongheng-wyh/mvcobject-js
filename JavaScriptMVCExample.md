# Introduction #

Chances are, you've read all about the Model View Controller pattern but want a real-world example - here you go:

Below we'll build a basic chat application that will illustrate the usefulness of the MVC pattern. We'll be using mvcobject-js to make life easier.

## Define our application's components ##
  * **Model** - Takes care of all back-end data. Receives messages, broadcasts messages, registers new users when they join.
  * **View** - Handles all display logic. Displays new messages, gives our users the interface to write new messages.
  * **Controller** - Facilitates communication between the Model and the View. Interprets actions from users and passes them to the Model and/or the View.