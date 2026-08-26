最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计最小权限原则落地实践
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.3f23ey.asia/arts/349607.Doc

原标题：golang k8s service 服务暴露几种类型
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.3f23ey.asia/arts/155502.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.3f23ey.asia/arts/590015.Doc

原标题：多版本开发环境共存配置
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.3f23ey.asia/arts/532993.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.3f23ey.asia/arts/204312.Doc

原标题：golang kafka 生产者参数调优
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.3f23ey.asia/arts/307169.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.3f23ey.asia/arts/729473.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.3f23ey.asia/arts/902992.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.3f23ey.asia/arts/407360.Doc

原标题：golang defer panic 异常处理
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.3f23ey.asia/arts/017630.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.3f23ey.asia/arts/378588.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.3f23ey.asia/arts/244747.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.3f23ey.asia/arts/550558.Doc

原标题：golang 系统设计参数校验统一处理方案
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.3f23ey.asia/arts/227448.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.3f23ey.asia/arts/752596.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.3f23ey.asia/arts/590056.Doc

原标题：golang 项目 docker compose 本地调试
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.3f23ey.asia/arts/187799.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.3f23ey.asia/arts/197428.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.3f23ey.asia/arts/484777.Doc

原标题：端口占用访问失败排查方案
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.3f23ey.asia/arts/329822.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.3f23ey.asia/arts/127335.Doc

原标题：golang redis 网络超时参数调优
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.3f23ey.asia/arts/342705.Doc

原标题：golang github actions 缓存依赖提速
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.3f23ey.asia/arts/241858.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.3f23ey.asia/arts/446804.Doc

原标题：golang redis 连接池参数最佳值
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.3f23ey.asia/arts/079555.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.3f23ey.asia/arts/412885.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.3f23ey.asia/arts/424734.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.3f23ey.asia/arts/230151.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.3f23ey.asia/arts/455765.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.3f23ey.asia/arts/546693.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.3f23ey.asia/arts/084067.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.3f23ey.asia/arts/127723.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.3f23ey.asia/arts/894069.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.3f23ey.asia/arts/640077.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.3f23ey.asia/arts/867036.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.3f23ey.asia/arts/059636.Doc

原标题：零基础理解HTTP常用请求头与状态码
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.3f23ey.asia/arts/420093.Doc

原标题：golang 系统设计大文件上传架构
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.3f23ey.asia/arts/831822.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.3f23ey.asia/arts/982342.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.3f23ey.asia/arts/502400.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计技术文档维护更新最佳实践
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.3f23ey.asia/arts/651054.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.3f23ey.asia/arts/608963.Doc

原标题：golang k8s helm chart 简单编写
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.3f23ey.asia/arts/097584.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.3f23ey.asia/arts/867336.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.3f23ey.asia/arts/217585.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.3f23ey.asia/arts/412243.Doc

原标题：线程池拒绝策略任务丢失防护
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.3f23ey.asia/arts/293951.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.3f23ey.asia/arts/012911.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.3f23ey.asia/arts/970218.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.3f23ey.asia/arts/161437.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.3f23ey.asia/arts/188847.Doc

原标题：接口签名校验防篡改实现
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.3f23ey.asia/arts/264722.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.3f23ey.asia/arts/938854.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.3f23ey.asia/arts/332448.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.3f23ey.asia/arts/338543.Doc

原标题：WebSocket 断线重连稳定优化
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.3f23ey.asia/arts/016374.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.3f23ey.asia/arts/539859.Doc

原标题：golang 简单爬虫请求防封禁
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.3f23ey.asia/arts/444188.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.3f23ey.asia/arts/195295.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.3f23ey.asia/arts/316084.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.3f23ey.asia/arts/464777.Doc

原标题：golang redis 五种数据结构实战
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.3f23ey.asia/arts/089603.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.3f23ey.asia/arts/161886.Doc

原标题：异步任务堆积消费能力优化
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.3f23ey.asia/arts/970286.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.3f23ey.asia/arts/290545.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.3f23ey.asia/arts/271743.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.3f23ey.asia/arts/100364.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.3f23ey.asia/arts/231115.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.3f23ey.asia/arts/460762.Doc

原标题：golang 系统信号信号量处理
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.3f23ey.asia/arts/768078.Doc

