最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计代码评审 checklist 清单
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.pcuidwn.asia/blog/4048045.sHtMl

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.pcuidwn.asia/blog/2373128.sHtMl

原标题：正则表达式优化 CPU 占满问题
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.pcuidwn.asia/blog/3302965.sHtMl

原标题：Performance：避免循环查询N+1问题完整优化
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.pcuidwn.asia/blog/1565394.sHtMl

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.pcuidwn.asia/blog/9383357.sHtMl

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.pcuidwn.asia/blog/4367788.sHtMl

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.pcuidwn.asia/blog/3205544.sHtMl

原标题：golang redis 分布式计数器开发
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.pcuidwn.asia/blog/0480851.sHtMl

原标题：Practice：实现异步回调处理通用组件封装
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.pcuidwn.asia/blog/9482302.sHtMl

原标题：Hands‑on：简易网关路由转发组件开发
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://book.pcuidwn.asia/blog/5273739.sHtMl

原标题：golang gorm 预加载关联查询优化
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.pcuidwn.asia/blog/5503294.sHtMl

原标题：golang kafka 监控指标简单梳理
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://book.pcuidwn.asia/blog/2632976.sHtMl

原标题：golang ci 流水线自动部署 k8s 示例
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.pcuidwn.asia/blog/1440673.sHtMl

原标题：提交第一个开源 PR 完整流程
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.pcuidwn.asia/blog/3180258.sHtMl

原标题：Redis 热点 key 拆分降低集群压力
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://book.pcuidwn.asia/blog/0484600.sHtMl

原标题：服务器 Swap 关闭提升响应速度
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.pcuidwn.asia/blog/5416230.sHtMl

原标题：golang 参数校验业务接口处理
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.pcuidwn.asia/blog/3850454.sHtMl

原标题：文件批量导入导出功能实现
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.pcuidwn.asia/blog/0527686.sHtMl

原标题：rebase 操作防止代码丢失
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.pcuidwn.asia/blog/8242560.sHtMl

原标题：golang 系统设计消息队列解耦削峰
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.pcuidwn.asia/blog/7046032.sHtMl

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.pcuidwn.asia/blog/9670092.sHtMl

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.pcuidwn.asia/blog/0181988.sHtMl

原标题：实践：大文件分片上传后端完整实现思路
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.pcuidwn.asia/blog/1431726.sHtMl

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.pcuidwn.asia/blog/2638509.sHtMl

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.pcuidwn.asia/blog/5807906.sHtMl

原标题：磁盘 inode 耗尽文件创建失败
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.pcuidwn.asia/blog/3771200.sHtMl

原标题：golang minio 分片上传断点续传
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.pcuidwn.asia/blog/0404049.sHtMl

原标题：从零搭建本地数据库开发环境
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.pcuidwn.asia/blog/1775385.sHtMl

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.pcuidwn.asia/blog/9829723.sHtMl

原标题：golang redis 限流几种实现方案
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.pcuidwn.asia/blog/2800533.sHtMl

原标题：golang 系统设计异步化改造业务流程思路
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.pcuidwn.asia/blog/5217437.sHtMl

原标题：入门实践：实现简单文件读写功能
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.pcuidwn.asia/blog/5660233.sHtMl

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.pcuidwn.asia/blog/6712132.sHtMl

原标题：golang 接口请求日志记录中间件
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.pcuidwn.asia/blog/8215069.sHtMl

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.pcuidwn.asia/blog/1600021.sHtMl

原标题：golang 系统设计序列化性能选型对比
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.pcuidwn.asia/blog/3879986.sHtMl

原标题：golang 数据库慢查询监控实现
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.pcuidwn.asia/blog/8969235.sHtMl

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.pcuidwn.asia/blog/1992761.sHtMl

原标题：零基础理解缓存基础原理与简单使用
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.pcuidwn.asia/blog/9569046.sHtMl

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.pcuidwn.asia/blog/0950131.sHtMl


二、踩坑排错｜Troubleshooting
原标题：设计思考：系统幂等性整体架构层面保障
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.pcuidwn.asia/blog/5717281.sHtMl

原标题：手写简易 MQ 理解消息存储消费
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.pcuidwn.asia/blog/9278057.sHtMl

原标题：golang gorm 批量插入性能调优
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.pcuidwn.asia/blog/4931274.sHtMl

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.pcuidwn.asia/blog/5929411.sHtMl

原标题：配置外部化线上部署防错误
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.pcuidwn.asia/blog/8241255.sHtMl

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.pcuidwn.asia/blog/3553479.sHtMl

