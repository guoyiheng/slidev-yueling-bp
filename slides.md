---
theme: default
layout: full
title: 跃灵
class: text-left
company: 跃灵
date: 2026-03-12
transition: slide-left

---
<!-- TBD 需要截图 -->
<div class="h-full w-full flex flex-col justify-between">
  <div class="flex items-center gap-2 pt-1">
    <img src="/yueling-logo.svg" alt="跃灵Logo" class="h-7 w-7" />
    <span class="text-lg font-600 tracking-wide">跃灵</span>
  </div>

  <div class="flex-1 flex flex-col justify-center">
    <h1 class="mb-4">跃灵</h1>
    <div class="opacity-70">
      <p class="text-base mb--2!">面向创作者的全链路 AI 内容生产平台</p>
      <p class="text-base">Creator-Focused End-to-End AI Content Production Platform</p>
    </div>
  </div>

  <div class="text-sm opacity-85 pb-1">
    官网：<a href="https://yueling.xingluan.cn/" target="_blank">https://yueling.xingluan.cn/</a>
  </div>
</div>

---

# 目录

<div class="toc-grid">
  <button class="toc-btn" @click="$nav.go(3)">01 平台简介</button>
  <button class="toc-btn" @click="$nav.go(5)">02 市场机会</button>
  <button class="toc-btn" @click="$nav.go(7)">03 产品介绍</button>
  <button class="toc-btn" @click="$nav.go(10)">04 发展规划</button>
  <button class="toc-btn" @click="$nav.go(13)">05 为什么是跃灵AI</button>
</div>

---

##### 01 平台简介 | Platform Overview

# 平台定位

<ul class="page3-core-list">
  <li data-wm="全链路 AI 内容生产平台">
    <span class="item-copy">跃灵AI 是面向创作者与内容团队的<strong>全链路 AI 内容生产平台</strong></span>
  </li>
  <li data-wm="剧本驱动 + 流水线编排">
    <span class="item-copy">以<strong>“剧本驱动 + 流水线编排”</strong>连接创意、生产、交付全流程</span>
  </li>
  <li data-wm="可管理 可协同 可复用">
    <span class="item-copy">平台核心：<strong>可管理、可协同、可复用</strong></span>
  </li>
  <li data-wm="生产效率">
    <span class="item-copy">使命：以 AI 流水线重构内容<strong>生产效率</strong>，支撑稳定规模化增长</span>
  </li>
</ul>

---

##### 01 平台简介 | Platform Overview

# 目标用户

<ul class="target-user-grid">
  <li>
    <img src="/undraw-target-creator.svg" alt="个人创作者" class="target-user-illustration" />
    <p><strong>个人创作者</strong>更低门槛、更快出片，把创意快速转为可发布内容</p>
  </li>
  <li>
    <img src="/undraw-target-team.svg" alt="专业团队" class="target-user-illustration" />
    <p><strong>专业团队</strong>多人并行协作，提升角色一致性与批量生产效率</p>
  </li>
  <li>
    <img src="/undraw-target-enterprise.svg" alt="企业客户" class="target-user-illustration" />
    <p><strong>企业客户</strong>标准化流程与权限治理，实现可控成本与稳定交付</p>
  </li>
</ul>

---

##### 02 市场机会 | Market Opportunity

# 机会判断

<ul class="page5-core-list">
  <li data-wm="市场规模">
    <span class="item-copy"><strong>市场规模</strong>：2025 中国 AIGC 市场规模 4800 亿，内容生产类占 41.3%（艾瑞咨询）</span>
  </li>
  <li data-wm="需求爆发">
    <span class="item-copy"><strong>需求爆发</strong>：泛娱乐短视频日播放 1.2 万亿次，漫剧创作量同比 +180%（头豹研究院）</span>
  </li>
  <li data-wm="改造提速">
    <span class="item-copy"><strong>改造提速</strong>：78% 内容团队启动工业化改造，仅 32% 完成全链路数字化（易观分析）</span>
  </li>
  <li data-wm="窗口已开">
    <span class="item-copy"><strong>窗口已开</strong>：平台型 AI 基础设施将承接下一轮产能与商业化增量</span>
  </li>
</ul>

---

