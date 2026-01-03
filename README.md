# config-files
## to update the env in every service
- localhost:8005/actuator/refresh

## to update all the configs via queue
- docker run -it --name rabbitmq -p15672:15672 -p5672:5672 rabbitmq:3.12-management
- localhost:8888/actuator/busrefresh
