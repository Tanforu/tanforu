---
title: Resources for newbies
layout: simple
---
<script src='https://unpkg.com/mermaid@7.1.2/dist/mermaid.min.js'></script>
<script>mermaid.initialize({startOnLoad:true});</script>

# Resources for newbies
# 新手资源

* [YAML 语言教程](http://www.ruanyifeng.com/blog/2016/07/yaml.html?f=tt)及[YAML 简介](https://www.ibm.com/developerworks/cn/xml/x-cn-yamlintro/index.html)
* Jekyll 的[配置](http://jekyllcn.com/docs/configuration/)[url, baseurl配置](https://byparker.com/blog/2014/clearing-up-confusion-around-baseurl/)
  * 从 Github 抄 [mattcouchman/jekyll-resume](https://github.com/mattcouchman/jekyll-resume)
  * 观察 [_config.yml](https://github.com/hanteng/jekyll-resume/blob/master/_config.yml)
* Jekyll 的[头信息](http://jekyllcn.com/docs/frontmatter/)如何让.md档转换成.html档
  * 前端 [Jekyll 简历 主题](https://hanteng.gitee.io/jekyll-resume/README.html)
  * 後端 [Jekyll 简历 主题](https://gitee.com/hanteng/jekyll-resume/blob/master/_config.yml)
  * 观察[提交史 (commit history)](https://gitee.com/hanteng/jekyll-resume/commits/master)
* 自己实践 [创建自定义的 Jekyll 404 页面](https://cn.yizeng.me/2013/05/26/create-a-custom-jekyll-404-page/)
* 看看[有道云笔记Markdown指南](http://note.youdao.com/iyoudao/?p=2411)，markdown可以作图像这个例子[专业核心课：《网页设计与制作》](https://hanteng.gitee.io/minimal-mistakes/%E7%BD%91%E7%BB%9C%E4%B8%8E%E6%96%B0%E5%AA%92%E4%BD%93%E4%B8%93%E4%B8%9A/importance_web_design_to_program_newmedia/)，[後遄代码在此](https://gitee.com/hanteng/minimal-mistakes/blob/master/_posts/2018-06-20-importance_web_design_to_program_newmedia.md)要怎麽抄用？
  * 用``` ...  ``` 行不通
  * 需要加javascript 
  * 及标出div class="mermaid"
  
<div class="mermaid">
graph LR;

Tech>网络新媒体技术与协作] --> Web
Tech --> Information_Visualization
Tech --> Python
Web --> |技术栈线|Bootstrap[前端开发框架]
Bootstrap --> |技术栈线|NodeJS[网新交互技术栈基础架]
NodeJS  --> |技术栈线|Vue[APP设计与制作]
Web --> |交互界面|Interactions[互动技术与应用]
Interactions --> |交互界面|Vue
Information_Visualization>信息可视化设计]--> |建立分析基础|Big_Data
Information_Visualization --> |建立分析基础|UX
Information_Visualization --> |应用设计|Interactions
Big_Data[大数据] --> |应用设计| API_ML_AI[API机器学习与人工智能]
Big_Data -->|应用设计| Big_Data_Capacity[大数据能力建设]
Big_Data --> |应用设计|Platform[平台经济与创新]
Python>Python语言] --> |建立分析基础|Big_Data
Python --> |技术栈线|NodeJS[网新交互技术栈基础架]
Web>网页设计与制作] --> |建立分析基础|UX[新媒体分析和用户体验]
Web --> |建立敍事基础|Convergence[媒介融合]
Web --> |建立敍事基础|Video_Editing[数字音视频编辑]
Convergence --> |应用设计|Video_Editing
Web --> |建立分析基础|Online_Survey[线上调查与统计]
Online_Survey --> |建立分析基础|User_Research[用户研究]
Convergence --> Platform
Python --> |建立基础|API_ML_AI
UX --> |应用设计|API_ML_AI
UX --> |应用设计|User_Research
UX --> |应用设计|Platform
Platform --> |应用设计|Vue
User_Research --> |应用设计|Vue
API_ML_AI --> |应用设计|Vue
Big_Data_Capacity --> |应用设计|Vue
</div>