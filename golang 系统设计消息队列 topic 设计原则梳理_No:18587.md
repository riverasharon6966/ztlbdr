最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.gnrx79.asia/blog/805272.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.gnrx79.asia/blog/199151.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.gnrx79.asia/blog/755223.Doc

原标题：从零搭建简单Mock接口服务
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.gnrx79.asia/blog/538140.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://book.gnrx79.asia/blog/022308.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://book.gnrx79.asia/blog/088429.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.gnrx79.asia/blog/462925.Doc

原标题：golang 系统设计短链接服务实现思路
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.gnrx79.asia/blog/437671.Doc

原标题：golang redis set 集合去重业务
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.gnrx79.asia/blog/825908.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.gnrx79.asia/blog/688845.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.gnrx79.asia/blog/637330.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.gnrx79.asia/blog/870278.Doc

原标题：golang 内存缓存简单实现方案
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.gnrx79.asia/blog/237393.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.gnrx79.asia/blog/466762.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.gnrx79.asia/blog/796033.Doc

原标题：golang 系统设计容量评估简单方法论
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.gnrx79.asia/blog/804052.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.gnrx79.asia/blog/356344.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.gnrx79.asia/blog/048523.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.gnrx79.asia/blog/904601.Doc

原标题：golang kafka 重试机制配置实操
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.gnrx79.asia/blog/377800.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.gnrx79.asia/blog/945567.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.gnrx79.asia/blog/107807.Doc

原标题：golang 表单文件大小限制配置
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.gnrx79.asia/blog/243691.Doc

原标题：golang mysql exists in 性能对比
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.gnrx79.asia/blog/723613.Doc

原标题：数据库分表路由写入分片修正
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.gnrx79.asia/blog/585928.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.gnrx79.asia/blog/483974.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.gnrx79.asia/blog/426217.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.gnrx79.asia/blog/688546.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.gnrx79.asia/blog/307145.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.gnrx79.asia/blog/946221.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.gnrx79.asia/blog/882867.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.gnrx79.asia/blog/342900.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.gnrx79.asia/blog/883007.Doc

原标题：Dockerfile 编写容器打包实战
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.gnrx79.asia/blog/593404.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.gnrx79.asia/blog/498693.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.gnrx79.asia/blog/914811.Doc

原标题：golang url 参数编码处理方案
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.gnrx79.asia/blog/192939.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.gnrx79.asia/blog/082504.Doc

原标题：golang redis 限流几种实现方案
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.gnrx79.asia/blog/974599.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.gnrx79.asia/blog/244882.Doc


二、踩坑排错｜Troubleshooting
原标题：踩坑：大事务引发数据库连接池耗尽
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.gnrx79.asia/blog/681596.Doc

原标题：接口压测定位系统性能瓶颈
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.gnrx79.asia/blog/393310.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.gnrx79.asia/blog/359350.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.gnrx79.asia/blog/464361.Doc

原标题：后端大文件分片上传接口开发
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.gnrx79.asia/blog/911446.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.gnrx79.asia/blog/372155.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.gnrx79.asia/blog/761592.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.gnrx79.asia/blog/627749.Doc

原标题：golang 数据库批量更新性能优化
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.gnrx79.asia/blog/898968.Doc

原标题：Shell 脚本自动化命令编写
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://book.gnrx79.asia/blog/667439.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.gnrx79.asia/blog/126066.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.gnrx79.asia/blog/590759.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.gnrx79.asia/blog/523841.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.gnrx79.asia/blog/238704.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.gnrx79.asia/blog/384959.Doc

原标题：快速入门消息通知简单实现方案
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.gnrx79.asia/blog/055814.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.gnrx79.asia/blog/431978.Doc

原标题：多线程线程安全脏数据规避
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.gnrx79.asia/blog/607625.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.gnrx79.asia/blog/171156.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.gnrx79.asia/blog/727652.Doc

原标题：分布式 ID 全局唯一生成方案
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.gnrx79.asia/blog/505119.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.gnrx79.asia/blog/824749.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.gnrx79.asia/blog/093600.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.gnrx79.asia/blog/796518.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.gnrx79.asia/blog/671739.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.gnrx79.asia/blog/614481.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.gnrx79.asia/blog/919865.Doc

原标题：golang github actions 多平台构建
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://book.gnrx79.asia/blog/251911.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.gnrx79.asia/blog/786230.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.gnrx79.asia/blog/835844.Doc

原标题：日志敏感信息脱敏泄露防护
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.gnrx79.asia/blog/363618.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.gnrx79.asia/blog/523348.Doc

