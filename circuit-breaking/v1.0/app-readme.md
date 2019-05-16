# Apply weight-based routing

You can use this chart to gradually migrate traffic from one version of a microservice to another. For example, you might migrate traffic from an older version to a new version.

A common use case is to migrate traffic gradually from one version of a microservice to another. In Istio, you accomplish this goal by configuring a sequence of rules that route a percentage of traffic to one service or another. In this task, you will send 50% of traffic to reviews:v1 and 50% to reviews:v3. Then, you will complete the migration by sending 100% of traffic to reviews:v3.