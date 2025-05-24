# Lab8-Starter
Name: Chakshan Kothakota 

Github Pages URL: 

How are graceful degradation and service workers related?
Service workers are related to graceful degradation in that service workers allow a form of graceful degradation to happen. Consider when a user with poor or spotty internet accesses a site that implements caching with service workers. Instead of having the fetch requests fail when the internet is unstable, the site gracefully degrades to support the user by utilizing whatever data it has stored in the cache. This way the application can support the user as much as much as possible locally instead of breaking down due to failed network requests.

PWA Image:
![pwa](./pwa.png)