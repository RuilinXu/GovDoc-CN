# GovDoc-CN: 多模态党政机关公文数据集
从[国务院政策文件库](http://www.gov.cn/zhengce/zhengcewenjianku/index.htm)获取Web公文，自动化排版后，清洗并标注了1 737篇文档，共6 816个页面。
目录结构为：
```
--GovDoc-CN
----1 # 文档编号
------1.pdf # Web公文批量排版后的PDF文档
------1.txt # 清洗后的公文文本
------1_a.txt # BIO标注的公文文本
------1_1.png # 公文文档页面图像1
------1_2.png # 公文文档页面图像2
------1_1.xml # VOC格式页面图像标注1
------1_2.xml # VOC格式页面图像标注2
```
统计信息为：
|类  型|数  量|
|---|---|
|发文机关标志|1 347|
|发文字号|1 344|
|正文标题|1 359|
|主送机关|1 065|
|一级标题|5 184|
|二级标题|4 697|
|三级标题|1 415|
|发文机关|2 073|
|成文日期|1 178|
|正    文|10 280|
|总    计|29 942|

[数据集获取](https://share.weiyun.com/6xOi3akN)
# GovDoc-CN: A Multi-Modal Dataset of Chinese Governmental Docunments
The official document data was obtained from the [Chinese State Council Policy Document Database](http://www.gov.cn/zhengce/zhengcewenjianku/index.htm), and after automatic typesetting, 1,737 documents were cleaned and annotated, with a total of 6,816 pages.
The structure of the dataset directory is like:
```
--GovDoc-CN
----1 # Number
------1.pdf # PDF documents after typesetting
------1.txt # text after cleaning
------1_a.txt # BIO marked text
------1_1.png # Image of document page 1
------1_2.png # Image of document page 2
------1_1.xml # VOC format image annotation 1
------1_2.xml # VOC format image annotation 2
```
The data set statistics are：
|Labels|#Labels|
|---|---|
|Sign of document issuing authority|1 347|
|Document number|1 344|
|Title|1 359|
|Addressee|1 065|
|1st level subtitle|5 184|
|2nd level subtitle|4 697|
|3rd level subtitle|1 415|
|Issuing authority|2 073|
|Date of writing|1 178|
|Main text|10 280|
|Count|29 942|

[Get GovDoc-CN](https://share.weiyun.com/6xOi3akN)
