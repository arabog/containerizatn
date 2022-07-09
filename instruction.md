https://www.udacity.com/course/full-stack-foundations--ud088

Instructions
Navigate to the Lesson-3-Containerization directory in the Github repo.
Check out the pre-built Flask app that will be containerized. If you haven't used Flask before, you can check out this free Udacity course, or check out Flask's documentation.
Look through the Dockerfile for the container (also included below).
Look through the Makefile to be run within the container.
The only real new thing so far is the inclusion of the Flask app - you got familiar with Dockerfiles and Makefiles in the Using Docker Format Containers Lesson, as well as how to create them. There are some additional steps we still want to go through to get the App up and running, but the important thing to notice here is that it doesn't necessarily matter what the application itself is, you can still easily containerize it.

Q: What is the advantage in building Dockerfiles from other Dockerfiles?
Building a Dockerfile from another Dockerfile lets you re-use high-quality work.

https://docs.docker.com/get-started/02_our_app/

<!-- /Desktop/local_env/Containerization$  -->
<!-- start -->
make start-api

Hint
To run this code you will need Docker installed. Remember the suggestion about using AWS Cloud9? It has Docker already installed for you. This may be a time to try this out and see if this workflow simplifies the way you work.

environment/containerizatn_docker
create a virtual env and activate(mking it automatic)
python3 -m venv ~/.containerizatn

source ~/.containerizatn/bin/activate

which python3

deactivate d virutal env:
deactivate

pwd

cr8 alias:
nano ~/.bashrc

add:
alias containerizatn="cd /home/ec2-user/environment/containerizatn && source ~/.containerizatn/bin/activate"

<!--voclabs:~/environment/containerizatn (main) $ -->
source ~/.bashrc

cd /tmp

type:
alias

type:
containerizatn
<!--dse automatically activate virtual env-->

make install

make lint

push to git

