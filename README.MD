# mysql sysbench
mysql sysbench是一款压测数据生成工具

## python3 生成压测数据说明
### quick_insert.py

使用程序方式批量插入数据的脚本，需要引入依赖包 pymysql

### quick_insert_threads.py

多线程批量插入数据的脚本，需要引入依赖包 pymysql

### quick_sql_insert.py

生成 insert 批量插入脚本，与上面的方式类似，只不过生成的文件需要手动执行。

### quick_txt_load.py

生成逗号分隔的 txt 文件，之后需要使用 `load data infile` 命令导入数据。
