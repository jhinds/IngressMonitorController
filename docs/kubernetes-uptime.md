# Kubernetes & Uptime

Monitoring uptime is very important; and when using microservices it becomes even more important to ensure all services 
are up and running; and get alerts when they go down. There is nothing worse then your website going down and you hearing 
about it from someone else. When it comes to downtime, every second counts. Uptime is one such service which sends alerts 
when services become unavailable. IngressMonitorController from Stakater automates the management of URL endpoint 
monitors in Uptime using kubernetes events.

## Use Cases / Questions:

- How to monitor microservices deployed on kubernetes/openshift?
- How to have automatic monitoring of kubernetes cluster with Uptime?
- How to ensure that web applications deployed on kubernetes cluster are up and available right now using Uptime?
- How to ensure that when a new web application is deployed its monitored automatically using Uptime?
- How to get notified when a web application, REST API or microservice running on kubernetes become unhealthy or unreachable?
- How to have web URL availability monitoring for applications deployed in Kubernetes using Uptime?
- How to have uptime monitoring for web applications or microservices deployed on kubernetes?
- How to have web application availability monitoring when deployed to kubernetes?
- If something deployed on kubernetes does go down, how to know about it immediately?
- How to get notified by SMS or email if your website is down?
- How to proactively monitor your websites and online services & receive immediate notification when a problem is detected so you can quickly resolve the root cause and prevent potential escalation when deployed on kubernetes?.

IngressMonitorController (IMC) offers exactly these features:

- Automatically create new URL endpoint monitors in Uptime when new applications / services / microservices / REST API's are deployed in Kubernetes
- Automatically update URL endpoint monitors in Uptime when applications / services / microservices / REST API's are changed/updated in Kubernetes
- Automatically delete URL endpoint monitors in Uptime when applications / services / microservices / REST API's are deleted/removed in Kubernetes

## Free Monitoring of Apps Deployed to Kubernetes

Uptime offers  21 day FREE trial; which is really awesome to get started! And with IngressMonitorController its even easier to get started and have free monitors for the services/apps/microservices deployed to Kubernetes.