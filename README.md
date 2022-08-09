# Deploy to Surge
In this guide, you will learn how to deploy your TezJs Site to Vercel Hosting.

## Deployed Url:
http://tezjs-deploy.surge.sh

## Preparing for deployment:
Run the following command to create tezjs project:
  - `npm create tez@latest`
  - `cd [projectName]`
  - `npm install` - for installing the required dependencies
  - `npm run build` - for build the project
  - `npm run dev` - for run the project

## Pre-requisites:
  - Surge cli install `npm install --global surge`
  - Surge account

## Deploying your Tezjs project to Surge:
1. Run the below command and provide the email and password for initiate
```
surge
```
2. Give the build folder path like `C:\\[folderPath]\dist`
3. Give the domain name you want like `[your project name].surge.sh`

## References:
- [Surge Docs](https://surge.sh/)
- [Getting Started with Surge](https://surge.sh/help/getting-started-with-surge)
- [Deploy Static Side to Surge](https://www.howtogeek.com/devops/how-to-deploy-static-websites-for-free-with-surge-sh/)
