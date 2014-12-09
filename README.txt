    README -- COMP 20 developent repo
    By Jay DeStories

Purpose:
    This git repository stores all of my individual project work for
COMP 20 at tufts.

Favorite Assignment:
    My favorite assignment over the course of the semeseter was the
marauder's map. I actually misinterpreted the instructions and created
a polling system which updated all locations in real-time on the map. It
was some extra effort, but I found it very interesting and I was able to
learn much more about javascript-- particularly with respect to closures.

Growth:
    At the beginning of the course I had zero web development experience.
I am now capable of building relatively complex dynamic site with things
like templating and databases. I am also more aware of security issues both
from a developer's perspective and a user's perspective.

Most important thing from the course:
    The most important thing I learned from this course is to never trust
user input. In class, we talked about security problems like cross-site-scripting
and arbitrary server-side code execution through eval. We were able to test
each other's code for security holes. I also inadvertently found a security
problem while doing the marauder's map. The assignment was intended to get
location only once, but my code updated in real-time, so many more requests
were sent, and my information was stored in the server many times. When I
hooked my own solution up to my server, I saw that I was creating a massive
number of check-ins when the page was left alone. This could of course be
done more easily using curl, but it demonstrates a point-- the server must be
able to check at some point against a malicious user sending too many request.

Topic I would like to explore further:
    I would love to learn more about security. This course only briefly touched
on the topic and I would like to learn more about it both with respect to
web applications and client applications.
