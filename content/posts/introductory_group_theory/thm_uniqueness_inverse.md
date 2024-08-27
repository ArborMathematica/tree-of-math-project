---
title: 逆元の一意性
date: 2024-08-23T10:05:00+09:00
lastmod: 2024-08-23T10:05:00+09:00
author: Author Name
# avatar: /img/author.jpg
# authorlink: https://author.site
# cover: /img/cover.png
# images:
#   - /img/cover.png
categories:
  - 代数学
tags:
  - 定理
# nolastmod: true
draft: false
---

群の各元について、逆元が一意に定まることを解説します。

<!--more-->

## 前提知識

- [群の定義]({{< ref "def_group" >}})

## 主張

{{% thm 群の逆元の一意性 %}}
$G$ を群とする。このとき、各元 $g \in G$ の逆元は一つしかない。すなわち、
$h, h' \in G$ がともに $g$ の逆元とすると、$h = h'.$
{{% /thm %}}

## 証明

$h, h'$ がともに $g$ の逆元であったとする。このとき、結合法則を用いると $hgh'$ を二通りに計算できて、
$$
\begin{align*}
  &h g h' = (h g) h' = e h' = h' \\
  &h g h' = h (g h') = h e = h
\end{align*}
$$
左辺が同じなので右辺は等しく、$h = h'$ が成り立つ。

## 注意

- 群に限らず、結合的な演算に逆元が存在すれば、それは一意であることが同様に証明できる。

## 参考文献