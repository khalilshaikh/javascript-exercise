# Javascript Exercise
The objective is to create an app called 'Stations'. This app will comprise of a listing page of nearby stations with the ability to add a station to a favourites list.

You have half an hour to complete this. We don't expect you to complete the exercise but we do expect you to have an understandable structure, clean code and mindful of others reviewing the code.

There are no restrictions on which frameworks you use to create this app. Feel free to use any single page app framework(s) you feel most comfortable with.

The HTML and CSS has been provided for you which you can choose to use as is or as a guide. For the station and favourites listings the list item templates are within HTML comments.

You will be evaluated on your ability to integrate with a RESTful JSON API including connections/error handling and your ability to structure the app appropriately.

The data will be provided by the [Transport API](https://www.transportapi.com/).

## Technical details

### Getting started
* Fork the project from here: https://github.com/EurostarDigital/javascript-exercise.git

### API

You will need to use the following url to make requests to the Transport API and retrieve the train stations near a given location:

[https://fcc.transportapi.com/v3/](https://fcc.transportapi.com/v3/)

#### Additional details

- **Documentation:** [https://developer.transportapi.com/](https://developer.transportapi.com/)
- **List of end points:** [https://developer.transportapi.com/docs?raml=https://transportapi.com/v3/raml/transportapi.raml](https://developer.transportapi.com/docs?raml=https://transportapi.com/v3/raml/transportapi.raml)

### Favourites

To open the favourites panel (```#favourites-panel```) you need to add a class of ```open```. Toggling this class will show/hide the panel.

* Each station within the list should have a button to add to the list
* If the station is already in the list the add button should be changed so you can remove it
* There should be a list that displays all the favourites
* The stations within the favourites list should have a button to remove

**Have fun!**
