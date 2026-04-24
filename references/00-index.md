# PCB/载板行业知识库索引

## 文件导航

- 定位
- 快速路由
- 核心边界
- 一级分类
- 分析主线
- 易错点
- 研究切入顺序
- 最小输出骨架
- 知识库专题组

## 定位

本知识库用于支持PCB和IC载板行业研究、公司分析、项目可研、技术路线判断、资料整理和术语统一。内容分为两类：

- 稳定知识：产业链结构、产品分类、常见制程、术语、财务分析框架。
- 动态事实：市场规模、价格、产能、公司排名、客户份额、扩产进度、政策、管理层和财务数据。

稳定知识可直接作为分析框架。动态事实必须按 `07-source-standards.md` 更新并标注来源日期。

## 快速路由

| 用户问题 | 先读 | 再读 |
| --- | --- | --- |
| 其他skill需要调用PCB/载板知识 | `38-cross-skill-integration.md` | `00-index.md`、按调用路由表选择专题 |
| PCB/载板基础入门、学习路径、跨职能口径统一 | `37-foundational-primer.md` | `01-industry-chain.md`、`02-products-tech.md` |
| PCB/载板行业是什么 | `01-industry-chain.md` | `02-products-tech.md` |
| HDI、FPC、IC载板、ABF载板区别 | `02-products-tech.md` | `06-terminology.md` |
| IPC/JEDEC/UL/车规/IATF/客户CSR怎么选口径；现行版本是什么 | `39-standards-certifications-and-compliance.md` | `07-source-standards.md` |
| HDI/mSAP/表面处理/可靠性（IST/CAF）怎么对比；如何提尽调问题 | `42-key-processes-hdi-msap-surfacefinish-reliability.md` | `04-process-quality.md` |
| 高速板设计约束、DFM/DFX、CAM资料、stack-up怎么判断 | `08-design-reliability-and-testing.md` | `02-products-tech.md` |
| 可靠性验证、失效机理、测试矩阵、FA怎么搭 | `08-design-reliability-and-testing.md` | `04-process-quality.md` |
| 工厂运营、成本结构、瓶颈、稼动率和现金回收怎么拆 | `09-operations-cost-and-delisking.md` | `05-financial-and-company-analysis.md` |
| 报价怎么拆、成本怎么建模、条款风险怎么写 | `40-quotation-costing-and-commercial-terms.md` | `09-operations-cost-and-delisking.md` |
| 扩产产能怎么看；名义到合格产出怎么换算；良率爬坡与瓶颈怎么判断 | `41-capacity-yield-ramp-and-bottlenecks.md` | `09-operations-cost-and-delisking.md` |
| 做公司/工厂尽调时优先问什么；按产品段怎么问到证据链 | `43-due-diligence-question-bank-by-segment.md` | `05-financial-and-company-analysis.md` |
| 缺陷机理怎么快速定位；FA怎么选最小验证；如何回写8D/FMEA/Control Plan | `44-defect-mechanisms-fa-linkage-library.md` | `32-8d.md` |
| ASP上涨来自哪里；技术参数如何映射到良率/折旧/COPQ/现金流 | `45-commercial-model-and-asp-drivers-by-segment.md` | `40-quotation-costing-and-commercial-terms.md` |
| 客户导入怎么定义阶段；如何证明“已认证/已量产”；需要哪些证据 | `46-customer-npi-evidence-pack-sample-to-massproduction.md` | `26-apqp.md` |
| 有没有可直接复制的交付物模板（尽调/访谈/商业模型/8D-FA/NPI状态/扩产评审） | `47-deliverable-templates-pack.md` | `07-source-standards.md` |
| AI服务器/交换机高速板怎么拆 | `10-ai-server-and-switch-high-speed-pcb.md` | `08-design-reliability-and-testing.md` |
| 汽车PCB/车载雷达板怎么拆 | `11-automotive-pcb-and-radar.md` | `04-process-quality.md` |
| ABF/BT载板与先进封装协同怎么拆 | `12-abf-bt-substrates-and-advanced-packaging.md` | `08-design-reliability-and-testing.md` |
| FPC/软硬结合板专项怎么拆 | `13-fpc-and-rigid-flex-special-topic.md` | `04-process-quality.md` |
| 某公司处于产业链哪里 | `01-industry-chain.md` | `05-financial-and-company-analysis.md` |
| 毛利率、产能、客户、扩产怎么分析 | `05-financial-and-company-analysis.md` | `03-materials-and-equipment.md` |
| 工艺流程、良率、可靠性怎么判断 | `04-process-quality.md` | `02-products-tech.md` |
| APQP、VOC、QFD、DFMEA/DVP&R、PFMEA、控制计划、Run at Rate、PPAP、SPC/8D/ECN怎么落地 | `26-apqp.md` | `04-process-quality.md` |
| DMAIC、六西格玛改善项目、良率/报废/缺陷率改善怎么做 | `14-dmaic.md` | `28-spc.md` |
| DMAIC项目章程、SIPOC、基线、改善验证、Control模板怎么写 | `15-dmaic-templates.md` | `14-dmaic.md` |
| PCB/载板典型DMAIC案例怎么复用 | `16-dmaic-case-library.md` | `14-dmaic.md` |
| MSA、量具GRR、偏倚、线性、稳定性、Kappa、测量系统怎么做 | `27-msa.md` | `04-process-quality.md` |
| SPC、控制图、Cp/Cpk/Pp/Ppk、判稳和过程能力怎么做 | `28-spc.md` | `27-msa.md` |
| Control Plan、Prototype/Pre-Launch/Production控制计划怎么做 | `29-control-plan.md` | `28-spc.md` |
| PPAP、PSW、提交等级、再PPAP评估怎么做 | `30-ppap.md` | `26-apqp.md` |
| FMEA、DFMEA、PFMEA、Action Priority/RPN、风险分析怎么做 | `31-fmea.md` | `26-apqp.md` |
| 8D、客诉、遏制、根因、预防再发和供应商闭环怎么做 | `32-8d.md` | `31-fmea.md` |
| 不合格品识别、隔离、MRB、让步、返工返修、报废怎么管理 | `17-nonconforming-product-management.md` | `29-control-plan.md` |
| 不合格品单、MRB单、返工放行、让步/报废模板怎么写 | `18-nonconforming-product-templates.md` | `17-nonconforming-product-management.md` |
| 电测/AOI/切片/阻抗/标签等MRB案例怎么复用 | `19-mrb-case-library.md` | `17-nonconforming-product-management.md` |
| ECR/ECN、材料替代、程序改版、设备/地点转移怎么管理 | `20-change-management-ecn-ecr.md` | `30-ppap.md` |
| 供应商准入、IQC、CoA/CoC、SCAR、供应商8D怎么做 | `21-supplier-quality-iqc-scar.md` | `32-8d.md` |
| 客户审核、LPA、过程审核、产品审核怎么准备 | `22-audit-readiness-lpa-process-audit.md` | `29-control-plan.md` |
| 客户投诉、现场失效、RMA、索赔和客户沟通怎么闭环 | `23-customer-complaint-field-failure-rma.md` | `32-8d.md` |
| 批次追溯、标签、包装、防潮、防静电和ECN切换怎么控 | `24-traceability-labeling-packaging.md` | `20-change-management-ecn-ecr.md` |
| 实验室测试、相关性、客户/供应商数据争议和年度验证怎么做 | `25-laboratory-correlation-test-management.md` | `27-msa.md` |
| 工程资料、CAM/MI、Gerber/ODB++、程序版本和工程放行怎么控 | `33-engineering-cam-mi-data-control.md` | `20-change-management-ecn-ecr.md` |
| 设备维护、治具、OEE、PM、备件和设备变更怎么管 | `34-equipment-maintenance-and-tooling.md` | `09-operations-cost-and-delisking.md` |
| EHS、环保、药水、危化品、废水废气和绿色供应链怎么拆 | `35-environment-ehs-chemical-management.md` | `03-materials-and-equipment.md` |
| 缺陷mapping、报废mapping、AOI/ET/FQC检验结果怎么整合 | `36-defect-scrap-mapping-aoi-et-fqc.md` | `28-spc.md` |
| 上游材料和设备怎么拆 | `03-materials-and-equipment.md` | `01-industry-chain.md` |
| 需要做最新市场或公司研究 | `07-source-standards.md` | 联网或读取用户提供资料 |

