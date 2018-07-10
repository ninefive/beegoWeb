![beego.png](/static/img/beego.png)
# BegooSolution
BeegoSolution 是一个关于 Begoo 的 Go 解决方案。  

## 功能特性

- 后台管理（用户管理、角色管理、资源管理、权限管理）
- 集成 Swagger
- 支持热重启

## 技术栈

| 技术项 | 版本 |  
| :---- |:----| 
| Go | go1.10.2 | 
| Beego | 1.9.2 | 
| Metronic | 5.0 | 
| Swagger | - |

## 目录说明

| 目录类型 | 目录 | 说明 |  
| :---- | :---- |:----| 
| 系统目录 | conf | 应用配置目录 | 
| 系统目录 | controllers | 控制器目录 | 
| 系统目录 | models | 业务实体目录 | 
| 系统目录 | routers | 路由信息目录 | 
| 系统目录 | static | css、图片、js目录 | 
| 系统目录 | test | 单元测试目录 | 
| 系统目录 | views | 模板目录 | 
| 自定义目录 | serice | 业务代码目录 | 
| 自定义目录 | database | 数据库、sql文件目录 | 

## 使用说明
```bash
$ go get github.com/astaxie/beego
$ go get github.com/beego/bee
$ cd $GOPATH/src/
$ git clone https://github.com/iamwlb/BeegoSolution.git
$ cd BeegoSolution
$ bee run
$ curl http://localhost:8080
```
