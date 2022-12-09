# Full Stack Assessment

## Services:
1. frontend: react
2. backend: nextJS || nestJS || nodeJS 
3. queue: kafka
4. database: mysql || others (if required)

## Task description
1. Create a simple input box with number (e.g. 100000) of emails to send and send button in frontend, which calls the backend to trigger the process
2. The request handler should respond with some sort of job id / email sending id right away
3. The request handler adds the job in the Kafka queue
4. Which eventually is picked up by workers to send emails. Note it doesn't need to send the actual email, just write a worker and comment out the last send part
5. Update the user browser with the status of how many emails are sent in near realtime
6. User can close the browser and come back and should be able to see the status of a job

Deliverable:
1. Docker compose to set up the environment
2. Github Repository
3. Readme file how to run

## Deadline:

Please let me know if you have any questions. 
Looking forward to hearing back from you.  

### What should I do when I'm finished?
After you have finished you work push all commits to your repository, and then send us email to inform that app has been finished, also please add following users there:
* raphael.mahiet@eqolux.com

