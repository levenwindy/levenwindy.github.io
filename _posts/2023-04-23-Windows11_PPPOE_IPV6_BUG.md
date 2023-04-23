---
layout: post
title: 关于 Windows 11 PPPoE 拨号无法正常获取 IPV6 的 BUG （已修复)
categories: [Windows 11, IPV6, PPPoE]
description: 测试当地宽带运营商 IPV6 MTU 的最佳值
keywords: Windows 11，PPPoE，拨号，IPV6，BUG
---

上年尝试用 **Windows 11** 拨号，一直拿不到 **IPV6** 地址，搜了一圈没有找到解决办法。直到前段时间疑似碰上了 PMTU 「[黑洞](https://www.v2ex.com/t/800024)」（将近两个月），这两天又突然好了，不能再复现。中途打算用 **Windows** 直接拨号测，结果和上年一样，还是拿不到 **IPV6**。谷歌搜了一圈，最终在台湾的论坛才查到原因，**PPPOE** 是要被淘汰了吗？奈何自用 Windows 都会关闭系统 **自动更新** ，哎。

## 教程

* **Windows 11 22H2**/**21H2** **PPPoE** 無法配置 **IPv6** 位址 修正檔 (KB5022913) [安裝步驟](https://spearmint-drspeed.cdn.hinet.net/Windows%2011%20PPPoE%E7%84%A1%E6%B3%95%E9%85%8D%E7%BD%AEIPv6%E4%BD%8D%E5%9D%80-%E4%BF%AE%E6%AD%A3%E6%AA%94KB5018483%E5%AE%89%E8%A3%9D%E6%AD%A5%E9%A9%9F.pdf)

    - **2023-02** 22H2 (KB5022913) 累积性更新包 <sup>[↗](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5022913)</sup>

    - **2022-10** 21H2 (KB5018483) 累积性更新包<sup>[↗](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5018483)</sup>

目前，国内的搜索引擎还是搜不到解决方法，在这开个贴，好让「爬虫」爬回去。
