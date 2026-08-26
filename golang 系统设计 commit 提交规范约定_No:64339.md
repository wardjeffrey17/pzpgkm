最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 commit 提交规范约定
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.b6irno.asia/blog/054755.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.b6irno.asia/blog/417681.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.b6irno.asia/blog/255213.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.b6irno.asia/blog/266142.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.b6irno.asia/blog/537432.Doc

原标题：golang github actions 多平台构建
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.b6irno.asia/blog/425296.Doc

原标题：快速上手简单性能监控指标查看
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.b6irno.asia/blog/303513.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.b6irno.asia/blog/166556.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.b6irno.asia/blog/958548.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.b6irno.asia/blog/086175.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.b6irno.asia/blog/522904.Doc

原标题：golang makefile 自动化构建脚本
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.b6irno.asia/blog/793900.Doc

原标题：golang go test 覆盖率统计实操
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.b6irno.asia/blog/276281.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.b6irno.asia/blog/882544.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.b6irno.asia/blog/898104.Doc

原标题：轻量 API 后端接口服务快速开发
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.b6irno.asia/blog/699487.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.b6irno.asia/blog/607458.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.b6irno.asia/blog/674658.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.b6irno.asia/blog/150226.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.b6irno.asia/blog/725515.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.b6irno.asia/blog/539907.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.b6irno.asia/blog/970133.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.b6irno.asia/blog/985465.Doc

原标题：vue pinia 状态管理实战教程
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.b6irno.asia/blog/351470.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.b6irno.asia/blog/822167.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://book.b6irno.asia/blog/285528.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.b6irno.asia/blog/637769.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.b6irno.asia/blog/563255.Doc

原标题：Git LFS 大文件推送失败解决
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.b6irno.asia/blog/757912.Doc

原标题：golang 分库分表简单路由实现
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.b6irno.asia/blog/236256.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.b6irno.asia/blog/344900.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.b6irno.asia/blog/088810.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.b6irno.asia/blog/873028.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.b6irno.asia/blog/252515.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.b6irno.asia/blog/156866.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.b6irno.asia/blog/080949.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.b6irno.asia/blog/715168.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.b6irno.asia/blog/257384.Doc

原标题：文件锁正确使用避免死锁
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.b6irno.asia/blog/752243.Doc

原标题：端口占用释放资源重启服务
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.b6irno.asia/blog/852282.Doc


二、踩坑排错｜Troubleshooting
原标题：golang k8s configmap secret 配置
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.b6irno.asia/blog/151163.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.b6irno.asia/blog/106465.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.b6irno.asia/blog/907063.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.b6irno.asia/blog/028970.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.b6irno.asia/blog/295577.Doc

原标题：golang redis 大 key 识别处理方案
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.b6irno.asia/blog/159985.Doc

原标题：golang traceId spanId 传递方案
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.b6irno.asia/blog/963980.Doc

原标题：golang channel 通道并发处理
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.b6irno.asia/blog/418039.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.b6irno.asia/blog/544433.Doc

原标题：时间同步修复令牌提前过期
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.b6irno.asia/blog/133062.Doc

原标题：golang docker 部署 es 本地开发
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.b6irno.asia/blog/276767.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.b6irno.asia/blog/273544.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.b6irno.asia/blog/835980.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.b6irno.asia/blog/733287.Doc

原标题：golang es 批量 bulk 操作性能调优
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.b6irno.asia/blog/541098.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://book.b6irno.asia/blog/171110.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.b6irno.asia/blog/758530.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.b6irno.asia/blog/828444.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.b6irno.asia/blog/433998.Doc

原标题：golang mysql 慢查询日志开启分析
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.b6irno.asia/blog/428953.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.b6irno.asia/blog/496511.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.b6irno.asia/blog/455400.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.b6irno.asia/blog/188184.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.b6irno.asia/blog/508006.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://book.b6irno.asia/blog/154647.Doc

原标题：短信服务封装失败自动重试
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.b6irno.asia/blog/122639.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.b6irno.asia/blog/233229.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.b6irno.asia/blog/728763.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.b6irno.asia/blog/805294.Doc

