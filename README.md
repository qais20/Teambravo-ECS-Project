# CoderCo Assignment 1 - Threat Modeling Tool App on ECS

Built on top of the Threat Composer Tool by Amazon (<https://awslabs.github.io/threat-composer/workspaces/default/dashboard>)

Repo used to deploy the app into AWS whether it's AWS ECS or EKS etc.

## Task/Assignment

- Your task will be to create a Dockerfile for it, push it to ECR.

- Deploy the app on ECS using Terraform.

- Make sure the app is live on `tm.<your-domain>` or `tm.labs.<your-domain>`

- App must use HTTPS. Hosted on ECS. Figure out the rest.

- Add architecture diagram of how the infrastructure is setup. (Use Lucidchart or draw.io or mermaid) You are free to use any diagramming tool.

## Local app setup

```bash
yarn install
yarn build
yarn start
http://localhost:3000/workspaces/default/dashboard

## or
yarn global add serve
serve -s build
```
