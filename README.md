# Go Service

## 项目简介
**基于`kratos`构建的土拨鼠社区基础服务**

## Start
1. Fork到自己账户下进行开发
2. PR到主库master分支合并
## Build & Run
1. 命令行:
    - Linux/Unix
        ```shell script
        cd go-base/cmd
        go build
        ./cmd -conf ../configs
        ```
    - Win
        ```shell script
        cd go-base/cmd
        go build
        cmd.exe -conf ../configs
        ```        
    
   
2. GoLand:

    在`Program arguments`中加入`-conf configs`
## 注意事项
- 配置环境变量
  - GO111MODULE=on
  - GOPROXY=https://goproxy.io
- 开发工具:[GoLand](https://www.jetbrains.com/go/)