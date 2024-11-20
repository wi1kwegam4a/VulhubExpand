# VulhubExpand

有时会遇到一些vulhub上没有的漏洞，故作此项目为补充。

## Usage

```
# 下载项目
wget https://github.com/wi1kwegam4a/VulhubExpand/archive/refs/heads/main.zip
unzip main.zip
cd VulhubExpand-main

# 进入某一个漏洞/环境的目录
cd SCM-Manager/CVE-2023-33829

# 启动整个环境
docker compose up -d
```

每个环境目录下都有相应的说明文件，请阅读该文件，进行漏洞/环境测试。