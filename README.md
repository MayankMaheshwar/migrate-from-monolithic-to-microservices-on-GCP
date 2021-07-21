# migrate-from-monolithic-to-microservices-on-GCP

Start by breaking the monolith into three microservices, one at a time. The microservices include, Orders, Products, and Frontend. Build a Docker image for each microservice using Cloud Build, then deploy and expose the microservices on Google Kubernetes Engine (GKE) with a Kubernetes service type LoadBalancer. You will do this for each service while simultaneously refactoring them out of the monolith. During the process you will have both the monolith and the microservices running until the very end when you are able to delete the monolith.

