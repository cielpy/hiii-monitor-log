### 介绍

本项目主要功能为监控爬虫打日志所用

### 安装

```
pipenv install -e git+https://github.com/cielpy/hiii-monitor-log.git

```

### 使用

```python
from monitor_log.monitor_log import count_log

count_log('数据类型', 1)
```