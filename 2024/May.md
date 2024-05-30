# 30th May
## Speed up your Docker builds with –cache-from
https://lipanski.com/posts/speed-up-your-docker-builds-with-cache-from

An article explaining the different ways we can use cache to speed up Docker image build process.

# 29th May

## Cheat sheet on Docker image best practices
https://lipanski.com/posts/dockerfile-ruby-best-practices

A great article on some of the best practices for Docker images

## Migrating a Trillion Entries of Uber’s Ledger Data from DynamoDB to LedgerStore
https://www.uber.com/en-IN/blog/migrating-from-dynamodb-to-ledgerstore/

Moving from one data store to another, the challenge of high volume data and how to ensure the new data 
is not corrupted. 
# 24th May

## Building a cost-effective logging platform using Clickhouse for petabyte scale
https://blog.zomato.com/building-a-cost-effective-logging-platform-using-clickhouse-for-petabyte-scale

A great article showcasing how Zomato handled their huge logging requirement and how Clickhouse helped them.

## Canva talking about how they saved a lot with S3 tier pricing
https://www.canva.dev/blog/engineering/optimising-s3-savings/

A great article talking about the AWS storage analytics and how Canva was able to save a lot on their storage cost.

# 21st May
## How Canva solved the problem of counting billions
https://www.canva.dev/blog/engineering/scaling-to-count-billions

Very detailed article on how Canva faced certain problems at scale and how they solved the problem.
It gives a great idea about how the engineering team iterated over the problem and considered different
aspects before coming to a final conclusion.

# 19th May
## Why choose boring tech for long-running projects
https://backpackforlaravel.com/articles/opinions/choose-boring-technology-for-long-term-projects

When we are doing side projects, we can leverage using new tech. However, when it comes to a long-running project, it's important to 
note that once a decision is made, it will last for a long time. And hence, we should not be emotional about these things. And should
not do it just because others are doing it. 


## What's new with PHP 8.4
https://laravel-news.com/php-8-4-0

PHP has been evolving significantly since PHP 7.x and the latest one due around end of November is coming with some 
great improvements which I am really excited about.

# 18th May
## Building a notification system and the APIs
https://www.notificationapi.com/blog/notification-service-design-with-architectural-diagrams

A detailed article on how the APIs should be when creating a Notification system.

# 16th May

## Working on side projects - a reflection 
https://aschmelyun.com/blog/the-crippling-problem-of-being-able-to-build-whatever-you-want/

A great article articulating the advantages, dis-advantages of working on our app ideas
and how we can set some priorities to it.

## Delegateed type pattern - Timeline table for Post and comment
https://mateusguimaraes.com/posts/the-delegated-type-pattern-and-multi-table-inheritance

This is an interesting approach when we need to show different types of entities in one place. Like showing Posts and comments
in a timeline would mean we will have to query and merge and play around with stuff. 
This approach shows something simple.

# 15th May
## Scaling Laravel to 100M+ jobs and 30,000 requests/sec
https://mateusguimaraes.com/posts/scaling-laravel

A great article on how they tackled the problem of handling multiple jobs at scale.

# 12th May
## Handling scale for notifications by Razorpay
https://engineering.razorpay.com/how-razorpays-notification-service-handles-increasing-load-f787623a490f

A great article describing how Razorpay handled the problem of scale for their notification service and the different 
strategies that they implemented to handle the problem of scaling.

# 11th May

## Great article on Strategy pattern
https://ashallendesign.co.uk/blog/using-the-strategy-pattern-in-laravel

I like to play with different patterns of code and try to understand what pattern is good for what kind of situations.
This article does the same.

## Running Sonarqube to scan code using Docker
https://dev.to/tacianosilva/running-a-sonarqube-server-and-client-with-docker-7bk

This article very nicely explains how we can set up Sonarqube to scan code using Docker.
Additionally, this GitHub code is what I have used to run the sonarqube container
https://github.com/emad-zaamout/SonarQube-Dockerized

# 9th May
## Docker profiles to manage multiple environments
https://collabnix.com/leveraging-compose-profiles-for-dev-prod-test-and-staging-environments/

This article talks about the use of Docker profiles and how it can help us manage our dev, test, and prod environments better. 
It helps us manage our composer file better because duplication can be reduced significantly.
https://collabnix.com/leveraging-compose-profiles-for-dev-prod-test-and-staging-environments/
https://docs.docker.com/compose/profiles/

# 8th May
## Native PHP support for Windows
https://laravel-news.com/nativephp-windows-builds

Now this is interesting. Building apps with Electron was fun. However, when I can do that in PHP, it's going to be next level. 
Now the overall framework looks quite matured and so it makes sense to look at some serious apps.

# 7th May

## Automatic Re-hashing password in Laravel with config
https://securinglaravel.com/security-tip-laravel-11s-automatic

This article shows how we can configure the hasing mechanism so that it re-hash the password of users.
With the increase power of computers, it becomes important that the rounds of hashing are increased from time to time.

## The conditional trait
https://ashallendesign.co.uk/blog/laravel-conditionable-trait

I like the when method that we can run on our queries. I find it more readable. 

And this conditional trait is something that I came to know today. And, I am quite confident I will bring this into my workflow. 

# 6th May

## Understanding Contextual binding and how we can use that for Inversion of Control
https://qirolab.com/posts/unveiling-laravels-service-container-and-dependency-injection-a-recipe-for-maintainable-applications
https://dev.to/carlomigueldy/laravel-inversion-of-control-implementation-using-contextual-binding-31cj

The first article talks briefly about how the Laravel's contextual binding can be used to inject a different class for the same interface being used by different controllers / events etc.
It was not getting clear at first how to do that with a Controller and an Interface. Later, going through the second article, things became clear. 
Now, I am going to create a video for this.

## Optimizing PHP applications for performance
https://mateusguimaraes.com/posts/optimizing-php-applications-for-performance

The second article that I read was about the Performance tweak that we can to in PHP-FPM so that we are able to get better results. The default config is a very safe config. 
The article is written in great details. 

As next steps, I am going to work my DevOps team to do some benchmark and then come up the config that we can use. 
Benchmark steps
1. Look at the default req/min using Apache AB
2. Look at the req/min with more workers
3. Look at the req/min after adding Opcache

This will help understand exactly what is the difference by introducing changes one at a time and their impact.
