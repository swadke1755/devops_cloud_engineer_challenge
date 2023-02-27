## Degreed Technical Challenge - DevOps Team (Cloud Engineer)

Welcome to the DevOps Cloud Engineer technical Challenge, we are glad to have you onboard and collaborating with us. For the time being we have opened this a little bit with using both AWS and Azure cloud providers. Depending on familiarity with Kubernetes, we would expect this exercise to take a few hours. If you have any questions or feedback please let us know.

### Steps
 - Clone this repository to your own Github (private recommended)
 - Perform part 1 and 2 of this task
 - Invite and share with us for the review

### Outcome

The total outcome for this challenge should be 
 - A Git repo with the work you have taken
 - A terraform template which could create a basic AKS Cluster
 - A deployment of an application with its own database (GoLang App and Postgres)
 - A Live endpoint with the application exposed publically

## Part One - Terraform an AKS Kubernetes Cluster

In part one of this, we want to see a kubernetes cluster created from Infrastructure as Code using Azure or AWS (Azure preferred) and AKS/ECK Technology using terraform. We should be able to change some configuration and be able to use the template to also spin up and tear down a cluster. This cluster should have clear naming conventions and needs to be a linux only cluster.

## Part Two - Deploy an Application which is publically accessible

In part two, we want to push a deployment to this kubernetes cluster and expose it to the world. For this challenge, we would like to see a Container application with a postgres DB deployed to the cluster you have provisioned as apart of part 1. The service we would like to be deployed can find the repo [here] (https://github.com/remast/gobuff_realworld_example_app), the container is also attatched in the packages section of the example repo aswell as a helpful compose file to get started.

You can use any public docker images and any tooling you see fit, as long as the deployment templates are in the codebase. At the end of this step we would expect to see an endpoint live with an encrypted https entrypoint as a bonus.

## Reflect

It's also good at this point to reflect on ways that this could be enhanced for scalability, readibility, security and continuous deployments. What other steps could you take to make this an enterprise grade implementation (there may be some limitations for the nature of this challenge)?