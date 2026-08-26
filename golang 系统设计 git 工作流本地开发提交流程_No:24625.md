最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 git 工作流本地开发提交流程
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.skth0o.asia/arts/744162.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.skth0o.asia/arts/595526.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.skth0o.asia/arts/603170.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.skth0o.asia/arts/151840.Doc

原标题：上传接口跨域配置特殊适配
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/773067.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.skth0o.asia/arts/716131.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.skth0o.asia/arts/576054.Doc

原标题：golang makefile 自动化构建脚本
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.skth0o.asia/arts/481496.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.skth0o.asia/arts/717105.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.skth0o.asia/arts/374176.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.skth0o.asia/arts/192520.Doc

原标题：golang github actions 完整工作流示例
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.skth0o.asia/arts/892744.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.skth0o.asia/arts/525480.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.skth0o.asia/arts/067043.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.skth0o.asia/arts/428149.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.skth0o.asia/arts/836314.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.skth0o.asia/arts/892111.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.skth0o.asia/arts/670362.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.skth0o.asia/arts/150562.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.skth0o.asia/arts/844090.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.skth0o.asia/arts/158080.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.skth0o.asia/arts/169652.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.skth0o.asia/arts/421548.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/630519.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.skth0o.asia/arts/636025.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.skth0o.asia/arts/387280.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.skth0o.asia/arts/434368.Doc

原标题：任务执行锁防止并发重复调度
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.skth0o.asia/arts/191611.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.skth0o.asia/arts/358073.Doc

原标题：express 中间件开发业务实践
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.skth0o.asia/arts/696078.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.skth0o.asia/arts/643021.Doc

原标题：单元测试用例编写入门实操
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.skth0o.asia/arts/040553.Doc

原标题：golang dockerfile 多阶段构建详解
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.skth0o.asia/arts/900073.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.skth0o.asia/arts/498511.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.skth0o.asia/arts/811894.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.skth0o.asia/arts/365111.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.skth0o.asia/arts/690957.Doc

原标题：golang kafka 监控指标简单梳理
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.skth0o.asia/arts/124286.Doc

原标题：golang redis 分布式计数器开发
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.skth0o.asia/arts/788334.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.skth0o.asia/arts/985968.Doc


二、踩坑排错｜Troubleshooting
原标题：golang k8s configmap secret 配置
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.skth0o.asia/arts/004180.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.skth0o.asia/arts/045861.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/209308.Doc

原标题：Git 混乱提交历史清理方法
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.skth0o.asia/arts/381524.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.skth0o.asia/arts/400212.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.skth0o.asia/arts/498765.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.skth0o.asia/arts/088738.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.skth0o.asia/arts/531856.Doc

原标题：WSL 文件权限访问异常修复
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.skth0o.asia/arts/440686.Doc

原标题：golang prometheus 告警规则编写
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.skth0o.asia/arts/374309.Doc

原标题：浮点计算精度错误处理方案
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.skth0o.asia/arts/821353.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.skth0o.asia/arts/561778.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.skth0o.asia/arts/222664.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.skth0o.asia/arts/084479.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.skth0o.asia/arts/533251.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.skth0o.asia/arts/482350.Doc

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.skth0o.asia/arts/898400.Doc

原标题：golang 项目目录分层规范设计
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.skth0o.asia/arts/909998.Doc

原标题：热更新开发环境配置教程
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.skth0o.asia/arts/418218.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.skth0o.asia/arts/679007.Doc

原标题：后端分页查询逻辑代码实现
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.skth0o.asia/arts/246771.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.skth0o.asia/arts/958431.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.skth0o.asia/arts/228349.Doc

原标题：Performance：数据库join优化，大表join规避
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.skth0o.asia/arts/482102.Doc

原标题：golang docker 镜像体积优化技巧
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.skth0o.asia/arts/798297.Doc

原标题：短信服务封装失败自动重试
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.skth0o.asia/arts/714187.Doc

原标题：echarts 大数据渲染性能调优
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.skth0o.asia/arts/243491.Doc

原标题：零基础理解前后端简单交互流程
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.skth0o.asia/arts/933086.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.skth0o.asia/arts/010463.Doc

原标题：线上接口超时故障排查思路
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.skth0o.asia/arts/811511.Doc

