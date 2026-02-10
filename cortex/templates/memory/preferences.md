# Preferences

从反馈日志中蒸馏出的行为规则。Agent 在每次 Context Loading 时读取此文件，用于约束输出行为。

---

## 活跃规则

<!-- 
  每条规则格式如下：

  <!-- rule | id: RULE-NN | created: YYYY-MM-DD | last_validated: YYYY-MM-DD | source: fb_NNN, fb_NNN | status: active -->
  - **RULE-NN**: 规则描述

  status 取值：
  - active — 规则生效中
  - pending_review — 超过 30 天未被验证，需要复查
  - retired — 已废弃
-->

<!-- 在此行下方追加新规则 -->

---

## 待复查规则

_超过 30 天未被验证的规则会移到这里，等待用户确认是否仍然适用。_

---

## 已废弃规则

_不再适用的规则归档在这里，保留溯源。_
