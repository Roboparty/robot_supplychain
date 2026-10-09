---
title: 引言
outline: deep
---

<div class="rp-hero">
  <p class="rp-kicker">机器人供应链 · Humanoid Supply Chain</p>
  <h1>人形机器人供应链知识库</h1>
  <p class="rp-lead">每种料是什么、用在哪一轴、选型必须冻什么、怎么验收、踩过什么坑。分类是大类、小类、细分。这里记判断口径，不记这一次买了谁。</p>
  <div class="rp-actions">
    <a class="primary" href="/knowhow/">进入分类树</a>
    <a class="ghost" href="/docs/gates">看 G0–G5</a>
  </div>
  <p class="rp-rule">无冻结图纸/规格不下正式单；无 IQC 不发料；无 NCR 不私下让步。</p>
</div>

这套站把仓库里的 knowhow、放行门和作业手册收成一棵可以搜索的目录。姊妹作业仓库 `作业仓库` 记询价、PO 和供应商名录。两边不要混：名录、电话、合同不进这里。

## 七个大类

<div class="rp-grid">
  <a class="rp-card" href="/knowhow/01-joint-modules/"><span>01</span><strong>关节模组</strong><p>谐波、行星、RV、无框电机、编码和驱动。</p></a>
  <a class="rp-card" href="/knowhow/02-structure/"><span>02</span><strong>结构件</strong><p>机加材料、钣金、压铸，以及阳极、发黑、喷涂。</p></a>
  <a class="rp-card" href="/knowhow/03-electronics/"><span>03</span><strong>电子器件</strong><p>线材 AWG、涂层，以及 XT30（2+2）。</p></a>
  <a class="rp-card" href="/knowhow/04-sensors/"><span>04</span><strong>传感器</strong><p>力、触觉、IMU、视觉。</p></a>
  <a class="rp-card" href="/knowhow/05-energy/"><span>05</span><strong>能源</strong><p>电芯到 PACK / BMS。</p></a>
  <a class="rp-card" href="/knowhow/06-end-effector/"><span>06</span><strong>末端</strong><p>灵巧手和作业接口。</p></a>
  <a class="rp-card" href="/knowhow/07-standard-parts/"><span>07</span><strong>标准件</strong><p>轴承、紧固件。</p></a>
</div>

## 放行门

买任何大类都走同一组门。细节差在对应 knowhow 里，门本身不跳。

<div class="rp-gates">
  <div><b>G0</b><span>需求与规格冻结</span></div>
  <div><b>G1</b><span>申购，图纸版本锁死</span></div>
  <div><b>G2</b><span>询价与首件</span></div>
  <div><b>G3</b><span>下单</span></div>
  <div><b>G4</b><span>来料检验入库</span></div>
  <div><b>G5</b><span>关单与复盘</span></div>
</div>

完整条件和单据状态见 [G0–G5 放行门](/docs/gates)。询价、准入、首件、来料和不合格闭环在 [作业手册](/playbooks/)。

## 怎么读一页

元器件页按同一骨架写：它是什么、用在机器人哪一段、选型必须冻结的字段、和谁配套、验收看什么、已知的坑。

关节先分谐波、行星、摆线，再往下看结构、额定和装配。结构件先定牌号和状态，再定表面处理。电子先定 AWG 和绝缘，再定插头针定义。

新页用 [元器件模板](/templates/component) 开，挂到对应大类下面。复盘用 [卡片模板](/templates/knowhow-card)，不写私人联系方式。
