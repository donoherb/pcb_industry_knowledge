# 跨Skill调用接口

## 定位

本文给其他skill提供调用PCB/载板知识库的最小协议。其他skill包括但不限于文档、演示、表格、研究、报告生成、翻译、质量工具、项目管理和自动化类skill。

核心原则：调用方保留自己的交付格式和工作流，本知识库只提供PCB/IC载板领域知识、口径校验、术语统一和风险提示。

## 调用入口

| 项目 | 约定 |
| --- | --- |
| skill名称 | `pcb-industry-knowledge` |
| 首读文件 | `references/38-cross-skill-integration.md` |
| 总路由 | `references/00-index.md` |
| 基础入口 | `references/37-foundational-primer.md` |
| 来源和动态事实规则 | `references/07-source-standards.md` |
| 术语统一 | `references/06-terminology.md` |

调用方若只能读取一个文件，应优先读取本文；若能读取两个文件，应读取本文和 `00-index.md`。

## 触发条件

其他skill在任务中遇到以下关键词或语义时，应调用本知识库：

- PCB、PWB、印制电路板、印制线路板、线路板、板厂。
- IC载板、封装基板、package substrate、ABF、BT、FC-BGA、FC-CSP、SiP。
- HDI、FPC、软硬结合、SLP、mSAP/SAP、高频高速板、高多层板、背板。
- CCL、PP、铜箔、ABF膜、BT树脂、PI、FCCL、PTFE、低损耗材料。
- AOI、AVI、ET、电测、阻抗、切片、孔铜、CAF、翘曲、可靠性、PPAP、APQP、8D、SPC、MSA。
- PCB/载板公司分析、产能、扩产、客户认证、良率、毛利率、项目可研、尽调。

如果任务只需要排版、文件格式转换或通用写作，不需要PCB/载板知识判断，则不必调用本知识库。

## 调用流程

调用方按以下顺序执行：

1. 识别问题边界：PCB还是IC载板；产品段、应用端、区域、时间口径和交付物类型。
2. 先读本文和 `00-index.md`；如果是新人入门或口径不清，再读 `37-foundational-primer.md`。
3. 按“调用路由表”读取最小专题文件，避免一次加载整个知识库。
4. 输出时保留调用方skill的格式，但在事实判断中标注“稳定知识、动态事实、待核验项”。
5. 涉及市场规模、公司排名、产能、价格、客户份额、财务、标准最新版本和政策时，按 `07-source-standards.md` 核验日期和来源。

## 调用路由表

| 调用意图 | 最小读取文件 | 适用输出 |
| --- | --- | --- |
| 基础解释、培训材料、术语统一 | `37-foundational-primer.md`、`06-terminology.md` | 培训稿、FAQ、入门说明、术语表 |
| 行业链条、商业模式、需求逻辑 | `01-industry-chain.md`、`00-index.md` | 行业报告、战略简报、研究框架 |
| 产品分类和技术路线对比 | `02-products-tech.md`、`37-foundational-primer.md` | 技术路线表、产品说明、竞品对比 |
| 材料、设备、耗材和供应风险 | `03-materials-and-equipment.md`、`21-supplier-quality-iqc-scar.md` | 供应链分析、采购评审、替代方案 |
| 制程、缺陷、良率和可靠性 | `04-process-quality.md`、`36-defect-scrap-mapping-aoi-et-fqc.md` | 质量报告、失效分析、改善项目 |
| 标准、认证、CSR和合规口径 | `39-standards-certifications-and-compliance.md`、`07-source-standards.md` | 标准口径、审核准备、客户要求解释 |
| 报价、成本建模和商业条款 | `40-quotation-costing-and-commercial-terms.md`、`09-operations-cost-and-delisking.md` | 报价评审、成本模型、商业风险清单 |
| 产能、良率爬坡和瓶颈 | `41-capacity-yield-ramp-and-bottlenecks.md`、`09-operations-cost-and-delisking.md` | 扩产可研、产能模型、爬坡复盘 |
| HDI/mSAP/表面处理/IST/CAF深挖 | `42-key-processes-hdi-msap-surfacefinish-reliability.md`、`04-process-quality.md` | 技术路线深挖、工艺尽调、可靠性评审 |
| 设计评审、DFM、可靠性验证、FA | `08-design-reliability-and-testing.md`、`33-engineering-cam-mi-data-control.md` | 工程评审、DVP&R、FA计划 |
| 工厂运营、成本、NPI、扩产去风险 | `09-operations-cost-and-delisking.md`、`05-financial-and-company-analysis.md` | 可研报告、产能模型、经营分析 |
| 公司财务、产能、客户和盈利质量 | `05-financial-and-company-analysis.md`、`01-industry-chain.md`、`07-source-standards.md` | 公司深度、尽调清单、投资备忘录 |
| 产品段尽调问题库和访谈脚本 | `43-due-diligence-question-bank-by-segment.md`、`05-financial-and-company-analysis.md` | 尽调问题清单、访谈提纲、证据索引 |
| 缺陷机理、FA和闭环回写 | `44-defect-mechanisms-fa-linkage-library.md`、`32-8d.md`、`31-fmea.md` | 8D、FA计划、根因分析、控制回写 |
| 产品段商业模型和ASP驱动 | `45-commercial-model-and-asp-drivers-by-segment.md`、`40-quotation-costing-and-commercial-terms.md`、`41-capacity-yield-ramp-and-bottlenecks.md` | 商业模型、盈利质量、敏感性分析 |
| 客户导入和NPI证据链 | `46-customer-npi-evidence-pack-sample-to-massproduction.md`、`26-apqp.md`、`30-ppap.md` | NPI状态页、客户认证证据、量产放行 |
| 可复制交付物模板 | `47-deliverable-templates-pack.md`、`07-source-standards.md` | 访谈纪要、尽调页、商业模型页、8D+FA页 |
| AI服务器/交换机高速板 | `10-ai-server-and-switch-high-speed-pcb.md`、`08-design-reliability-and-testing.md` | 高速板专题、AI硬件供应链分析 |
| 汽车PCB和车载雷达 | `11-automotive-pcb-and-radar.md`、`26-apqp.md` | 车规项目、客户导入、质量策划 |
| ABF/BT载板和先进封装协同 | `12-abf-bt-substrates-and-advanced-packaging.md`、`08-design-reliability-and-testing.md` | 载板专题、封装供应链分析 |
| FPC和软硬结合板 | `13-fpc-and-rigid-flex-special-topic.md`、`04-process-quality.md` | FPC专题、弯折可靠性、装配协同 |
| APQP、PPAP、FMEA、MSA、SPC、8D | `26-apqp.md`、`27-msa.md`、`28-spc.md`、`29-control-plan.md`、`30-ppap.md`、`31-fmea.md`、`32-8d.md` | 质量工具模板、客户提交、改善闭环 |
| 不合格品、MRB、客诉、RMA、变更 | `17-nonconforming-product-management.md`、`20-change-management-ecn-ecr.md`、`23-customer-complaint-field-failure-rma.md` | 8D、MRB、客诉闭环、ECN评审 |
| 追溯、标签、包装、实验室相关性 | `24-traceability-labeling-packaging.md`、`25-laboratory-correlation-test-management.md` | 客诉证据链、包装规范、数据争议 |
| 设备、治具、EHS、化学品 | `34-equipment-maintenance-and-tooling.md`、`35-environment-ehs-chemical-management.md` | 工厂审核、运营风险、合规清单 |