## 核心边界

PCB是电子整机内的互连载体，连接芯片、被动元件、连接器、模组和电源/信号路径。典型客户包括消费电子、汽车电子、通信、服务器、工业、医疗和军工等终端或EMS厂。

IC载板是封装环节的高密度互连基板，位于裸芯片和PCB之间，服务于芯片封装。它既有PCB工艺基础，也更接近半导体封装体系，在线宽线距、尺寸稳定、翘曲、洁净度、良率和客户认证方面要求更高。

载板在中文语境中可能指：

- IC载板或封装基板：package substrate, IC substrate。
- PCB作为承载板：少数语境会泛称为载板。
- 显示、LED、陶瓷或其他承载基板：需根据上下文确认。

如果用户说“载板行业”，默认按IC载板处理，并在输出中说明该假设。

## 一级分类

| 类别 | 典型产品 | 关键关注 |
| --- | --- | --- |
| 刚性PCB | 单双面板、多层板、高多层板 | 层数、面积、阻抗、良率、交期、成本 |
| HDI | 一阶、二阶、任意层HDI | 微孔、盲埋孔、叠孔、mSAP能力 |
| FPC | 单面、双面、多层、软硬结合 | 弯折、PI材料、补强、贴装良率 |
| 高频高速板 | 通信、服务器、交换机、雷达 | Dk/Df、损耗、阻抗、公差、材料认证 |
| 特种PCB | 金属基、厚铜、陶瓷、背板 | 散热、电流、机械可靠性、尺寸 |
| IC载板 | BT、ABF、FC-CSP、FC-BGA等 | 线宽线距、翘曲、平整度、良率、客户认证 |

