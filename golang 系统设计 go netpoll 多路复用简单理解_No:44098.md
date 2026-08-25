最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0915380.sHtML

原标题：方案设计：异步解耦业务架构边界识别
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2405243.sHtML

原标题：全局本地依赖隔离冲突规避
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3049469.sHtML

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9168481.sHtML

原标题：手写简易 RPC 服务通信原型
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3791426.sHtML

原标题：零基础理解前后端简单交互流程
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6171170.sHtML

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5427346.sHtML

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9712123.sHtML

原标题：golang 配置文件多环境加载
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8533511.sHtML

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4588689.sHtML

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6101436.sHtML

原标题：服务启动依赖顺序配置正确
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0498789.sHtML

原标题：golang grpc protobuf 开发实操
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9409552.sHtML

原标题：golang 优雅停机服务关闭实现
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4191515.sHtML

原标题：HelloCI：理解持续集成基础工作流程
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8591579.sHtML

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8752059.sHtML

原标题：坑点：环境配置写死代码，上线忘记修改
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6364725.sHtML

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2135988.sHtML

原标题：golang goroutine 池任务调度
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0838625.sHtML

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5541164.sHtML

原标题：方案设计：异步解耦业务架构边界识别
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6329862.sHtML

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1427298.sHtML

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6463689.sHtML

原标题：golang 系统设计容量评估简单方法论
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0466140.sHtML

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7552091.sHtML

原标题：golang dockerfile 多阶段构建详解
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4888010.sHtML

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9052314.sHtML

原标题：并发数据覆盖加锁安全处理
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6041136.sHtML

原标题：接口限流逻辑简单模拟实现
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3130094.sHtML

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0209476.sHtML

原标题：golang k8s 监控 prometheus 部署
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7400451.sHtML

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0702787.sHtML

原标题：golang redis 缓存预热实现思路
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3484349.sHtML

原标题：golang consul 健康检查服务注册
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5644667.sHtML

原标题：css 动画性能优化 GPU 加速
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2527534.sHtML

原标题：新手指南：本地多版本环境共存配置
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1676084.sHtML

原标题：golang 系统设计压测数据构造方法实现
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4980084.sHtML

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9327677.sHtML

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1395210.sHtML

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9404033.sHtML


二、踩坑排错｜Troubleshooting
原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4758106.sHtML

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2776484.sHtML

原标题：实践：数据库回滚点业务调试实践
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4169194.sHtML

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4903933.sHtML

原标题：Shell 运维脚本服务器效率提升
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6893277.sHtML

原标题：数据库排序规则统一结果一致
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7694723.sHtML

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8667905.sHtML

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0176885.sHtML

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7023832.sHtML

原标题：nodejs 数据库连接池配置调优
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5714724.sHtML

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7475245.sHtML

原标题：快速上手搭建简易内网测试服务
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7625287.sHtML

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7432167.sHtML

原标题：零基础学习简单正则表达式实战案例
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2381207.sHtML

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4803729.sHtML

原标题：Cookie 跨环境登录配置调整
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6449761.sHtML

原标题：golang base64 编码解码实操
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8307028.sHtML

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3786497.sHtML

原标题：nestjs 全局返回格式统一处理
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9757624.sHtML

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0440411.sHtML

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6067084.sHtML

原标题：数值 key 浮点匹配异常规避
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2460385.sHtML

原标题：服务健康检查告警监控体系
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0739540.sHtML

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2092501.sHtML

原标题：SourceMap 生成线上报错定位
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4100611.sHtML

原标题：DNS 解析异常第三方调用故障
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3169500.sHtML

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1656084.sHtML

原标题：nodejs 日志轮转生产环境配置
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2039916.sHtML

原标题：SDK 版本兼容线上崩溃修复
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8624461.sHtML

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5126953.sHtML

原标题：从零搭建简单CLI命令行工具
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3692300.sHtML

