# CI CD Jenkins -> AWS

​
Give a brief overview of the project.
​

## Demo

![GIF showing command](https://github.com/waltervoynarovsky/ci-cd-aws/blob/main/images/230125-Gif-for-Nology.gif)
​
Research how you can create Gifs from screen recordings, demo the following:
​
​

## How have you use Jenkins to add Continuous integration with this project?

Code is tested after every commit. If the test is passed, the build is tested for deployment.

### How did you allow Jenkins access to the Github repo?

Copying SSH from github repo to Jenkins.

### How did you get the Github repo to trigger the build?

Added option on Jenkins to allow source code managment and implemented github Webhook. Webhooks can be triggered whenever a variety of actions are performed on a repository or an organization.

## ​

​

## How have you use Jenkins to add Continuous delivery with this project?

We used shell commands to do that. Also gitpublisher to merge branches.

### How did you allow Jenkins access to the EC2 instance?

​By using SSH agent with AWS private key.

### How did you get the CI project to trigger the CD build?

by activating Post-build Actions -> build other projects -> name of the cd project -> triggers only if build is stable

## ​