## 分析主线

任何PCB/载板分析至少要覆盖五个问题：

1. 产品段：做什么板，技术难度处于哪一层。
2. 应用端：服务哪些终端和客户，需求周期由什么驱动。
3. 制造能力：层数、线宽线距、微孔、材料、设备、良率、认证。
4. 商业质量：ASP、毛利率、稼动率、客户集中度、议价能力、交付能力。
5. 扩张风险：资本开支、爬坡周期、良率、客户导入、折旧压力和供需错配。

## 易错点

- 不要把PCB产值、PCB面积、IC载板产值和封装产值混用。
- 不要把“高层数”等同于“高毛利”。材料、客户、认证、良率、稼动率同样关键。
- 不要把ABF载板等同于所有IC载板。BT载板和ABF载板应用、材料、供应链和设备瓶颈不同。
- 不要只看扩产名义产能。应同时看爬坡时间、产品结构、良率、认证和客户订单。
- 不要将会计期间混用。财年、自然年、季度和滚动十二个月必须分开。

## 研究切入顺序

| 任务 | 先界定什么 | 再拆什么 |
| --- | --- | --- |
| 行业入门 | 是PCB还是IC载板，讨论的是产值、面积还是工艺 | 产品分类、应用端、需求驱动、商业模式 |
| 公司研究 | 公司卖什么板、给谁、在哪些工厂做 | 技术能力、客户结构、产能、财务质量、扩产风险 |
| 技术路线比较 | 比的是产品定义、工艺路线还是客户认证门槛 | 材料、设备、良率、可靠性和替代路线 |
| 质量/客诉分析 | 缺陷发生在设计、制程、测量还是判定标准 | 失效机理、测量系统、过程控制和标准口径 |
| 项目可研/投资判断 | 目标产品、目标客户和目标区域是否清楚 | 需求空间、产线能力、资本开支、认证节奏和退出条件 |

## 最小输出骨架

做任何PCB/载板分析，建议至少包含以下四层：

1. 对象和口径：产品、客户、区域、时间、单位和关键假设。
2. 结论和主因：先回答“为什么成立/不成立”，再给证据。
3. 五条主线：产品段、需求端、制造能力、商业质量、扩张风险。
4. 待核验项：把动态事实、证据缺口、依赖客户文件的事项单列出来。

如果用户需求不明确，优先先问自己六个问题：做什么板、服务谁、技术难点在哪里、谁来认证、盈利靠什么、失败风险在哪里。

## 知识库专题组

本库按以下主题组维护稳定知识和可复用交付物：

