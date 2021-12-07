### Jira настройка

Поднятие Jira и активации лицензии:
```
# host: docker-compose up -d
# host: docker-compose exec jira /bin/bash
# jira: java -jar /opt/atlassian/jira/atlassian-agent.jar -p jira -m test@test.com -n hex -o https://host_jira -s <код экземляра: например, BATS-WNXJ-K6GX-C35R>
```
