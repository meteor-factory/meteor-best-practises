# Project Setup

NB: Replace project-name anywhere in text with current project name.


### Step 1: Repo & Meteor-starter

1. Create repository for project.
⋅⋅⋅Repository for the project should be created with the name of the project under the meteorfactory organisation.
⋅⋅⋅In the case where client decides already has repo created, that would be the repository to be used. 
⋅⋅⋅So for a project called 'don-lobster', a repo would be created for it under meteorfactory like so: meteor-factory/don-lobster

2. Clone repo to local machine.

3. Clone [meteor-starter](https://github.com/yogiben/meteor-starter) into the repo folder and rename to 'app'

4. Delete the .git folder in the 'app' folder

5. Commit as 'initial commit' and push to origin master


### Step 2: Accounts

1. Create a gmail account for the project.
⋅⋅⋅Emails should look like so: developers.project-name@gmail.com
⋅⋅⋅When done. Create a 'credentials' heading if it doesn't exist in the project's repo readme and record the email details there

2. Create a modulus account with the email created above.
⋅⋅⋅Record credentials details in the credentials section of the project's readme

3. Create an organisation for the project on modulus
⋅⋅⋅You would be required for an email when creating the organisation. Email to use should look like so: organisation.project-name@gmail.com.
⋅⋅⋅Organisation names should look like so: project-name-organisation

4. Create two databases that belong to the project-name-organisation
⋅⋅⋅These two databases would be for staging and production and should have the names 'project-name-stage' and 'project-name' respectively.
⋅⋅⋅NB: The production database user. password should be a strong password.

5. Create two projects that belong to the project-name-organisation
⋅⋅⋅These two projects represent staging and production and should have the names 'project-name-stage' and 'project-name' respectively.
⋅⋅⋅Add databases to respective projects through the administration menu item of the projects and do the neccesary configurations as needed.
⋅⋅⋅NB: Make sure the 'project-name-stage' database is mapped to the 'project-name-stage' project and likewise the 'project-name' project.


### Step 3: Deployment

On your local machine, logon to modulus with the new created modulus credentials and deploy app to staging and production.
