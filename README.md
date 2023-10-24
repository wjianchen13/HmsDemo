# 华为服务相关测试

# 把项目改成低版本
1.	修改settings.gradle，直接使用项目的格式替换
2.	修改根目录下的build.gradle, 直接使用项目的格式替换
3.	app下的build.gradle namespace去掉，在AndroidManifest.xml添加 package
4.	修改gradle-wrapper.properties，把gradlew版本从8.0改成7.4重新编译就可以了

# 编译环境
android studio：Android Studio Flamingo | 2022.2.1 Patch 2
gradle 插件版本： 4.1.2
gradle版本： distributionUrl=https\://services.gradle.org/distributions/gradle-7.4-bin.zip






