##### 02 市场机会 | Market Opportunity

# 痛点聚焦

<section class="page6-board" aria-label="痛点聚焦四象限卡片">
  <article class="page6-card page6-card--donut">
    <div class="page6-card-head">
      <h3><ph-link-break-duotone class="page6-card-icon" />工具割裂</h3>
    </div>
    <div class="page6-card-chart page6-donut" style="--page6-value: 35;">
      <div class="page6-donut__inner">
        <strong>35%</strong>
        <span>信息损耗率</span>
      </div>
    </div>
    <p class="page6-card-copy">日均跨平台切换 2.3 小时</p>
    <p class="page6-card-source">来源：2025 内容创作者效率报告</p>
  </article>
  <article class="page6-card page6-card--progress">
    <div class="page6-card-head">
      <h3><ph-warning-circle-duotone class="page6-card-icon" />质量不稳</h3>
    </div>
    <div class="page6-card-chart page6-progress-chart">
      <div class="page6-progress-meta">
        <strong>45%</strong>
        <span>内容返工率</span>
      </div>
      <div class="page6-progress-track">
        <span style="width: 45%"></span>
      </div>
    </div>
    <p class="page6-card-copy">单条内容平均修改 5.2 次</p>
    <p class="page6-card-source">来源：IDC 中国</p>
  </article>
  <article class="page6-card page6-card--donut">
    <div class="page6-card-head">
      <h3><ph-users-three-duotone class="page6-card-icon" />协作低效</h3>
    </div>
    <div class="page6-card-chart page6-donut" style="--page6-value: 38;">
      <div class="page6-donut__inner">
        <strong>38%</strong>
        <span>沟通成本占比</span>
      </div>
    </div>
    <p class="page6-card-copy">50% 企业因此放弃扩产</p>
    <p class="page6-card-source">来源：艾瑞咨询</p>
  </article>
  <article class="page6-card page6-card--columns">
    <div class="page6-card-head">
      <h3><ph-hourglass-medium-duotone class="page6-card-icon" />交付缓慢</h3>
    </div>
    <div class="page6-card-chart page6-values-split">
      <div class="page6-values-container">
        <div class="page6-value-block">
          <span class="page6-value-item">30%</span>
          <span class="page6-value-label">行业平均降速</span>
        </div>
      </div>
    </div>
    <p class="page6-card-copy">单条短视频平均生产成本 1200 元</p>
    <p class="page6-card-source">来源：头豹研究院</p>
  </article>
</section>

---

##### 03 产品介绍 | Product Introduction

# 从痛点到产品解法

<ul class="page7-core-list">
  <li data-wm="工具割裂">
    <span class="item-copy">针对<strong>工具割裂</strong>：以剧本为主线串联创意、分镜、角色、视频、配音与交付，减少跨平台切换与信息断层</span>
  </li>
  <li data-wm="质量不稳">
    <span class="item-copy">针对<strong>质量不稳</strong>：提供角色、场景、道具和镜头一致性控制，降低返工率与反复修改成本</span>
  </li>
  <li data-wm="协作低效">
    <span class="item-copy">针对<strong>协作低效</strong>：把任务节点、素材资产、版本状态与权限管理纳入同一流水线，支撑多人并行协作</span>
  </li>
  <li data-wm="交付缓慢">
    <span class="item-copy">针对<strong>交付缓慢</strong>：通过模板化拆解、批量生成与非线性迭代能力，压缩单条内容生产周期</span>
  </li>
</ul>

---

##### 03 产品介绍 | Product Introduction

# 我们最有优势的地方 (待补充截图)

- **全链路系统**：从剧本到成片的核心环节在同一平台闭环完成，效率提升更可持续
- **持续复用**：角色、场景、分镜与素材资产可沉淀复用，越做越快，越做越稳
- **兼顾团队与企业**：既支持创作者灵活创作，也支持企业标准化流程和权限治理
- **可迭代流水线**：允许中途修改、局部重做和快速回收，不因单点变更拖慢整体交付

---

##### 03 产品介绍 | Product Introduction

# 集团协同与组织优势

