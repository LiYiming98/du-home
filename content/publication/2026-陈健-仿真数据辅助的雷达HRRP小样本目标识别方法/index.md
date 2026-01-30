---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: "仿真数据辅助的雷达HRRP小样本目标识别方法"

# 作者信息
authors:
  - 陈健
  - 於刚
  - 杜兰
  - 董文强
  - 郭昱辰



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2026-01-29T00:00:00Z'

# 2期刊论文；1会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: '雷达学报'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: '雷达高分辨距离像(HRRP)目标识别研究广泛、方法众多，特别是深度学习在雷达HRRP识别领域的应用与发展，为直接利用雷达回波实现高效、精确的目标感知提供了技术支撑。然而，深层识别网络依赖大量训练数据。对于非合作目标，受雷达系统参数、目标快速机动等因素限制，实际很难提前获取姿态完备的HRRP训练样本，深层识别网络面临学习过拟合、泛化能力显著下降的问题。针对上述问题，考虑关注目标的全姿态电磁仿真数据易获取，该文以仿真数据为辅助，从数据扩充和跨域知识迁移学习两方面来缓解小样本问题。数据扩充方面，结合一定姿态角角域范围内仿真、实测HRRP在均值和方差特性两方面的差异分析，对与少量实测HRRP同角域的大量仿真HRRP样本进行线性变换，使其均值、方差满足实测域HRRP特性，实现可表征真实HRRP分布特性的数据扩充。跨域知识迁移学习方面，考虑数据扩充策略仅能实现临近姿态角的样本扩充，对仿真数据知识的利用仍不充分，所提方法利用基于生成对抗约束的域对齐策略和基于对比学习约束的类对齐策略，将具有强可分性与泛化性的仿真域全姿态数据特征和实测域特征按类拉近，进一步辅助实测域数据的学习，实现小样本识别性能的更大提升。基于3类飞机目标以及10类地面车辆目标电磁仿真和实测HRRP数据的实验表明，所提方法相较于现有小样本识别方法具有更优的识别稳健性。'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://radars.ac.cn/article/doi/10.12000/JR25123
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2026-陈健-仿真数据辅助的雷达HRRP小样本目标识别方法.pdf'
# 都留空
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


image:
  caption: 
  focal_point: ''
  preview_only: false

projects: []
slides:
---
