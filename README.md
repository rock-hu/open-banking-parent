# parent

## docs

| artifact             | link(s)                                                                                                                                                         |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| spring-cloud-config  | https://docs.spring.io/spring-cloud-config/docs/4.0.0/reference/html/                                                                                           |
| spring-cloud-gateway | https://docs.spring.io/spring-cloud-gateway/docs/4.0.0/reference/html/ <br> https://docs.spring.io/spring-cloud-gateway/docs/4.0.0/reference/html/appendix.html |

## maven

```bash

mvn spotless:apply

mvn license:help
mvn dependency-check:aggregate
```

## spring-boot-dependencies

https://repo1.maven.org/maven2/org/springframework/boot/spring-boot-dependencies/3.0.0/spring-boot-dependencies-3.0.0.pom
https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-dependencies/3.0.0

## dependencies - bom`

| bom                                                    | version      |
| ------------------------------------------------------ | ------------ |
| com.querydsl:querydsl-bom                              | 5.0.0        |
| com.squareup.okhttp3:okhttp-bom                        | 4.10.0       |
| io.micrometer:micrometer-bom                           | 1.10.2       |
| io.micrometer:micrometer-tracing-bom                   | 1.0.0        |
| io.netty:netty-bom                                     | 4.1.85.Final |
| io.opentelemetry:opentelemetry-bom                     | 1.19.0       |
| io.zipkin.reporter2:zipkin-reporter-bom                | 2.16.3       |
| org.apache.logging.log4j:log4j-bom                     | 2.19.0       |
| org.junit:junit-bom                                    | 5.9.1        |
| org.springframework:spring-framework-bom               | 6.0.2        |
| org.springframework.batch:spring-batch-bom             | 5.0.0        |
| org.springframework.data:spring-data-bom               | 2022.0.0     |
| org.springframework.integration:spring-integration-bom | 6.0.0        |
| org.springframework.security:spring-security-bom       | 6.0.0        |
| org.springframework.session:spring-session-bom         | 3.0.0        |
| org.springframework.ws:spring-ws-core                  | 4.0.0        |

## [testcontainers](https://www.testcontainers.org/)

```xml
<dependencyManagement>
	<dependencies>
		<dependency>
			<groupId>org.testcontainers</groupId>
			<artifactId>testcontainers-bom</artifactId>
			<version>1.17.6</version>
			<type>pom</type>
			<scope>import</scope>
		</dependency>
	</dependencies>
</dependencyManagement>
```

artifacts

| groupId            | artifactId       | version |
| ------------------ | ---------------- | ------- |
| org.testcontainers | azure            | 1.17.6  |
| org.testcontainers | cassandra        | 1.17.6  |
| org.testcontainers | clickhouse       | 1.17.6  |
| org.testcontainers | cockroachdb      | 1.17.6  |
| org.testcontainers | consul           | 1.17.6  |
| org.testcontainers | couchbase        | 1.17.6  |
| org.testcontainers | database-commons | 1.17.6  |
| org.testcontainers | db2              | 1.17.6  |
| org.testcontainers | dynalite         | 1.17.6  |
| org.testcontainers | elasticsearch    | 1.17.6  |
| org.testcontainers | gcloud           | 1.17.6  |
| org.testcontainers | hivemq           | 1.17.6  |
| org.testcontainers | influxdb         | 1.17.6  |
| org.testcontainers | jdbc             | 1.17.6  |
| org.testcontainers | junit-jupiter    | 1.17.6  |
| org.testcontainers | k3s              | 1.17.6  |
| org.testcontainers | kafka            | 1.17.6  |
| org.testcontainers | localstack       | 1.17.6  |
| org.testcontainers | mariadb          | 1.17.6  |
| org.testcontainers | mockserver       | 1.17.6  |
| org.testcontainers | mongodb          | 1.17.6  |
| org.testcontainers | mssqlserver      | 1.17.6  |
| org.testcontainers | mysql            | 1.17.6  |
| org.testcontainers | neo4j            | 1.17.6  |
| org.testcontainers | nginx            | 1.17.6  |
| org.testcontainers | oracle-xe        | 1.17.6  |
| org.testcontainers | orientdb         | 1.17.6  |
| org.testcontainers | postgresql       | 1.17.6  |
| org.testcontainers | presto           | 1.17.6  |
| org.testcontainers | pulsar           | 1.17.6  |
| org.testcontainers | questdb          | 1.17.6  |
| org.testcontainers | r2dbc            | 1.17.6  |
| org.testcontainers | rabbitmq         | 1.17.6  |
| org.testcontainers | redpanda         | 1.17.6  |
| org.testcontainers | selenium         | 1.17.6  |
| org.testcontainers | solr             | 1.17.6  |
| org.testcontainers | spock            | 1.17.6  |
| org.testcontainers | testcontainers   | 1.17.6  |
| org.testcontainers | tidb             | 1.17.6  |
| org.testcontainers | toxiproxy        | 1.17.6  |
| org.testcontainers | trino            | 1.17.6  |
| org.testcontainers | vault            | 1.17.6  |
| org.testcontainers | yugabytedb       | 1.17.6  |

