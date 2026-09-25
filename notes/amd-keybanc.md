# AMD KeyBanc 对话：18 轮细读卡片

原始对话：https://chatgpt.com/share/6ab5bec2-6ee8-83e8-a0de-bccd2bc28607

阅读状态：2026-09-24 已逐轮读完 18 个用户回合。以下是供节目制作使用的概括，不是原文存档，更不是投资结论。

## 论证怎样转向

- 1–2：从 KeyBanc 投资者会议会不会有新消息，转到认为财报与产品发布后难有独立催化剂；用户又提出地缘政治尾部风险。会议本身不足以支撑一期。
- 3–4：用户质疑卖方对 AMD 2027 年 EPS 的谨慎，追问 OpenAI、Meta、Anthropic、Microsoft 到底能带来多少收入。旧 AI 将多年 GW 部署规划换算为 2027 年三大客户 300–450 亿美元收入，并把 2027 年数据中心收入 600–700 亿美元讲成基础情景；这是**旧 AI 推算，不是公司指引或已确认订单收入**。对话随后把争点从 ROCm 能否运行，转到机柜可靠性、收入确认、毛利率、费用率和稀释。
- 5–8：用户补入 Meta 机柜标准、ZT Systems 的系统工程能力、AMD 供应链及 TSMC 先进工艺。旧 AI 因而逐步下调执行风险，并赞赏 Lisa Su 的跨团队协调。这是一条很好的节目线，但“客户参与设计”与“大规模部署已通过可靠性测试”不能划等号。
- 9–14：从 Lisa Su 与 Jensen Huang 的不同起点，转到 NVIDIA 成功中决策能力和历史运气各占多少。用户指出通用 GPU 计算并非 NVIDIA 独有，ATI/AMD 也做过相关软件，AMD 当时的财务约束影响软件生态持续投入。旧 AI 多次修正、最终大幅靠向用户；录制时需要真正的反论证，避免只换一种措辞附和。
- 15–18：转向 Jensen 在首尔谈 AI 股票价格、CEO 的专业边界及传播效果。旧对话中有关于韩国股灾与人物动机的推断，时间线与原话都应单独核实；不能把对韩国人的刻板印象当事实。

## 最值得录的两期

**A. AMD 客户已经来了，为什么华尔街还不敢给 2027 年 EPS 20 美元？** 把“多年合作规模 → 实际出货 → 年度收入确认 → 毛利 → 费用 → 稀释后 EPS”逐层摊开。主持人的强项是指出新客户、ZT 和供应链协同；AI 必须认真挑战每一步的确定性。微软作为云平台/部署渠道，与终端 AI 客户的收入模型可能重复计算。

**B. NVIDIA 是押中了未来，还是准备好后碰上了金矿？** 分开评估早期通用 GPU 计算、CUDA 持续投资、深度学习兴起后的 cuDNN 工程化，以及 Transformer 带来的外生需求。对照 AMD 当年的资源限制和 Lisa Su 后来的修复路径。结论应区分“好决策”和“好结果”，反事实没有唯一答案。

首尔发言与 CEO 的公共责任可作第二期的一节。KeyBanc 活动只是对话起点，不建议单独成片。

## 已独立核实的关键事实

- AMD 2025 年年报将年 EPS 超过 20 美元列为**未来三至五年**财务目标，而非 2027 年明确指引：https://d1io3yog0oux5.cloudfront.net/_eb2711373b51580db826567d926e17fc/amd/files/pages/news-events/annual-meeting-of-stockholders/2025_Annual_Report.pdf
- Meta 的 2026 年 8-K 说明，具约束力的购买承诺是初始 **1GW**；达到 6GW 对应后续购买里程碑。最高 1.6 亿股为有条件分期归属的权证，不能表述成 Meta 已取得 AMD 10% 股权：https://ir.amd.com/financial-information/sec-filings/content/0000002488-26-000045/amd-20260223.htm
- AMD 与 OpenAI 公布的是跨多年、多代的 6GW 合作，首批 1GW 计划从 2026 年下半年开始；公告并未给出 2027 年客户收入拆分：https://ir.amd.com/financial-information/sec-filings/content/0001193125-25-230895/d28189dex991.htm
- AMD 与 Anthropic 公布最多 2GW、首批 1GW 从 2027 年上半年开始，并计划共同优化 ROCm；“最多”与“已在 2027 年全部产生收入”不同：https://ir.amd.com/news-events/press-releases/detail/1292/amd-and-anthropic-announce-strategic-partnership-to-deploy-up-to-2-gigawatts-of-amd-instinct-mi450-series-gpus
- Helios 机柜参考设计基于 Meta 提交的 Open Rack Wide 标准；这是设计合作证据，不是现场可靠性已经验证的证据：https://www.amd.com/en/products/rackscale-solutions/helios.html
- Stanford 的 BrookGPU 论文在 CUDA 之前就实现了 ATI 与 NVIDIA 硬件后端；称它为“CUDA 的原型”仍需更严格的技术史论证：https://graphics.stanford.edu/papers/brookgpu/brookgpu.pdf
- AMD 2011 年公告证实与 MulticoreWare 合作优化 OpenCL；这支持“AMD 并非没看见通用 GPU 计算”，但不足以单独证明外部合作是失败主因：https://ir.amd.com/news-events/press-releases/detail/17/amd-and-multicoreware-team-to-help-developers-optimize-the-use-of-opencltm-for-amd-fusion-apus
- 美国 SEC 对 NVIDIA 矿卡影响披露的认定，针对 2017 年提交的 FY2018 第二、三季度文件；不能混同于后来的第二轮矿潮，也不能据此断言 Jensen 本人已被证明撒谎：https://www.sec.gov/files/litigation/admin/2022/33-11060.pdf

## 录制前待核实

- 2026 年 Q2 财报电话会里关于 2027 年数据中心增速、HBM 可见度、每 GW 经济价值的逐字原话及语境。
- 各客户合同中的“up to”“计划部署”“购买承诺”“已交货”“收入确认”分别是什么，CSP 渠道是否重复计入。
- ZT 团队整合、Sanmina 制造安排、首批 Helios 实际上线时间与运行表现。
- 首尔发言的完整视频或可靠逐字稿、提问者的问题、当日市场时间线；对 Jensen 动机与韩国社会反应只作为讨论假说。
