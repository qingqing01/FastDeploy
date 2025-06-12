# FastDeploy

FastDeploy 是飞桨（PaddlePaddle）开源的面向大模型的推理部署工具。当前，FastDeploy 支持 xxxx 模型，其推理部署功能涵盖：

- 一行命令即可快速实现模型的服务化部署，并支持流式生成
- 利用张量并行技术加速模型推理
- 支持 PagedAttention 与 continuous batching（动态批处理）
- 兼容 OpenAI 的 HTTP 协议
- 提供 Weight only int8/int4 无损压缩方案
- 支持 Prometheus Metrics 指标

了解更多FastDeploy使用方式，阅读相关文档，

- [10分钟完成部署](./get_started/quick_start.md)
