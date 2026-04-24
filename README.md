# pcb-industry-knowledge

PCB / IC载板行业研究、制造质量与商业分析知识库。

本 skill 通过 `SKILL.md` 和 `references/` 文件，为 Codex 以及其他 skills 提供 PCB、HDI、FPC、软硬结合板、IC载板、ABF/BT载板、材料设备、制程质量、成本产能、客户导入、尽调和交付物模板等领域知识。

## 使用入口

- 主入口：`SKILL.md`
- 总索引：`references/00-index.md`
- 跨 skill 调用接口：`references/38-cross-skill-integration.md`
- 基础入门：`references/37-foundational-primer.md`
- 来源与动态事实规则：`references/07-source-standards.md`
- 术语统一：`references/06-terminology.md`

其他 skills 需要调用 PCB/载板知识时，优先读取 `references/38-cross-skill-integration.md`，再按其中的路由表读取最小专题文件。

## 内容结构

### 基础与总览

- `references/00-index.md`：总索引、任务路由、PCB与IC载板基本边界
- `references/01-industry-chain.md`：产业链、商业模式、需求驱动和区域分工
- `references/02-products-tech.md`：产品分类、技术路线和关键能力指标
- `references/03-materials-and-equipment.md`：CCL、铜箔、树脂、ABF/BT、药水、设备和耗材
- `references/06-terminology.md`：中英文术语、缩写和易混词
- `references/07-source-standards.md`：来源分级、引用格式、动态事实和标准资料更新规则

### 基础知识与跨 skill 调用

- `references/37-foundational-primer.md`：新人入门、跨职能沟通和基础口径统一
- `references/38-cross-skill-integration.md`：供文档、演示、表格、翻译、质量工具和自动化类 skills 调用

### 工艺、工程与可靠性

- `references/04-process-quality.md`：制程流程、良率瓶颈、可靠性、质量指标和常见标准
- `references/08-design-reliability-and-testing.md`：DFM/DFX、CAM/MI、stack-up、高速设计、可靠性验证和FA
- `references/33-engineering-cam-mi-data-control.md`：工程资料、Gerber/ODB++/IPC-2581、程序版本和工程放行
- `references/34-equipment-maintenance-and-tooling.md`：设备维护、治具、OEE、PM、备件和设备变更
- `references/35-environment-ehs-chemical-management.md`：EHS、环保、化学品、废水废气、危废和绿色供应链
- `references/36-defect-scrap-mapping-aoi-et-fqc.md`：AOI/AVI、ET、FQC、缺陷位置图和报废 mapping
- `references/42-key-processes-hdi-msap-surfacefinish-reliability.md`：HDI、mSAP/SAP、表面处理、IST/CAF和关键工艺路线

### 运营、成本、产能与商业模型

- `references/05-financial-and-company-analysis.md`：公司研究、财务指标、产能、资本开支和尽调模板
- `references/09-operations-cost-and-delisking.md`：工厂运营指标、成本结构、NPI、Safe Launch和扩产去风险
- `references/40-quotation-costing-and-commercial-terms.md`：报价拆解、成本建模、质量成本、商业条款和风险
- `references/41-capacity-yield-ramp-and-bottlenecks.md`：名义产能、有效产能、良率爬坡、瓶颈识别和扩产去风险
- `references/45-commercial-model-and-asp-drivers-by-segment.md`：按产品段拆解 ASP、良率、折旧、COPQ、条款和现金流敏感项

### 标准、认证与客户导入

- `references/39-standards-certifications-and-compliance.md`：IPC、JEDEC、UL、ISO/IATF、OEM CSR和合规口径
- `references/46-customer-npi-evidence-pack-sample-to-massproduction.md`：客户导入证据链，覆盖样品、小批量、Safe Launch和量产放行

### 质量工具链

