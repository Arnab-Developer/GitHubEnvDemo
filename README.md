# GitHub environment demo

This is a demo app to show CI CD with GitHub action and environment.

There are two environments in this repo. 

- Dev
- Prd

CI CD workflow used for this app.

- For pull request to `main` only build.
- When pull request merged in `main` then build and deploy to `Dev` environment.
- When a release has been created then deploy to `Prd` environment.

Deployment to `Prd` environment needs approval.