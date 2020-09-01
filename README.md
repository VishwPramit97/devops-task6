# devops-task6
#Task Description:

Deploy your website on kubernetes with the help of Jenkins coding file as follows:

Create container image that's has Jenkins installed using docker file Or You can use the Jenkins Server on RHEL 8/7

When we launch this image, it should automatically starts Jenkins service in the container.

Create a job chain of job 1, job 2, job 3 and job 4 using build pipeline plugin in Jenkins

Job 1 ( Seed Job ) : Pull the GitHub repo automatically when some developers push repo to Github.

The remaining jobs should be written using Groovy language by the developer:

Job 2:

By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code on top of Kubernetes ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )

Expose your pod so that testing team could perform the testing on the pod

Make the data to remain persistent using PVC ( If server collects some data like logs, other user information )

Job 3: Test your app if it is working or not.

Job 4: if app is not working , then send email to developer with error messages and redeploy the application after code is being edited by the developer
