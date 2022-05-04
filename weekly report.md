# 7th week: 25.04 - 01.05.2022
## 综述  
我们离正式开发越来越近啦，无论是技术组还是运营组，姐妹们都在按节奏有序地推进：  

PM和TPM
- 在过去的一周里输出了详细的领养人流程图
- 计划与发起人一起将产品框架与规划文档化，以便指导后续的任务  

uxui  
- 参考开发姐妹的建议对用户流程图进行了修改
- 经过品牌探索workshop后，将在接下来一周出配色方案与logo草图  

npo姐妹  
- 完成了领养人审核问卷的基础版，将继续优化各个问题的选项
- 开始做正式版领养人审核问卷  

新媒体  
- 梳理了品牌定位，确定了未来三个月的[发展计划](https://miro.com/app/board/uXjVO6GBdjA=/)
- 明确了宣传平台与各个平台负责人，将在接下来这周陆续开设账号  

谢谢大家的付出，祝姐妹们有一个阳光明媚的五月！  






## 成果链接 & 会议记录
### PM & TPM
- [领养人流程图](https://www.processon.com/view/link/626eec286376891e1c1f4298)

### UXUI：
- [info与idea汇总板块](https://miro.com/app/board/uXjVOADbDC0=/)  

### 前端：
- [会议记录](https://demo.hedgedoc.org/IuxuzXNcRiCPIl_TCDAAaQ?both)

### 后端：
- [会议记录](https://github.com/Furiends/Backend/blob/main/meeting_minutes.md)

### AI:
- [会议记录](https://github.com/Furiends/AI/blob/main/meeting%20notes.md)

### 新媒体：
- [新媒体运营框架与时间线](https://miro.com/app/board/uXjVO6GBdjA=/)


---
# 6th week: 18.04 - 24.04.2022
## 综述  
首先呢要欢迎我们新加入的后端姐妹Cherie🎉  
然后呢，在过去的这一周里，我们项目的开发准备工作进入了尾声：  
uxui姐妹超强输出，  
- 通过对2B问卷与竞品调研的结果分析确定了top3痛点，
- 并主持了与PM和技术组姐妹的workshop，通过头脑风暴的方式初步确定了三个痛点的解决方案。
- 结合workshop的成果与PM的mvp1功能清单，输出了[用户流程图草稿](https://miro.com/app/board/uXjVO6AHydU=/)

> 用户流程图草稿在由PM与技术组确认后，将由PM将其划分为不同模块，决定开发顺序。  

在PM & tPM会议上确定了五月的一些重要时间点， 
- 5月7日，PM出mvp1的PRD文档，后端和AI姐妹可以根据PRD开始做一些不依赖于原型图的开发工作
- 5月14日，uxui交付第一个模块的低保真原型给前端，前端开始开发
- 5月28日，uxui交付第一个模块的高保真原型

前端
- 确定参照Airbnb的代码规范进行开发  
- 丰富例会形式，加入pair programming session   

后端
- 用开源小程序练习spring boot，本地改写出我们项目所需基本features

NPO姐妹
- 收集了多个机构的领养人资质审核问卷，分别整理出了猫猫与狗狗的审核表单初版，列出了我们平台将来要考虑的审核点，并依据重要程度，对这些要点进行了赋值评分
- 接下来会将领养人审核表单拆分为“基础版”与“正式版”，分别作为用户注册时的基础审核问题与申请领养时的严格审核问卷。  
> 初版审核表单已交给AI组用于训练机器筛选模型

AI姐妹  
- CV组收集了千张猫猫照片，利用kaggle数据集与Oxford数据集做宠物分类模型demo，将于下周进行测试
- DA组分享并讨论了提高收养率的机器学习模型(adoption rates increasing model)

新媒体姐妹  
- 将与发起人，pm，uxui姐妹一起探索品牌定位  



五一将至，预祝大家节日快乐！假日周末为大家准备了多场会议供围观，周末到来前会在群里终极预告，see you ❤

## 成果链接 & 会议记录
### UXUI：
- [Brainstorm workshop 成果](https://miro.com/app/board/uXjVO-PX0uk=/)
- [Flowchart mvp1 用户流程图草稿](https://miro.com/app/board/uXjVO6AHydU=/)  

### 前端：
- [会议记录](https://demo.hedgedoc.org/IuxuzXNcRiCPIl_TCDAAaQ?both)

### 后端：
- [会议记录](https://github.com/Furiends/Backend/blob/main/meeting_minutes.md)

### AI:
- [会议记录](https://github.com/Furiends/AI/blob/main/meeting%20notes.md)

### NPO:
- [狗狗领养人审核条件赋值表](https://docs.qq.com/sheet/DS0xNdnFoTUpMS29D)
- [猫猫领养人审核条件赋值表](https://docs.qq.com/sheet/DRUpObm5LQmJqclls)




---
# 5th week: 11.04 - 17.04.2022
## 综述  
出于各组的需要，在过去的一周里，我们又迎来了3名npo姐妹烁烁、墨鱼和洋洋，和2名前端姐妹加贝和阿若，非常欢迎大家的加入！  
同时我们也有了自己的中文名<b>“茸茸星球”</b> ❤ 耶  

PM & TPM 会议上，综合考虑了用户需求/终端用户使用习惯/开发学习成本/中期寻求资金支持/推广难易度/一期数据回收量等因素后，最终确定了第一阶段的开发内容:  
<b>B端小程序 + C端小程序 + 网页端组织展示页面</b>  

uxui姐妹
- 在过去的一周完成了竞品调研
- 同时对回收的需求进行了分析，将于北京时间本周日早九点与PM和技术组姐妹开展探讨需求与功能的workshop
> workshop结束后由PM输出PRD文档  

npo姐妹
- 分组制作领养人审核信息表单

前端
- 将在这一周确定代码审查规范与ui框架
- 使用Vue.js练习filter feature  

后端
- 确定了开发语言为java，开发框架为Spring Boot
- 输出了AWS EC2文档
- 将在本周的workshop中与AI姐妹、PM共同确定数据库  

AI姐妹们  
- CV组经测试确定了背景替换模型的可实施性，
- 选择了可行的图片压缩算法，
- 接下来计划将动物毛色分类算法应用到程序上
- DA组确定了智能推荐系统的可实施性，将在未来一段时间内寻找数据


由于项目有不同阶段，到目前为止各个组的参与度也不同，也许有的姐妹已经进入了疲惫期，而有的姐妹还没能深度投入。希望大家给我们的小小事业小小社区一点时间去成长，同时也欢迎大家随时公聊或私聊建议与想法。祝我们带着信心继续往前走，一起把想做的事情做下去。

## 成果链接 & 会议记录
### UXUI：
- [会议记录](https://github.com/Furiends/UXUI/blob/main/meeting%20note.md)
- [竞品调研结果](https://docs.google.com/spreadsheets/d/1pdruLOvovZ-0p6Kg3lq3QgrvKE_KDGiJU3BXhE8C0_U/edit?resourcekey=0-dCjA0PHl8JAf_1ktwv373g#gid=2073884517)

### 前端：
- [会议记录](https://demo.hedgedoc.org/IuxuzXNcRiCPIl_TCDAAaQ?both)

### 后端：
- [会议记录](https://github.com/Furiends/Backend/blob/main/meeting_minutes.md)

### AI:
- [会议记录](https://github.com/Furiends/AI/blob/main/meeting%20notes.md)

### NPO:
- [任务分配](https://github.com/Furiends/NPO/blob/main/images/151650364094_.pic.jpg)

---
# 4th week: 03.04 - 10.04.2022
## 综述
在过去的一周里，我们许多小组都有了固定的[例会时间](https://github.com/Furiends/PM/blob/main/Regularly-Scheduled%20Meetings.md)。
PM & TPM明确了项目推进过程中需要使用的各平台的职能：
![项目管理工具及其职能（图1）](https://github.com/Furiends/PM/blob/0be433b084ad2b8b0ce18cb1e6f5fbd571eaabd8/images/%E9%A1%B9%E7%9B%AE%E7%AE%A1%E7%90%86%E5%B7%A5%E5%85%B7%E8%81%8C%E8%83%BD.png)  

与此同时，我们的用户调研进入了后期。  
在NPO姐妹的全力努力下，
- 于上周六结束了2B调研问卷的发放，五天内共收回48份。
- 此外，NPO姐妹们也在收集低质量宠物送养照片，作为AI姐妹训练图片美化算法的样本集。
- 接下来将制作领养人审核信息表单的初稿，
- 并陆续调查打捞全国各处的救助组织，与之建立联系。

uxui姐妹  
- 筛选出了要重点调研的竞品，将在接下来的一周内完成竞品调研。  
- 同时，收回的2B问卷已交到uxui姐妹手上，她们将用未来两周的时间分析整理问卷的调研结果，提炼需求。  

新媒体姐妹  
- 用过去的两周时间详尽地整理了小红书/微博/抖音/豆瓣/b站上与我们平台相似类型的热门账号的用户画像及内容特色。  
- 将在接下来的时间里与PM,UXUI,发起人一起合作探索确定Furiends品牌定位。  

前端姐妹  
- 在彭彭的建议下重新考虑开发框架，最终决定基于vue.js并使用uni-app框架开发全平台，用SASS做CSS编译。  
- 接下来学习uni-app，并使用vue.js练习sign up feature  

后端姐妹  
- 确定使用Python开发。接下来调研Django, Flask和Fastapi框架，三选一  
- 继续学习部署aws并输出使用文档，学习GitHub Actions  

AI姐妹  
- CV组确定背景分离和图片压缩功能可使用的模型并测试；确定数据分析开发平台  
- DA组学习智能推荐和排序相关模型  
 
项目已经run了一个月啦！撒花~ 感恩大家出于爱意聚到一起做这件事。希望在接下来的日子里我们继续一起快乐成长，一起努力圆梦。同时也希望大家互相尊重，积极沟通，无论是缺席会议还是无暇顾及项目相关工作，请提前向一起合作的伙伴说明情况。谢谢姐妹们！


## 成果链接 & 会议记录
### PM&TPM：
- [项目管理工具及其职能 miro链接](https://miro.com/app/board/uXjVO-PX0uk=/)
- [Furiends 四月计划](https://www.processon.com/view/link/6244023e1efad40756d366a9#map)  
- [各组例会时间及会议链接](https://github.com/Furiends/Private#readme)

### UXUI：
- [2B问卷调研结果](https://docs.google.com/spreadsheets/d/1sws-2KmPS0x-sp1lqJ7aGHYMHaczdqom82j9A-fdtn8/edit#gid=0)
- [2B问卷调研结果图表统计图（按问题划分）](https://slack-files.com/T0356J16W02-F03AZ3G5RPE-6219c16e40)
- [UXUI组四月任务分配与截止时间](https://docs.google.com/spreadsheets/d/1xfTIdd8zJHDkJUrDygJWQcLCLondpIwflx5IZ7CjGfM/edit#gid=0)

### 前端：
- [会议记录](https://demo.hedgedoc.org/IuxuzXNcRiCPIl_TCDAAaQ?both)

### 后端：
- [会议记录](https://github.com/Furiends/Backend/blob/main/meeting_09Apr2022.md)

### AI:
- [会议记录](https://github.com/Furiends/AI/blob/main/meeting%20notes.md)

### NPO：
- [NPO任务文档](https://docs.qq.com/doc/DSEtpRHd2RnlDdEJN)

### 新媒体:
- [SNS平台用户画像及内容特点调查报告](https://github.com/Furiends/Media/blob/main/resource.md)



---

# 3rd week: 28.03 - 03.04.2022
## 综述
上一周我们陆续迎来了新的姐妹怡静(PM)，Lila(NPO)，米喵(新媒体)，Caicai(AI)，欢迎撒花~   
与此同时，我们的项目也开始快速运转起来:  

首先是PM/TPM
- 对我们项目的整体框架做了一个展示，
- 随后迅速安排了全员的四月计划，
- 再次明确我们的项目定位，即：<b>集项目开发与学习社区于一体，实现最终产品不是唯一目标，大家在过程中的成长与收获同样重要</b>。

uxui姐妹们
- 重新制定了需求调研计划，决定将机构(2B)与个人(2C)分开调研。
- 随后对有救助经验的姐妹们进行了采访，敲定了2B问卷最终版，已预备发放。

> 问卷的发放工作将主要由NPO姐妹负责。

在过去的一周里NPO姐妹
- 为2B问卷提供了内容支持，
- 分类整理按现有机构名单，为深入机构做准备。

AI姐妹  
- 提取了有救助经验的姐妹们的关键需求后，分为CV组和DA组，在接下来一周将分别对图片压缩及美化、黑名单数据收集、智能排序与推荐等功能的实现开展技术调研。

前端姐妹
- 确定了react框架和TypeScript语言,
- 接下来一周将进行SignUp feature的code练习。

后端姐妹
- 开始调研后端框架、数据库，
- 开始学习部署aws服务器。

新媒体姐妹
- 延续上周的安排，对各大SNS平台流量及用户进行调研。


最后想说，这里只是简单罗列了一些结果和结论，但是每条通向结论的路上都包含了非常非常多的努力和付出。所以想再特别感谢过去一周里最辛苦最忙碌的pm、uxui姐妹和NPO姐妹~！谢谢你们！也谢谢所有姐妹的认真积极和热情！

### 分享会计划（具体时间待定）  
【架构流程经验分享会】面向前端/后端，主讲人：彭彭，时间：4月9/10  
【CICD分享会】面向前端/后端/AI 姐妹，主讲人：Alice， 时间：4月23/24  
【开源项目分享会】面前全体，主讲人：Soledad，时间：4月24  





## 成果链接 & 会议记录
### PMs：
- [Furiends 整体框架](https://www.processon.com/embed/624189941e0853078935d0eb)  
- [Furiends 四月计划](https://www.processon.com/view/link/6244023e1efad40756d366a9#map)  
- [Furiends 功能清单（一期简版)](https://www.processon.com/view/link/6249b65e1e08530789495640#map)  
- [PM & TPM 会议记录](https://docs.google.com/document/d/1X0qaFgdfi42xZH344wK7FhznTz-cnNLb/edit)

### UXUI：
- [最终版2B问卷](https://docs.google.com/document/d/15oi1wsZ--rXVPv7weM5oWU-R7fS-SPGzS77ofz40rPQ/edit)
- [问卷入口 *请大家不要填写哈，这是给救助机构填的](https://wj.qq.com/s2/9977460/61b1/)
- [UXUI组四月任务分配与截止时间](https://docs.google.com/spreadsheets/d/1xfTIdd8zJHDkJUrDygJWQcLCLondpIwflx5IZ7CjGfM/edit#gid=0)

### 前端：
- [会议记录](https://demo.hedgedoc.org/IuxuzXNcRiCPIl_TCDAAaQ?both)

### 后端：
- [会议记录](https://github.com/Furiends/Backend/blob/main/meeting%20notes.md)

### AI:
- [会议记录](https://github.com/Furiends/AI/blob/main/meeting%20notes.md)

### NPO：
- [不同类型救助机构比较表格](https://onedrive.live.com/view.aspx?resid=BD140D9542C4D73A!1903&ithint=file%2cxlsx&wdhostclicktime=1649112643371&authkey=!ACrzMoyzP2ilia0) 

### 新媒体
- [会议记录](https://drive.google.com/file/d/1hdgr7h01fbf0oEV0rVLafHmQfQsnxnPm/view?usp=sharing)
