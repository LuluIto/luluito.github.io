---
title: Practicality and Limitation of Differential Privacy
description: First research on differential privacy.
author: Lulu
date: 2024-06-05 13:33:00 +0800
categories: [Blogging]
tags: [privacy]
pin: false
math: false
mermaid: true
---
## Intro
- 差分プライバシーは、プライバシー保護の強さを定量的に評価する安全性基準であり、適度なプライバシー保護の実現に有用な概念である。
<dr>
    - 差分プライバシーの安全基準は、「特定の攻撃モデルに依存せず無条件で成立する」安全性に基づいている。
    <dr>
    - プライバシー侵害の脅威が増していくにつれて[* 予防的措置]が望まれるようになった

- 差分プライバシーの問題点
<dr>
    - プライバシー保護の強さを表すパラメータを定める方法には明確な合意がない。
    <dr>
    - 代表的なラプラスメカニズムからは実用に足る十分な精度や性質を持った出力が得られないことがある。
    <dr>
	→ 実務に応用するには個別の応用例ごとに調整が必要

- プライバシーとは
 <dr>
    - 「機微な情報の漏洩防止」
     <dr>
    - 「自己情報のコントロール権」
     <dr>
    - 1980年代：「1人にしてもらう権利」
     <dr>
    - 現代：「忘れられる権利」、「追加拒否権」も追加
     <dr>