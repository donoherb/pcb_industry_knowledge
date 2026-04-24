# pcb-industry-knowledge

PCB / IC载板行业研究与制造质量工具知识库（Cursor Agent Skill）。

## 这是什么

本 skill 将 PCB 与 IC 载板（封装基板）相关的**稳定方法论**与**可复用交付物模板**沉淀为一套可路由的 `references/` 文档，用于支持：

- 行业/公司研究与尽调（商业模型、产能/良率爬坡、扩产去风险）
- 工艺与技术路线对比（HDI、(m)SAP、表面处理、可靠性）
- 质量体系工具落地（APQP、MSA、SPC、Control Plan、PPAP、FMEA、8D、NCM/MRB、ECN）
- 客户导入与证据链管理（样品→小批量→Safe Launch→量产放行）
- 术语中英统一与资料整理

## 如何使用（推荐路径）

- **入口路由**：先看 `references/00-index.md` 的“快速路由”，用“用户问题 → 先读/再读”定位要加载的参考文件。
- **引用与更新规则**：涉及市场规模、公司排名、产能、报价、客户、资本开支、政策、标准版本等**动态事实**时，必须按 `references/07-source-standards.md` 标注来源与日期。
- **输出结构**：遵循 `SKILL.md` 的“输出结构建议”，先写结论与边界，再给证据链与待核验项。

## 内容结构

- **基础与总览**
  - `references/00-index.md`：总索引与任务路由
  - `references/01-industry-chain.md`：产业链与商业模式
  - `references/02-products-tech.md`：产品分类与技术路线
  - `references/06-terminology.md`：术语与缩写
  - `references/07-source-standards.md`：来源分级、引用格式、更新规则

- **工艺/工程/可靠性**
  - `references/03-materials-and-equipment.md`：材料与设备
  - `references/04-process-quality.md`：制程与质量指标
  - `references/08-design-reliability-and-testing.md`：DFM/可靠性/FA边界
  - `references/40-key-processes-hdi-msap-surfacefinish-reliability.md`：HDI/(m)SAP/表面处理/IST/CAF

- **运营/产能/成本/条款**
  - `references/09-operations-cost-and-delisking.md`：运营指标、成本、去风险
  - `references/38-quotation-costing-and-commercial-terms.md`：报价/成本建模/条款风险
  - `references/39-capacity-yield-ramp-and-bottlenecks.md`：名义→合格产出、爬坡与瓶颈
  - `references/43-commercial-model-and-asp-drivers-by-segment.md`：商业模型与ASP驱动（按产品段）

- **质量工具链（APQP → PPAP）与闭环**
  - `references/26-apqp.md`、`27-msa.md`、`28-spc.md`、`29-control-plan.md`、`30-ppap.md`
  - `references/31-fmea.md`、`32-8d.md`
  - `references/17-nonconforming-product-management.md`、`18-nonconforming-product-templates.md`、`19-mrb-case-library.md`
  - `references/20-change-management-ecn-ecr.md`、`21-supplier-quality-iqc-scar.md`、`22-audit-readiness-lpa-process-audit.md`
  - `references/23-customer-complaint-field-failure-rma.md`、`24-traceability-labeling-packaging.md`、`25-laboratory-correlation-test-management.md`
  - `references/42-defect-mechanisms-fa-linkage-library.md`：缺陷机理→最小验证→回写（联动8D/FMEA/Control Plan/SPC/MSA）

- **尽调/导入与模板**
  - `references/41-due-diligence-question-bank-by-segment.md`：按产品段的尽调问题库（强调证据链）
  - `references/44-customer-npi-evidence-pack-sample-to-massproduction.md`：客户导入证据链包
  - `references/45-deliverable-templates-pack.md`：交付物模板包（尽调/访谈/商业模型/8D-FA/NPI状态/扩产评审）

- **标准/认证/合规口径**
  - `references/37-standards-certifications-and-compliance.md`：IPC/JEDEC/UL/ISO/IATF/OEM CSR 的版本核验与口径边界（不替代授权原文）

## 典型交付物（快速索引）

- **尽调访谈与结论**：`41-...`、`45-...`
- **商业模型与盈利质量**：`43-...`、`38-...`、`39-...`、`09-...`
- **缺陷FA与闭环回写**：`42-...`、`32-...`、`31-...`、`29-...`
- **客户导入证据链**：`44-...`、`26-...`、`30-...`、`20-...`

## 重要约束（务必遵守）

- **动态事实必须核验**：任何“最新/现在/今年/目前”相关结论，先联网或读取用户提供材料核验，并在输出里标注来源与日期。
- **客户文件优先**：客户图纸/质量协议/CSR 优先于通用标准与知识库说明。
- **不要把推断当事实**：明确区分“已确认 / 合理推断 / 待核验”。