| 主题组 | 文件 | 主要用途 |
| --- | --- | --- |
| 跨skill调用 | `38-cross-skill-integration.md` | 供文档、演示、表格、翻译、质量工具、自动化等其他skill按最小文件集调用知识库 |
| 基础知识入口 | `37-foundational-primer.md` | 新人入门、跨职能沟通、基础口径统一、从产品到制程再到经营的学习路径 |
| 标准、商业和产能增强 | `39-standards-certifications-and-compliance.md`、`40-quotation-costing-and-commercial-terms.md`、`41-capacity-yield-ramp-and-bottlenecks.md`、`45-commercial-model-and-asp-drivers-by-segment.md` | 标准/认证口径、报价成本、产能爬坡、ASP驱动和商业模型 |
| 深度尽调和证据链 | `42-key-processes-hdi-msap-surfacefinish-reliability.md`、`43-due-diligence-question-bank-by-segment.md`、`44-defect-mechanisms-fa-linkage-library.md`、`46-customer-npi-evidence-pack-sample-to-massproduction.md`、`47-deliverable-templates-pack.md` | 关键工艺深挖、产品段尽调题库、缺陷机理FA联动、客户导入证据链和交付物模板 |
| 工程、可靠性与运营 | `08-design-reliability-and-testing.md`、`09-operations-cost-and-delisking.md` | 工程评审、项目可研、扩产去风险、成本和现金流判断 |
| 重点应用和产品段 | `10-ai-server-and-switch-high-speed-pcb.md`、`11-automotive-pcb-and-radar.md`、`12-abf-bt-substrates-and-advanced-packaging.md`、`13-fpc-and-rigid-flex-special-topic.md` | 高速板、汽车板、ABF/BT载板、FPC/软硬结合板专项分析 |
| 改善项目和案例复用 | `14-dmaic.md`、`15-dmaic-templates.md`、`16-dmaic-case-library.md` | 良率、报废、缺陷率、周期和过程能力改善 |
| 不合格品与变更闭环 | `17-nonconforming-product-management.md`、`18-nonconforming-product-templates.md`、`19-mrb-case-library.md`、`20-change-management-ecn-ecr.md` | NCM/MRB、让步、返工返修、报废、ECR/ECN和再PPAP判断 |
| 供应链和审核闭环 | `21-supplier-quality-iqc-scar.md`、`22-audit-readiness-lpa-process-audit.md` | 供应商质量、IQC、SCAR、客户审核、LPA、过程审核和产品审核 |
| 客户现场与证据链闭环 | `23-customer-complaint-field-failure-rma.md`、`24-traceability-labeling-packaging.md`、`25-laboratory-correlation-test-management.md` | 客户投诉、RMA、批次追溯、标签包装、实验室相关性、数据争议和年度验证 |
| 工程、设备和EHS基础能力 | `33-engineering-cam-mi-data-control.md`、`34-equipment-maintenance-and-tooling.md`、`35-environment-ehs-chemical-management.md` | 工程资料、CAM/MI、设备维护、治具、OEE、化学品、环保和绿色供应链 |
| 缺陷和报废数据闭环 | `36-defect-scrap-mapping-aoi-et-fqc.md` | AOI/AVI、ET电测、FQC/终检、缺陷位置图、报废原因、MRB和SPC联动 |

这些内容主要服务于以下场景：

- 工程评审：图纸和规范是否真的能转成稳定量产。
- 跨skill调用：让其他skill在生成文档、PPT、表格、翻译和质量工具交付时使用统一PCB/载板知识口径。
- 基础入门：先把PCB、IC载板、产品分类、制造流程、材料逻辑、质量可靠性和经营口径串起来。
- 商业与产能判断：把报价、良品成本、ASP驱动、名义产能、良率爬坡和现金流压力连起来。
- 深度尽调和证据链：把访谈问题、NPI阶段门控、缺陷机理、FA验证和可复制模板沉淀为可审计输出。
- 项目可研和尽调：名义能力能否转成节拍、良率和现金流。
- 客诉和失效分析：失效机理、验证覆盖和根因闭环是否完整。
- 审核和供应链管理：客户要求、现场执行、供应商输入和变更纪律是否可追溯。
- 客户现场和证据链：退货样品、包装标签、测试数据和客户沟通是否能支撑结论。
- 工程与基础设施：工程资料、设备状态、治具和EHS能力是否支撑稳定量产。
- 缺陷数据闭环：AOI、ET、FQC、MRB和报废结果是否能按panel/pcs/strip/unit位置统一呈现。
