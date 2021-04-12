---
layout: page
title: About
permalink: /about/
---

# 鄭靖憲（Edgar Cheng）

- E-mail：<future.starshine@gmail.com>
- Linkedin：[Edgar Cheng](https://www.linkedin.com/in/yuki-cheng-ss)
- Blog：[Yuki-Blog](https://yukifans.com/)
- Github：[48763](https://github.com/48763)

## Profile

您好！我是 Edgar，個性樂觀，與人相處較為慢熟，但對人並不吝嗇。在學習方面，樂於接觸新的技術與事物，也喜歡分享所學。雖然我是網路技術學程，但在程式方面，像是資料結構或演算法...等，都不遜色。目前在學習系統效能分析和優化，未來也會深入學習微服務架構規劃和 devops 文化建立。

> 日常筆記：https://github.com/48763/devops-note

## Experience 

### 思華科技有限公司：系統工程師

> 2020年3月 – 目前

1. 建置 prometheus server，配合 exporter 和 pushgateway 收集地端、雲端主機指標，並自製配置檔生成腳本，能隨雲端主機增減，生成對應的配置。
2. Grafana 串接 prometheus server，以製作儀表板，並利用 alertermanager，將告警推送至 slack。
3. 建置 nagios 從境內/外監控網頁憑證與狀態，也撰寫腳本自動生成配置。
4. 建置域名自動化健檢（到期日、創建憑證及刷新、ICP 檢測），也會將告警推送至 slack。
5. 建置自動化生成及設定雲端主機/資料庫/redis的對應內部域名。
6. 建置平台餘額告警。
7. 建置 jenkins，將自動化腳本加入至流水線。
8. 協助機房搬遷規劃與實行。
9. 教導/協助/支援運維人員日常故障排除。
10. 其它主管交辦之事項。

### 薩摩亞商百星數位智能股份有限公司台灣分公司：DevOps

> 2017年8月 - 2020年2月

#### 建置/維護機房：
1. 規劃辦公司與機房線路。
2. 防火牆設置（e.g. DMZ, DNAT）。
3. 伺服器（ESXi）建置。
4. 資料備份與備援線路設置。

#### 服務：
1. 網路相關應用建置（e.g. DHCP, VPN, NGINX, DNS, etc.）。
2. 導入自動化應用（Jenkins）。
3. 容器（Docker）化應應用操作，建置私有倉（Harbor）。
4. 監控與稽核應用設置（e.g. ELK, Prometheus, exporter）。

## Education

### 高雄科技大學：電子工程系碩士班
> 高雄市, 三民區 – 2018/09～2019/01

### 樹德科技大學：資訊工程系（網路工程技術學程）
> 高雄市, 燕巢區 – 2013/09～2017/06（畢業）

## Skills

基礎技能：熟悉 linux 文字介面操作，會撰寫 shell script 或 python 以解決需要重複操作的工作，程式語言會使用 Java[*][1]、java script、C。在網路的部分，擁有 CCNA[*][2]，熟悉交換器和路由器的操作，能獨立建置小型機房網路，也瞭解網路封包運作（ e.g. arp, icmp, tcp, udp, http, etc.）。

系統和監控：對作業系統概論有很好的掌握，效能問題排查時，能有一定的概念；熟悉 prometheus[*][3][*][5] 和 nagios[*][4] 兩套監控，能夠獨立建置 prometheus 整個監控架構，並使用 grafana 製作儀表板，以及結合 alertmanager 推送告警至 slack。

虛擬化應用：深入瞭解 Docker[*][6]，會撰寫最佳實踐的 dockerfile[*][7]，能得心應手的操作容器，也會撰寫 compose。會建置 docker 私有儲存倉 - Harbor。對於 swarm 或 kubernetes 的操作，也有一定的知識與熟悉度（後者比較常接觸）。

版控及 CI/CD：瞭解 git 基本操作，能使用指令完成日常操作。在自動化的部分，熟悉 jenkins[*][8] 自動整合及部署，也有自行撰寫個人的 groovy 公版。

謝謝您撥冗觀看我的履歷表！

<!-- 隱藏連結 -->

[1]: https://github.com/48763/Leetcode "test"
[2]: https://github.com/48763/CCNA "test"
[3]: https://github.com/48763/prometheus-monitor "test"
[4]: https://github.com/48763/nagios "test"
[5]: https://github.com/48763/prom-client-ex "test"
[6]: https://github.com/48763/docker-tutorial "test"
[7]: https://github.com/48763/docker-tutorial/blob/master/dockerfile/design-tips.md#設計技巧 "test"
[8]: https://github.com/48763/jenkins-pipeline "test"
