# Week 1 — App Containerization
## Required Homework
  
This week we were tasked with learning how to use containers to isolate the instance that will be running our application.
I reviewed the instructional video and completed the tasks for this week
While completing the docker files my github instance crashed and was very discouraged. I stopped for a couple days and came back. 
I was able to figure out how to return to a previous session. (Then i watched your video about commiting code) I wish i had seen that video earlier. 
I was able to complete the containers but had to troubleshoot many syntax errors along the way.


## Computers do what you tell them to do , not what you want them to do!

After completing the initial instruction i moved on to the notification feature. This is where i ran into my first problem.
I am so thankful that most of the time an error is going to tell your where to look. Line 69 in app.py has a problem.

![Indentation Error](/journal/assets/apperror.JPG)

> While very helpful the red squiggle lines dont always show up initially.

![Found Error](/journal/assets/apperror2.JPG)

Next we moved to the Front-End Notification Configuration. When I checked my work the page was completely blank!

![CRUDDUR Failure](/journal/assets/apperror4.JPG)

This one almost had me rage quit after i found what it was. You instructed us to put in some test data and change some text. 
I forgot to place a comma between the notifications strings.

![Syntax Hell](/journal/assets/apperror3.JPG)

Added a comma and success!

![Happy Days](/journal/assets/appsuccess.JPG)

With notifications finally finished I moved on to adding the DynamoDB services.
This was not met with immediate success, as I had placed the volume one level deep and got the following when starting the docker container

![Volume Error](/journal/assets/apperror5.JPG)


