# Troubleshooting
This section will state some common problems when new web development learner will encounter. 
We listed out five different common problems in this section

## Debugging
Logs are the first place to look when your users report seeing the Heroku error pages. Use the heroku logs command to view the unified event stream for your application and the state of the Heroku platform components supporting your application.

## H11 - Backlog too deep
When HTTP requests arrive faster than your application can process them, they can form a large backlog on a number of routers. When the backlog on a particular router passes a threshold, the router determines that your application isn’t keeping up with its incoming request volume. You’ll see an H11 error for each incoming request as long as the backlog is over this size.

## H12 - Request timeout
An HTTP request took longer than 30 seconds to complete. Therefore, we recieve an H12 error instead of waiting for it to load.

## H24 - Forced close
The routing node serving this request was either shutdown for maintenance or terminated before the request completed.
## H81 - Blank App
No code has been pushed to this application. To get rid of this message you need to do one deploy. This is not an error, but we give it a code for the sake of completeness.
