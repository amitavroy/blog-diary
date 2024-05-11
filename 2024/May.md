# 11th May
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