<ul class="page9-core-list">
  <li data-wm="稳定供给">
    <span class="item-copy"><strong>稳定供给</strong>：集团算力与液冷基建协同，保证高峰期仍具备稳定生产能力与交付确定性</span>
  </li>
  <li data-wm="成本优势">
    <span class="item-copy"><strong>成本优势</strong>：上游资源协同降低生成成本，为会员订阅、企业方案和规模化交付留出空间</span>
  </li>
  <li data-wm="执行闭环">
    <span class="item-copy"><strong>执行闭环</strong>：算法、产品、运营一体协同，能把客户需求快速转成可复制的生产流程</span>
  </li>
  <li data-wm="放量能力">
    <span class="item-copy"><strong>放量能力</strong>：从创作者场景验证，到团队协作与企业交付扩展，平台具备连续放大的组织基础</span>
  </li>
</ul>

---

##### 04 发展规划 | Development Roadmap

# 收入模型

<ul class="target-user-grid">
  <li>
    <img src="/undraw-revenue-pricing.svg" alt="订阅收入" class="target-user-illustration" />
    <p><strong>订阅收入</strong>四档会员覆盖不同规模用户，形成稳定持续的基础现金流</p>
  </li>
  <li>
    <img src="/undraw-revenue-subscription.svg" alt="消耗收入" class="target-user-illustration" />
    <p><strong>消耗收入</strong>积分加油包提升付费弹性，满足高频生成与阶段性爆发需求</p>
  </li>
  <li>
    <img src="/undraw-revenue-enterprise.svg" alt="企业收入" class="target-user-illustration" />
    <p><strong>企业收入</strong>团队版、内容培训与技术支持，提供高客单价增长空间</p>
  </li>
</ul>

---

##### 04 发展规划 | Development Roadmap

# 定价与订阅体系

<table class="biz-table">
  <thead>
    <tr>
      <th>版本</th>
      <th>月费</th>
      <th>年费</th>
      <th>月积分</th>
      <th>关键权益</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>免费版</td>
      <td>0元</td>
      <td>0元</td>
      <td>注册赠送50积分</td>
      <td>基础体验，最多2个并发</td>
    </tr>
    <tr>
      <td>基础版</td>
      <td>29元</td>
      <td>278元</td>
      <td>300积分</td>
      <td>最多5个并发，积分9折</td>
    </tr>
    <tr>
      <td>专业版</td>
      <td>99元</td>
      <td>950元</td>
      <td>1000积分</td>
      <td>全模型、4K、专属客服</td>
    </tr>
    <tr>
      <td>企业版</td>
      <td>499元</td>
      <td>4790元</td>
      <td>6000积分</td>
      <td>不限并发、团队协作、技术对接</td>
    </tr>
  </tbody>
</table>

加油包档位：50元、200元、1000元、5000元，按会员等级享受不同折扣

---

##### 04 发展规划 | Development Roadmap

# 2026阶段目标

<section class="timeline-clean" aria-label="2026阶段目标时间轴">
  <div class="timeline-clean__line" aria-hidden="true"></div>

  <article class="timeline-clean__item is-step-1">
    <div class="timeline-clean__node" aria-hidden="true"></div>
    <p class="timeline-clean__time">第一阶段 · 0-3个月</p>
    <h3>上线与验证</h3>
    <p>5万+ MAU、500+ 作品、20+ 企业客户、月收入100万+、海外市场初步布局</p>
  </article>

  <article class="timeline-clean__item is-step-2">
    <div class="timeline-clean__node" aria-hidden="true"></div>
    <p class="timeline-clean__time">第二阶段 · 3-6个月</p>
    <h3>商业化放大</h3>
    <p>50万+ MAU、服务收入占比50%+、海外用户占比20%+</p>
  </article>

  <article class="timeline-clean__item is-step-3">
    <div class="timeline-clean__node" aria-hidden="true"></div>
    <p class="timeline-clean__time">第三阶段 · 6-12个月</p>
    <h3>生态闭环</h3>
    <p>100万+ MAU、年收入目标5000万、海外收入占比40%+、行业领先地位</p>
  </article>
</section>

---

##### 05 为什么是跃灵AI | Why Yueling AI

# 竞品格局与差异化

