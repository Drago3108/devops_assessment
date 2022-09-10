# devops_assessment

Q1,Q2.

Clone the Git repository using the below github url.

https://github.com/dhamodaranv/devops_assessment.git

once clone the repository build the docker using the Docker file

Command for docker image build:  docker build -t api .

Now run the Docker container the api running inside container is 3000. if you wants to access outside world you  have to do the port mapping
docker run -it -p 8089:3000 api
now you can be able to access using URL:  http://<dockerhost>:<hostport>/employee - This is from all object if you wants to get particular id details you have to use
below mentioned url

All Object - URL: http://<dockerhost>:<hostport>/employee
Particular Object - URL:http://<dockerhost>:<hostport>/employee/empid=1 #here the empid from 1 to 10.

Q3.

You have to install  Plugins.
1.credentials
2. docker pipeline

CI/CD pipeline script attached in jenkins file you have to change the  jenkins dockerhub credentials id, thes id may looks little bit long because forgot to give name during the
credentials store in jenkins.