## jackson

## logbook

## spring-cloud-dependencies

https://spring.io/cloud

```xml
<dependency>
	<groupId>org.springframework.cloud</groupId>
	<artifactId>spring-cloud-dependencies</artifactId>
	<version>2021.0.5</version>
	<type>pom</type>
	<scope>import</scope>
</dependency>

```

https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-dependencies/2022.0.0

```xml
<dependency>
	<groupId>org.springframework.cloud</groupId>
	<artifactId>spring-cloud-dependencies</artifactId>
	<version>2022.0.0</version>
	<type>pom</type>
	<scope>import</scope>
</dependency>
```

| Group                        | Artifact                                                 | Version                |
| ---------------------------- | -------------------------------------------------------- | ---------------------- |
| com.netflix.eureka           | eureka-client                                            | 2.0.0-rc.4             |
| com.netflix.eureka           | eureka-core                                              | 2.0.0-rc.4             |
| com.netflix.eureka           | eureka-core-jersey3                                      | 2.0.0-rc.4             |
| com.netflix.eureka           | eureka-client-jersey3                                    | 2.0.0-rc.4             |
| io.github.resilience4j       | resilience4j-bom                                         | 1.7.0                  |
| org.eclipse.jgit             | org.eclipse.jgit                                         | 6.2.0.202206071550-r r |
| org.eclipse.jgit             | org.eclipse.jgit.junit.http                              | 6.2.0.202206071550-r r |
| org.eclipse.jgit             | org.eclipse.jgit.http.apache                             | 6.2.0.202206071550-r r |
| org.eclipse.jgit             | org.eclipse.jgit.ssh.apache                              | 6.2.0.202206071550-r r |
| org.springframework.cloud    | spring-cloud-function-dependencies                       | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-gateway-dependencies                        | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-consul-dependencies                         | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-vault-dependencies                          | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-zookeeper-dependencies                      | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-bus-dependencies                            | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-contract-dependencies                       | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-openfeign-dependencies                      | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-kubernetes-dependencies                     | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-commons                                     | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-context                                     | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-loadbalancer                                | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-starter                                     | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-bootstrap                           | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-loadbalancer                        | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-test-support                                | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-netflix-eureka-client                       | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-netflix-eureka-client               | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-netflix-eureka-server               | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-netflix-eureka-server                       | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream                                      | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-test-binder                          | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-test-support                         | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-binder-kafka                         | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-binder-kafka-reactive                | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-binder-kafka-streams                 | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-binder-kafka-core                    | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-stream-kafka                        | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-binder-rabbit                        | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-binder-rabbit-core                   | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-stream-rabbit                       | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-binder-rabbit-test-support           | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-schema-registry-client               | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-schema-registry-core                 | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-stream-schema-registry-server               | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-task                                | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-task-core                                   | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-task-batch                                  | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-task-stream                                 | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-circuitbreaker-resilience4j                 | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-circuitbreaker-spring-retry                 | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-circuitbreaker-spring-retry         | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-circuitbreaker-resilience4j         | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-circuitbreaker-reactor-resilience4j | 3.0.0                  |
| org.springframework.cloud    | spring-cloud-starter-config                              | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-config-client                               | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-config-server                               | 4.0.0                  |
| org.springframework.cloud    | spring-cloud-config-monitor                              | 4.0.0                  |
| org.springframework.credhub  | spring-credhub-core                                      | 2.1.1.RELEASE          |
| org.springframework.security | spring-security-rsa                                      | 1.0.11.RELEASE         |
| org.springframework.vault    | spring-vault-core                                        | 3.0.0                  |
| org.tmatesoft.svnkit         | svnkit                                                   | 1.10.1                 |

## spring-cloud-function-dependencies