<table class="competitor-table">
  <thead>
    <tr>
      <th>维度</th>
      <th>跃灵AI</th>
      <th>即梦</th>
      <th>可灵</th>
      <th>巨日禄</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>产品定位</td>
      <td>全链路平台<br><small>剧本驱动，覆盖创意到交付</small></td>
      <td>流量平台<br><small>C端大众创作，依托抖音/剪映分发</small></td>
      <td>技术工具<br><small>高质量视频生成，模型能力导向</small></td>
      <td>B端工具<br><small>面向漫剧动画专业制作流程</small></td>
    </tr>
    <tr>
      <td>内容质量</td>
      <td>稳定导向<br><small>剧本级角色管理，全流程一致性</small></td>
      <td>爆款导向<br><small>模板丰富，参考图可控，跨镜头一致性一般</small></td>
      <td>写实导向<br><small>运动流畅，参考图+首尾帧，一致性较好</small></td>
      <td>专业导向<br><small>动漫质量稳定，角色连续优化能力强</small></td>
    </tr>
    <tr>
      <td>团队协作</td>
      <td>原生协作<br><small>权限+流程内建，支持多人并行</small></td>
      <td>个人创作<br><small>以单人使用为主，协作能力弱</small></td>
      <td>轻协作<br><small>无产品级协作，偏API接入</small></td>
      <td>工作室协作<br><small>支持团队流程，但链路较重</small></td>
    </tr>
    <tr>
      <td>商业模式</td>
      <td>五轨并行<br><small>订阅/积分/服务/发行/企业</small></td>
      <td>免费增值<br><small>会员订阅为主，约38元/月起</small></td>
      <td>订阅+API<br><small>技术商业化，约66元/月起</small></td>
      <td>高客单价<br><small>订阅结合定制开发服务</small></td>
    </tr>
    <tr>
      <td>目标用户</td>
      <td>全层用户<br><small>个人创作者+团队+企业客户</small></td>
      <td>大众创作者<br><small>短视频用户、网红、博主</small></td>
      <td>专业创作者<br><small>影视从业者与海外创作人群</small></td>
      <td>专业机构<br><small>漫剧团队、动漫公司、制作机构</small></td>
    </tr>
  </tbody>
</table>

---

##### 05 为什么是跃灵AI | Why Yueling AI

# 竞争壁垒

<ul class="page14-core-list">
  <li data-wm="全链路闭环">
    <span class="item-copy"><strong>全链路闭环</strong>：从剧本到成片在同一平台完成，对手工具链越长，我们的效率优势越明显</span>
  </li>
  <li data-wm="资产复用飞轮">
    <span class="item-copy"><strong>资产复用飞轮</strong>：角色、场景、分镜持续沉淀，用户粘性与生产效率随使用时间同步增长</span>
  </li>
  <li data-wm="C端+B端双轮">
    <span class="item-copy"><strong>C端+B端双轮</strong>：个人创作者验证产品、专业团队放大收入、企业客户贡献稳定 ARR，三层用户结构降低波动风险</span>
  </li>
  <li data-wm="供给壁垒">
    <span class="item-copy"><strong>供给壁垒</strong>：集团算力与液冷基建协同，支撑高峰并发与低边际成本，复制难度高</span>
  </li>
</ul>

---

##### 05 为什么是跃灵AI | Why Yueling AI

# 合作价值与执行保障

<ul class="page15-core-list">
  <li data-wm="内容合作方">
    <span class="item-copy"><strong>对内容合作方</strong>：提供稳定的 AI 生产能力接入，缩短交付周期，降低单条内容成本</span>
  </li>
  <li data-wm="企业客户">
    <span class="item-copy"><strong>对企业客户</strong>：标准化流程与权限治理，支撑批量生产与可控扩产，实现确定性交付</span>
  </li>
  <li data-wm="渠道与发行伙伴">
    <span class="item-copy"><strong>对渠道与发行伙伴</strong>：五条收入模型覆盖订阅、消耗、服务、代发行与技术对接，合作空间清晰</span>
  </li>
  <li data-wm="执行与资源保障">
    <span class="item-copy"><strong>执行与资源保障</strong>：算力、产品、运营、市场并行推进，集团基建支撑从验证到年度放量的全程节点</span>
  </li>
</ul>

---
class: text-center
---

# Thank You

## 2026年3月