# To Microservices or to Not - Part 1

## The back story

By now everyone has talked about and thought about moving to Microservices. Its the new kid on the block that everyone whats to move to. Like all new things everyone is thinking it will solve every problem that your project has. Well I am drinking the juice. Over the next few weeks I will be trying to work through how I can take my 5 year old monolithic .NET application and move it to the new age of microservices. I will be making up a new application but the structure of the project will try to mimic.

## The Why

Like everything I needed a why for doing this. Yes, the monolithic app works, it has been for 5 year. Yes, I could keep pushing code into the application and everything would be fine but I was given the opening to rebuild the application and why not try something the could really change how my company builds application. Lets break down some of the issues we have. First, there are many different components of the application. We have a CMS, admin and user accounts, the user accounts have many components to them, a few different data lookup sections out side of the CMS and a few different integrations with other application. Looking at the different components, how nice would it be to have them completely separate from each other. I could work on them with out even loading the other projects. Deploy with out even building the other applications. Even deploy with out bringing down the whole application. Different teams could work on the different components without relying on the whole project to be running.

## The How

Well, I am not sure. This is my plan, each week I am going to build a part of the application. Some weeks might be more DevOps and other will be more in the programming world. I will try to work through my ideas and create a guild of how I am going to build the application for my company. I will post some type of road map of why my overall idea is so I somewhat have a game plain.

## Results

I am hoping by the end of the this I will have an example and walk through of how I would build and deploy a Microservices application. I will have the road map out soon and link to it here.  Wish me luck, I am sure I will need it.