原标题：golang 系统设计分表字段选择路由规则设计
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.pcuidwn.asia/blog/2758722.sHtMl

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.pcuidwn.asia/blog/7060021.sHtMl

原标题：设计思考：分布式ID系统架构选型对比
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.pcuidwn.asia/blog/6820745.sHtMl

原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.pcuidwn.asia/blog/1766169.sHtMl

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.pcuidwn.asia/blog/2581512.sHtMl

原标题：nodejs 多进程任务分发处理
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.pcuidwn.asia/blog/0786892.sHtMl

原标题：golang rate‑limiter 限流组件
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.pcuidwn.asia/blog/2572591.sHtMl

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.pcuidwn.asia/blog/3026469.sHtMl

原标题：golang traceId spanId 传递方案
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.pcuidwn.asia/blog/5047754.sHtMl

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.pcuidwn.asia/blog/0291710.sHtMl

原标题：实践：大文件分片上传后端完整实现思路
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.pcuidwn.asia/blog/2506833.sHtMl

原标题：Practice：实现请求body重复读取中间件实践
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.pcuidwn.asia/blog/1131463.sHtMl

原标题：golang 系统设计文件存储选型对比
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.pcuidwn.asia/blog/8736382.sHtMl

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.pcuidwn.asia/blog/6662030.sHtMl

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.pcuidwn.asia/blog/1862958.sHtMl

原标题：golang etcd 租约 lease 过期机制
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.pcuidwn.asia/blog/9777900.sHtMl

原标题：golang redis 过期 key 监听业务
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.pcuidwn.asia/blog/9324341.sHtMl

原标题：Architecture：对象存储接入业务整体架构
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.pcuidwn.asia/blog/2023803.sHtMl

原标题：简易日志收集集中管理方案
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.pcuidwn.asia/blog/3587680.sHtMl

原标题：避坑：版本升级之后项目直接无法启动
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.pcuidwn.asia/blog/9984325.sHtMl

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.pcuidwn.asia/blog/7747995.sHtMl

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.pcuidwn.asia/blog/1589032.sHtMl

原标题：golang 系统设计创建更新时间自动维护方案
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.pcuidwn.asia/blog/7872262.sHtMl

原标题：golang 系统设计压测指标确定与分析
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.pcuidwn.asia/blog/8642161.sHtMl

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.pcuidwn.asia/blog/0119108.sHtMl

原标题：Dockerfile 编写容器打包实战
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.pcuidwn.asia/blog/8512101.sHtMl

原标题：前后端会话登录状态持久化
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.pcuidwn.asia/blog/5844088.sHtMl

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.pcuidwn.asia/blog/4978628.sHtMl

原标题：golang gin 中间件执行顺序讲解
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.pcuidwn.asia/blog/1677497.sHtMl

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.pcuidwn.asia/blog/1440105.sHtMl

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.pcuidwn.asia/blog/2379599.sHtMl

原标题：新手教程：如何给开源项目提交第一个PR
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://book.pcuidwn.asia/blog/3826814.sHtMl

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.pcuidwn.asia/blog/2825057.sHtMl

原标题：实战：Redis管道批量操作性能优化实践
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.pcuidwn.asia/blog/9351792.sHtMl

三、实战开发｜Practice
原标题：Git 分支切换合并删除完整操作
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.pcuidwn.asia/blog/0421017.sHtMl

原标题：golang docker 部署 mysql 注意事项
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.pcuidwn.asia/blog/6445318.sHtMl

原标题：golang prometheus 指标暴露实现
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.pcuidwn.asia/blog/0127021.sHtMl

原标题：安全实践：最小权限原则数据库账号管控
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.pcuidwn.asia/blog/7468522.sHtMl

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.pcuidwn.asia/blog/2463879.sHtMl

原标题：入门实践：使用模板快速生成项目脚手架
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.pcuidwn.asia/blog/1690977.sHtMl

原标题：golang k8s cronjob 定时任务配置
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.pcuidwn.asia/blog/5213014.sHtMl

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.pcuidwn.asia/blog/9387111.sHtMl

原标题：nodejs 读取大文件 csv 处理方案
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.pcuidwn.asia/blog/4876699.sHtMl

原标题：Docker 容器网络不通排查
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.pcuidwn.asia/blog/9504597.sHtMl

原标题：前端骨架屏提升页面体验
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.pcuidwn.asia/blog/9860088.sHtMl

