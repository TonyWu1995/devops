# windows 10 安裝包

## 安裝清單
- chocolatey
- openJDK8
- postgres13
- postman

## 使用說明

### bat
1. 執行install_choco.bat
2. 執行install_all.bat

### powershell
1. 執行`set-executionpolicy remotesigned`
2. 執行install_choco.ps1
3. 執行install_all.ps1


## 其他說明
1. install_jdk8.ps1
    - 安裝openjdk8
2. install_postgres.ps1
    - 安裝postgres 9.6
3. install_postman.ps1
    - 安裝 postamn

## Postgres 連線說明
```
psql postgresql://{user}:{password}@127.0.0.1:{port}
```

```
psql -c {sql command}' postgresql://{user}:{password}@127.0.0.1:{port}
```


