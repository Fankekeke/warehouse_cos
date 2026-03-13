### 基于SpringBoot + Vue的仓库管理系统.

库存管理、进销存同、批次追溯管理、入库出库、安全库存预警

##### 基础档案与准入管理
###### 商户管理： 统一维护合作商户信息与资质档案，建立供应商信用体系，为后续采购与结算提供基础数据支持。

###### 套餐管理： 灵活配置标准化的物品组合包，简化商户申请流程，实现高频领用物资的快速打包与高效下发。

###### 耗材类别： 建立科学的物品分类体系，通过树状结构管理资产属性，确保海量库存物资的检索与统计条理清晰。

##### 需求申请与审批流
###### 制定申请物品： 业务端根据实际需求发起领用或采购申请，详细记录物品规格与用途，启动标准化审批工作流。

###### 审批记录管理： 实时追踪申请单据的审核进度与历史记录，通过多级权限控制确保物资调拨决策的合规与严谨。

###### 制定采购计划： 管理员根据审批通过的申请自动汇总生成采购单，科学规划进货周期，确保库房水位维持在安全区间。

##### 仓储作业与全链路追踪
###### 库房管理/物品明细： 数字化展示库位分布与实时库存清单，精确记录每一件物品的规格与位置，实现货位精细化管控。

###### 采购员采购入库： 记录采购员执行进度并核实到货数量，通过扫码入库自动更新库存，确保账面资产与实物高度一致。

###### 出库记录管理： 严格审核出库指令并记录领用人去向，系统自动扣减即时库存，实现物资从入库到消耗的全程溯源。

##### 数据分析与决策支持
###### 报表统计： 聚合入库、出库及耗损等多维数据生成可视化看板，通过库龄分析与周转率报表辅助优化库存配置。

#### 安装环境

JAVA 环境 

Node.js环境 [https://nodejs.org/en/] 选择14.17

Yarn 打开cmd， 输入npm install -g yarn !!!必须安装完毕nodejs

Mysql 数据库 [https://blog.csdn.net/qq_40303031/article/details/88935262] 一定要把账户和密码记住

redis

Idea 编译器 [https://blog.csdn.net/weixin_44505194/article/details/104452880]

WebStorm OR VScode 编译器 [https://www.jianshu.com/p/d63b5bae9dff]

#### 采用技术及功能

后端：SpringBoot、MybatisPlus、MySQL、Redis、
前端：Vue、Apex、Antd、Axios
报表：Spread.js

平台前端：vue(框架) + vuex(全局缓存) + rue-router(路由) + axios(请求插件) + apex(图表)  + antd-ui(ui组件)

平台后台：springboot(框架) + redis(缓存中间件) + shiro(权限中间件) + mybatisplus(orm) + restful风格接口 + mysql(数据库)

开发环境：windows10 or windows7 ， vscode or webstorm ， idea + lambok

商户管理，套餐管理，申请记录，库房管理，入库记录，出库记录，采购计划，报表统计，耗材类别，出入库物品明细

制定申请物品->管理员审批制定采购计划->采购员采购->入库->出库


#### 前台启动方式
安装所需文件 yarn install 
运行 yarn run dev

#### 默认后台账户密码
[管理员]
admin
1234qwer

[采购员]
caigou
1234qwer

[用户]
lisi
1234qwer
#### 项目截图

|  |  |
|---------------------|---------------------|
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080753720.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080969395.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080712574.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080953291.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703084753472.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080878407.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703081092356.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080862614.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703081076525.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080844691.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703081052848.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080830613.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703081035620.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080818367.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703081023390.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080803381.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080992261.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080792182.jpg) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1703080981840.jpg) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/work/936e9baf53eb9a217af4f89c616dc19.png) |


#### 演示视频

暂无

#### 获取方式

Email: fan1ke2ke@gmail.com

WeChat: `Storm_Berserker`

`附带部署与讲解服务，因为要恰饭资源非免费，伸手党勿扰，谢谢理解😭`

> 1.项目纯原创，不做二手贩子 2.一次购买终身有效 3.项目讲解持续到答辩结束 4.非常负责的答辩指导 5.**黑奴价格**

> 项目部署调试不好包退！功能逻辑没讲明白包退！

#### 其它资源

[2025年-答辩顺利通过-客户评价🍜](https://berserker287.github.io/2025/06/18/2025%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2024年-答辩顺利通过-客户评价👻](https://berserker287.github.io/2024/06/06/2024%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2023年-答辩顺利通过-客户评价🐢](https://berserker287.github.io/2023/06/14/2023%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2022年-答辩通过率100%-客户评价🐣](https://berserker287.github.io/2022/05/25/%E9%A1%B9%E7%9B%AE%E4%BA%A4%E6%98%93%E8%AE%B0%E5%BD%95/)

[毕业答辩导师提问的高频问题](https://berserker287.github.io/2023/06/13/%E6%AF%95%E4%B8%9A%E7%AD%94%E8%BE%A9%E5%AF%BC%E5%B8%88%E6%8F%90%E9%97%AE%E7%9A%84%E9%AB%98%E9%A2%91%E9%97%AE%E9%A2%98/)

[50个高频答辩问题-技术篇](https://berserker287.github.io/2023/06/13/50%E4%B8%AA%E9%AB%98%E9%A2%91%E7%AD%94%E8%BE%A9%E9%97%AE%E9%A2%98-%E6%8A%80%E6%9C%AF%E7%AF%87/)

[计算机毕设答辩时都会问到哪些问题？](https://www.zhihu.com/question/31020988)

[计算机专业毕业答辩小tips](https://zhuanlan.zhihu.com/p/145911029)

#### 接JAVAWEB毕设，纯原创，价格公道，诚信第一

`网站建设、小程序、H5、APP、各种系统 选题+开题报告+任务书+程序定制+安装调试+项目讲解+论文+答辩PPT`

More info: [悲伤的橘子树](https://berserker287.github.io/)

<p><img align="center" src="https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/%E5%90%88%E4%BD%9C%E7%89%A9%E6%96%99%E6%A0%B7%E5%BC%8F%20(3).png" alt="fankekeke" /></p>
