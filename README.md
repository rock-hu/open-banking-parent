# open-banking-parent

| on push                                                                                         | on schedule                                                                                          |
| ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| ![](https://github.com/rock-hu/open-banking-parent/actions/workflows/mvn-deploy.yaml/badge.svg) | ![](https://github.com/rock-hu/open-banking-parent/actions/workflows/mvn-site-weekly.yaml/badge.svg) |

## maven

```bash
mvn initialize

```

```bash
mvn spotless:apply

mvn license:help
mvn dependency-check:aggregate
```

```bash
mvn versions:parent-updates-report
mvn versions:dependency-updates-aggregate-report
mvn versions:property-updates-aggregate-report
mvn versions:plugin-updates-aggregate-report

mvn dependency-check:aggregate
```

```bash
mvn antrun:run
```

## [spring-boot-dependencies/4.0.5](https://central.sonatype.com/artifact/org.springframework.boot/spring-boot-dependencies/4.0.5)

## [spring-cloud-dependencies/2025.1.1](https://central.sonatype.com/artifact/org.springframework.cloud/spring-cloud-dependencies/2025.1.1)

## dependencies - bom`

| bom                                                    | version  |
| ------------------------------------------------------ | -------- |
| org.springframework:spring-framework-bom               | 7.0.6    |
| org.springframework.batch:spring-batch-bom             | 6.0.3    |
| org.springframework.data:spring-data-bom               | 2025.1.4 |
| org.springframework.integration:spring-integration-bom | 7.0.4    |
| org.springframework.security:spring-security-bom       | 7.0.4    |
| org.springframework.session:spring-session-bom         | 4.0.2    |
| org.springframework.ws:spring-ws-core                  | 5.0.1    |

## jackson

## logbook

## spring-cloud-dependencies

```xml
<dependency>
	<groupId>org.springframework.cloud</groupId>
	<artifactId>spring-cloud-dependencies</artifactId>
	<version>2025.1.1</version>
	<type>pom</type>
	<scope>import</scope>
</dependency>

```

| Group                     | Artifact                             | Version |
| ------------------------- | ------------------------------------ | ------- |
| org.springframework.cloud | spring-cloud-function-dependencies   | 5.0.1   |
| org.springframework.cloud | spring-cloud-gateway-dependencies    | 5.0.1   |
| org.springframework.cloud | spring-cloud-consul-dependencies     | 5.0.1   |
| org.springframework.cloud | spring-cloud-vault-dependencies      | 5.0.1   |
| org.springframework.cloud | spring-cloud-zookeeper-dependencies  | 5.0.1   |
| org.springframework.cloud | spring-cloud-bus-dependencies        | 5.0.1   |
| org.springframework.cloud | spring-cloud-contract-dependencies   | 5.0.1   |
| org.springframework.cloud | spring-cloud-openfeign-dependencies  | 5.0.1   |
| org.springframework.cloud | spring-cloud-kubernetes-dependencies | 5.0.1   |

## [spring-cloud-function-dependencies](https://central.sonatype.com/artifact/org.springframework.cloud/spring-cloud-function-dependencies/5.0.1)

```xml
<dependency>
	<groupId>org.springframework.cloud</groupId>
	<artifactId>spring-cloud-function-dependencies</artifactId>
	<version>5.0.1</version>
	<type>pom</type>
</dependency>
```

| Group                     | Artifact                                | Version | Updates |
| ------------------------- | --------------------------------------- | ------- | ------- |
| org.springframework.cloud | spring-cloud-function-adapter-gcp       | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-adapter-azure     | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-rsocket           | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-serverless-web    | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-integration       | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-starter-function-web       | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-starter-function-webflux   | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-deployer          | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-adapter-aws       | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-adapter-azure     | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-adapter-azure-web | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-adapter-openwhisk | 5.0.1   |         |
| org.springframework.cloud | spring-cloud-function-kotlin            | 5.0.1   |         |

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
