# To Microservices or to Not

## The back story

By now everyone has talked about and thought about moving to Microservices. Its the new kid on the block that everyone whats to move to. Like all new things everyone is thinking it will solve every problem that your project has. Well I am drinking the juice. Over the next few weeks I will be trying to work through how I can take my 5 year old monolithic .NET application and move it to the new age of microservices. I will be making up a new application but the structure of the project will try to mimic.

## The Why

Like everything I needed a why for doing this. Yes, the monolithic app works, it has been for 5 year. Yes, I could keep pushing code into the application and everything would be fine but I was given the opening to rebuild the application and why not try something the could really change how my company builds application. Lets break down some of the issues we have. First, there are many different components of the application. We have a CMS, admin and user accounts, the user accounts have many components to them, a few different data lookup sections out side of the CMS and a few different integrations with other application.