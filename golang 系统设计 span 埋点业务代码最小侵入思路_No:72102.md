最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.zyjh0y.asia/blog/245844.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://book.zyjh0y.asia/blog/271772.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.zyjh0y.asia/blog/373274.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.zyjh0y.asia/blog/423706.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.zyjh0y.asia/blog/201933.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.zyjh0y.asia/blog/134617.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.zyjh0y.asia/blog/819444.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.zyjh0y.asia/blog/537255.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.zyjh0y.asia/blog/774365.Doc

原标题：nodejs redis 缓存业务实战
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.zyjh0y.asia/blog/604259.Doc

原标题：golang 系统设计压测数据构造方法实现
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.zyjh0y.asia/blog/747926.Doc

原标题：服务健康检查告警监控体系
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.zyjh0y.asia/blog/196800.Doc

原标题：golang docker compose 完整语法
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.zyjh0y.asia/blog/856559.Doc

原标题：Nginx 请求头大小上限调整
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.zyjh0y.asia/blog/533920.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.zyjh0y.asia/blog/499183.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://book.zyjh0y.asia/blog/244524.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.zyjh0y.asia/blog/441000.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.zyjh0y.asia/blog/948512.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.zyjh0y.asia/blog/797683.Doc

原标题：golang 时间时区处理避坑指南
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.zyjh0y.asia/blog/308350.Doc

原标题：动态定时任务业务调度实现
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.zyjh0y.asia/blog/226956.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.zyjh0y.asia/blog/641548.Doc

原标题：从零搭建简单的健康检查接口示例
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.zyjh0y.asia/blog/787951.Doc

原标题：golang mongodb 聚合管道实操案例
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.zyjh0y.asia/blog/930761.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.zyjh0y.asia/blog/725172.Doc

原标题：golang rate‑limiter 限流组件
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.zyjh0y.asia/blog/286546.Doc

原标题：golang mysql 联合索引最左匹配
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.zyjh0y.asia/blog/642899.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.zyjh0y.asia/blog/045134.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.zyjh0y.asia/blog/748020.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.zyjh0y.asia/blog/750403.Doc

原标题：时间精度统一业务判断修复
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.zyjh0y.asia/blog/659362.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.zyjh0y.asia/blog/000611.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.zyjh0y.asia/blog/239514.Doc

原标题：golang mongodb 分页性能优化技巧
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.zyjh0y.asia/blog/671491.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.zyjh0y.asia/blog/959944.Doc

原标题：文件句柄上限调整上传随机失败
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.zyjh0y.asia/blog/274039.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.zyjh0y.asia/blog/661774.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.zyjh0y.asia/blog/948839.Doc

原标题：快速入门异步编程基础模型
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.zyjh0y.asia/blog/575102.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.zyjh0y.asia/blog/123173.Doc


二、踩坑排错｜Troubleshooting
原标题：架构笔记：高并发系统核心设计思路总结
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.zyjh0y.asia/blog/134475.Doc

原标题：Docker Compose 一键搭建本地栈
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.zyjh0y.asia/blog/153399.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.zyjh0y.asia/blog/022614.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.zyjh0y.asia/blog/633879.Doc

原标题：配置外部化线上部署防错误
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.zyjh0y.asia/blog/141373.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.zyjh0y.asia/blog/181175.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.zyjh0y.asia/blog/930686.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.zyjh0y.asia/blog/756106.Doc

原标题：前端图片懒加载性能优化
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.zyjh0y.asia/blog/822770.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.zyjh0y.asia/blog/041003.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.zyjh0y.asia/blog/950518.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.zyjh0y.asia/blog/834382.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.zyjh0y.asia/blog/280062.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.zyjh0y.asia/blog/056871.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.zyjh0y.asia/blog/527366.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.zyjh0y.asia/blog/177816.Doc

原标题：本地运行正常线上报错排查
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.zyjh0y.asia/blog/416158.Doc

原标题：实战：Redis管道批量操作性能优化实践
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.zyjh0y.asia/blog/748618.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.zyjh0y.asia/blog/082868.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.zyjh0y.asia/blog/070249.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.zyjh0y.asia/blog/647549.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.zyjh0y.asia/blog/380316.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.zyjh0y.asia/blog/016392.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.zyjh0y.asia/blog/286294.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.zyjh0y.asia/blog/237660.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.zyjh0y.asia/blog/136251.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.zyjh0y.asia/blog/138852.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.zyjh0y.asia/blog/113283.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.zyjh0y.asia/blog/389108.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.zyjh0y.asia/blog/224757.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://book.zyjh0y.asia/blog/901843.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.zyjh0y.asia/blog/207736.Doc

