---
name: pcb-industry-knowledge
description: "PCB及IC载板行业知识库。Use when Codex or another skill needs PCB, printed circuit board, PWB, CCL, HDI, FPC, rigid-flex, SLP, IC substrate, package substrate, ABF, BT, FC-BGA, FC-CSP, mSAP/SAP, PCB manufacturing, PCB materials, PCB equipment, advanced packaging substrates, industry-chain research, company analysis, due diligence, project feasibility, customer/supplier mapping, financial analysis, quotation/costing, capacity/yield ramp, NPI evidence, technology-route comparison, Chinese/English terminology support, deliverable templates, or cross-skill PCB/domain knowledge retrieval."
---

# PCB/载板行业知识库

## 使用原则

先判断用户任务属于技术、产业链、公司研究、财务分析、项目可研、术语翻译还是资料更新，再只读取需要的 `references/` 文件。

默认用中文输出。对市场规模、公司排名、产能、报价、客户份额、资本开支、政策和管理层信息，必须标注日期和来源；如果用户要求“最新”“现在”“今年”或结论依赖当前事实，先联网或读取用户给定材料核验，不能只依赖本地知识库。

## 参考文件选择

- `references/00-index.md`: 总索引、任务路由、PCB与IC载板的基本边界。
- `references/37-foundational-primer.md`: PCB/载板基础知识补强，适合新人入门、跨职能沟通、基础口径统一和学习路径搭建。
- `references/38-cross-skill-integration.md`: 跨skill调用接口，供文档、演示、表格、翻译、质量工具、自动化等其他skill按最小文件集调用本知识库。
- `references/01-industry-chain.md`: 产业链、商业模式、需求驱动、周期性、区域分工。
- `references/02-products-tech.md`: PCB与IC载板产品分类、技术路线、关键能力指标。
- `references/03-materials-and-equipment.md`: CCL、铜箔、玻纤布、树脂、ABF/BT、药水、设备和耗材。
- `references/04-process-quality.md`: 制程流程、良率瓶颈、可靠性、质量指标、常见标准。
- `references/39-standards-certifications-and-compliance.md`: IPC/JEDEC/UL/ISO/IATF与客户CSR的版本核验、适用边界、认证与合规口径。
- `references/40-quotation-costing-and-commercial-terms.md`: 报价拆解、成本建模、良品成本/质量成本、商业条款与风险。
- `references/41-capacity-yield-ramp-and-bottlenecks.md`: 名义产能到合格产出换算、良率爬坡、瓶颈识别和扩产去风险。
- `references/42-key-processes-hdi-msap-surfacefinish-reliability.md`: HDI、mSAP/SAP、表面处理和IST/CAF等可靠性关键工艺路线。
- `references/43-due-diligence-question-bank-by-segment.md`: 按高速、HDI、mSAP、FPC、IC载板等产品段拆分的尽调问题库。
- `references/44-defect-mechanisms-fa-linkage-library.md`: 缺陷现象、机理假设、最小验证、遏制、对策和8D/FMEA/Control Plan/SPC/MSA回写。
- `references/45-commercial-model-and-asp-drivers-by-segment.md`: 按产品段拆解ASP驱动、良率、折旧、COPQ、条款和现金流敏感项。
- `references/46-customer-npi-evidence-pack-sample-to-massproduction.md`: 客户导入证据链，覆盖样品、小批量、Safe Launch和量产放行门控。
- `references/47-deliverable-templates-pack.md`: 访谈纪要、尽调结论页、商业模型、8D+FA、NPI状态和扩产评审模板包。
- `references/26-apqp.md`: APQP专题，VOC到项目指标、QFD、DFMEA/DVP&R、PFMEA、Control Plan、MSA、过程能力、Run at Rate、PPAP/PSW、SPC/8D/ECN、持续改善、初始特殊特性、Program Metrics和RYG状态管理。
- `references/27-msa.md`: MSA专题，测量系统分析、分辨率、偏倚、线性、稳定性、GRR、Kappa、属性一致性和PCB/载板测量系统落地。
- `references/28-spc.md`: SPC专题，控制图选择、判稳、Cp/Cpk/Pp/Ppk、抽样分层、异常反应和PCB/载板过程能力落地。
- `references/29-control-plan.md`: Control Plan专题，Prototype/Pre-Launch/Production控制计划、字段设计、反应计划和PCB/载板现场控制落地。
- `references/30-ppap.md`: PPAP专题，提交等级、PSW、试生产证据、一致性评审、再PPAP触发和PCB/载板客户提交落地。
- `references/31-fmea.md`: FMEA专题，DFMEA/PFMEA边界、风险分析、AIAG & VDA与RPN、PCB/载板失效模式和与Control Plan/8D的联动。
- `references/32-8d.md`: 8D专题，D1-D8、遏制、根因分析、永久措施、验证、防再发和PCB/载板客诉/供应商闭环落地。
- `references/17-nonconforming-product-management.md`: 不合格品管理专题，识别、隔离、标识、MRB、让步接收、返工返修、报废、追溯和客户通知。
- `references/18-nonconforming-product-templates.md`: 不合格品管理模板库，不合格品单、隔离记录、MRB评审单、返工放行、让步/偏差、报废和恢复放行模板。
- `references/19-mrb-case-library.md`: MRB案例库，电测争议、AOI过杀、切片不良、阻抗偏差、表面处理异常、标签追溯错误等场景复用。
- `references/20-change-management-ecn-ecr.md`: 变更管理专题，ECR/ECN、影响评估、客户批准、再PPAP、切换控制、版本冻结和量产后追溯。
- `references/21-supplier-quality-iqc-scar.md`: 供应商质量专题，供应商分级、准入、IQC、CoA/CoC、供应商APQP、SCAR、加严/恢复和变更纪律。
- `references/22-audit-readiness-lpa-process-audit.md`: 审核专题，客户审核、内部审核、LPA、过程审核、产品审核、审核证据矩阵和CAPA闭环。
- `references/23-customer-complaint-field-failure-rma.md`: 客户投诉专题，现场失效、RMA、客户筛选、索赔、失效分析、客户沟通和8D回写。
- `references/24-traceability-labeling-packaging.md`: 追溯包装专题，批次追溯、标签、条码、包装、防潮、防静电、ECN切换和RMA标识。
- `references/25-laboratory-correlation-test-management.md`: 实验室专题，测试计划、样品管理、测试相关性、实验室比对、客户/供应商数据争议和年度验证。
- `references/14-dmaic.md`: DMAIC专题，Define/Measure/Analyze/Improve/Control、六西格玛改善项目、良率/报废/缺陷率/周期改善和与SPC/8D/APQP的接口。
- `references/15-dmaic-templates.md`: DMAIC项目模板库，项目章程、SIPOC、数据收集、分析摘要、改善验证、Control Plan和结案模板。
- `references/16-dmaic-case-library.md`: PCB/载板DMAIC案例库，孔铜、阻抗、AOI过杀、翘曲、FPC补强、Cycle Time等案例骨架与复用方法。
- `references/05-financial-and-company-analysis.md`: 公司研究、财务指标、产能与资本开支、尽调模板。
- `references/06-terminology.md`: 中英文术语、缩写、易混词。
- `references/07-source-standards.md`: 来源分级、引用格式、数据更新规则、资料沉淀格式。
- `references/08-design-reliability-and-testing.md`: DFM/DFX、CAM/MI、stack-up、高速设计、可靠性验证、FA、先进封装与载板边界。
- `references/09-operations-cost-and-delisking.md`: 工厂运营指标、成本结构、报价逻辑、NPI、Safe Launch、扩产去风险、供应商切换。
- `references/10-ai-server-and-switch-high-speed-pcb.md`: AI服务器、交换机、高速背板、高速材料、SI/PI、散热、背钻和运营判断。
- `references/11-automotive-pcb-and-radar.md`: 汽车PCB、域控、BMS、功率板、ADAS/毫米波雷达板、车规验证和项目导入。
- `references/12-abf-bt-substrates-and-advanced-packaging.md`: ABF/BT载板、FC-BGA/FC-CSP、SiP、先进封装接口、良率与经营框架。
- `references/13-fpc-and-rigid-flex-special-topic.md`: FPC、软硬结合板、动态/静态弯折、补强、贴装协同和专项尽调。
- `references/33-engineering-cam-mi-data-control.md`: 工程资料专题，客户设计资料、Gerber/ODB++/IPC-2581、CAM/MI、程序版本、工程放行和数据安全。
- `references/34-equipment-maintenance-and-tooling.md`: 设备治具专题，关键设备、工装治具、预防维护、OEE、备件、设备故障和设备变更。
- `references/35-environment-ehs-chemical-management.md`: EHS专题，化学品、药水、废水废气、危废、职业健康、客户绿色供应链和化学品变更。
- `references/36-defect-scrap-mapping-aoi-et-fqc.md`: 缺陷与报废mapping专题，AOI/AVI、ET电测、FQC/终检、panel/pcs/strip/unit位置图、缺陷码、报废原因和检验结果整合。

