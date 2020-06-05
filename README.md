# kong-limite-rate-plugin
kong 限制下载速率 插件

## 功能
- 通过配置插件的config类型，进行限制下载速率的大小
- 支持在下载多少大小后，开始执行限速的大小

## 核心实现
`ngx.var.limit_rate`  
`ngx.var.limit_rate_after`

这个是在OpenResty提供的两种方式
