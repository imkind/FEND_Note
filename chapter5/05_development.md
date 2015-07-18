## 开发实践

### 系统设计

NOTE：综合运用实习案例，本章使用案例为网易云音乐，
并且主要关注前端工程师的工作职责，其他工程师的职责规范并不包含。

**交互流程说明**

通过交互文案来了解用户行为与异常提示。

**系统分解**

例如下面的独立的子系统：

- 注册登录密码
- 系统主框架
  - 顶栏
    - 搜索
    - 账号
    - 消息
    - 设置
  - 边栏
    - 歌单操作
    - 其他
  - 底栏
    - 播放器
    - 播放列表
    - 歌曲详情
  - 内容区
    
系统分解必须对照交互稿做到百分之百的对应，不能漏掉任何一个模块。
后续的开发与评估都需根据此分解进行。

**接口设计**

分析模块交互理解需求以及交互行为。对于数据获取的形式进行适当的假设，
并定义*数据类型*、*模板资源*、*异步接口*、以及*页面摘要*。

**项目结构**

根据规范说明就可以做出项目的结构定义，项目结构分两部分*后端模板*与*前端实现*。

**初始代码**

前端工程师需要在开发工具中添加开发规范，以及测试使用的模拟数据。

### 系统实现

