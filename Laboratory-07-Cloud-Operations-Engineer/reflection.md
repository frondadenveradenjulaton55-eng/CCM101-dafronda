# Mission Reflection

During this laboratory activity, I learned that keeping a cloud application running is not only about making sure that the container starts successfully. I realized that the resources of the host server also need to be checked because containers depend on the available CPU, memory, and disk space. If these resources become limited, the application can experience performance problems even when the container appears to be working normally. Checking the server's condition helps identify possible resource issues before they affect the application.

I also learned how the `docker logs` command can help when investigating application problems. If a user reports that they cannot log into a web application, the logs can provide information about requests, errors, and other events inside the container. Instead of only guessing what caused the problem, I can use the recorded information to help find the possible cause.

The activity also helped me understand the difference between logs and metrics. Logs contain records of events that happen in an application, while metrics provide numerical information about system performance. CPU percentage, memory usage, and network activity are examples of metrics that can be used to check how a container is performing. I learned that both logs and metrics are useful because they provide different information about the condition of an application.

For large companies that manage thousands of containers, monitoring tools such as Prometheus and Grafana can help collect and display information from many systems. Prometheus can collect metrics, while Grafana can present the information through dashboards. This makes it easier for engineers to monitor a large number of containers and identify unusual resource usage.

Overall, this activity gave me more experience with Linux and Docker. I became more familiar with `free`, `df`, `top`, `curl`, `docker logs`, and `docker stats`. I learned that troubleshooting should be based on actual information from the system rather than simply guessing what caused a problem.