- `references/26-apqp.md`：APQP、VOC、QFD、项目指标、DFMEA/DVP&R、PFMEA、Run at Rate、PPAP和量产反馈
- `references/27-msa.md`：MSA、GRR、偏倚、线性、稳定性、Kappa和属性一致性
- `references/28-spc.md`：SPC、控制图、Cp/Cpk、Pp/Ppk、判稳和异常反应
- `references/29-control-plan.md`：Prototype、Pre-Launch、Production 控制计划和现场反应计划
- `references/30-ppap.md`：PPAP、PSW、提交等级、试生产证据和再PPAP触发
- `references/31-fmea.md`：DFMEA/PFMEA、AIAG & VDA、Action Priority/RPN和风险分析
- `references/32-8d.md`：8D、遏制、根因、永久措施、验证和防再发

### 不合格品、变更、供应链与客户现场

- `references/17-nonconforming-product-management.md`：不合格品识别、隔离、MRB、让步、返工返修、报废和追溯
- `references/18-nonconforming-product-templates.md`：不合格品单、MRB评审单、返工放行、让步/偏差和报废模板
- `references/19-mrb-case-library.md`：MRB案例库，覆盖电测、AOI、切片、阻抗、表面处理和标签追溯
- `references/20-change-management-ecn-ecr.md`：ECR/ECN、影响评估、客户批准、再PPAP和切换控制
- `references/21-supplier-quality-iqc-scar.md`：供应商准入、IQC、CoA/CoC、供应商APQP、SCAR和变更纪律
- `references/22-audit-readiness-lpa-process-audit.md`：客户审核、内部审核、LPA、过程审核和产品审核准备
- `references/23-customer-complaint-field-failure-rma.md`：客诉、现场失效、RMA、索赔、失效分析和客户沟通
- `references/24-traceability-labeling-packaging.md`：追溯、标签、条码、包装、防潮、防静电和ECN切换
- `references/25-laboratory-correlation-test-management.md`：实验室、测试计划、相关性、数据争议和年度验证

### 改善项目、案例与模板

- `references/14-dmaic.md`：DMAIC、六西格玛改善、良率/报废/缺陷率/周期改善
- `references/15-dmaic-templates.md`：DMAIC项目章程、SIPOC、数据收集、分析摘要、改善验证和结案模板
- `references/16-dmaic-case-library.md`：孔铜、阻抗、AOI过杀、翘曲、FPC补强和Cycle Time改善案例
- `references/43-due-diligence-question-bank-by-segment.md`：按高速、HDI、mSAP、FPC、IC载板拆分的尽调问题库
- `references/44-defect-mechanisms-fa-linkage-library.md`：缺陷现象、机理假设、最小验证、遏制、对策和文件回写
- `references/47-deliverable-templates-pack.md`：访谈纪要、尽调结论页、商业模型、8D+FA、NPI状态和扩产评审模板

### 重点产品与应用

- `references/10-ai-server-and-switch-high-speed-pcb.md`：AI服务器、交换机、高速背板、高速材料、SI/PI、散热和背钻
- `references/11-automotive-pcb-and-radar.md`：汽车PCB、域控、BMS、功率板、ADAS/毫米波雷达板和车规导入
- `references/12-abf-bt-substrates-and-advanced-packaging.md`：ABF/BT载板、FC-BGA/FC-CSP、SiP和先进封装接口
- `references/13-fpc-and-rigid-flex-special-topic.md`：FPC、软硬结合板、动态/静态弯折、补强和贴装协同

## 使用原则

- 先判断任务边界：PCB还是IC载板；产品段、应用端、区域、时间口径和交付物类型。
- 稳定知识可以直接用于定义、框架、检查清单和术语统一。
- 市场规模、公司排名、产能、报价、客户份额、财务、政策、标准版本和客户认证状态属于动态事实，必须确认来源、日期和口径。
- 客户图纸、采购文件、质量协议、CSR和授权标准原文优先于知识库说明。
- 证据不足时，明确区分“已确认”“合理推断”“待核验”。
