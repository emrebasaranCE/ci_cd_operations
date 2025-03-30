# What is CI/CD?

In DevOps, we hear the terms CI and CD a lot but what do they actually mean? Let’s dive deeper into this essential part of modern software development.

## Continuous Integration (CI)

Continuous Integration is a process where we build and run tests on our applications or services. 

    Why do we need this constantly? 
    Can’t we just build and test manually?

Yes, you can but in a company where tens or hundreds of developers contribute to same project, you will get a lot of changes and updates. So for our deployment process to be fast and easily scalable, we use additional tools to help us automate the entire pipeline. While staying up-to-date with code itself, we also create automated test systems for our codes, this way we can check failures before deploying to production. 

## Continuous Deployment (CD)

CD picks up where CI leaves off.

Once your code is:

- Built
- Tested
- Packaged

In this step we have to deploy this new created application into our product line which might be on-premise or cloud systems. CD tools come into the game right here, they help us to control all of this versioning and server management with ease. 



### Important Note:

While creating this automated architecture you have to be cautious, because everything you make could have catastrophic effects on servers and deployments. Therefor its important to work in a development environment before deploying to prod.

