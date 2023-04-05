# [Openbiox 社区开源之夏 2023 活动项目](https://github.com/openbiox/summer-ospp)

![](https://summer-ospp.ac.cn/img/indexBanner.jpg)

## 活动简介

开源之夏是由中科院软件所“开源软件供应链点亮计划”发起并长期支持的一项暑期开源活动，旨在鼓励在校学生积极参与开源软件的开发维护，培养和发掘更多优秀的开发者，促进优秀开源软件社区的蓬勃发展，助力开源软件供应链建设。

开源之夏活动组织方与国内外开源社区针对重要开源软件的开发与维护提供项目任务，面向全球高校学生开放报名中选学生将在项目资深开发者（项目导师）的指导下，参与开源贡献，完成开发工作并贡献给开源社区。

2023 年，Openbiox 生物信息学开源社区首次报名参加本次活动 。项目申请人（学生）成功参与并顺利结题将可以获得 8000（基础难度）、12000 （进阶难度）元现金资助。Openbiox 社区将提供额外项目支持。

## Openbiox 社区 2023 开源之夏拟申请项目（拟申请组委会支持项目）

### 项目一：Hiplot (ORG) 在线绘图网站工具开发及其 ChatGPT 人工智能辅助接口实现

#### 项目大背景

[Hiplot (ORG)](https://hiplot.cn) 于 2022 年 7 月发表于生物信息学领域国际知名期刊《生物信息学简报》（Briefings in Bioinformatics），该网站由包括上海交通大学医学附属瑞金医院、上海交通大学生命科学技术学院、上海交通大学附属第一人民医院、上海科技大学、中山大学、广东海洋大学以及 Openbiox 开源社区在内的多家国内单位/机构/生物信息学社区共同贡献的一个免费的、综合性生物医学数据可视化分析网站 Hiplot（ORG）。自 2020 年上线以来，Hiplot (ORG) 可视化工具箱已提供超过 240 个一键式数据可视化分析插件，涉及基础统计图形、组学和其他常见的生物医学数据可视化分析任务。注册用户近 3 万 5 千人，累计访问超 500 万次。

研究者（第一作者）之前发起了一个跨学科的生物信息学协作社区，Openbiox，并在这项工作中共同建立了一个新兴的易于使用和可扩展的在线网页分析工具，Hiplot（ORG）。据我们所知，这是目前最大规模的社区驱动的协作尝试之一，以期建立一个免费的网页服务来辅助高质量、发表级别的综合性生物医学数据交互式可视化分析工具。大多数现代统计图形已经在这个网页服务中实现。用户可以使用这个网站上的开放工具来进行日常的生物医学数据可视化分析，比如进行数据的相关性、分布、百分比、演变、流动关系、排名和空间特征分析，且不受操作系统和软件环境的限制。该网站还提供了与组学和临床数据分析相关的可视化功能则可以进一步辅助生物医学和生物学领域的研究人员开展相关研究工作。特别地，利用该网站提供的一键式分析工具，用户可以自由探索癌症多组学数据集、基因组结构、染色体分布、遗传变异、群体遗传学、基因表达谱、基因通路富集和肿瘤微环境（TME）。与此同时，他们还提供了许多基于机器学习的可视化分析功能，包括无监督聚类、降维算法（dimensionality reduction algorithm，DRA）、线性/非线性回归、荟萃分析、生存分析和疾病风险模型等，帮助用户关联其他临床特征，建立临床预测模型等。

#### 项目小背景/需求

1. Hiplot (ORG) 网站目前在生物/临床统计分析、一些前沿领域的绘图功能（单细胞、空间转录组等）方面功能仍相对欠缺，亟需在相关方向组织攻关和协作；
2. ChatGPT 提供了极佳的机会来让在线工具变得更加自动化和个性化：可以辅助我们完成数据的自动预处理和格式化、绘图样式的修改和调整等。因此我们希望可以打通自然语言处理的部分接口，允许用户输入自然语言或编程代码来自定义我们发布的数百个标准化绘图工具。

#### 项目产出要求

1. 新贡献至少 100 个统计/绘图工具插件（学生参与者至少完成其中 20 个工具的开发）；
2. 实现一个通用 R 包，接入 ChatGPT 和 编程语言进行数据预处理和 ggplot2 绘图对象的自定义，并至少完成和调试 10 个统计/绘图工具的测试；

#### 项目技术要求

项目申请人需要有较为扎实的数学/统计学背景知识，可以熟练使用 R 语言/统计/绘图工具包、熟悉 ChatGPT 接口和常用 Prompt，了解 Hiplot（ORG）绘图插件开发框架（见已发表论文），有单细胞数据分析、自然语言处理和 Web 工具开发经验优先。

#### 项目产出仓库

1. https://github.com/openbiox/hiplot-org-plugins ：绘图插件新增），Academic Free License version 3.0 协议，商业使用需获得工具开发人员授权；
2. https://github.com/hiplot/hiplotlib ：绘图插件本地执行框架，ChatGPT 接口实现仓库)；MIT 协议（完全自由使用）。

### 项目二：自动化建立临床模型（疾病亚型、预后分层）及其药物敏感性（待定）

#### 项目大背景

#### 项目小背景/需求

#### 项目产出要求

#### 项目技术要求

#### 项目产出仓库

## 其他社区支持项目（内部支持）

### No. 2023-1: Weekly Journal of Bioinformatics

-   Short Intro: This weekly magazine is maintained by Shixiang Wang at GitHub, which records weekly news or publications worth sharing and releasing on Sundays. More than 60 issues have been released so far: [Issues](https://github.com/ShixiangWang/weekly/tree/main/issues).
-   Difficulty: Easy
-   Requirements: An undergraduate level in biology and medicine; good reading and writing skills in English and Chinese.
-   Repo: [https://github.com/ShixiangWang/weekly](https://github.com/ShixiangWang/weekly).
-   Language requirements: Chinese.
-   Type: Education (News and Knowledge Transmission).
-   Participants: [Shixiang Wang](https://github.com/ShixiangWang) (Mentor), [kkjtmac](https://github.com/kkjtmac), [NiEntropy](https://github.com/NiEntropy), [He-Kai-fly](https://github.com/He-Kai-fly), [JnanZhang](https://github.com/JnanZhang), [Tomcxf](https://github.com/Tomcxf), [wangdepin](https://github.com/wangdepin).
-   Mentor Contact: Dr. Wang (shixiang1994wang@gmail.com), Ph.D., PostDoc Position at Sun Yat-Sen University Cancer Center.

### No. 2023-2 Systematic Evaluation of Visual Analytics Methods

-   Short Intro: The project will conduct a systematic evaluation of some commonly used visualization analysis methods in the biomedical field. It will provide detailed methodological evaluation results for researchers and guide the optimization and development of relevant methodologies. The project may involve the systematic collation and classification of relevant visualization methods, the construction of standard test data sets, the design of performance evaluation indicators, and actual software evaluation.
-   Difficulty: Intermediate
-   Requirements: Undergraduate students in computer science, or graduate students related to bioinformatics
-   Repo: [https://github.com/openbiox/benchmark](https://github.com/openbiox/benchmark).
-   Language requirements: English.
-   Type: Benchmarks
-   Participants: [Jianfeng Li](https://github.com/Miachol) (Mentor)
-   Mentor Contact: Dr. Li (lee_jianfeng@openbiox.org), Ph.D., Research Associate of Shanghai Institute of Hematology, State Key Laboratory of Medical Genomics, National Research Center for Translational Medicine at Shanghai, and Ruijin Hospital Affiliated to Shanghai Jiao Tong University School of Medicine.

### No. 2023-3 Next version of Visualization System

-   Short Intro: We plan to develop the next version of visualization system. The gold of this project is to make the plot easier, faster, and more functions.
-   Difficulty: Hard
-   Requirements: Undergraduate students in computer science, or graduate students related to bioinformatics
-   Repo: Todo
-   Language requirements: English.
-   Type: Software

### No. 2023-4 Clinical-level RNA-Seq, Panel, WES, and WGS Full Workflow

-   Short Intro: The project aims to maintain and establish a full pipeline that can be directly used in clinical molecular diagnosis, in order to provide complete clinical data analysis and reporting capabilities.
-   Difficulty: Hard
-   Requirements: Independent coding, familiarity with workflow languages, and experience in clinical data analysis
-   Repo: [https://github.com/clindet](https://github.com/clindet).
-   Language requirements: English.
-   Type: Translational Medicine

### No. 2023-5 Evaluation of Data Analysis Methods: metabolomics, proteomics and spatial transcriptomics

-   Difficulty: Hard
-   Requirements: Familiar with omics data analysis, experience in single cell, metabolomics and proteomics data analysis is preferred.
-   Repo: [https://github.com/openbiox/benchmark](https://github.com/openbiox/benchmark).
-   Language requirements: English.
-   Type: Benchmarks

### No. 2023-6 Multi-omics Data Integration Tool For Single Sample/Cohorts

-   Short Intro: The project aims to establish bioinformatics methods that integrate multi-omics data (single-sample and multi-sample) and the potential biologically/clinically meaningful knowledge base.
-   Difficulty: Hard
-   Requirements: Familiar with omics data analysis, experience in single cell, metabolomics and proteomics data analysis is preferred.
-   Repo: [https://github.com/openbiox](https://github.com/openbiox).
-   Language requirements: English.
-   Type: Software

### No. 2023-7 Structural Variation Visualizer

-   Short Intro: This project aims to provide new visual tools for structural variation in genomic and RNA-sequencing data. It can provide the ability to integrate additional information including gene expression, eQTL, and sQTL, etc.
-   Difficulty: Hard
-   Requirements: Omics+ Rust/Golang/Python Programming.
-   Repo: [https://github.com/openbiox](https://github.com/openbiox).
-   Language requirements: English.
-   Type: Software

### No. 2023-8 Systematic Evaluation of Cluster Analysis Methods/Processes

-   Short Intro: This project aims to systematically evaluate currently known methods for unsupervised cluster analysis (with different preprocessing steps), considering RNA-Seq and methylation-sequencing data as data input.
-   Difficulty: Intermediate
-   Requirements: Familiar with clustering algorithms.
-   Repo: [https://github.com/openbiox](https://github.com/openbiox).
-   Language requirements: English.
-   Type: Benchmarks

### No. 2023-9 Tumor Clone Evolution Toolkit

-   Short Intro: This project aims to establish a tumor clonal evolution tool based on gene mutation/expression/alternative splicing.
-   Difficulty: Hard
-   Requirements: Familiar with tumor evolution and Python/R.
-   Repo: [https://github.com/openbiox](https://github.com/openbiox).
-   Language requirements: English.
-   Type: Software

### No. 2023-10 Template Library For Thesis

-   Short Intro: Reduce our extra time on writing the thesis/paper.
-   Difficulty: Easy
-   Repo: [https://github.com/openbiox/thesis-template](https://github.com/openbiox/thesis-template).
-   Type: Education

### No. 2023-11 Development of Visualization Tool For Single-cell Multi-omics Data

-   Short Intro: This project aims to establish a single-cell multi-omics data visualization tool based on the Shiny framework, which integrates the preprocess, statistical method and visualization methods in single-cell multi-omics data (scRNA-seq, scATAC-seq, and scTCR-seq, etc.). It will generate potential knowledge and biological/clinical significance.
-   Difficulty: Hard
-   Requirements: Familiar with single-cell multi-omics data analysis, experience in single-cell, transcriptomics, and epigenomics data analysis is preferred.
-   Repo: [https://github.com/openbiox](https://github.com/openbiox).
-   Language requirements: English.
-   Type: Software

### No. 2023-12 Evaluation of Cloud Bioinformatics Workflow Management System

## 补充说明

Openbiox 开源社区为非营利性社区组织，不归属于任何商业公司，项目产出原则上由项目参与人或其指定机构共同所有，项目产出和知识产权申请（软件著作权等）均需主要项目参与人知情同意。

Openbiox 商标此前由项目合作方代为托管，可随时捐赠开源基金会或其他非营利性开源项目运营机构，欢迎大家与我们进行联系：committee@openbiox.org
