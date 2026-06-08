<div align="center">

![DJAOD Logo](https://img.alicdn.com/bao/uploaded/i2/O1CN01T40tdG24PTHFqFNIA_!!4611686018427384439-2-rate.png)

# 🎵 DJAOD 电音舞曲建站系统

### 专为职业 DJ 与音乐人打造的一站式智能曲库管理平台

[![Version](https://img.shields.io/badge/version-1.0.59-blue.svg)](https://www.djaod.com/)
[![Node.js](https://img.shields.io/badge/Node.js-%3E%3D%20v22.20.0-brightgreen.svg)](https://nodejs.org/)
[![Downloads](https://img.shields.io/badge/downloads-21,702%2B-orange.svg)](https://www.djaod.com/download)
[![License](https://img.shields.io/badge/license-Commercial-red.svg)](https://www.djaod.com/)
[![Website](https://img.shields.io/badge/website-djaod.com-0366d6.svg)](https://www.djaod.com/)

**全流程规范化归档音源资产，自动解析舞曲参数，盘活闲置音源，让海量舞曲源源不断转化为长期收益。**

[🌐 官方网站](https://www.djaod.com/) &nbsp;|&nbsp;
[📦 立即下载](https://www.djaod.com/download) &nbsp;|&nbsp;
[💰 价格套餐](https://www.djaod.com/pricing) &nbsp;|&nbsp;
[📖 文档中心](https://www.djaod.com/docs) &nbsp;|&nbsp;
[🎨 模板市场](https://www.djaod.com/templates) &nbsp;|&nbsp;
[🔌 插件市场](https://www.djaod.com/plugins)

</div>

---

## ✨ 核心功能

### 🚀 全新技术栈
后端采用**非阻塞异步 IO 引擎 + 分布式数据库**，支持高并发请求，性能远超传统 CMS。支持海量 DJ 站长同时在线管理曲库、处理订单与会员请求，高流量下仍保持秒级响应。

### 🎹 自动 BPM & KEY 分析
上传自动精准识别 **BPM（节拍）、KEY（调性）、码率、声道、采样率、音频封面**，一键替代多种分析工具，大幅提升 DJ 工作效率。

### ☁️ 云端存储 & CDN 加速
网站与存储完全分离，文件托管云端并全程 CDN 加速，秒级响应。杜绝传统龟速上传与播放卡顿，海量音频也能流畅试听。

### 🔒 多码率 HLS 流媒体
一键上传自动生成 320k / 256k / 192k / 128k 多码率文件，试听采用 **M3U8 HLS 流播放**，杜绝浏览器抓包盗取音源，兼顾试听体验与版权保护。

### 🛒 专业商城系统
支持多属性规格、商品评论、库存管理、物流追踪、多支付渠道。可出售 **音乐 U 盘、DJ 设备、门票、优惠券、网盘虚拟资源**，帮助站长快速变现。

### 🎤 音乐人平台
音乐人投稿 → 审核 → **可控分佣制度** → 收益明细 → 提现管理，打造完整音乐人生态闭环。站长灵活设置分佣比例，让音乐人自主上传获取收益。

### 💬 圈子社区
创建、加入、关注圈子，发布动态、评论点赞、转发分享。增强用户粘性与社交属性，打造活跃垂直电音社群。

### 📢 多种营销功能
**秒杀 · 团购 · 预售 · 积分 · VIP 等级** —— 丰富的促销玩法助力会员转化率提升与快速变现。

### 📺 多内容管理
统一管理 **音乐、专辑、歌单、视频、商城、圈子、音乐人投稿**，一站式支撑大型媒体平台。

---

## 🛠️ 技术栈

| 类别         | 技术                        |
| ------------ | --------------------------- |
| 运行环境     | Node.js >= v22.20.0         |
| 后端引擎     | 非阻塞异步 IO 引擎          |
| 数据库       | 分布式数据库                |
| 文件存储     | 云端对象存储 + CDN 加速     |
| 流媒体       | M3U8 / HLS 自适应码率       |
| 音频分析     | 自动 BPM / KEY / 码率识别   |

---

## 🎯 适用场景

- 🎧 **DJ 个人网站** —— 展示作品集、推广演出、出售资源
- 🏢 **电音厂牌 / 音乐平台** —— 管理多艺人曲库、运营社区
- 🛍️ **舞曲资源下载站** —— 会员制付费下载、VIP 订阅变现
- 🎓 **DJ 教学平台** —— 视频教程 + 音频素材一体化管理

---

## 🏆 合作客户

| 网站 | 类型 | 链接 |
| ---- | ---- | ---- |
| **CNDJPooL** | 一站式 DJ 服务 | [jcdjpool.com](https://www.jcdjpool.com/) |
| **海螺电音** | 音乐素材 / 采样包 | [hlydjs.com](https://www.hlydjs.com/) |
| **老虎电音网** | 原创电音 / 夜店歌曲 | [pthedm.cn](https://www.pthedm.cn/) |
| **CPUDJ 电音网** | 酒吧包房舞曲 | [cpudj.com](https://www.cpudj.com/) |
| **DJMIX** | 电音厂牌 SET 发布 | [djmix.cn](https://www.djmix.cn/) |
| **MLK 电音网** | EDM 电音资讯 | [mlkdj.com](https://www.mlkdj.com/) |

---

## 🚀 快速开始

```sh
curl -sL https://download.djaod.com/install.sh -o install.sh && chmod +x install.sh && ./install.sh
```

- 建议新手使用宝塔面板 + 一键安装脚本
- 先在宝塔安装好 `Nginx`、 `Nodejs` 和 `Redis`，但是`MongoDB`不要再宝塔面板安装，因为无法配置集群（程序需要）！
- 等执行脚本全部通过后，再在宝塔面板中创建node站点
- 在node站点管理 以`“默认项目“` 创建 前台站点 ，绑定入口为 `/index.js`，绑定命令为：`npm run index` 启动端口为`3080`
- 在node站点管理 以`“默认项目“` 创建 后台站点 ，绑定入口为 `/admin.js`，绑定命令为：`npm run admin` 启动端口为`3000`
- 注意：在宝塔面板创建站点后默认会启动网站，我们要先给他关闭，然后使用命令进行启动站点
- 启动 前台站点:
```sh
systemctl start djaod-index.service
```
- 启动 后台站点：
```sh
systemctl start djaod-admin.service
```

## 视频教程
<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=116588648928433&bvid=BV1RCLE6SEWY&cid=38397151746&p=1" width="100%" height="450"  scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

> **部署极简**：上传源码 → 配置数据库 → 绑定域名 → 即可上线运营。

---

## 📈 DJ 站长变现路径

```
上传舞曲资源 → 会员付费下载 → 商城出售设备/U盘
                ↓
      音乐人入驻投稿 → 分佣抽成
                ↓
      圈子社区运营 → VIP 订阅 → 持续收益
```

---

## 🌟 为什么选择 DJAOD？

| 对比维度     | 传统 CMS / WordPress | DJAOD          |
| ------------ | -------------------- | -------------- |
| 音频 BPM 分析 | 需第三方工具         | ✅ 自动识别     |
| 试听防盗链   | 易于抓包             | ✅ HLS 流加密   |
| 云端存储     | 占用服务器带宽       | ✅ CDN 加速     |
| 音乐人分佣   | 无                   | ✅ 内置系统     |
| 电商标配     | 需装插件             | ✅ 原生商城     |
| 高并发       | 容易卡顿             | ✅ 异步 IO 引擎 |

---

## 🔗 相关链接

- 🌐 官方网站：[https://www.djaod.com/](https://www.djaod.com/)
- 📦 下载安装：[https://www.djaod.com/download](https://www.djaod.com/download)
- 💰 价格套餐：[https://www.djaod.com/pricing](https://www.djaod.com/pricing)
- 📖 文档中心：[https://www.djaod.com/docs](https://www.djaod.com/docs)
- 🎨 模板市场：[https://www.djaod.com/templates](https://www.djaod.com/templates)
- 🔌 插件市场：[https://www.djaod.com/plugins](https://www.djaod.com/plugins)
- 🛠 定制开发：[https://www.djaod.com/custom](https://www.djaod.com/custom)

---

## 📬 联系我们

- 🏢 **开发商**：大图计算机网络工作室
- 🌐 **官网**：[https://www.djaod.com/](https://www.djaod.com/)
- 📧 在线咨询与技术支持请访问官网

---

<div align="center">

### 📢 从 "手里有资源" 到 "手里有钱"，你只差一个 DJAOD！

[⭐ Star 收藏本项目](https://www.djaod.com/) &nbsp;|&nbsp;
[🔗 Fork 分享给朋友](https://www.djaod.com/)

---

© 2026 DJAOD. All rights reserved. [黔ICP备17003115号-4](https://beian.miit.gov.cn/)

</div>
