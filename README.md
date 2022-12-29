# My DolphinScheduler docker swarm stack
Based on original repo https://github.com/apache/dolphinscheduler

Deploy:

```$ docker stack deploy -c docker-stack.yml dolphinscheduler```

on Mac M1:

pull all images and run:

```docker stack deploy -c docker-stack.yml dolphinscheduler --resolve-image "never"```