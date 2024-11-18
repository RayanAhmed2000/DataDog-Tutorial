# DataDog-Tutorial
- cloud-based monitoring and observability platform
- APM monitoring (Application Performance Monitoring using open tracing and error tracking)
- RUM (Real user Monitoring - Tracks end-user interactions with web applications, helping you understand user experience and performance issues)
- Log monitoring 
- particularly popular for monitoring cloud-native, microservices, and containerized applications
- Setup alerting and dashboards

# How it works
- For APM monitoring an application code changes are made in nginx or tomcat or whatever we want to monitor which creates an agent within the application
- This agent then sends metrics to datadog agent which is then send to datadog cloud platform
