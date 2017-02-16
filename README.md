
## 项目简介
spring boot 示例项目。主要实现了操作mongodb数据库，网页模板，装饰器布局，验证和鉴权，前端样式等。

## 组件
- Spring Boot
- Spring Security
- Spring Data Mongodb
- Fastjson
- Thymeleaf3
- Thymeleaf Layout Dialect
- Semantic UI

## 运行


- 本地编译运行：
  1. 启动mongodb
```
docker run -d -p 27017:27017 -p 28017:28017 -e MONGODB_USER=user7 -e MONGODB_PASS=xinhua -e MONGODB_DATABASE=demo-spring-boot tutum/mongodb
```
  2.编译运行
```
mvn package
java -jar target/spring-boot-sample-1.0-SNAPSHOT.jar
```

- docker compose方式运行：
  1. 按“本地编译运行”先编译jar包   
  2. 启动
```
docker-compose up -d
```