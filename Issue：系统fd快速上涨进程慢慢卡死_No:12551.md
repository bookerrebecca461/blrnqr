最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.sezp3s.asia/arts/519068.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.sezp3s.asia/arts/636229.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.sezp3s.asia/arts/911739.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.sezp3s.asia/arts/784222.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.sezp3s.asia/arts/300329.Doc

原标题：golang 配置热更新不重启服务
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.sezp3s.asia/arts/830297.Doc

原标题：接口请求重试容错机制实现
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.sezp3s.asia/arts/412791.Doc

原标题：Performance：JSON序列化性能优化实践
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.sezp3s.asia/arts/827216.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.sezp3s.asia/arts/826112.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.sezp3s.asia/arts/881660.Doc

原标题：golang 参数校验业务接口处理
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.sezp3s.asia/arts/857658.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.sezp3s.asia/arts/748453.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.sezp3s.asia/arts/595142.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.sezp3s.asia/arts/823408.Doc

原标题：golang websocket 服务端开发
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.sezp3s.asia/arts/690762.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.sezp3s.asia/arts/459121.Doc

原标题：golang 表单文件大小限制配置
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.sezp3s.asia/arts/299483.Doc

原标题：分布式任务调度集群原型开发
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.sezp3s.asia/arts/099990.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.sezp3s.asia/arts/296567.Doc

原标题：golang 接口请求日志记录中间件
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.sezp3s.asia/arts/885876.Doc

原标题：多实例部署 Session 共享方案
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.sezp3s.asia/arts/347096.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.sezp3s.asia/arts/245436.Doc

原标题：Spring 事务传播机制配置生效
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.sezp3s.asia/arts/417387.Doc

原标题：golang docker 镜像构建最佳实践
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.sezp3s.asia/arts/454833.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.sezp3s.asia/arts/290035.Doc

原标题：golang yaml 解析配置加载实操
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.sezp3s.asia/arts/877883.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.sezp3s.asia/arts/290682.Doc

原标题：文件监控服务自动重启开发
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.sezp3s.asia/arts/396628.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.sezp3s.asia/arts/806361.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.sezp3s.asia/arts/668814.Doc

原标题：无用对象回收抑制内存上涨
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.sezp3s.asia/arts/826867.Doc

原标题：前端 pdf 预览渲染方案对比
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.sezp3s.asia/arts/850965.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.sezp3s.asia/arts/592732.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.sezp3s.asia/arts/907465.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.sezp3s.asia/arts/229769.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.sezp3s.asia/arts/204033.Doc

原标题：Git 分支管理多人协作实战教程
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.sezp3s.asia/arts/647365.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.sezp3s.asia/arts/889706.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.sezp3s.asia/arts/537936.Doc

原标题：从零学习基础的接口请求与参数处理
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.sezp3s.asia/arts/048309.Doc


二、踩坑排错｜Troubleshooting
原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.sezp3s.asia/arts/004006.Doc

原标题：golang 系统设计字段命名类型选择最佳实践
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.sezp3s.asia/arts/044035.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.sezp3s.asia/arts/856206.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.sezp3s.asia/arts/195709.Doc

原标题：golang redis 集群 hash 槽讲解
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.sezp3s.asia/arts/566125.Doc

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.sezp3s.asia/arts/865306.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.sezp3s.asia/arts/707217.Doc

原标题：golang mongodb 索引优化查询速度
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.sezp3s.asia/arts/840688.Doc

原标题：golang minio 对象存储接口开发
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.sezp3s.asia/arts/758333.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.sezp3s.asia/arts/783114.Doc

原标题：golang redis 发布订阅简单示例
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.sezp3s.asia/arts/534631.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.sezp3s.asia/arts/937887.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.sezp3s.asia/arts/205777.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.sezp3s.asia/arts/956196.Doc

原标题：golang 系统设计分库分表中间件思路
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.sezp3s.asia/arts/389001.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.sezp3s.asia/arts/555495.Doc

原标题：golang es 聚合统计查询实现
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.sezp3s.asia/arts/234513.Doc

原标题：分页逻辑错误数据漏查修复
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.sezp3s.asia/arts/822113.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.sezp3s.asia/arts/558314.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.sezp3s.asia/arts/118444.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.sezp3s.asia/arts/696922.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.sezp3s.asia/arts/604531.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.sezp3s.asia/arts/301938.Doc

