## Usage

```
# 下载项目
wget https://github.com/wi1kwegam4a/VulhubExpand/archive/refs/heads/main.zip
unzip vulhub-master.zip
cd vulhub-master

# 进入某一个漏洞/环境的目录
cd flask/ssti

# 自动化编译环境
docker compose build

# 启动整个环境
docker compose up -d
```



每个环境目录下都有相应的说明文件，请阅读该文件，进行漏洞/环境测试。