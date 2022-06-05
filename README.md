**Deploying static website in EC2 using Jenkins 

Technologies used:
   Git
   Github
   AWS EC2
   Jenkins

Project Description:
   The project is aimed at automatic deployment of a static website in the AWS EC2 instance using Jenkins for CI/CD  
   For CI I used git and GitHub as version control systems and Jenkins with maven for the build.  
   For the CD I used Jenkins to get the source file from GitHub to deploy 
   in the AWS EC2 instance. 

Steps Involved:
   Creating the git repository in local and adding source files
   Creating new project in github and adding the project URL as remote branch
   Generating the SSH keys using SSH-keygen and adding public key to github
   Committing the local changes to remote repository
   Creating two EC2 instances one is for web server and another is for Jenkins server
   Creating a new jenkins maven prodject and adding git repository URL with git webhooks and pointing target EC2 instance
   If EC2 runs successfully checking the files in Github 
   Checking the deployment process by commiting a new changes from local git repo and checking if changes are reflected in the EC2.
  
  	

