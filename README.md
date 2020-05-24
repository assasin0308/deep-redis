## deep-redis

### 1. introduction

```json
# 单线程 VS 多线程
# 单线程:工作线程
# 多线程: IO线程
# 五种数据类型 --- 都具备本地方法 --- 计算向数据移动

客户端---> kernel --> epoll多路复用器 --> Redis server 计算串行化 ---> R/W 串行 ---> kernel---> 客户端

Memcache VS Redis:

memcache的value仅为string类型,返回的全量数据;
Redis的value类型具备本地方法,调用时仅仅调用本地方法后返回 index ;

```

### 2. value

```json
1. String



2. list


3. hash


4. set


5. zset

```

### 3. 

```json

```

### 4. 

```json

```

### 5. 

```json

```

### 6. 

```json

```

### 7. 

```json

```

### 8. 

```json

```

### 9. 

```json

```

### 10. 

```json

```

### 11. 

```json

```

### 12. 

```json

```

### 13. 

```json

```

### 14. 

```json

```

### 15. 

```json

```

### 16. 

```json

```

### 17. 

```json

```

### 18. 

```json

```

### 19. 

```json

```

### 20. 

```json

```

