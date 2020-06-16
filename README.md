# BDP2_mid-term

This is the mid-term BDP2 project

I linked this repo to a dockerHub repo so that as I commit the code my docker container is simultaneously built by dockerHub.
dockerHUb repo --> https://hub.docker.com/repository/docker/idazucchi/bdp2_midterm

The aim is to extend the jupyter notebook docker to include matplotlib so that I can plot data from the italian covid19 epidemic.

So far:
  - extended the jupyter notebook container to include matplotlib
  - run the image built by dockerHub locally with bind mount to persist data
  docker run -p 8888:8888 -v /home/ubuntu/BDP2_mid-term/work:/home/jovyan/work idazucchi/bdp2_midterm:latest
  - script to produce the graphs

