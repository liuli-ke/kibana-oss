# 基于官方的Dockerfile修改构建 kibana-oss ARM 镜像

## 说明
```
整体没有做太大的修改, 主要调整了kibana-oss-7.10.2安装包下载地址、 dumb-init的下载和校验逻辑, 其他内容未作调整
```

## 镜像构建
```shell
docker build -t liulik/kibana-oss:7.10.2 .
```