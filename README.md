## 在根目录添加config.ini

### 格式如下：
```ini
[mysql]  
ip = 127.0.0.1  
port = 3306  
user = root  
password = ******  
database = 数据库名  
  
;管理页面账号  
[super]  
account = account  
password = password  
  
;后端域名和cors  
[host]  
domain = http://localhost:8820  
cors = *  
  
;邮箱配置  
[email]  
addr = smtp.example.com:465  
username = username@example.com  
password = ******  
host = smtp.example.com  
```

  