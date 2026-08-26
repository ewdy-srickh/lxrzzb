最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.cnd9jg.asia/arts/380033.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.cnd9jg.asia/arts/723552.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.cnd9jg.asia/arts/627424.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.cnd9jg.asia/arts/468412.Doc

原标题：golang 速率限制令牌桶实现
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.cnd9jg.asia/arts/527060.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.cnd9jg.asia/arts/863483.Doc

原标题：网关超时时间调优后端等待
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.cnd9jg.asia/arts/265775.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/867637.Doc

原标题：数据库索引重建提升查询速度
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.cnd9jg.asia/arts/190967.Doc

原标题：golang websocket 消息广播实现
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.cnd9jg.asia/arts/207515.Doc

原标题：服务启动依赖顺序配置正确
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/026825.Doc

原标题：golang goroutine 池任务调度
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/448542.Doc

原标题：从零搭建简单定时任务demo
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/761900.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.cnd9jg.asia/arts/363628.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.cnd9jg.asia/arts/459618.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.cnd9jg.asia/arts/504518.Doc

原标题：后端大文件分片上传接口开发
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.cnd9jg.asia/arts/235502.Doc

原标题：不必要字符转义关闭业务异常
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.cnd9jg.asia/arts/199084.Doc

原标题：OAuth2 第三方登录服务搭建
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.cnd9jg.asia/arts/820917.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.cnd9jg.asia/arts/959916.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/315527.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.cnd9jg.asia/arts/663767.Doc

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.cnd9jg.asia/arts/065688.Doc

原标题：golang redis 集群 hash 槽讲解
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.cnd9jg.asia/arts/715843.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.cnd9jg.asia/arts/818464.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.cnd9jg.asia/arts/665658.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.cnd9jg.asia/arts/048103.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.cnd9jg.asia/arts/504628.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.cnd9jg.asia/arts/498107.Doc

原标题：新手参与开源社区贡献指南
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/309203.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/492252.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.cnd9jg.asia/arts/204573.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.cnd9jg.asia/arts/181799.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.cnd9jg.asia/arts/473301.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.cnd9jg.asia/arts/459224.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.cnd9jg.asia/arts/992570.Doc

原标题：文件读写与异常捕获代码示例
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.cnd9jg.asia/arts/192111.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/442132.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.cnd9jg.asia/arts/101303.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.cnd9jg.asia/arts/423181.Doc


二、踩坑排错｜Troubleshooting
原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.cnd9jg.asia/arts/126404.Doc

原标题：golang 系统设计防爬虫简单策略
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.cnd9jg.asia/arts/334731.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.cnd9jg.asia/arts/712882.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.cnd9jg.asia/arts/188396.Doc

原标题：golang cron 定时任务防并发执行
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.cnd9jg.asia/arts/497984.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.cnd9jg.asia/arts/315922.Doc

原标题：Docker 容器时区错误修复方案
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.cnd9jg.asia/arts/604740.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.cnd9jg.asia/arts/949776.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.cnd9jg.asia/arts/745400.Doc

原标题：vite 项目配置与构建提速技巧
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.cnd9jg.asia/arts/682726.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.cnd9jg.asia/arts/740588.Doc

原标题：浏览器缓存强制刷新方案
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.cnd9jg.asia/arts/854462.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.cnd9jg.asia/arts/078927.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.cnd9jg.asia/arts/249723.Doc

原标题：Docker 容器时区错误修复方案
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.cnd9jg.asia/arts/382872.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.cnd9jg.asia/arts/904375.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.cnd9jg.asia/arts/548321.Doc

原标题：golang redis 主从复制哨兵原理
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.cnd9jg.asia/arts/486602.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.cnd9jg.asia/arts/225102.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.cnd9jg.asia/arts/186386.Doc

原标题：排错：前端缓存304异常更新不及时
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/395455.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.cnd9jg.asia/arts/516869.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.cnd9jg.asia/arts/493546.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.cnd9jg.asia/arts/429891.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.cnd9jg.asia/arts/193961.Doc

原标题：快速入门简单签名校验实现思路
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.cnd9jg.asia/arts/978145.Doc

原标题：开源源码阅读拆解学习思路
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.cnd9jg.asia/arts/717815.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/630035.Doc

原标题：axios 二次封装请求拦截处理
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.cnd9jg.asia/arts/904401.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.cnd9jg.asia/arts/935448.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.cnd9jg.asia/arts/715848.Doc

