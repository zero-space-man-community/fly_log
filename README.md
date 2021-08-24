fly_log
========

最简单的日志，比 print 函数，多了时间与源文件信息。用于比较小的python项目，是适合的。

特点
========
功能少，与print函数一致

安装说明
=======

代码对 Python 3 兼容
* 全自动安装：`pip install fly_log` / `pip3 install fly_log`

代码示例
 
```python
from fly_log import debug_print

print = debug_print

print("my fly log ") 

# 输出这样的格式
# 2021-08-24 22:03:13 dev_run1(fly_log_sample_dev_run.py:7) dev_run1
# 2021-08-24 22:03:13 dev_run1(fly_log_sample_dev_run.py:8) dev_run1
```
