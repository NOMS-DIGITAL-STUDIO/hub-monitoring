Hub Monitoring
====
Monitoring for the HUB, this use smashing which is forked from Dashing, as Dashing is no longer being maintained.

Currently only setup to monitor CircleCI builds, but its expected other pages will be added.

Local
----
http://localhost:3030/circle

Heroku
----
https://hub-monitor.herokuapp.com/circle

Environment variable required by the application
----
```
CIRCLE_CI_TOKEN - Your Circle CI Token
This is used to call the Rest API on CircleCI.
```

Further Reading on Smashing
----
Check out http://smashing.github.io/ for more information.