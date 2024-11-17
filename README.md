# Integrated-CI-CD-pipeline-with-Github-Jenkins-and-WebEx-notifications
Objective: Create an automated CI/CD pipeline that builds and tests code committed to GitHub, with build status notifications sent to a WebEx space.

Requirements

1. A GitHub repository
2. Jenkins running in a Docker container
3. ngrok for exposing local Jenkins to the internet
4. A WebEx bot for receiving notifications

Tasks

1. Set up a GitHub repository with simple Python code. It should have tests for the Python code. You will commit the code to your repo from your local machine.
2. Configure a webhook in the GitHub repository settings to listen to commits.
3. Install and run Jenkins in a Docker container on your local machine.
4. Use ngrok to expose your local Jenkins to the internet.
5. Configure Jenkins:
   - Install necessary plugins
   - Set up build steps and GitHub webhook trigger
6. Create a WebEx bot and configure it to receive notifications.
7. Integrate the WebEx bot with Jenkins for build notifications.
8. Test the entire pipeline to ensure it works as expected: Commit code > Code committed on GitHub > Webhook on GitHub sends event to Jenkins through ngrok > Jenkins triggers a build > Jenkins notifies you though a message in your WebEx space
