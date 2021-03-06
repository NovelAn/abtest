# 网页优化A/B测试

- 项目报告分享：[CSDN](https://blog.csdn.net/novelan/article/details/115212986)

 - 项目源码链接：[Github Repo](https://github.com/NovelAn/abtest)

```shell
## 下载源码，请使用以下命令在你的本地上克隆repo

git init
git clone [项目源码链接]

```



## 项目简介

本项目是关于某电商平台在更新网页版本后，随机选取了两组用户，跟踪并收集了这两组用户在新旧网页的转化数据。
项目采用Python作为分析工具，通过A/B测试，检测新页面的转化量是否显著优于旧页面，如果优于，则发布新页面，反之则不发布。

## 项目流程
- 数据评估与清洗
	- 数据评估
	- 数据预处理
	- 数据可视化
- A/B测试
	- 假设检验
	- 公式计算
	- 模拟抽样分布（自助抽样法）
	- 调包—statsmodel.api功能库
- 回归分析法
	- sklearn.Logicregression
	- statsmodel.api
	- 添加特征项
	- 添加交互项
- 结论

## 数据集说明
- `ab_data.csv`：两组用户在不同页面的转化数据
- `countries.csv`：用户所在的地区和国家，主要用户检测国家项和相关的交互项与转化率是否存在相关性