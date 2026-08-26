最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 git 钩子自动化校验实现
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.3jhb3c.asia/arts/040323.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.3jhb3c.asia/arts/724553.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.3jhb3c.asia/arts/336473.Doc

原标题：磁盘占满服务不可用清理方案
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.3jhb3c.asia/arts/957855.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.3jhb3c.asia/arts/782554.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.3jhb3c.asia/arts/906910.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.3jhb3c.asia/arts/018311.Doc

原标题：nodejs 内存溢出问题排查修复
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.3jhb3c.asia/arts/000095.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.3jhb3c.asia/arts/097113.Doc

原标题：文件编码统一随机乱码修复
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.3jhb3c.asia/arts/782704.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.3jhb3c.asia/arts/845743.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.3jhb3c.asia/arts/159472.Doc

原标题：golang 单例模式实现几种方式
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.3jhb3c.asia/arts/639630.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.3jhb3c.asia/arts/995424.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.3jhb3c.asia/arts/662236.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.3jhb3c.asia/arts/863530.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.3jhb3c.asia/arts/300361.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.3jhb3c.asia/arts/301147.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.3jhb3c.asia/arts/743978.Doc

原标题：业务幂等键设计防重复逻辑
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.3jhb3c.asia/arts/613811.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.3jhb3c.asia/arts/169053.Doc

原标题：快速入门消息通知简单实现方案
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.3jhb3c.asia/arts/019894.Doc

原标题：移动端适配 rem vw 方案对比
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.3jhb3c.asia/arts/452118.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.3jhb3c.asia/arts/169783.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.3jhb3c.asia/arts/312475.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.3jhb3c.asia/arts/969866.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.3jhb3c.asia/arts/730390.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.3jhb3c.asia/arts/183254.Doc

原标题：golang 文件上传下载接口开发
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.3jhb3c.asia/arts/717031.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.3jhb3c.asia/arts/633386.Doc

原标题：CI 构建缓存加速编译速度
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.3jhb3c.asia/arts/881696.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.3jhb3c.asia/arts/479072.Doc

原标题：异步编程 Promise 执行流程解析
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.3jhb3c.asia/arts/961398.Doc

原标题：golang 系统设计短信发送限流降级
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.3jhb3c.asia/arts/231627.Doc

原标题：开源项目构建失败排查步骤
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.3jhb3c.asia/arts/374097.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.3jhb3c.asia/arts/959443.Doc

原标题：golang redis 缓存雪崩完整处理
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.3jhb3c.asia/arts/185399.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.3jhb3c.asia/arts/388889.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.3jhb3c.asia/arts/287523.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.3jhb3c.asia/arts/795918.Doc


二、踩坑排错｜Troubleshooting
原标题：TCP 心跳检测清理僵死连接
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.3jhb3c.asia/arts/230831.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.3jhb3c.asia/arts/532215.Doc

原标题：全局异常处理器接口返回统一
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.3jhb3c.asia/arts/906909.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.3jhb3c.asia/arts/005057.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.3jhb3c.asia/arts/883879.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.3jhb3c.asia/arts/820961.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.3jhb3c.asia/arts/682996.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.3jhb3c.asia/arts/133683.Doc

原标题：golang mysql json 字段查询使用
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.3jhb3c.asia/arts/136620.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.3jhb3c.asia/arts/905275.Doc

原标题：golang 结构体深拷贝几种实现
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.3jhb3c.asia/arts/152275.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.3jhb3c.asia/arts/223097.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.3jhb3c.asia/arts/700618.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.3jhb3c.asia/arts/964318.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.3jhb3c.asia/arts/963354.Doc

原标题：浏览器内存泄漏排查前端页面
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.3jhb3c.asia/arts/993151.Doc

原标题：golang mysql 联合索引最左匹配
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.3jhb3c.asia/arts/926975.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.3jhb3c.asia/arts/189649.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.3jhb3c.asia/arts/606572.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.3jhb3c.asia/arts/679133.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.3jhb3c.asia/arts/790388.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.3jhb3c.asia/arts/175113.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.3jhb3c.asia/arts/112589.Doc

原标题：MySQL 慢查询索引优化实战
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.3jhb3c.asia/arts/490289.Doc

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.3jhb3c.asia/arts/818346.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.3jhb3c.asia/arts/183202.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.3jhb3c.asia/arts/493668.Doc

原标题：文件读写与异常捕获代码示例
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.3jhb3c.asia/arts/534246.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.3jhb3c.asia/arts/663923.Doc

原标题：golang 日志与链路 ID 关联打印
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.3jhb3c.asia/arts/121668.Doc