原标题：golang 系统设计短信发送限流降级
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.gnrx79.asia/blog/685159.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.gnrx79.asia/blog/894383.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.gnrx79.asia/blog/406630.Doc

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.gnrx79.asia/blog/071885.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.gnrx79.asia/blog/291051.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.gnrx79.asia/blog/153633.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.gnrx79.asia/blog/376814.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.gnrx79.asia/blog/762701.Doc

三、实战开发｜Practice
原标题：golang redis 批量 pipeline 实践
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.gnrx79.asia/blog/955111.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.gnrx79.asia/blog/898396.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.gnrx79.asia/blog/941060.Doc

原标题：读懂开源项目 README 实用技巧
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.gnrx79.asia/blog/517607.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.gnrx79.asia/blog/356843.Doc

原标题：YAML 配置文件语法快速上手
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.gnrx79.asia/blog/884306.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.gnrx79.asia/blog/892123.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.gnrx79.asia/blog/891721.Doc

原标题：文件读写与异常捕获代码示例
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.gnrx79.asia/blog/631381.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.gnrx79.asia/blog/178004.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.gnrx79.asia/blog/320314.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.gnrx79.asia/blog/234463.Doc

原标题：golang 内存缓存简单实现方案
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.gnrx79.asia/blog/282008.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.gnrx79.asia/blog/502920.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.gnrx79.asia/blog/186330.Doc

原标题：golang prometheus counter gauge 使用
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.gnrx79.asia/blog/271565.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.gnrx79.asia/blog/818399.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.gnrx79.asia/blog/961933.Doc

原标题：全量回归测试提升代码质量
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.gnrx79.asia/blog/184213.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.gnrx79.asia/blog/740918.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.gnrx79.asia/blog/041734.Doc

原标题：golang dockerfile 多阶段构建详解
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.gnrx79.asia/blog/856257.Doc

原标题：golang k8s configmap secret 配置
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.gnrx79.asia/blog/141811.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.gnrx79.asia/blog/642523.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.gnrx79.asia/blog/673689.Doc

原标题：日志输出规范防止磁盘爆满
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.gnrx79.asia/blog/428427.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.gnrx79.asia/blog/840139.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.gnrx79.asia/blog/088131.Doc

原标题：前端组件库按需加载性能优化
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.gnrx79.asia/blog/681328.Doc

原标题：版本升级服务启动失败处理
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.gnrx79.asia/blog/085243.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.gnrx79.asia/blog/943411.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.gnrx79.asia/blog/235246.Doc

原标题：golang 速率限制令牌桶实现
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.gnrx79.asia/blog/388890.Doc

原标题：golang 信号量控制并发数量
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.gnrx79.asia/blog/340898.Doc

原标题：布隆过滤器误判问题修正
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.gnrx79.asia/blog/780645.Doc

原标题：进程线程并发基础概念讲解
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.gnrx79.asia/blog/015404.Doc

原标题：前端静态缓存更新生效处理
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.gnrx79.asia/blog/603116.Doc

原标题：Shell 运维脚本服务器效率提升
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.gnrx79.asia/blog/089159.Doc

原标题：golang redis 缓存预热实现思路
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.gnrx79.asia/blog/277308.Doc

原标题：快速入门对象存储基础使用场景
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.gnrx79.asia/blog/012755.Doc

四、架构设计｜Architecture
原标题：实战：单元测试+集成测试完整项目落地实践
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.gnrx79.asia/blog/897063.Doc

原标题：批量操作分批处理防止 OOM
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.gnrx79.asia/blog/786284.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.gnrx79.asia/blog/380355.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.gnrx79.asia/blog/444090.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.gnrx79.asia/blog/495394.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.gnrx79.asia/blog/744387.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.gnrx79.asia/blog/180415.Doc

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.gnrx79.asia/blog/751800.Doc

原标题：golang redis 缓存击穿防护实现
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.gnrx79.asia/blog/593093.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.gnrx79.asia/blog/207472.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.gnrx79.asia/blog/939289.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.gnrx79.asia/blog/883151.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.gnrx79.asia/blog/011421.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.gnrx79.asia/blog/339206.Doc

原标题：golang 系统设计容量评估简单方法论
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.gnrx79.asia/blog/644833.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.gnrx79.asia/blog/292515.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.gnrx79.asia/blog/480451.Doc

原标题：接口限流逻辑简单模拟实现
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.gnrx79.asia/blog/528731.Doc

?
