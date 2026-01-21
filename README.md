# 🖕 田中飞马 | Fuck Kensuke Tanaka | 田中謙介ファック 🖕

---

# AwesomeKanColleProxyRules

[[中文]](#中文) | [[English]](#english) | [[日本語]](#日本語)

---

## 中文

🚢 舰队收藏（砍口垒）Clash Party 分流规则配置文件

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

### 简介

本仓库提供专为网页游戏 **舰队Collection（KanColle）** 优化的网络代理分流规则，适用于 [Clash Party](https://github.com/mihomo-party-org/clash-party) 客户端。

### 功能特性

- ✅ 完整覆盖 DMM 游戏平台域名
- ✅ 支持全部 20 个游戏服务器直连
- ✅ 第三方工具（曙站、明石的改修工厂早见表）代理支持
- ✅ 三语注释（中文/English/日本語）

### 分流策略

```text
DMM 平台登录 ──────────► 日本节点（绕过地区限制）
砍口垒游戏服务器 ───► 直连（DIRECT）
第三方辅助工具 ────────► 指定代理（飞鸟云）
```

### 使用方法

1. 打开 Clash Party
2. 进入 **覆写** > 点击右上角的 **+** 按钮 > 选择 **新建 YAML**
3. 点击刚刚创建的 YAML 文件的图标右上角的 **...** 按钮 > 选择 **编辑文件**
4. 复制 `KanColle.yaml` 的内容并粘贴到编辑器中
5. 点击右下角的 **确认** 按钮
6. **大功告成！**

> **注意**：请确保将代理组 `飞鸟云` 和日本节点替换为你实际可用的代理组和日本节点。

---

## English

🚢 Clash Party Proxy Rules for KanColle (Fleet Girls Collection)

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

### Introduction

This repository provides optimized proxy routing rules for the web game **Fleet GirlsCollection (KanColle)**, designed for [Clash Party](https://github.com/mihomo-party-org/clash-party) client.

### Features

- ✅ Complete coverage of DMM game platform domains
- ✅ Direct connection support for all 20 game servers
- ✅ Proxy support for third-party tools (TsunKit, Akashi's Improvement Arsenal Quick Reference Table)
- ✅ Trilingual comments (中文/English/日本語)

### Routing Strategy

```text
DMM Platform Login ──────────► Japan Node (bypass geo-restriction)
KanColle Game Servers ───────► DIRECT Connection
Third-party Tools ───────────► Designated Proxy (Feiniaoyun)
```

### Usage

1. Open Clash Party
2. Go to **Override** > Click the **+** button in the top right corner > Select **New YAML**
3. Click the **...** button on the newly created YAML file icon > Select **Edit File**
4. Copy the contents of `KanColle.yaml` and paste into the editor
5. Click the **Confirm** button in the bottom right corner
6. **Done!**

> **Note**: Make sure to replace the proxy groups and Japan nodes with your actual available proxies.

---

## 日本語

🚢 艦隊これくしょん（艦これ）Clash Party プロクシ分流ルール設定ファイル

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

### はじめに

本リポジトリは、ブラウザゲーム **艦隊これくしょん（艦これ）** に最適化されたプロクシ分流ルールを提供します。[Clash Party](https://github.com/mihomo-party-org/clash-party) クライアント用です。

### 特徴

- ✅ DMM ゲームプラットフォームドメインを完全カバー
- ✅ 全 20 ゲームサーバーの直接接続をサポート
- ✅ サードパーティツール（曙站、明石の改修工廠早見表）のプロクシサポート
- ✅ 三言語コメント（中文/English/日本語）

### 分流ストラテジー

```text
DMM プラットフォームログイン ──► 日本ノード（地域制限回避）
艦これゲームサーバー ──────────► 直接接続（DIRECT）
サードパーティツール ──────────► 指定プロクシ
```

### 使い方

1. Clash Party を開く
2. **オーバーライド** へ移動 > 右上の **+** ボタンをクリック > **新規 YAML** を選択
3. 作成した YAML ファイルのアイコンの **...** ボタンをクリック > **ファイルを編集** を選択
4. `KanColle.yaml` の内容をコピーしてエディタに貼り付ける
5. 右下の **確認** ボタンをクリック
6. **完了！**

> **注意**：プロクシグループと日本ノードは、実際に利用可能なものに置き換えてください。

---

## 游戏服务器列表 / Game Server List / ゲームサーバー一覧

| # | 中文名 | English | 日本語 | IP |
|---|--------|---------|--------|-----|
| 1 | 横须贺镇守府 | Yokosuka Naval District | 横須賀鎮守府 | 203.104.209.71 |
| 2 | 吴镇守府 | Kure Naval District | 呉鎮守府 | 203.104.209.87 |
| 3 | 佐世保镇守府 | Sasebo Naval District | 佐世保鎮守府 | 125.6.184.215 |
| 4 | 舞鹤镇守府 | Maizuru Naval District | 舞鶴鎮守府 | 203.104.209.183 |
| 5 | 大凑警备府 | Oominato Guard District | 大湊警備府 | 203.104.209.150 |
| 6 | 特鲁克泊地 | Truk Anchorage | トラック泊地 | 203.104.209.134 |
| 7 | 林加泊地 | Lingga Anchorage | リンガ泊地 | 203.104.209.167 |
| 8 | 拉包尔基地 | Rabaul Naval Base | ラバウル基地 | 203.104.209.199 |
| 9 | 肖特兰泊地 | Shortland Anchorage | ショートランド泊地 | 125.6.189.7 |
| 10 | 布因基地 | Buin Naval Base | ブイン基地 | 125.6.189.39 |
| 11 | 塔威塔威泊地 | Tawi-Tawi Anchorage | タウイタウイ基地 | 125.6.189.71 |
| 12 | 帕劳泊地 | Palau Anchorage | パラオ泊地 | 125.6.189.103 |
| 13 | 文莱泊地 | Brunei Anchorage | ブルネイ泊地 | 125.6.189.135 |
| 14 | 单冠湾泊地 | Hitokappu Bay Anchorage | 単冠湾泊地 | 125.6.189.167 |
| 15 | 幌筵泊地 | Paramushir Anchorage | 幌筵泊地 | 125.6.189.215 |
| 16 | 宿毛湾泊地 | Sukumo Bay Anchorage | 宿毛湾泊地 | 125.6.189.247 |
| 17 | 鹿屋基地 | Kanoya Airfield | 鹿屋基地 | 203.104.209.23 |
| 18 | 岩川基地 | Iwagawa Airfield | 岩川基地 | 203.104.209.39 |
| 19 | 佐伯湾泊地 | Saiki Bay Anchorage | 佐伯湾泊地 | 203.104.209.55 |
| 20 | 柱岛泊地 | Hashirajima Anchorage | 柱島泊地 | 203.104.209.102 |

## 相关链接 / Related Links / 関連リンク

- [Clash Party 官方文档 / Documentation](https://mihomo.party/docs/guide/override/yaml)
- [DMM GAMES](https://games.dmm.com/)
- [曙站 / TsunKit](https://tsunkit.net/)
- [明石的改修工厂早见表 / Akashi's Arsenal / 明石の改修工廠早見表](https://akashi-list.me/)

## 贡献 / Contributing / コントリビュート

欢迎提交 Issue 和 Pull Request！  
Issues and Pull Requests are welcome!  
Issue と Pull Request を歓迎します！

## 许可证 / License / ライセンス

MIT License
