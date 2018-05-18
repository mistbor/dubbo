1. 下载dubbox的源代码：https://github.com/dangdangdotcom/dubbox
2. 使用maven进行编译：mvn clean install -Dmaven.test.skip=true
3. 在target目录下会有dubbo-2.8.4.jar包
4. 使用时引入：
<dependency>
    <groupId>com.alibaba</groupId>
    <artifactId>dubbo</artifactId>
    <version>2.8.4</version>
</dependency>