# museum-api
|  发布日期 | 2019-12-01 |
 | -- | -- |
 |  名称 | 不完美的天使 |
 |  文件现状 | 已完成 |
 |  文件的主人 |  刘主茵|
 |  领头的设计师 | 刘主茵 |
 |  领头的开发者 |  刘主茵|
 |  领头的测试者 |  刘主茵 |
# 价值主张设计：
运用百度云人体检测api和智能对话定制与服务平台api为身障人士和多动症患者提供细致的关注和关爱。人体检测api通过实时检测身障人士和多动症患者的肢体动作来推测和判断其是否遇到困难或其行为会产生危险性，而智能语音交互api则用于向身障人士发出询问和为提供咨询和求助的渠道。
## （一）加值宣言：
1. 人体检测api，检测图像中的所有人体，标记出每个人体的坐标位置；不限人体数量，适应中低空斜拍、人体轻度遮挡、截断等场景检测图像中的所有人体，识别人体的20余类通用属性，包含性别年龄、服饰类别、服饰颜色、佩戴物、行为动作
2. 智能语言交互api，提供融合组合语义推导、语义匹配的对话理解技术，预置涵盖生活娱乐、设备控制等领域的可干预对话能力及50+场景的词典，助开发者高效定制对话能力,从而完善服务生态。
## （二）核心价值：（最小可行性产品）
1. 检测残障人士的动作行为，及时获知其可能的需求和可能产生的危机。
2. 检测多动症患者的动作行为，及时获知其行为是否存在一定的危害性或需要得到帮助。
2. 为身障人士和多动症患者定制智能对话p平台，提供咨询服务。
## (三）人工智能概率
1. 人体检测功能可以检测到用户姿势的多个参数，但是无法将这个数据进行组合推测，需要在后台建立数据库进行推测
2. 智能语言交互API在语言的回答上大部分是可取的，但是回答的有些比较不针对，所以还得依照博物馆的情况为其回答进行进一步的设定
## （四）背景：
博物馆的游客众多，其中身障人士和多动症人士作为其中的一种较为特殊群体，他们存在一些特殊的需求并且在观赏过程中会遇到一些困难甚至存在一定的安全风险。
## （五）目的：
保护身障人士参观博物馆时的权利，给予他们特殊的关怀，及时检测他们的需求并且帮助他们解决，从而弥补他们因身体原因而导致的一些不便。而对于多动症患者一是做到一定程度的留意与监测，二是帮助和缓解其克制自己行为的难度。
## （六）用户：参观博物馆的身障人士和多动症患者
## （七）用户痛点：
1. 身障人士可能会有肢体行动、听力或其他方面的障碍，导致他们难以完成一些在参观中产生的任务，例如找不升降电梯，只能走楼梯；没有听到他人的的话语从而产生误解，无法很好的观看展品等
2. 身障人士用个人的某些需求交较难表达或是只有专业人士才能解答
3. 多动症患者活动较多、情绪易波动，容易受到周围环境的影响感到情绪急躁或产生多频率的某一行动的现象。
## （八）用户需求:（使用的人工智能要反映到需求列表中）
| 用户案例	| 对应标题	| 重要程度 |
| -- | -- | -- |
| 听力有障碍人士无法听到讲解员对展品的介绍	| 智能对话平台为听力障碍者发来相关展品的详细文字介绍	|低  |
| 行动不便人士想找到升降机去另一个楼层，想问路	| 智能对话平台根据其需求和通过人体检测获知他的周边情况，为其指路	|  中|
|  行动不便人士因人群较多无法靠近展品参观| 人体检测api得知情况后为期提供向导  |高|
|  多动症患者无法控制自己的行为多次触摸展品| 人体检测api得知情况上报相关人员该情况，及时的引导和制止  |高|
### 具体应用场景
在博物馆中，身障人士因个人身体存在的不便而在参观中产生困难，于是使用这款产品为其提供帮助
## （九）使用者交互与设计（axure产品原型）
### 框架图
![tu](https://github.com/nfu3059/API_ML_AI/upload)
### 原型图
![首页](https://github.com/nfu3059/graduation/blob/master/%E9%A6%96%E9%A1%B5.jpg)
![功能1](https://github.com/nfu3059/graduation/blob/master/%E5%B1%95%E8%A7%88%E6%B4%BB%E5%8A%A8.jpg)
![功能2](https://github.com/nfu3059/graduation/blob/master/%E6%B6%88%E6%81%AF.jpg)
![功能3](https://github.com/nfu3059/graduation/blob/master/%E6%88%91%E7%9A%84.jpg)
![功能4](https://github.com/nfu3059/graduation/blob/master/%E5%AE%A2%E6%9C%8D%E5%B9%B3%E5%8F%B0.jpg)
### 原型文件
[原型page]( http://nfunm059.gitee.io/yuan)
