# cobra快速的实现一个命令行客户端

### 1. 命令行项目三个关键配置

###### （1）命令，代表动作

###### （2）参数，代表事务

###### （3）标志，代表动作的修饰

##### 标志类型：

- 本地标志，只能当前命令使用
- 持久化标志，当前命令及当前命令的所有下级命令都可以使用
- 全局标志，根命令的持久化标志，所有命令都能使用



### 2. flags的定义与配置绑定

### 3. 自定义参数验证与内置验证