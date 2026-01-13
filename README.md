# 产品详细设计文档 Skill

## 概述

这是一个基于业界最佳实践的产品详细设计文档生成工具，综合了多个GitHub开源项目的优秀经验。

## 功能特性

- 基于IEEE 1016-2009和ISO/IEC/IEEE 42010标准
- 支持多视图架构设计（应用、安全、规模、基础设施、开发）
- 包含完整的非功能性需求和质量属性分析
- 提供可追溯的需求-设计-决策链路
- Markdown格式，版本控制友好

## 使用方法

```bash
# 使用Claude Code调用此skill
/product-design-doc
```

## 模板来源

本模板综合了以下开源项目的最佳实践：

- [bflorat/architecture-document-template](https://github.com/bflorat/architecture-document-template) - 五视图架构模板
- [jam01/SDD-Template](https://github.com/jam01/SDD-Template) - IEEE标准的软件设计描述
- [shekhargulati/software-architecture-document-template](https://github.com/shekhargulati/software-architecture-document-template) - 软件架构文档模板
- [wepay/design_doc_template](https://github.com/wepay/design_doc_template) - 微服务设计文档

## 文档结构

详细设计文档包含以下主要部分：

1. **文档概述** - 元数据、版本信息
2. **引言** - 目的、范围、术语、参考
3. **设计概述** - 利益相关者、关注点、设计视角
4. **架构视图** - 五个核心架构视图
   - 应用视图
   - 开发视图
   - 安全视图
   - 规模视图
   - 基础设施视图
5. **架构决策** - 重要设计决策及其理由
6. **附录** - 补充材料

## 许可证

MIT License

## 贡献

欢迎提交Issue和Pull Request！