## 分析工作流

1. 明确范围：PCB还是IC载板；产品段、应用终端、区域、时间口径、输出用途。
2. 读取对应参考文件，先建立产品和产业链位置，再进入技术或财务判断。
3. 区分稳定知识与动态事实。工艺、术语、分析框架可直接引用本地知识；市场和公司事实要核验。
4. 输出时给出假设、口径和风险点。涉及数字时说明币种、期间、数据口径和来源日期。
5. 如果用户提供公司公告、研报、访谈纪要或客户资料，以用户资料为一手上下文；本知识库只做结构化解释和交叉检查。

## 跨Skill调用

当其他skill需要PCB/载板领域知识时，先读 `references/38-cross-skill-integration.md`，再按其中的调用路由表读取最小专题文件。调用方保留自己的交付格式和工作流，本知识库只提供领域定义、口径校验、分析框架、术语统一和待核验风险。

跨skill调用时必须遵守两点：

- 稳定知识可以直接用于框架、解释和检查清单；动态事实必须按 `references/07-source-standards.md` 核验来源、日期和口径。
- 不要一次加载全部 `references/`。先读 `38-cross-skill-integration.md` 或 `00-index.md`，再按任务读取2-4个最相关文件。

## 常见交付物

- 行业入门说明：读 `00-index`、`37-foundational-primer`、`01-industry-chain`、`02-products-tech`。
- 新人培训、基础口径统一或知识库导读：读 `37-foundational-primer.md`、`00-index.md`、`06-terminology.md`。
- 其他skill需要调用PCB/载板知识：读 `38-cross-skill-integration.md`、`00-index.md`，再按调用路由表读取最小专题文件。
- 公司深度分析：读 `01-industry-chain`、`02-products-tech`、`05-financial-and-company-analysis`，必要时补 `03-materials-and-equipment`。
- 项目可研或投资判断：读 `02-products-tech`、`03-materials-and-equipment`、`04-process-quality`、`05-financial-and-company-analysis`、`07-source-standards`。
- 标准/认证/合规口径核对：读 `39-standards-certifications-and-compliance.md`、`07-source-standards.md`，并以客户文件/授权原文为准。
- 报价、成本与条款拆解：读 `40-quotation-costing-and-commercial-terms.md`、`09-operations-cost-and-delisking.md`、`05-financial-and-company-analysis.md`。
- 产能、稼动、良率爬坡与瓶颈诊断：读 `41-capacity-yield-ramp-and-bottlenecks.md`、`09-operations-cost-and-delisking.md`、`04-process-quality.md`。
- 关键工艺路线深挖（HDI/mSAP/表面处理/可靠性）：读 `42-key-processes-hdi-msap-surfacefinish-reliability.md`、`04-process-quality.md`、`25-laboratory-correlation-test-management.md`。
- APQP/IATF工具落地：读 `26-apqp.md`、`27-msa.md`、`04-process-quality`、`07-source-standards`。
- SPC/过程能力/控制图落地：读 `28-spc.md`、`27-msa.md`、`04-process-quality.md`。
- Control Plan/现场控制落地：读 `29-control-plan.md`、`28-spc.md`、`27-msa.md`、`04-process-quality.md`。
- PPAP/PSW/客户提交准备：读 `30-ppap.md`、`26-apqp.md`、`29-control-plan.md`、`27-msa.md`、`28-spc.md`。
- FMEA/DFMEA/PFMEA风险分析：读 `31-fmea.md`、`26-apqp.md`、`29-control-plan.md`。
- 8D/客诉/供应商异常闭环：读 `32-8d.md`、`31-fmea.md`、`04-process-quality.md`。
- 缺陷机理定位、验证计划与闭环回写：读 `44-defect-mechanisms-fa-linkage-library.md`、`32-8d.md`、`31-fmea.md`、`29-control-plan.md`、`25-laboratory-correlation-test-management.md`。
- 不合格品管理和MRB处置：读 `17-nonconforming-product-management.md`、`29-control-plan.md`、`32-8d.md`、`30-ppap.md`。
- 不合格品管理模板和执行表单：读 `18-nonconforming-product-templates.md`、`17-nonconforming-product-management.md`。
- MRB案例复用：读 `19-mrb-case-library.md`、`17-nonconforming-product-management.md`、`32-8d.md`。
- ECR/ECN和量产变更管理：读 `20-change-management-ecn-ecr.md`、`26-apqp.md`、`30-ppap.md`、`17-nonconforming-product-management.md`。
- 客户导入证据链与阶段门控（样品到量产放行）：读 `46-customer-npi-evidence-pack-sample-to-massproduction.md`、`26-apqp.md`、`30-ppap.md`、`20-change-management-ecn-ecr.md`。
- 供应商质量、IQC、SCAR和二供导入：读 `21-supplier-quality-iqc-scar.md`、`32-8d.md`、`20-change-management-ecn-ecr.md`。
- 客户审核、LPA、过程审核和产品审核准备：读 `22-audit-readiness-lpa-process-audit.md`、`29-control-plan.md`、`04-process-quality.md`。
- 客户投诉、现场失效、RMA和索赔闭环：读 `23-customer-complaint-field-failure-rma.md`、`32-8d.md`、`17-nonconforming-product-management.md`。
- 追溯、标签、包装、防潮和ECN切换控制：读 `24-traceability-labeling-packaging.md`、`20-change-management-ecn-ecr.md`、`17-nonconforming-product-management.md`。
- 实验室、测试相关性、数据争议和年度验证：读 `25-laboratory-correlation-test-management.md`、`27-msa.md`、`08-design-reliability-and-testing.md`。
- DMAIC/六西格玛改善项目：读 `14-dmaic.md`、`28-spc.md`、`27-msa.md`、`31-fmea.md`。
- DMAIC项目模板和执行表单：读 `15-dmaic-templates.md`、`14-dmaic.md`。
- PCB/载板DMAIC案例复用：读 `16-dmaic-case-library.md`、`14-dmaic.md`、`28-spc.md`。
- 技术路线对比：读 `02-products-tech`、`04-process-quality`。
- 尽调问题清单与访谈脚本（按产品段）：读 `43-due-diligence-question-bank-by-segment.md`、`05-financial-and-company-analysis.md`、`07-source-standards.md`。
- 设计评审、可靠性验证或先进封装边界判断：读 `08-design-reliability-and-testing.md`、`04-process-quality.md`。
- 项目可研、工厂运营、扩产节奏和盈利质量判断：读 `09-operations-cost-and-delisking.md`、`05-financial-and-company-analysis.md`。
- 产品段商业模型与ASP驱动拆解：读 `45-commercial-model-and-asp-drivers-by-segment.md`、`40-quotation-costing-and-commercial-terms.md`、`41-capacity-yield-ramp-and-bottlenecks.md`。
- AI服务器/交换机高速板分析：读 `10-ai-server-and-switch-high-speed-pcb.md`、`08-design-reliability-and-testing.md`、`04-process-quality.md`。
- 汽车PCB/车载雷达板分析：读 `11-automotive-pcb-and-radar.md`、`04-process-quality.md`、`26-apqp.md`。
- ABF/BT载板和先进封装协同分析：读 `12-abf-bt-substrates-and-advanced-packaging.md`、`08-design-reliability-and-testing.md`、`05-financial-and-company-analysis.md`。
- FPC/软硬结合板专项分析：读 `13-fpc-and-rigid-flex-special-topic.md`、`04-process-quality.md`、`09-operations-cost-and-delisking.md`。
- 工程资料、CAM/MI、Gerber/ODB++、程序版本和工程放行：读 `33-engineering-cam-mi-data-control.md`、`08-design-reliability-and-testing.md`、`20-change-management-ecn-ecr.md`。
- 设备维护、治具、OEE、PM、备件和设备变更：读 `34-equipment-maintenance-and-tooling.md`、`09-operations-cost-and-delisking.md`、`20-change-management-ecn-ecr.md`。
- EHS、环保、药水、危化品、废水废气和绿色供应链：读 `35-environment-ehs-chemical-management.md`、`03-materials-and-equipment.md`、`07-source-standards.md`。
- 缺陷mapping、报废mapping、AOI/ET/FQC检验结果整合：读 `36-defect-scrap-mapping-aoi-et-fqc.md`、`17-nonconforming-product-management.md`、`28-spc.md`。
- 术语翻译或材料整理：读 `06-terminology`。
- 交付物模板快速套用（尽调/访谈/商业模型/8D-FA/NPI状态/扩产评审）：读 `47-deliverable-templates-pack.md`、`07-source-standards.md`。

