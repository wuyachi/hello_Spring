# hello Spring

##### 打包 跳过测试
`
mvn clean package -Dmaven.test.skip
`

##### 执行
`
java -jar hello-spring-0.0.1-SNAPSHOT.jar
`
##### 健康检查
`
curl localhost:8080/actuator/health
`

##### 测试
`
curl localhost:8080/hello
`


