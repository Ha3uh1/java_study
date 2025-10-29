# SpringBoot的项目结构
主要是src和pom.xml
## src文件夹
src下面有main和test文件夹，其中main文件夹是项目文件，test文件夹是测试文件，和项目没啥关系，用来测试的。

main文件夹下Java文件夹用来放置项目代码，resources下有两个文件夹，看名字就知道一个是静态目录一个是模板目录。还有一个文件**application.properties**，这个文件是springboot的配置文件

pom.xml是maven的配置文件，用来配置库之类的

# 开发小记
Spring boot对Java包的层级有一个要求，启动类必须在package的根目录下，所以我们的启动类application.java放在org.example.java_web下