原标题：数据库主从延迟业务兼容处理
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.pcuidwn.asia/blog/9807315.sHtMl

原标题：新手指南：项目本地编译输出产物解析
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.pcuidwn.asia/blog/6743873.sHtMl

原标题：golang url 参数编码处理方案
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://book.pcuidwn.asia/blog/3494233.sHtMl

原标题：数据库连接池参数调优
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.pcuidwn.asia/blog/2346438.sHtMl

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.pcuidwn.asia/blog/3130204.sHtMl

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.pcuidwn.asia/blog/1774367.sHtMl

原标题：golang gin 框架接口开发实战
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.pcuidwn.asia/blog/3657335.sHtMl

原标题：从零搭建简单的健康检查接口示例
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.pcuidwn.asia/blog/7919120.sHtMl

原标题：日志切割配置防止日志丢失
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.pcuidwn.asia/blog/9518731.sHtMl

原标题：内存溢出问题现象识别排查
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.pcuidwn.asia/blog/9802048.sHtMl

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.pcuidwn.asia/blog/1453936.sHtMl

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.pcuidwn.asia/blog/1919135.sHtMl

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.pcuidwn.asia/blog/5209965.sHtMl

原标题：安全实践：容器最小化镜像减少攻击面
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.pcuidwn.asia/blog/9820471.sHtMl

原标题：部署实践：告警收敛避免告警风暴配置
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.pcuidwn.asia/blog/6852117.sHtMl

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.pcuidwn.asia/blog/1769511.sHtMl

原标题：ORM 隐式慢查询问题规避
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.pcuidwn.asia/blog/6658790.sHtMl

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.pcuidwn.asia/blog/3825888.sHtMl

原标题：提交第一个开源 PR 完整流程
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.pcuidwn.asia/blog/8687418.sHtMl

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.pcuidwn.asia/blog/3247591.sHtMl

原标题：Practice：简易限流器分布式版本Redis实现
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.pcuidwn.asia/blog/0915346.sHtMl

原标题：golang validator 自定义校验规则
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.pcuidwn.asia/blog/6404735.sHtMl

原标题：数据库主从延迟业务兼容处理
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.pcuidwn.asia/blog/7886460.sHtMl

原标题：golang k8s 本地 minikube 调试应用
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.pcuidwn.asia/blog/2558560.sHtMl

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.pcuidwn.asia/blog/5864746.sHtMl

原标题：服务器时钟同步任务错乱修复
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.pcuidwn.asia/blog/9872437.sHtMl

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.pcuidwn.asia/blog/9999800.sHtMl

原标题：golang 系统设计接口超时设计原则梳理
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.pcuidwn.asia/blog/6502341.sHtMl

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.pcuidwn.asia/blog/1149084.sHtMl

四、架构设计｜Architecture
原标题：新手教程：本地项目初始化gitignore配置
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.pcuidwn.asia/blog/5226574.sHtMl

原标题：HTTPS 证书过期更新操作
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.pcuidwn.asia/blog/4158252.sHtMl

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.pcuidwn.asia/blog/6771324.sHtMl

原标题：golang 系统设计 api 接口兼容性设计原则
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.pcuidwn.asia/blog/2656300.sHtMl

原标题：golang 互斥锁读写锁并发安全
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.pcuidwn.asia/blog/8352532.sHtMl

原标题：golang 系统设计接口返回格式统一规范
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.pcuidwn.asia/blog/0832131.sHtMl

原标题：分布式锁失效问题排查修复
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.pcuidwn.asia/blog/6713380.sHtMl

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.pcuidwn.asia/blog/9705684.sHtMl

原标题：golang 开发环境快速搭建指南
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.pcuidwn.asia/blog/6767814.sHtMl

原标题：golang minio 分片上传断点续传
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.pcuidwn.asia/blog/9964396.sHtMl

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.pcuidwn.asia/blog/2997672.sHtMl

原标题：nodejs 全局异常捕获进程防护
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.pcuidwn.asia/blog/4792435.sHtMl

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.pcuidwn.asia/blog/0057026.sHtMl

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.pcuidwn.asia/blog/7499351.sHtMl

原标题：静态站点自动部署发布方案
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.pcuidwn.asia/blog/9747320.sHtMl

原标题：golang 系统设计数据库基准压测简单思路
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.pcuidwn.asia/blog/2669648.sHtMl

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.pcuidwn.asia/blog/8884037.sHtMl

原标题：零基础理解前后端简单交互流程
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.pcuidwn.asia/blog/4536827.sHtMl

?
