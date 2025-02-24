# Serverless-Build-Platform

Resource:
https://vercel.com/blog/behind-the-scenes-of-vercels-infrastructure

## Architecture
**1. Upload Service**: Upload the user code to the system

**2. Deployment Service**: Build (e.g. convert React to HTML/CSS/JS) and deploy a project (Put the converted files somewhere so other users can access them when hit the website)

**3. Request Handle Service**: Handle the request and return the user with the code.

