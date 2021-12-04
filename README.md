# 区块链选举系统

## 运行方法

- 安装依赖

  `pip install -r requirements.txt`

- 建表

  `python manage.py makemigrations`

  `python3 manage.py migrate`

- 运行

  `python manage.py runserver 0.0.0.0:8000`

- 从浏览器访问 http://localhost:8000 进入测试页面。

## 数据结构

![image-20211204115156031](typora/README/image-20211204115156031.png)

## 系统架构

### 初始化

![image-20211204115512324](typora/README/image-20211204115512324.png)

### 投票

![image-20211204115531517](typora/README/image-20211204115531517.png)

### 计票

![image-20211204115633174](typora/README/image-20211204115633174.png)

