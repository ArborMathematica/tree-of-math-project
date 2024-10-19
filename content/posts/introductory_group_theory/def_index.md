---
title: 部分群の指数
date: 2024-10-16
author: Enklht
avatar: img/avatars/enklht.webp
categories:
  - 代数学
  - 群論
tags:
  - 定義
draft: false
---

指数について解説します。

<!--more-->

## 前提知識

- [左、右剰余類]({{< ref "def_coset">}})

## 定義

{{% def "部分群の指数 (index)" %}}
$G$を群、$H$をその部分群とする。このとき、その左、右剰余類の集合$G/H$, $H \backslash G$の濃度は一致する。この濃度を部分群$H$の**指数**といい、$[G:H]$とかく。

{{% /def %}}

## 注意

- $[G:H]$の他に、$(G:H)$や$|G:H|$といった書き方もある。
- $G/H$が群となるのは$H$が正規部分群であるときだけだが、集合の濃度の一致はいつでも起こり、指数は一般の部分群に対して定義される。
- [Lagrangeの定理]({{< ref "thm_lagrange_theorem">}})により、**$[G:H]$は$|G|$の約数である**ことがわかる。

## 参考文献