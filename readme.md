# Justice League API

* In this activity, we will create an API route that returns the superhero name and real name for every member of the DC Comics Justice League.

## Instructions

* Create a file called `app.py` for your Flask app.

* Define a Python dictionary containing the superhero name and real name for each member of the DC Comics Justice League (Superman, Batman, Wonder Woman, Green Lantern, Flash, Aquaman, and Cyborg).

  * we can gather that information here: [Justice League](https://en.wikipedia.org/wiki/Justice_League)

  * we will Only gather the information for the 7 characters listed above.

* Create a **GET** route called `/api/v1.0/justice-league`.

  * Inside of our GET route, create a function called `justice_league` that will use `jsonify` to convert the dictionary of Justice League members to a JSON object and return that data as a request.

* Define a root route `/` that will return the usage statement for your API.

- - -

