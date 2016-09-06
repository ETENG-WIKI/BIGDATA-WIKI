### 乡村销客日志离线处理之--hive简单使用

### hive 安装参考 

http://sishuok.com/forum/blogPost/list/6221.html

http://blog.fens.me/hadoop-hive-intro/

### hive 控制台命令

在hive 的安装目录bin 文件夹下执行

 ./hive

启动hive的命令控制台


参考:
http://fyzjhh.blog.163.com/blog/static/16944422620124971826648/


```bash
show databases;


show tables;


create table if not exists log_nginx_access (
  remote_addr string, user_id string
  sum_count double ) 
row format delimited 
fields terminated by '\t' 
lines terminated by '\n' 
STORED AS TEXTFILE ";


select * from tablename;

```



