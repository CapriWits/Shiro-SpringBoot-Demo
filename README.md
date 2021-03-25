# Shiro-SpringBoot

---

- 本项目涉及两个 `Module`
- `hello-shiro`是 Shiro 官方的十分钟快速入门的案例，只有 `Quickstart.java`和 `.ini`的配置文件
- `shiro-springboot`是一个小Demo，Shiro整合Springboot，还使用`Mybatis`作为`ORM`。



- Demo 用的 Shiro 整合 Spring 的包

```xml
<!--shiro 整合 spring 的包-->
<dependency>
    <groupId>org.apache.shiro</groupId>
    <artifactId>shiro-spring</artifactId>
    <version>1.5.3</version>
</dependency>
```

- 但网上的一些开源项目中使用的是 Shiro 整合 SpringBoot 的包

```xml
<dependency>
    <groupId>org.apache.shiro</groupId>
    <artifactId>shiro-spring-boot-starter</artifactId>
    <version>1.7.1</version>
</dependency>
```

看了一下 这个多了一个 `spring-boot-autoconfigure` 的包，其他 Shiro 核心代码都有。



> 鸣谢：KuangStudy