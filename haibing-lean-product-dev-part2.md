# 精益产品开发
## Part2 方法
### 6.看板方法和看板实践体系
* 限制在制品形成虚拟看板拉动机制
* 产品开发的看板方法
    * 建立看板系统
        * 可视化价值流动
            * 可视化用户价值
            * 可视化用户价值端到端的流动过程
            * 可视化问题和瓶颈
        * 显示化流程规则
            * 流转规则
            * 协作规则
        * 控制在制品数量
            * 看板方法核心，可以形成拉动机制，暴露问题和瓶颈
    * 运作看板系统
        * 管理工作项流动
            * 管理价值的输入、中间过程和输出
                * 就绪队列填充活动
                * 看板站会
                * 发布评审
            * 目的：使用户价值顺畅、高质量的流动
        * 建立反馈，持续改进
            * 流动是否顺畅的反馈
            * 质量问题的反馈
* 常见问题
    * 下游有能力（在制品未达到上限），才能从上游拉入新的工作
    * 看板方法所发挥的作用是加速反馈，以更好的支持价值探索和验证
### 7. 可视化价值流动（上）：案例
* 看板系统优化案例
    * 原有前后端分离的电子看板的问题
        * 对产品经理不友好，没有反映用户价值端到端的流动过程
        * 没有反映团队协作的过程
        * 不能即时和清晰的展示问题和瓶颈
* 质量管理之父戴明说过：“如果你不能以一个清晰的过程来展示你所从事的工作，你就不会真正了解自己在做什么。”
* 设计看板系统的要求
    * 看板系统能全面地反映需求交付过程么？
    * 瓶颈和问题能在看板墙上得到即时体现么？
    * 团队可以根据看板墙上的信息协作和做决定么？
* 故事：以简短语言描述用户的具体需求，故事应该是完整可测试的，且规模相对较小
### 8. 可视化价值流动（下）：看板系统建模
* 看板系统设计原则
    * 体现价值
        * 需求
        * 探索
        * 技术改造
    * 反映协作
        * 环节切换
        * 环节内完成
        * 最终价值合并输出
    * 暴露问题
        * 实现中的问题
        * 实现缺陷
        * 操作问题
* 看板系统设计的步骤
    * 一、分析价值流动过程
        * 识别团队交付的价值类型
            * 管理学大师德鲁克说：一个组织的价值只能存在于其外部
            * 从团队外部视角审视团队提供哪些服务
        * 确定看板系统的基本流动单元
            * 按占比确定”基本流动单元“和”次要流动单元“
        * 分析流动单元的流动步骤
        * 识别流动过程中的价值分解和合并
    * 二、选取可视化设计元素
        * 队列
        * 卡片
        * 标志
        * 泳道
        * 区域
    * 三、建模价值流动
* IT圈里有一句术语“Garbage in， Garbage out”
### 9. 显示化流程规则
* 团队成员对流程规则形成一致的理解和承若，并真正“拥有”这些规则
* 流程规则分类
    * 价值流转规则
    * 周期性事件相关的规则
    * 其他协作规则
* 显示化流程规则操作步骤
    * 组织和明确流程规则
    * 团队共同拥有流程规则
    * 持续改进流程规则
### 10. 控制在制品数量（上）：为什么要控制
* 目的
    * 加速价值交付
    * 即时暴露问题
* 用户视角判断在制品
* 在制品就是所有已经开始但还没有完成价值交付的工作
* 开发管理的基本单元是在制品
* 产品中在制品不可见，所以很难有效管理
### 11. 控制在制品数量（中）：控制什么
* 暂缓开始、聚焦完成
* 问题：现实中交付压力非常大，控制在制品数量很难执行下去，怎么办？
* 回答：面临压力就增加并行，这是自然的反应，但不是正确的反应，它往往会降低有效产出
### 12. 控制在制品数量（下）：如何控制
* 有意思的湖水岩石效应比喻
* 限制在制品的原则
    * 现实
    * 有用
* 个人经验：每一两周达到上限一次，是一个合适的初始值
* 合适的在制品限制数量，应该偶尔被触及，从而为团队发出信号；但也不总是被触及，避免频繁打断团队的工作
* 应该逐步降低在制品数量，逐步解决深层次的问题
* 随着在制品数量的降低，问题会暴露得更加充分，层次更深
* 确定初始限制值
    * 常用的方法：根据团队人数，乘以合理的并行系数
### 13. 管理价值流动（上）：看板站会
* 协调人带领团队成员从右至左走读看板
### 14. 管理价值流动（中）：就绪队列填充
* 就绪队列填充的原则
    * 越频繁的填充，带来越高的敏捷性
    * 合理的填充频率还取决于填充带来的成本及其必要性
    * 在特定场景下，二级填充可以更好的平衡前面两点
### 15. 管理价值流动（下）：发布规划会议
* 概念区分
    * 部署：技术决策和行为
    * 发布：业务决策和行为
### 16. 建立反馈，持续改进（上）：定型反馈和改进
* 差距是问题，更是改进机会，前提是正确地看待差距，并采取行动
* 有效反馈的三原则
    * 方便获取
    * 易于理解
    * 与目标相关
* 关于顺畅程度的反馈
    * 不顺畅的迹象
        * 流动过程中发生阻碍
        * 需求交付事件过长
    * 详细记录每次的阻碍项并进行归类
    * 阻碍原因及影响分析举证
    * 前置时间控制图
* 关于质量的反馈
    * 使用缺陷原因分类及分布矩阵
* 将改进落实为具体行动
    * 流程操作
    * 开发环境
    * 代码、设计
    * 测试守护
    * 人员技能
* “建立反馈、持续改进”使得整个看板系统成为一个闭环，可以自我进化
### 17. 建立反馈，持续改进（下）：定量的综合反馈和改进
* 累积流图
    * 大面积区域肯定存在问题
* 控制图
* 前置时间分布图
    * 截尾
    * 瘦身
    * 左移
* 附录一有用Excel生成这些图表的模版
### 18. 看板方法的规模化应用