## 输出结构建议

- 先定义边界：PCB还是IC载板；产品段、应用端、区域、时间口径和关键假设。
- 再给判断：先写结论，再写产品、需求、制造、财务和风险的支撑链。
- 稳定知识和动态事实分开写。框架、工艺、术语可直接使用本地知识；市场、产能、财务、客户和标准版本要单列来源与日期。
- 证据不完整时，不要硬补结论。应明确写出“已确认”“合理推断”“待核验”三类信息。
- 用户给了纪要、公告、客户规范或图纸时，优先按用户资料组织，再用知识库做解释、补缺和交叉检查。

## 知识库补充与维护原则

- 扩写参考文件时，优先补四类内容：边界定义、比较框架、尽调问题清单、跨文件引用关系。
- 稳定知识写入对应 `references/` 文件；动态数据、公司事件和标准版本状态应写入带日期的资料记录，不覆盖通用框架。
- 新增长期会反复使用的主题时，同时更新 `00-index.md` 的路由和 `07-source-standards.md` 的写作/引用规则。
- 对存在行业分歧或客户差异的主题，优先写“适用条件”和“不要混用的口径”，避免把局部经验写成普遍规律。
- 任何涉及标准、认证、PPAP、客户批准和合规边界的内容，都应写清“知识库说明不能替代客户文件和授权标准原文”。
