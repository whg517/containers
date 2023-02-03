# bitnami spark

## dep

```text
"https://repo1.maven.org/maven2/org/apache/hadoop/hadoop-aws/3.3.4/hadoop-aws-3.3.4.jar" \
"https://repo1.maven.org/maven2/com/amazonaws/aws-java-sdk-s3/1.12.398/aws-java-sdk-s3-1.12.398.jar" \
"https://repo1.maven.org/maven2/com/amazonaws/aws-java-sdk-dynamodb/1.12.398/aws-java-sdk-dynamodb-1.12.398.jar" \
"https://repo1.maven.org/maven2/com/amazonaws/aws-java-sdk-core/1.12.398/aws-java-sdk-core-1.12.398.jar" \
"https://repo1.maven.org/maven2/com/amazonaws/aws-java-sdk/1.12.398/aws-java-sdk-1.12.398.jar" \
"https://repo1.maven.org/maven2/com/amazonaws/aws-java-sdk-bundle/1.12.398/aws-java-sdk-bundle-1.12.398.jar" \
"https://repo1.maven.org/maven2/org/wildfly/openssl/wildfly-openssl/2.2.5.Final/wildfly-openssl-2.2.5.Final.jar" \
"https://downloads.bitnami.com/files/stacksmith/spark-3.3.1-6-linux-amd64-debian-11.tar.gz" \
"https://downloads.bitnami.com/files/stacksmith/spark-3.3.1-6-linux-arm64-debian-11.tar.gz" \
```

## build

```bash
docker buildx build --platform linux/amd64 -t docker-private.zncdata.net/bitnami/spark:v0.0.2-spark3.3.1 .
```
