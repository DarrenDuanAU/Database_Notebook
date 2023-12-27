# postgreSQL
## 基本操作

### 检查是否运行
```bash
pg_isready
```

## 链接
```bash
psql -h /tmp -p 5432
```

## 进入DB后
### 查看所有table
```bash
\dt
```

### 创建其他数据库
```bash
CREATE DATABASE NEW_DB_NAME;
```

### 切换链接到目标数据库
```bash
\c TARGET_DB_NAME
```

### 离开
```bash
quit
```