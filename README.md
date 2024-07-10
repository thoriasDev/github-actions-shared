# Salesforce CI/CD GitHub Action

This repository contains a GitHub Action to automate the CI/CD process for Salesforce projects. The action is triggered on `workflow_call` and performs a series of steps to test and validate the changes using a Salesforce scratch org. It also creates front-door link and comments the link on the PR that triggered this GitHub action.