# MovieManagementService

## Members
### Names
* DUPUIS MicaÃ«l
* PINNA Maxime

### Emails
* micaeldupuis@live.fr
* max.pinna@hotmail.fr

## Services' description
We have created two services to provide different functionalities around movie management. One is a REST web service and the other is a WS-* (or SOAP) web service.

Our services allow us to manage movies and actors. Indeed, different functionalities have been implemented to manage them. Movies and actors can be added to the services. When these movies and actors are added, they are not linked. However, added actors can be linked to movies by specifying the movie title and the actor's name. Finally, all information about a movie can be retrieved.

In addition, when the user requests information about a movie, the service will also make use of the OMDB api allowing us to retrieve the ranking of the movie concerned.

Furthermore, each movie in the services will include the following information:
* title
* release date
* list of genres
* list of actors playing in the film

Similarly, each actor present in the services will include the following information:
* a name
* the name of its role

## Clients' description
The different clients of the two services created are presented in the form of a graphical application, where the user can navigate between different windows to perform actions on the services.

The user will be able to navigate between the different tabs of the application in order to add films and actors, to link an actor to a film or to display all the information concerning a film. In addition, a form is present in the different tabs, allowing the user to fill in the necessary information. Once the form has been filled in, the user can execute the action concerned by pressing the appropriate button. Finally, the user will be able to observe the response to their request by means of a text box displaying the action carried out in the event of success, and the error made in the event of failure.
