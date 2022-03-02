---
layout: post
title: "Spring Blog 3 - GitHub Actions"
date: 2022-03-01 23:45:17 -700
categories: jekyll update
---

## GitHub Actions
Github Actions is a CI/CD platform that automates your build, test, and deployment pipeline. It allows you to create custom software development lifecycle workflows directly in one’s Github repository. The workflows are made up of actions that are executed automatically on certain events.

### Core Components of GitHub Actions 
- Workflow: A workflow is an automated process that runs one or more jobs and can be triggered by an event. They can also be triggered manually or at an assigned schedule. Workflows are defined in the .github/workflows directory using a YAML file.  Users can have multiple workflows in their repository, and each can have a different set of steps. 
- Events: Events are specific activities that trigger a workflow run.
- Jobs: A job is a set of steps in a workflow that operates on the same runner. Steps are executed in order and dependent on each other. 
- Actions:  Actions are combined as steps to create a job. Action helps reduce redundant code in workflow files. You can create your own actions or find ones in GitHub Marketplace. 
  
- Runners: A runner is a server that runs the workflows when it is triggered. Runners can be hosted on GitHub or self-hosted. Github provides Ubuntu Linux, Microsoft Windows, and macOS runners to run workflows. Each workflow operates in a newly-provisioned virtual machine.

### Example Workflow:
1. Create the .github/workflows directory in your repository
2. Inside the .github/workflows/ directory, create a new file (.yml) and add the following code. This is an example of a workflow that I attempted to do for the senior design  (this is to publish the docker image to Docker Hub): 
![Example of a Workflow](/assets/images/example-workflow.png)

3. Commit the new changes and push them to your repository

### To view the workflow’s activity
You are able to view a visualization graph of the run’s progress and view each step’s activity.

1. Go to the main page of the repository on GitHub
2. Under the repository name, click Actions
3. In the left sidebar, click the workflow you want to see
4. Under “Workflows runs”, click the name of the run  you want to see
5. Under Jobs, click the job you want to see
6. View the results of each step

For more information, I use this documentation to learn about [GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#overview).
