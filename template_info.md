# 源码自动生成模板 java-demo

### 概述

* 模板: java-demo
* 模板使用时间: 2018-01-23 19:41:13

### Docker
* Image: registry.cn-beijing.aliyuncs.com/codebase/java-demo
* Tag: 2.0
* SHA256: 023365d0a0e030bc467dae593e829da24dd355e1508ddcecc1745bb05774808c

### 用户输入参数
* repoUrl: "git@code.aliyun.com:1135-liqiang-test-group/hehe.git" 
* appName: "hehe" 
* operator: "aliyun_011625" 
* appReleaseContent: "# 
* 请参考: 请参考 
* https://help.aliyun.com/document_detail/59293.html: https://help.aliyun.com/document_detail/59293.html 
* 了解更多关于release文件的编写方式: 了解更多关于release文件的编写方式 
* [NEWLINE][NEWLINE]#: [NEWLINE][NEWLINE]# 
* 构建源码语言类型[NEWLINE]code.language: oracle-jdk1.7[NEWLINE][NEWLINE]# 
* 构建打包使用的打包文件[NEWLINE]build.output: target/hehe.war[NEWLINE][NEWLINE]# 
* 应用部署脚本[NEWLINE]deploy.appctl.path: deploy.sh" 

### 上下文参数
* appName: hehe
* operator: aliyun_011625
* gitUrl: git@code.aliyun.com:1135-liqiang-test-group/hehe.git
* branch: master


### 命令行
	sudo docker run --rm -v `pwd`:/workspace -e repoUrl="git@code.aliyun.com:1135-liqiang-test-group/hehe.git" -e appName="hehe" -e operator="aliyun_011625" -e appReleaseContent="# 请参考 https://help.aliyun.com/document_detail/59293.html 了解更多关于release文件的编写方式 [NEWLINE][NEWLINE]# 构建源码语言类型[NEWLINE]code.language=oracle-jdk1.7[NEWLINE][NEWLINE]# 构建打包使用的打包文件[NEWLINE]build.output=target/hehe.war[NEWLINE][NEWLINE]# 应用部署脚本[NEWLINE]deploy.appctl.path=deploy.sh"  registry.cn-beijing.aliyuncs.com/codebase/java-demo:2.0