原标题：golang makefile 自动化构建脚本
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.3jhb3c.asia/arts/013919.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.3jhb3c.asia/arts/896820.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.3jhb3c.asia/arts/787023.Doc

原标题：golang 系统设计性能优化通用思路方法论
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.3jhb3c.asia/arts/030693.Doc

原标题：golang 大文件 http 下载服务
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.3jhb3c.asia/arts/005746.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.3jhb3c.asia/arts/141427.Doc

原标题：golang 布隆过滤器实现去重
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.3jhb3c.asia/arts/421302.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.3jhb3c.asia/arts/582951.Doc

原标题：golang 接口限流中间件开发
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.3jhb3c.asia/arts/047099.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.3jhb3c.asia/arts/999659.Doc

三、实战开发｜Practice
原标题：入门实践：简单数据脱敏处理示例
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.3jhb3c.asia/arts/018127.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.3jhb3c.asia/arts/612849.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.3jhb3c.asia/arts/842732.Doc

原标题：golang redis 批量 pipeline 实践
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.3jhb3c.asia/arts/155126.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.3jhb3c.asia/arts/619611.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.3jhb3c.asia/arts/337115.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.3jhb3c.asia/arts/901466.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.3jhb3c.asia/arts/166266.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.3jhb3c.asia/arts/154109.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.3jhb3c.asia/arts/711339.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.3jhb3c.asia/arts/340834.Doc

原标题：nodejs 集成测试业务流程编写
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.3jhb3c.asia/arts/007953.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.3jhb3c.asia/arts/316619.Doc

原标题：CLI 工具进度条交互效果开发
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.3jhb3c.asia/arts/057008.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.3jhb3c.asia/arts/603380.Doc

原标题：业务错误码体系设计方案
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.3jhb3c.asia/arts/033989.Doc

原标题：golang mongodb 分页性能优化技巧
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.3jhb3c.asia/arts/370816.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.3jhb3c.asia/arts/748629.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.3jhb3c.asia/arts/226075.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.3jhb3c.asia/arts/435116.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.3jhb3c.asia/arts/405772.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.3jhb3c.asia/arts/318992.Doc

原标题：GraphQL 接口查询优化实操
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.3jhb3c.asia/arts/926813.Doc

原标题：从零搭建简单定时任务demo
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.3jhb3c.asia/arts/559434.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.3jhb3c.asia/arts/813677.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.3jhb3c.asia/arts/811676.Doc

原标题：golang defer panic 异常处理
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.3jhb3c.asia/arts/522813.Doc

原标题：静态资源 404 路径打包修复
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.3jhb3c.asia/arts/126077.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.3jhb3c.asia/arts/898479.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.3jhb3c.asia/arts/483414.Doc

原标题：从零搭建本地数据库开发环境
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.3jhb3c.asia/arts/042762.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.3jhb3c.asia/arts/003017.Doc

原标题：monorepo 项目多包管理最佳实践
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.3jhb3c.asia/arts/566295.Doc

原标题：实践：灰度流量切分简易实现方案
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.3jhb3c.asia/arts/854692.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.3jhb3c.asia/arts/537696.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.3jhb3c.asia/arts/202926.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.3jhb3c.asia/arts/014520.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.3jhb3c.asia/arts/656038.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.3jhb3c.asia/arts/225209.Doc

原标题：日志切割配置防止日志丢失
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.3jhb3c.asia/arts/563872.Doc

四、架构设计｜Architecture
原标题：ServiceWorker 缓存页面更新清理
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.3jhb3c.asia/arts/978289.Doc

原标题：golang k8s liveness readiness 探针
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.3jhb3c.asia/arts/126121.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.3jhb3c.asia/arts/920569.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.3jhb3c.asia/arts/815859.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.3jhb3c.asia/arts/964666.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.3jhb3c.asia/arts/417886.Doc

原标题：css 动画性能优化 GPU 加速
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.3jhb3c.asia/arts/860114.Doc

原标题：golang 参数校验业务接口处理
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.3jhb3c.asia/arts/268642.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.3jhb3c.asia/arts/282908.Doc

原标题：golang grafana 面板变量模板制作
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.3jhb3c.asia/arts/420034.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.3jhb3c.asia/arts/203413.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.3jhb3c.asia/arts/220319.Doc

原标题：Docker Compose 一键搭建本地栈
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.3jhb3c.asia/arts/188094.Doc

原标题：golang 系统设计排行榜几种实现
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.3jhb3c.asia/arts/712840.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.3jhb3c.asia/arts/639536.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.3jhb3c.asia/arts/763008.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.3jhb3c.asia/arts/825115.Doc

原标题：游标分页大数据查询性能提升
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.3jhb3c.asia/arts/896008.Doc

?
