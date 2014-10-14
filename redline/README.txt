        README
        Lab: Where's the Train (MBTA Red Line)?
        By: Jay DeStories (jdesto01)

1.)
The page renders a google map and attempts to load the current locations of
red line trains from a developer API from the MBTA.

The page cannot load locations of trains because loading the MBTA API violates
the javascript same-origin policy.

This can be circumvented using jsonp or a proxy, but doing so would violate
the assignment specification, which states that the task must be completed
in client-side javascript and must use XMLHttpRequest.

It would be possible to request the real-time data from the MBTA using
XMLHttpRequest if and only if the MBTA API allowed cross-origin
resource sharing.

Therefore, the assignment does not meet the specifications in that it cannot
load the locations of the red line trains.

2.)
I have not collaborated with anyone on this assignment.

3.)
I have spent approximately 1 hour completing this assignment.
