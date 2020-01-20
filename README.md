# AppDynamics Docker Projects

A collection of Docker projects that I built while leading the Sales Enablement and Online Demo teams at AppDynamics. These projects include:

[appdynamics-docker-images](https://github.com/mqprichard/appdynamics-docker-images) Source code for the images published on the [AppDynamics DockerHub](https://hub.docker.com/_/appdynamics) site, which I set up and maintained during my time at AppDYnamics. 

[appdynamics-docker-platform](https://github.com/mqprichard/appdynamics-docker-platform) Docker containers for installing and running the AppDynamics Controller with EUM Server and Analytics support on Centos or Ubuntu base images. These containers allow you to manage an AppDynamics Platform install using Docker, with persistent data storage for the AppDynamics installation and database. This project uses a single-host installation for the AppDynamics Controller and End User Monitoring, with either the embedded or clustered Events Service. This is suitable for small, demonstration installations.

See [AppDynamics Demo Projects](https://github.com/mqprichard/appdynamics-demos/blob/master/README.md) for examples of demo applications I built using Docker and Kubernetes for our sales teams to use.