原标题：nodejs http 服务性能调优实战
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.3f23ey.asia/arts/599992.Doc

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.3f23ey.asia/arts/542881.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.3f23ey.asia/arts/120678.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.3f23ey.asia/arts/649262.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.3f23ey.asia/arts/549991.Doc

原标题：golang 优雅处理数据库事务
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.3f23ey.asia/arts/279531.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.3f23ey.asia/arts/894616.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.3f23ey.asia/arts/962435.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.3f23ey.asia/arts/751702.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.3f23ey.asia/arts/209713.Doc

三、实战开发｜Practice
原标题：网关集成鉴权限流日志一体化
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.3f23ey.asia/arts/736285.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.3f23ey.asia/arts/521853.Doc

原标题：文件读写与异常捕获代码示例
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.3f23ey.asia/arts/900438.Doc

原标题：项目脚手架模板生成工具
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.3f23ey.asia/arts/786543.Doc

原标题：定时任务周期调度 demo 开发
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.3f23ey.asia/arts/217258.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.3f23ey.asia/arts/420809.Doc

原标题：文件批量导入导出功能实现
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.3f23ey.asia/arts/771041.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.3f23ey.asia/arts/925026.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.3f23ey.asia/arts/309406.Doc

原标题：golang 分布式锁防死锁处理
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.3f23ey.asia/arts/939807.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.3f23ey.asia/arts/310140.Doc

原标题：部署实践：告警收敛避免告警风暴配置
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.3f23ey.asia/arts/966414.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.3f23ey.asia/arts/272869.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.3f23ey.asia/arts/555103.Doc

原标题：css 动画性能优化 GPU 加速
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.3f23ey.asia/arts/590890.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.3f23ey.asia/arts/561395.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.3f23ey.asia/arts/696352.Doc

原标题：golang 系统设计海量数据分页查询
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.3f23ey.asia/arts/252602.Doc

原标题：golang 表单文件大小限制配置
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.3f23ey.asia/arts/649430.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.3f23ey.asia/arts/834700.Doc

原标题：golang redis lua 脚本开发调试
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.3f23ey.asia/arts/908630.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.3f23ey.asia/arts/963718.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.3f23ey.asia/arts/992163.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.3f23ey.asia/arts/317545.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.3f23ey.asia/arts/853254.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.3f23ey.asia/arts/695692.Doc

原标题：Shell 脚本自动化命令编写
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.3f23ey.asia/arts/551321.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.3f23ey.asia/arts/678066.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.3f23ey.asia/arts/223003.Doc

原标题：前端大文件分片上传完整方案
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.3f23ey.asia/arts/979887.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.3f23ey.asia/arts/077942.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.3f23ey.asia/arts/475002.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.3f23ey.asia/arts/629510.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.3f23ey.asia/arts/966439.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.3f23ey.asia/arts/563185.Doc

原标题：golang 跨域处理中间件编写
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.3f23ey.asia/arts/423206.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.3f23ey.asia/arts/671236.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.3f23ey.asia/arts/181967.Doc

原标题：golang 空接口 interface 使用技巧
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.3f23ey.asia/arts/141355.Doc

原标题：nodejs 全局异常捕获进程防护
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.3f23ey.asia/arts/900228.Doc

四、架构设计｜Architecture
原标题：实战项目：百万日志文件解析处理脚本实践
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.3f23ey.asia/arts/815476.Doc

原标题：nodejs 多进程任务分发处理
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.3f23ey.asia/arts/646833.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.3f23ey.asia/arts/269091.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.3f23ey.asia/arts/858329.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.3f23ey.asia/arts/851626.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.3f23ey.asia/arts/614918.Doc

原标题：golang 接口限流中间件开发
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.3f23ey.asia/arts/154673.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.3f23ey.asia/arts/206831.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.3f23ey.asia/arts/810434.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.3f23ey.asia/arts/420677.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.3f23ey.asia/arts/607469.Doc

原标题：golang es 索引生命周期管理思路
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.3f23ey.asia/arts/880235.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.3f23ey.asia/arts/125230.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.3f23ey.asia/arts/521763.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.3f23ey.asia/arts/895465.Doc

原标题：环境变量不生效问题修复
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.3f23ey.asia/arts/033505.Doc

原标题：nestjs 框架模块化项目搭建
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.3f23ey.asia/arts/016651.Doc

原标题：YAML 配置文件语法快速上手
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.3f23ey.asia/arts/646311.Doc

?