原标题：golang redis set 集合去重业务
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.sezp3s.asia/arts/197588.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.sezp3s.asia/arts/961693.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.sezp3s.asia/arts/553111.Doc

原标题：依赖安装失败全方位排错
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.sezp3s.asia/arts/008442.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.sezp3s.asia/arts/187020.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.sezp3s.asia/arts/815446.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.sezp3s.asia/arts/759771.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.sezp3s.asia/arts/808552.Doc

原标题：依赖版本冲突兼容修复方案
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.sezp3s.asia/arts/562258.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.sezp3s.asia/arts/912408.Doc

原标题：Git commit 钩子提交规范校验
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.sezp3s.asia/arts/692775.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.sezp3s.asia/arts/257738.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.sezp3s.asia/arts/340923.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.sezp3s.asia/arts/385368.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.sezp3s.asia/arts/578339.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.sezp3s.asia/arts/501620.Doc

原标题：golang 系统设计延迟队列业务实现
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.sezp3s.asia/arts/485432.Doc

三、实战开发｜Practice
原标题：golang mysql 长连接短连接对比
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.sezp3s.asia/arts/016542.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.sezp3s.asia/arts/375736.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.sezp3s.asia/arts/681819.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/004769.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.sezp3s.asia/arts/923139.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.sezp3s.asia/arts/681973.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.sezp3s.asia/arts/441996.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.sezp3s.asia/arts/204697.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.sezp3s.asia/arts/907889.Doc

原标题：golang gitlab runner 部署与注册实操
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.sezp3s.asia/arts/000811.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.sezp3s.asia/arts/631730.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.sezp3s.asia/arts/551436.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.sezp3s.asia/arts/889796.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.sezp3s.asia/arts/247282.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.sezp3s.asia/arts/237282.Doc

原标题：文件监控服务自动重启开发
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.sezp3s.asia/arts/111090.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.sezp3s.asia/arts/171752.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.sezp3s.asia/arts/072824.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.sezp3s.asia/arts/829157.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.sezp3s.asia/arts/434339.Doc

原标题：golang github actions 发布 release 包
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.sezp3s.asia/arts/784873.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.sezp3s.asia/arts/815061.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.sezp3s.asia/arts/896542.Doc

原标题：快速上手调试工具定位简单代码错误
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.sezp3s.asia/arts/670320.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.sezp3s.asia/arts/782112.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.sezp3s.asia/arts/633606.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/739583.Doc

原标题：日志输出规范防止磁盘爆满
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.sezp3s.asia/arts/112546.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.sezp3s.asia/arts/601642.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.sezp3s.asia/arts/603068.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.sezp3s.asia/arts/528491.Doc

原标题：golang minio 对象存储接口开发
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.sezp3s.asia/arts/219398.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.sezp3s.asia/arts/132866.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.sezp3s.asia/arts/473940.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.sezp3s.asia/arts/674415.Doc

原标题：vite 插件开发自定义构建逻辑
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/073064.Doc

原标题：golang 信号捕获程序退出处理
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.sezp3s.asia/arts/666387.Doc

原标题：项目语义化版本号规范管理
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.sezp3s.asia/arts/184463.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.sezp3s.asia/arts/344019.Doc

原标题：接口限流逻辑简单模拟实现
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.sezp3s.asia/arts/415475.Doc

四、架构设计｜Architecture
原标题：浮点计算精度错误处理方案
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.sezp3s.asia/arts/975420.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.sezp3s.asia/arts/182871.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.sezp3s.asia/arts/345171.Doc

原标题：前端工程化 webpack 打包优化
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.sezp3s.asia/arts/860496.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.sezp3s.asia/arts/890519.Doc

原标题：golang 告警推送钉钉机器人实现
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.sezp3s.asia/arts/397356.Doc

原标题：批量异步处理系统业务落地
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.sezp3s.asia/arts/869513.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.sezp3s.asia/arts/161076.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.sezp3s.asia/arts/021993.Doc

原标题：读懂开源项目 README 实用技巧
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.sezp3s.asia/arts/625599.Doc

原标题：golang 系统设计全局异常处理器实现
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.sezp3s.asia/arts/541498.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.sezp3s.asia/arts/954326.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.sezp3s.asia/arts/184981.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.sezp3s.asia/arts/539733.Doc

原标题：包管理器依赖冲突解决方案
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.sezp3s.asia/arts/373622.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.sezp3s.asia/arts/245006.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.sezp3s.asia/arts/539663.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.sezp3s.asia/arts/222260.Doc

?
