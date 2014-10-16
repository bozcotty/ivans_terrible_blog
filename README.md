# Ivan the Terabyte Blog. An exercise in Performance with Rails

## Here's a list of performance enhancing tasks I tried to make Ivan's Blog
more useable:
- added Bullet gem to be notified of N+1 errors
- page caching
- using a different server (Puma)
- used some show/hide with jquery to hide comments and replies with a toggle button
- eager loading of comments under posts and replies under comments
- pagination with will_paginate

## Here are my test results of production site on Heroku at loadimpact.com:
- http://loadimpact.com/test/view/1822547
- (app name at heroku: afternoon-falls-1374.herokuapp.com/)



