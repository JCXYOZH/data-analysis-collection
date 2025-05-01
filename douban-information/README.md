# douban-information 项目运行注意事项 <br>

1. 项目包含 python爬虫 豆瓣电影Top250数据分析与可视化（应用Flask框架、Echarts、WordCloud等技术）
2. 此文件中含有python虚拟环境venv文件夹，版本python3.7，记得修改venv目录中的pyvenv.cfg文件中的home路径，
修改为自己电脑中python的对应位置
3. 数据库使用的SQLite，需要安装配置，数据库脚本文件名：`movie.db`
4. 爬取成功后生成的Excel表格路径：`savepath = "豆瓣电影top250.xls"`
5. 实现数据可视化项目快速部署于服务器教程：<br><br>

##### 1. 在宝塔面板下载 “ python项目管理器 ”
##### 2. 上传至文件至服务器
##### 3. 生成 requirements.txt 文件
进入项目根目录，使用命令把项目依赖包导出到项目根目录。

```python
pip freeze >requirements.txt
```

##### 4.在 python项目管理器添加 python项目
