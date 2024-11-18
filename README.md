# DataDog-Tutorial
- cloud-based monitoring and observability platform (Cloud Monitoring as a service)
- APM monitoring (Application Performance Monitoring using open tracing and error tracking)
- RUM (Real user Monitoring - Tracks end-user interactions with web applications, helping you understand user experience and performance issues)
- Log monitoring 
- particularly popular for monitoring cloud-native, microservices, and containerized applications
- Setup alerting and dashboards

# How it works
- For APM monitoring an application code changes are made in nginx or tomcat or whatever we want to monitor which creates an agent within the application
- This agent then sends metrics to datadog agent which is then send to datadog cloud platform


# Setting Up
- Create a datadog account
- It will ask for details then sources you want to monitor
- after that select your OS and it will give a command with a key to install datadog-agent
```
DD_API_KEY=f941f7d37aad5df80eb995e8216d0e16 DD_SITE="us5.datadoghq.com" bash -c "$(curl -L https://install.datadoghq.com/scripts/install_script_agent7.sh)"
```
- The agent will automatically connect to your datadog cloud account and you will be prompted with a message "Agent is running successfully"
- After that click on finish and youll be prompted to your dashboard

# Extra
- Synthetic Monitoring, also known as synthetic testing or active monitoring, is a technique used to monitor the performance and availability of applications, websites, and APIs by simulating user interactions. Instead of relying on real user data, it involves running scripted tests (synthetic tests) at regular intervals from different locations around the world to check the health and performance of your services.

# Basics types of monitoring / Observability (In Bracket is the name on Datadog Dashboard)
- Infra (Infrastructure)
- Logs (Logs)
- Trace (APM / Synthetic Monitoring)