原标题：实战：WebSocket断线重连完整业务处理实践
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3738164.sHtML

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5988494.sHtML

原标题：极简 API 网关路由转发实现
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7730107.sHtML

原标题：异步异常捕获避免进程崩溃
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3177135.sHtML

原标题：缓存穿透防护保护数据库
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8880228.sHtML

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7147299.sHtML

原标题：运维笔记：系统文件句柄数调整生产配置
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6067051.sHtML

原标题：接口幂等性防重复请求实现
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2879321.sHtML

原标题：实战项目：实现分布式任务调度最小原型
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6121019.sHtML

三、实战开发｜Practice
原标题：Shell 脚本自动化命令编写
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9096772.sHtML

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9788191.sHtML

原标题：Nginx 请求头大小上限调整
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7797873.sHtML

原标题：golang k8s 监控 prometheus 部署
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9579202.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1283166.sHtML

原标题：Docker Compose 一键搭建本地栈
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4711788.sHtML

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2425497.sHtML

原标题：方案对比：单体、微服务、模块化单体取舍
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2350235.sHtML

原标题：上传接口跨域配置特殊适配
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5026672.sHtML

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8576509.sHtML

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3137610.sHtML

原标题：golang mysql 分表自增 id 方案
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7584672.sHtML

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2547783.sHtML

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7947388.sHtML

原标题：ICMP 放通网络丢包问题修复
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1265695.sHtML

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4264941.sHtML

原标题：golang 系统设计分布式任务调度
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8848493.sHtML

原标题：时间同步修复令牌提前过期
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3520311.sHtML

原标题：golang gin 中间件执行顺序讲解
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8234187.sHtML

原标题：golang redis 连接池参数最佳值
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4772128.sHtML

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3120309.sHtML

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2393637.sHtML

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6719404.sHtML

原标题：短信服务封装失败自动重试
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3129937.sHtML

原标题：golang mysql 避免 select * 查询
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1860406.sHtML

原标题：主干开发团队代码合并策略
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8393978.sHtML

原标题：多线程线程安全脏数据规避
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2623082.sHtML

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6944513.sHtML

原标题：golang 系统设计缓存预热脚本编写实操
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9641900.sHtML

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4555066.sHtML

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8513877.sHtML

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1579530.sHtML

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1604384.sHtML

原标题：Git 仓库瘦身加快克隆下载速度
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5875328.sHtML

原标题：golang ci 流水线环境变量管理方案
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9374993.sHtML

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1620812.sHtML

原标题：分页逻辑错误数据漏查修复
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2730550.sHtML

原标题：golang redis pipeline 批量操作
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7206780.sHtML

原标题：限流组件计数器令牌桶模式实现
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1555796.sHtML

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3507919.sHtML

四、架构设计｜Architecture
原标题：设计思考：分布式ID系统架构选型对比
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7511127.sHtML

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1280213.sHtML

原标题：部署实践：服务器时间同步chrony配置
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/1882029.sHtML

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7981729.sHtML

原标题：进程线程并发基础概念讲解
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6822147.sHtML

原标题：golang kafka 批量发送消费优化
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/8466106.sHtML

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/0180437.sHtML

原标题：golang 优雅处理 http 超时设置
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/9740875.sHtML

原标题：golang git 提交信息规范校验
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4689318.sHtML

原标题：5分钟快速搭建个人技术文档站点
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4133904.sHtML

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6869940.sHtML

原标题：golang kafka 消息丢失重复消费
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/4590798.sHtML

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/3407557.sHtML

原标题：GET POST 接口请求参数处理
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5657870.sHtML

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/2653867.sHtML

原标题：新手向：开源项目依赖安装失败排查
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/7550622.sHtML

原标题：文件监控服务自动重启开发
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/6721729.sHtML

原标题：ORM 框架数据库增删改查实操
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://zhishi.4nz2g7.asia/blog/5329165.sHtML

?
