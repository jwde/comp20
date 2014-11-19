        README
        Assignment 3: Where in the World...
        By: Jay DeStories

1.) What has been implemented
        An express-js server script which responds to four types of requests:
        POST to /sendLocation
                Client posts three parameters, login, lat, and lng. If all are
        properly passed, they, along with a timestamp, will be stored in a
        database. If the parameters are passed properly, a JSON string with an
        empty array of characters and a students array populated with the last
        100 check-ins will be returned.

        GET to /locations.json with a login parameter
                ex. .../locations.json?login=name
                Client performs a GET with a login query, which returns an
        array of the last 100 check-ins by the specified login.

        GET to /
                Client performs a GET at the root and receives a webpage which
        displays all check-ins made to the server sorted from most recent to
        least recent.

        GET to /redline.json
                Client performs a GET to /redline.json and receives a live
        version of the data at http://developer.mbta.com/lib/rthr/red.json
        Since this server enables CORS, this gets around the lack of CORS
        on the mbta server.

2.) Collaboration
        I did not collaborate with anyone on this assignment.

3.) Time spent
        I spent approximately 4 hours on this assignment.
