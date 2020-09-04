# open-his
分布式医疗系统 - Open - His

### 一、项目模块结构
#### 父模块 - open-his
说明:
#### 公共模块 - his-common
说明: 工具类、公共实例、Vo对象等
#### 系统模块 - his-system
说明:
#### 就诊模块 - his-doctor
说明:
#### 进销存模块 - his-erp
说明:
#### 统计模块 - his-statistics

### 开发日志
* (2020/08/31 09:13 --- 2020/08/31 14:09) init : 环境搭建 --- 父项目 open-his 初始化
* (2020/08/31 14:12 --- 2020/08/31 16:11) init : 环境搭建 --- 子项目 his-commons、his-doctor、his-erp、his-statistics、his-system 基本结构初始化
* (2020/09/01 14:49 --- 2020/09/01 15:42) init : 环境搭建 --- 公共模块 his-common 基础架构完善(全局常量、响应状态码、公共传输对对象、公共前台显示对象、工具类)
* (2020/09/01 15:59 --- 2020/09/01 23:59) init、feature : 环境搭建、登录模块 --- 系统模块初始化、新增用户登录、获取用户信息、退出、用户动态菜单列表等首要接口
* (2020/09/02 11:14 --- 2020/09/02 11:43) feature : 登录模块 --- 新增登录用户后端数据校验，以及全局异常处理器
* (2020/09/03 11:35 --- 2020/09/03 14:57) feature : 字典类型 --- 新增字典类型(DictType)的相关接口
* (2020/09/03 18:31 --- 2020/09/03 21:30) feature : 字典数据 --- 新增字典数据(DictData)的相关接口，同时新增的字典的 Redis 缓存以及主动同步
* (2020/09/04 15:01 --- 2020/09/04 16:09) feature : 操作日志 --- 新增日志管理-操作日志的相关方法接口，以及 AspectJ 日志切面的设计