原标题：golang redis 网络超时参数调优
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.zyjh0y.asia/blog/986622.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.zyjh0y.asia/blog/377210.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.zyjh0y.asia/blog/127046.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.zyjh0y.asia/blog/901438.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.zyjh0y.asia/blog/908545.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.zyjh0y.asia/blog/208024.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.zyjh0y.asia/blog/713792.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.zyjh0y.asia/blog/950286.Doc

三、实战开发｜Practice
原标题：调优方案：JVM内存参数优化，降低GC频率
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.zyjh0y.asia/blog/818445.Doc

原标题：golang redis zset 延时队列实现
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.zyjh0y.asia/blog/492472.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.zyjh0y.asia/blog/246979.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.zyjh0y.asia/blog/865860.Doc

原标题：简易网关请求路由过滤模拟
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.zyjh0y.asia/blog/587259.Doc

原标题：安全组端口开放网络访问
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.zyjh0y.asia/blog/931460.Doc

原标题：异步异常捕获避免进程崩溃
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.zyjh0y.asia/blog/491491.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.zyjh0y.asia/blog/503921.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.zyjh0y.asia/blog/103694.Doc

原标题：消息队列重复消费业务处理
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.zyjh0y.asia/blog/672298.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.zyjh0y.asia/blog/302157.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.zyjh0y.asia/blog/649038.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.zyjh0y.asia/blog/998143.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.zyjh0y.asia/blog/614689.Doc

原标题：golang 系统设计全局异常处理器实现
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.zyjh0y.asia/blog/707986.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.zyjh0y.asia/blog/428068.Doc

原标题：golang redis zset 排行榜业务实现
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.zyjh0y.asia/blog/645762.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.zyjh0y.asia/blog/831480.Doc

原标题：定时任务重复执行分布式锁
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.zyjh0y.asia/blog/341271.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.zyjh0y.asia/blog/022472.Doc

原标题：进程线程并发基础概念讲解
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.zyjh0y.asia/blog/207813.Doc

原标题：零基础理解进程、线程基础概念区别
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.zyjh0y.asia/blog/001699.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.zyjh0y.asia/blog/429087.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.zyjh0y.asia/blog/376076.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.zyjh0y.asia/blog/592732.Doc

原标题：golang 分布式上下文传递方案
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.zyjh0y.asia/blog/881557.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://book.zyjh0y.asia/blog/988660.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://book.zyjh0y.asia/blog/996880.Doc

原标题：SourceMap 生成线上报错定位
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.zyjh0y.asia/blog/323849.Doc

原标题：入门实践：实现简单文件读写功能
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.zyjh0y.asia/blog/420945.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.zyjh0y.asia/blog/537182.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.zyjh0y.asia/blog/823943.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.zyjh0y.asia/blog/314797.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.zyjh0y.asia/blog/549446.Doc

原标题：golang prometheus histogram 指标
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.zyjh0y.asia/blog/929132.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.zyjh0y.asia/blog/255007.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.zyjh0y.asia/blog/042285.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.zyjh0y.asia/blog/456818.Doc

原标题：golang etcd 分布式锁实现原理
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.zyjh0y.asia/blog/383817.Doc

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.zyjh0y.asia/blog/809349.Doc

四、架构设计｜Architecture
原标题：优化实践：LRU本地缓存优化热点访问性能
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.zyjh0y.asia/blog/202582.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.zyjh0y.asia/blog/459815.Doc

原标题：WebSocket 双向通信 demo 开发
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://book.zyjh0y.asia/blog/641458.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.zyjh0y.asia/blog/880650.Doc

原标题：分页逻辑错误数据漏查修复
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.zyjh0y.asia/blog/064616.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.zyjh0y.asia/blog/422444.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.zyjh0y.asia/blog/345076.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.zyjh0y.asia/blog/533254.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.zyjh0y.asia/blog/903593.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.zyjh0y.asia/blog/869844.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.zyjh0y.asia/blog/699407.Doc

原标题：批量操作分批处理防止 OOM
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.zyjh0y.asia/blog/486224.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.zyjh0y.asia/blog/274959.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.zyjh0y.asia/blog/744666.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.zyjh0y.asia/blog/538614.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.zyjh0y.asia/blog/907036.Doc

原标题：golang docker 部署 es 本地开发
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.zyjh0y.asia/blog/767687.Doc

原标题：Security：RPC调用身份认证安全加固
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.zyjh0y.asia/blog/561135.Doc

?