原标题：golang mongodb 索引优化查询速度
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.cnd9jg.asia/arts/979821.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.cnd9jg.asia/arts/242519.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.cnd9jg.asia/arts/844894.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.cnd9jg.asia/arts/311777.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.cnd9jg.asia/arts/663337.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/599105.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.cnd9jg.asia/arts/717968.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.cnd9jg.asia/arts/517878.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.cnd9jg.asia/arts/202957.Doc

三、实战开发｜Practice
原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.cnd9jg.asia/arts/526816.Doc

原标题：golang ci 流水线单元测试集成测试
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.cnd9jg.asia/arts/175183.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.cnd9jg.asia/arts/342868.Doc

原标题：golang 项目环境变量加载方案
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/399812.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/123413.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.cnd9jg.asia/arts/534337.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.cnd9jg.asia/arts/150250.Doc

原标题：热更新开发环境配置教程
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.cnd9jg.asia/arts/934294.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.cnd9jg.asia/arts/042556.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/759528.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.cnd9jg.asia/arts/782663.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.cnd9jg.asia/arts/820546.Doc

原标题：包管理器依赖缓存清理
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.cnd9jg.asia/arts/015048.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/964212.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.cnd9jg.asia/arts/973273.Doc

原标题：数据库连接及时关闭连接泄漏
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.cnd9jg.asia/arts/344047.Doc

原标题：golang 单元测试 table‑driven
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.cnd9jg.asia/arts/199344.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/196793.Doc

原标题：日志切割配置防止日志丢失
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.cnd9jg.asia/arts/036251.Doc

原标题：golang 时间时区处理避坑指南
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.cnd9jg.asia/arts/926955.Doc

原标题：golang 配置热更新不重启服务
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.cnd9jg.asia/arts/950942.Doc

原标题：golang kafka 重试机制配置实操
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/318329.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.cnd9jg.asia/arts/124513.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.cnd9jg.asia/arts/038237.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.cnd9jg.asia/arts/596207.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.cnd9jg.asia/arts/061992.Doc

原标题：golang 消息死信处理业务逻辑
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.cnd9jg.asia/arts/553677.Doc

原标题：文件句柄上限调整上传随机失败
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.cnd9jg.asia/arts/116892.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.cnd9jg.asia/arts/394617.Doc

原标题：程序日志分级输出规范实践
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.cnd9jg.asia/arts/856062.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.cnd9jg.asia/arts/426710.Doc

原标题：golang 布隆过滤器实现去重
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.cnd9jg.asia/arts/452067.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.cnd9jg.asia/arts/441924.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/318136.Doc

原标题：前端大文件分片上传完整方案
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/276060.Doc

原标题：golang pprof 线上采集性能数据
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.cnd9jg.asia/arts/241358.Doc

原标题：从零搭建简单CLI命令行工具
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.cnd9jg.asia/arts/600617.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.cnd9jg.asia/arts/605194.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.cnd9jg.asia/arts/001947.Doc

原标题：golang redis 缓存预热实现思路
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/311578.Doc

四、架构设计｜Architecture
原标题：程序信号中断退出处理逻辑
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.cnd9jg.asia/arts/067067.Doc

原标题：golang 系统设计延迟队列业务实现
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.cnd9jg.asia/arts/850809.Doc

原标题：golang minio 对象存储接口开发
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.cnd9jg.asia/arts/079538.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.cnd9jg.asia/arts/681051.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.cnd9jg.asia/arts/166783.Doc

原标题：golang redis 五种数据结构实战
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.cnd9jg.asia/arts/529735.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.cnd9jg.asia/arts/786872.Doc

原标题：布隆过滤器数据高效去重实现
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.cnd9jg.asia/arts/155979.Doc

原标题：hosts 配置本地回环访问修复
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.cnd9jg.asia/arts/836656.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/856129.Doc

原标题：golang 日志与链路 ID 关联打印
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.cnd9jg.asia/arts/337795.Doc

原标题：入门实践：实现简单文件读写功能
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.cnd9jg.asia/arts/417389.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.cnd9jg.asia/arts/191711.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.cnd9jg.asia/arts/348446.Doc

原标题：golang 集成测试启动测试数据库
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.cnd9jg.asia/arts/588573.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.cnd9jg.asia/arts/537576.Doc

原标题：golang 静态文件服务搭建教程
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.cnd9jg.asia/arts/642638.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.cnd9jg.asia/arts/385113.Doc

?
