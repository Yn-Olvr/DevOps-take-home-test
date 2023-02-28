# DevOps-take-home-test
In this exercise, we assume that we are working on one node and we will be creating two deployments with a horizontal pod scaler each. We would need to create a service in order to render our application accessible on the web.
Also assuming we already have a databse, we will not create one here but if we were using a database say mysql, our docker image would built to go fetch the data we want for each container.
We could also use volumes to persist data but we are not going to do that here as we are keeping the exercise basic.

Answers to questions 1-3 are in the yml files



answer #4: A role-based access control can be used to limit usage by certain people

Bonus:
 To apply the configs to multiple environments, we need to use config maps so we can change the variables all the time without changing our definition file.
 We could use metrics for request duration.
