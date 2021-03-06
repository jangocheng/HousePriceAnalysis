# HousePriceAnalysis

上海地区新房和二手房数据的爬虫抓取, 数据处理和可视化分析

### 项目背景：
本人预计于近两年购房，所以准备获取上海地区二手房和新房数据进行数据清洗和转换，并基于该数据进行可视化分析和统计学分析，以期获取上海各区内地区的基础房价情况，并从中获取一些可用的信息和结论。

### 项目过程：

- 初步研究根据房天下的页面结构和基础的反爬策略，确定需要的字段信息
- 根据需要的字段信息，设计爬虫程序，支持指定区和地区的爬取和全区爬取
- 将爬取得到的数据进行本地持久化化存储(暂时保持在CSV文件)
- 对已经获取数据进行清洗和优化，通过高德API获取经纬度， 并计算到特定点的直线距离
- 基于 Tableau 进行数据可视化分析，包括各区的房价分布情况和小区的基础信息
- 更进一步的统计学分析(暂未进行)


![实例](images/上海全市二手房分析报表.png)


> 注意:本项目仅用于学习和个人分析使用, 不得用于任何商业目的, 有违反者后果自行承担.