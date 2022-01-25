* Troubleshooting Remote Agents: https://confluence.atlassian.com/bamkb/troubleshooting-remote-agents-216957427.html

* Broker URL: nio://0.0.0.0:54663?wireFormat.maxInactivityDuration=300000

* Broker client URL: failover:(tcp://bamboo-server:54663?wireFormat.maxInactivityDuration=300000)?initialReconnectDelay=15000&maxReconnectAttempts=10

* Database URL: jdbc:postgresql://postgres:5432/bamboo

* BAMBOO_SERVER: http://bamboo-server:8085/agentServer/

* Logs:

INFO   | jvm 3    | 2022/01/25 19:17:37 | 2022-01-25 19:17:37,884 INFO [AgentRunnerThread] [RemoteAgent] *                                                                                                                                              *
INFO   | jvm 3    | 2022/01/25 19:17:37 | 2022-01-25 19:17:37,885 INFO [AgentRunnerThread] [RemoteAgent] * Bamboo agent '54991aee1e94' ready to receive builds.
INFO   | jvm 3    | 2022/01/25 19:17:37 | 2022-01-25 19:17:37,885 INFO [AgentRunnerThread] [RemoteAgent] * Remote Agent Home: /var/atlassian/application-data/bamboo-agent
INFO   | jvm 3    | 2022/01/25 19:17:37 | 2022-01-25 19:17:37,885 INFO [AgentRunnerThread] [RemoteAgent] * Broker URL: failover:(tcp://bamboo-server:54663?wireFormat.maxInactivityDuration=300000)?initialReconnectDelay=15000&maxReconnectAttempts=10