## 知识包输出格式

调用方可把从本知识库获得的信息整理为以下结构，再嵌入自己的最终交付物：

```text
PCB知识包
对象边界：PCB / IC载板 / FPC / HDI / ABF / BT / 其他。
读取文件：列出实际读取的references文件。
稳定知识：可直接用于分析框架的定义、分类、机理、流程或检查清单。
动态事实：需要来源、日期和口径核验的市场、公司、产能、财务、客户、政策或标准信息。
关键口径：时间、区域、单位、产品、公司主体、产能类型、认证状态。
风险提示：不要混用的概念、客户文件优先事项、待核验项。
```

不要求每次都把知识包全文展示给用户；当调用方生成报告、PPT、表格或文档时，可把知识包作为内部依据，并在最终输出中保留必要的口径和来源说明。

## 动态事实规则

以下内容不能只依赖本地知识库：

- 最新市场规模、价格、供需、增长率和行业排名。
- 公司产能、扩产进度、客户份额、财务数据、管理层和股权结构。
- 客户认证状态、供应商名单、报价条款和订单状态。
- 政策、关税、出口管制、环保法规和标准最新版本。

遇到这些内容，调用方应先读 `07-source-standards.md`，再联网或读取用户提供的一手资料核验。若无法核验，应在输出中写明“待核验”或“合理推断”，不要写成事实。

## 与常见Skill的协作方式

| 调用方skill | 本知识库提供 | 调用方保留 |
| --- | --- | --- |
| 文档/报告skill | 行业框架、术语、事实口径、风险提示 | 文档结构、排版、引用样式、最终交付文件 |
| 演示/PPT skill | slide内容逻辑、图表口径、讲述主线 | 版式、视觉层级、母版、导出和渲染验证 |
| 表格/建模skill | 成本项、产能口径、财务分析字段 | 公式、工作表结构、图表和数据校验 |
| 翻译/术语skill | PCB/载板双语术语和易混词 | 目标语言风格、术语表格式和上下文适配 |
| 质量工具skill | APQP/PPAP/FMEA/SPC/MSA/8D行业落地逻辑 | 企业模板、客户特定要求和表单格式 |
| 自动化/检索skill | 路由关键词、文件选择和待核验规则 | 检索实现、索引机制、权限和缓存策略 |

## 调用示例

文档skill遇到“做一份ABF载板行业入门报告”时：

1. 先读 `38-cross-skill-integration.md`、`00-index.md`。
2. 再读 `37-foundational-primer.md`、`12-abf-bt-substrates-and-advanced-packaging.md`、`01-industry-chain.md`。
3. 若报告包含最新市场规模或公司排名，再按 `07-source-standards.md` 核验来源。
4. 最终仍由文档skill负责报告结构、样式和文件生成。

表格skill遇到“做PCB扩产项目测算模型”时：

1. 读 `09-operations-cost-and-delisking.md`、`05-financial-and-company-analysis.md`、`03-materials-and-equipment.md`。
2. 将设计产能、有效产能、良率后合格产出、稼动率、ASP、材料成本、折旧和现金流分开建模。
3. 对具体价格、产能和财务数据按 `07-source-standards.md` 标注来源和日期。

## 调用边界

- 本知识库不替代客户图纸、质量协议、采购文件、授权标准原文和企业QMS程序。
- 本知识库不保证动态事实最新；调用方必须按日期和来源核验。
- 本知识库提供行业稳定知识和分析框架，不替调用方决定最终交付格式。
- 若调用方输出面向投资、供应商选择、客户批准或合规判断，应显式写清假设、来源和待核验项。
