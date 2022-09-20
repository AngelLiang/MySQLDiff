MySQLDiff
=========

对两个不同的mysql数据库的表进行比较

fork from https://github.com/whiteclover/MySQLDiff

升级为python3，mysqldb包切换为pymysql包


## 如何使用

## 进入虚拟环境

    poetry install
    poetry shell

## 执行

    python mysqldiff.py user:password@db-host/database  user:password@db-host-to-diff/database

