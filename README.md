# libra-api

分离服务协议和服务实现，不同语言可以基于统一的协议实现系统接入。

## package 命名规则

full.directory.path

eg:

libra/health/v1/xxx.proto

libra.health.v1

## RESTFul 命名规则

/full/directory/path/service_name{/collection_name}

eg:

Service Health in libra/health/v1/health.proto

/libra/health/v1/health

eg:

Service Account in libra/ptapi/v1/account.proto

/libra/health/v1/account/user