原标题：排错：前端缓存304异常更新不及时
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.b6irno.asia/blog/770436.Doc

原标题：golang redis 缓存预热实现思路
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.b6irno.asia/blog/217622.Doc

原标题：OOMKilled 容器被杀完整排查
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.b6irno.asia/blog/346645.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.b6irno.asia/blog/934844.Doc

原标题：前端 pdf 预览渲染方案对比
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.b6irno.asia/blog/306325.Doc

原标题：从零搭建简单定时任务demo
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.b6irno.asia/blog/056938.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.b6irno.asia/blog/584286.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.b6irno.asia/blog/436523.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.b6irno.asia/blog/962110.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.b6irno.asia/blog/854349.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.b6irno.asia/blog/931063.Doc

三、实战开发｜Practice
原标题：GC 垃圾回收优化降低 CPU 占用
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.b6irno.asia/blog/370633.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.b6irno.asia/blog/420233.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://book.b6irno.asia/blog/528564.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.b6irno.asia/blog/350163.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.b6irno.asia/blog/902585.Doc

原标题：golang 限流熔断降级完整示例
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.b6irno.asia/blog/798426.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.b6irno.asia/blog/973724.Doc

原标题：golang k8s 资源请求限制配置
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.b6irno.asia/blog/282071.Doc

原标题：分布式 ID 生成器高并发实现
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.b6irno.asia/blog/314690.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.b6irno.asia/blog/347627.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.b6irno.asia/blog/173708.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.b6irno.asia/blog/624810.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.b6irno.asia/blog/431236.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.b6irno.asia/blog/995800.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.b6irno.asia/blog/661429.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.b6irno.asia/blog/469698.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.b6irno.asia/blog/296317.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.b6irno.asia/blog/007657.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.b6irno.asia/blog/899907.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.b6irno.asia/blog/425273.Doc

原标题：golang k8s cronjob 定时任务配置
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.b6irno.asia/blog/321439.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.b6irno.asia/blog/888857.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.b6irno.asia/blog/339794.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.b6irno.asia/blog/715544.Doc

原标题：CI 构建缓存加速编译速度
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.b6irno.asia/blog/515198.Doc

原标题：golang 单元测试 mock http 请求
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.b6irno.asia/blog/577353.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.b6irno.asia/blog/425907.Doc

原标题：golang 接口请求日志记录中间件
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.b6irno.asia/blog/509864.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.b6irno.asia/blog/297875.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.b6irno.asia/blog/158360.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.b6irno.asia/blog/815964.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.b6irno.asia/blog/829706.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.b6irno.asia/blog/754183.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.b6irno.asia/blog/482442.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.b6irno.asia/blog/239997.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.b6irno.asia/blog/545251.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.b6irno.asia/blog/284372.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.b6irno.asia/blog/610980.Doc

原标题：CLI 批量处理工具文件操作开发
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.b6irno.asia/blog/791027.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.b6irno.asia/blog/117635.Doc

四、架构设计｜Architecture
原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.b6irno.asia/blog/437757.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://book.b6irno.asia/blog/191950.Doc

原标题：golang mongodb 文档结构设计原则
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.b6irno.asia/blog/367627.Doc

原标题：分布式任务调度集群原型开发
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.b6irno.asia/blog/357257.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.b6irno.asia/blog/402477.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.b6irno.asia/blog/187555.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.b6irno.asia/blog/262413.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.b6irno.asia/blog/946951.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.b6irno.asia/blog/120695.Doc

原标题：golang mongodb 文档结构设计原则
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.b6irno.asia/blog/822957.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.b6irno.asia/blog/383761.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.b6irno.asia/blog/254982.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.b6irno.asia/blog/682992.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.b6irno.asia/blog/649138.Doc

原标题：实践：数据库回滚点业务调试实践
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.b6irno.asia/blog/292392.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.b6irno.asia/blog/179587.Doc

原标题：不必要字符转义关闭业务异常
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.b6irno.asia/blog/666229.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.b6irno.asia/blog/198868.Doc

?
