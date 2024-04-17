# 项目介绍

## 概述
这个项目是一个用于检测域名是否有效的工具。它通过解析给定的域名，并检查是否能成功解析到IP地址来判断域名的有效性。

## 使用方法
1. 将需要检测的hosts放在和脚本同目录下再运行`DomainExtractor.py`得到 `hosts.txt` 。
2. 再运行 `DomainResolver.py` 脚本，它将解析域名并输出有效的域名列表到 `hosts.1` 文件中。

## 依赖
- Python 3.x
- tqdm

## 安装
```bash
pip install tqdm
