# maven命令速查表

## 1. 创建项目

创建普通java项目

```shell
mvn archetype:create -DgroupId=packageName -DartifactId=projectName
```

创建web项目

```shell
mvn archetype:create -DgroupId=packageName -DartifactId=webappName -DarchetypeArtifactId=maven-archetype-webapp
```

使用生成器创建项目，可以通过交互，选择，创建一个项目模板

```shell
mvn archetype:generate
```

生成eclipse项目

```shell
mvn eclipse:eclipse
```

生产idea项目

```shell
mvn idea:idea
```

## 2. 编译

编译源代码

```shell
mvn compile
```

编译测试代码

```shell
mvn test-compile
```

## 3. 运行

运行测试

```shell
mvn test
```

## 4. 打包

打包成jar

```shell
mvn jar:jar
```

打包

```shell
mvn package
```

## 5. 在本地安装依赖

```shell
mvn install
```