```xml
<dependency>
	<groupId>org.springframework.cloud</groupId>
	<artifactId>spring-cloud-function-dependencies</artifactId>
	<version>3.0.0.RELEASE</version>
	<type>pom</type>
</dependency>
```

| Group                     | Artifact                                     | Version       | Updates        |
| ------------------------- | -------------------------------------------- | ------------- | -------------- |
| org.springframework.cloud | spring-cloud-function-context1 vulnerability | 3.0.0.RELEASE | 3.2.8          |
| org.springframework.cloud | spring-cloud-function-core1 vulnerability    | 3.0.0.RELEASE | 3.2.8          |
| org.springframework.cloud | spring-cloud-function-compiler               | 3.0.0.RELEASE | 3.0.14.RELEASE |
| org.springframework.cloud | spring-cloud-function-task                   | 3.0.0.RELEASE | 3.0.14.RELEASE |
| org.springframework.cloud | spring-cloud-function-web                    | 3.0.0.RELEASE | 3.2.8          |
| org.springframework.cloud | spring-cloud-starter-function-web            | 3.0.0.RELEASE | 3.2.8          |
| org.springframework.cloud | spring-cloud-starter-function-webflux        | 3.0.0.RELEASE | 3.2.8          |
| org.springframework.cloud | spring-cloud-function-deployer               | 3.0.0.RELEASE | 3.2.8          |
| org.springframework.cloud | spring-cloud-function-adapter-aws            | 3.0.0.RELEASE | 3.2.8          |
| org.springframework.cloud | spring-cloud-function-adapter-azure          | 3.0.0.RELEASE | 3.2.8          |
| org.springframework.cloud | spring-cloud-function-adapter-openwhisk      | 3.0.0.RELEASE | 3.0.14.RELEASE |
| org.springframework.cloud | spring-cloud-function-kotlin                 | 3.0.0.RELEASE | 3.2.8          |

## cloudevents-bom

```xml
<dependencies>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-api</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-core</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-json-jackson</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-protobuf</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-amqp-proton</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-http-basic</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-http-vertx</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-http-restful-ws</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-kafka</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>cloudevents-spring</artifactId>
	</dependency>
	<dependency>
		<groupId>io.cloudevents</groupId>
		<artifactId>io.cloudevents.sql</artifactId>
	</dependency>
</dependencies>
```

## [resilience4j](https://resilience4j.readme.io/)

```xml
<dependencies>
	<dependency>
		<groupId>io.github.resilience4j</groupId>
		<artifactId>resilience4j-circuitbreaker</artifactId>
	</dependency>
	<dependency>
		<groupId>io.github.resilience4j</groupId>
		<artifactId>resilience4j-ratelimiter</artifactId>
	</dependency>
	<dependency>
		<groupId>io.github.resilience4j</groupId>
		<artifactId>resilience4j-retry</artifactId>
	</dependency>
	<dependency>
		<groupId>io.github.resilience4j</groupId>
		<artifactId>resilience4j-bulkhead</artifactId>
	</dependency>
	<dependency>
		<groupId>io.github.resilience4j</groupId>
		<artifactId>resilience4j-cache</artifactId>
	</dependency>
	<dependency>
		<groupId>io.github.resilience4j</groupId>
		<artifactId>resilience4j-timelimiter</artifactId>
	</dependency>
</dependencies>
```

| name            | how does it work?                           | description                                                                               | links                                        |
| --------------- | ------------------------------------------- | ----------------------------------------------------------------------------------------- | -------------------------------------------- |
| Retry           | repeats failed executions                   | Many faults are transient and may self-correct after a short delay.                       | overview, documentation,Spring               |
| Circuit Breaker | temporary blocks possible failures          | When a system is seriously struggling, failing fast is better than making clients wait.   | overview,documentation,Feign,Retrofit,Spring |
| Rate Limiter    | limits executions/period                    | Limit the rate of incoming requests.                                                      | overview,documentation,Feign,Retrofit,Spring |
| Time Limiter    | limits duration of execution                | Beyond a certain wait interval, a successful result is unlikely.                          | documentation,Retrofit,Spring                |
| Bulkhead        | limits concurrent executions                | Resources are isolated into pools so that if one fails, the others will continue working. | overview,documentation,Spring                |
| Cache           | memorizes a successful result               | Some proportion of requests may be similar.                                               | documentation                                |
| Fallback        | provides an alternative result for failures | Things will still fail - plan what you will do when that happens.                         | Try::recover,Spring,Feign                    |
