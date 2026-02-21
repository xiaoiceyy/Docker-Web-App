# Docker-Web-App

用Docker Compose一键部署WordPress应用（Nginx代理 + MySQL数据库）。

## 技术栈
- Docker
- Docker Compose
- Nginx (反向代理 + 静态缓存)
- MySQL
- WordPress

## 运行方式
1. 克隆仓库
git clone https://github.com/xiaoiceyy/Docker-Web-App.git

2. 进入文件夹
cd Docker-Web-App

3. 启动
docker-compose up -d




### docker ps输出：3个容器都在up状态
<img width="1687" height="140" alt="image" src="https://github.com/user-attachments/assets/29095c38-a100-4172-920e-cce38ef51cb1" />

### wordpress安装页面访问成功
<img width="635" height="645" alt="image" src="https://github.com/user-attachments/assets/1a7516bc-55eb-4ac2-a0f9-801db9333a63" />

### 成功进入wordpress
<img width="770" height="415" alt="image" src="https://github.com/user-attachments/assets/8df9bc65-0ee1-405c-8733-62090d25a8df" />
<img width="763" height="413" alt="image" src="https://github.com/user-attachments/assets/e52926cd-4454-43d4-8a61-92d02f5505c4" />


### nginx成功代理：访问nginx的代理端口会跳到xiaoiceyy的站
<img width="440" height="85" alt="image" src="https://github.com/user-attachments/assets/b552026f-8b7e-48bc-8ecb-12a16b885ac5" />




