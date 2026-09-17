# Mission Reflection

This laboratory activity helped me understand how containers are different from traditional Virtual Machines. A Virtual Machine requires a complete guest operating system, so starting and setting it up usually takes more time and resources. In comparison, a Docker container shares the host operating system kernel and can start in only a few seconds. Because of this, containers are useful for applications that need quick deployment and efficient resource usage.

I learned that port mapping is important when running a web server inside a container. The command `-p 8080:80` connects port 8080 on the host machine to port 80 inside the container. Nginx uses port 80 inside the container, while users can access it through port 8080 on the host. Without port mapping, the web server may not be accessible through the host's selected port.

I also learned that using `docker rm` removes a stopped container from Docker. The container itself is deleted, including its writable container layer and any data stored only inside that layer. This taught me that important data should be stored using appropriate storage methods, such as volumes, when it needs to remain available after a container is removed.

Containerization can improve cooperation between software developers and IT operations teams. Developers can package an application and its dependencies into a container, while operations teams can run the same container in different environments. This supports DevOps practices because it makes deployment more consistent and reduces problems caused by differences between development and production systems.

My GitHub portfolio is also improving because I am adding more technical documentation and practical laboratory evidence. In this activity, I documented Docker commands, container deployment, lifecycle management, and the differences between VMs and containers. I also included screenshots to show the actual results of my work. This makes my portfolio more organized and demonstrates my growing knowledge of cloud computing and cloud-native technologies.
