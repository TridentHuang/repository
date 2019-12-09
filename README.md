# repository

### 发布

```java
mvn clean deploy -DaltDeploymentRepository=TridentHuang-repository::default::file:/soft/maven/github/repository
```

### 使用

```
1 pom文件中添加仓库
<repositories>
	<repository>
		<id>repository</id>
		<url>https://raw.github.com/TridentHuang/repository/master</url>
	</repository>
</repositories>
2 pom文件中添加依赖
<dependency>
	<groupId>cn.fanyu</groupId>
		<artifactId>common</artifactId>
	<version>1.2</version>
</dependency>
```

