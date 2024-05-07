# 7th May
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