原标题：golang http client 连接池调优
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.skth0o.asia/arts/940795.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.skth0o.asia/arts/630857.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.skth0o.asia/arts/044181.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/298499.Doc

原标题：前端权限路由动态生成实现
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.skth0o.asia/arts/678918.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.skth0o.asia/arts/363883.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.skth0o.asia/arts/028788.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.skth0o.asia/arts/609353.Doc

原标题：空指针异常判空容错处理
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.skth0o.asia/arts/180608.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.skth0o.asia/arts/362398.Doc

三、实战开发｜Practice
原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.skth0o.asia/arts/363374.Doc

原标题：golang proto 默认值坑点梳理
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.skth0o.asia/arts/881780.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.skth0o.asia/arts/645286.Doc

原标题：业务幂等键设计防重复逻辑
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.skth0o.asia/arts/620046.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.skth0o.asia/arts/595506.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.skth0o.asia/arts/413835.Doc

原标题：读懂开源项目 README 实用技巧
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.skth0o.asia/arts/784798.Doc

原标题：golang mongodb 文档结构设计原则
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.skth0o.asia/arts/123766.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/596091.Doc

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.skth0o.asia/arts/739206.Doc

原标题：golang mongodb 事务多文档使用
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.skth0o.asia/arts/417046.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.skth0o.asia/arts/909670.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.skth0o.asia/arts/224583.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.skth0o.asia/arts/639630.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.skth0o.asia/arts/601913.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.skth0o.asia/arts/348656.Doc

原标题：golang 系统设计 README 开源文档模板
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.skth0o.asia/arts/036795.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.skth0o.asia/arts/647709.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.skth0o.asia/arts/844780.Doc

原标题：echarts 大数据渲染性能调优
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.skth0o.asia/arts/317096.Doc

原标题：前端工程化 webpack 打包优化
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.skth0o.asia/arts/404479.Doc

原标题：golang validator 自定义校验规则
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.skth0o.asia/arts/122210.Doc

原标题：死信队列处理消息阻塞业务
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.skth0o.asia/arts/239209.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.skth0o.asia/arts/086342.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/317461.Doc

原标题：多操作系统开发兼容处理
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.skth0o.asia/arts/714871.Doc

原标题：并发数据覆盖加锁安全处理
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.skth0o.asia/arts/644009.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.skth0o.asia/arts/375864.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.skth0o.asia/arts/854331.Doc

原标题：批量数据处理脚本编写技巧
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.skth0o.asia/arts/017413.Doc

原标题：Cookie Session 会话状态管理
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.skth0o.asia/arts/745863.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.skth0o.asia/arts/858777.Doc

原标题：golang ci 流水线单元测试集成测试
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.skth0o.asia/arts/344116.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.skth0o.asia/arts/933436.Doc

原标题：编译打包产物依赖分析解读
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.skth0o.asia/arts/654691.Doc

原标题：gitignore 文件编写过滤规则
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.skth0o.asia/arts/979256.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.skth0o.asia/arts/091057.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.skth0o.asia/arts/858350.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.skth0o.asia/arts/880366.Doc

原标题：站内邮件消息通知功能开发
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.skth0o.asia/arts/554469.Doc

四、架构设计｜Architecture
原标题：磁盘占满服务不可用清理方案
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.skth0o.asia/arts/968329.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.skth0o.asia/arts/387206.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.skth0o.asia/arts/703835.Doc

原标题：golang toml 配置文件解析教程
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.skth0o.asia/arts/222517.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.skth0o.asia/arts/022905.Doc

原标题：golang 接口返回统一封装工具
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.skth0o.asia/arts/711175.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.skth0o.asia/arts/603759.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.skth0o.asia/arts/270718.Doc

原标题：数据库连接及时关闭连接泄漏
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.skth0o.asia/arts/704498.Doc

原标题：golang goroutine 池任务调度
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.skth0o.asia/arts/494865.Doc

原标题：零基础理解进程、线程基础概念区别
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.skth0o.asia/arts/676986.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.skth0o.asia/arts/588574.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.skth0o.asia/arts/185944.Doc

原标题：golang 系统设计分布式任务调度
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.skth0o.asia/arts/318191.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.skth0o.asia/arts/599247.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.skth0o.asia/arts/828914.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.skth0o.asia/arts/561356.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.skth0o.asia/arts/239721.Doc

?
