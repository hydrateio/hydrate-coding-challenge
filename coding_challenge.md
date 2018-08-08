Coding Challenge Guidelines
===========================

If you don't have code to share, you can work on our coding challenge described
below. 

Please organize, design, test, document and deploy your code as if it were
going into production, then send us a link to the hosted repository (e.g.
Github, Bitbucket...).

Functional spec
---------------

Prototype **one** of the following projects:

1. Departure Times
2. SF Movies
3. Food Trucks

The UX/UI is totally up to you. If you like, get creative and add additional
features a user might find useful!

### Departure Times

Create a service that gives real-time departure time for public transportation
(use freely available public API). The app should geolocalize the user.

Here are some examples of freely available data:

* [511](http://511.org/developer-resources_transit-api.asp) (San Francisco)
* [Nextbus](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) (San
  Francisco)
* [Transport for London Unified API](https://api.tfl.gov.uk/) (London)

### SF Movies

Create a service that shows on a map where movies have been filmed in San
Francisco. The user should be able to filter the view using autocompletion
search.

The data is available on [DataSF](http://www.datasf.org/): [Film
Locations](https://data.sfgov.org/Arts-Culture-and-Recreation-/Film-Locations-in-San-Francisco/yitu-d5am).

### Food Trucks

Create a service that tells the user what types of food trucks might be found
near a specific location on a map.

The data is available on [DataSF](http://www.datasf.org/): [Food
Trucks](https://data.sfgov.org/Permitting/Mobile-Food-Facility-Permit/rqzj-sfat)

Technical spec
--------------

The architecture will be split between a back-end and a web front-end. On the back-end, expose a graphql server that resolves against a public API. On the front-end, build out a react-front end that consumes that graph service. Feel free to use any other technologies provided that the general client/service architecture is respected.

Choose **one** of the following technical tracks that best suits your skillset:

1. **Full-stack**: include both front-end and back-end.
2. **Back-end track**: include a minimal front-end (e.g. a static view or API
   docs). Write, document and test your API as if it will be used by other
   services.
3. **Front-end track**: include a minimal back-end, or use one of several graphql-as-a-service options. Focus on making the interface as polished as possible.

Host it!
--------

When you’re done, host it somewhere (e.g. on Amazon EC2, Heroku, Google AppEngine, etc.). If time constraints limit ability to spin up both backend and static front-end, provide documentation for spinning up the app locally.

How will we review?
-------------------

[Guidelines can be found here](https://github.com/uber/coding-challenge-tools/blob/master/README.md)
