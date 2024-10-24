---
title: 冪集合
date: 2024-10-23
author: Enklht
avatar: img/avatars/enklht.webp
categories:
  - 論理と集合
tags:
  - 定義
draft: false
---

冪集合について解説します。

<!--more-->

## 前提知識

- [集合]({{< ref "def_set">}})
- [部分集合]({{< ref "def_subset">}})

## 定義

{{% def "冪集合 (power set)" %}}

$X$を集合とする。$X$のすべての部分集合の集合を**冪集合**といい、$\mathcal{P}(X)$や$\frak{P}(X), 2^{X}$とかく。つまり、
$$\mathcal{P}(X) := \set{Y; Y \subset X}$$

{{% /def %}}

## 注意

- 濃度について、$|\mathcal{P}(X)| = 2^{|X|}$が成り立つ。
  - 実際$X$が有限のとき、$\mathcal{P}(X)$の元の個数は、$X$の各元について含むか含まないかの2通りずつの選択肢があるから、$2^{|X|}$である。
  - 任意の集合について、冪集合を取ると真に濃度が大きくなる。つまり、単射$X \to \mathcal{P}(X)$は存在しない。このことは対角線論法により示される。
- 普通、冪集合の存在は公理によって要請する。

## 参考文献