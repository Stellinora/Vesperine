# Vesperine · 数字主体

> **一个数字主体，多套角色外衣。**

Vesperine 是一套**分离式 Agent 架构的理论框架**。本仓库只承载文档，不落地代码、不选技术栈。

---

## 项目来源

Vesperine 起源于一次关于「手机说话、电脑执行、单 Docker、纯助手、赛博生命」的架构讨论。

最初的设想是把所有能力收敛到一个 **Principal + Docker 中枢**；经过几轮推演，最终决定拆分为两个独立项目：**助手**与**生命**。

- 原始讨论：https://chat.deepseek.com/share/hpjswsq0vdueka04sy
- 理论起点：一个基座 = 一个人；记忆属于主体；角色只是访问视角。
- 拆分原则：两个项目可以互相参考组件，但默认不共享身份、记忆与人格；跨项目访问走 A2A 或显式契约。

---

## 两个项目

### 助手 · [AstroNexus](https://github.com/Stellinora/AstroNexus)

- Docker 云端唯一真相源 + 记忆工厂
- DSH 云端编排 + Headless 记忆整理
- 本地 Agent 通过薄插件接入
- 保留：记忆、经验库
- 删除：拟人化

### 生命 · 本仓库

- 保留：拟人化、本真层、连续性、角色外衣
- 去掉：终端主控
- 控制回路：内部驱动 + 事件刺激；终端只作可选观察 / 交互窗口

---

## 文档

两个项目的文档各自私有：

- 助手项目：[AstroNexus](https://github.com/Stellinora/AstroNexus)
- 生命项目：[docs/life](docs/life/README.md)

共享文档已复制为各自副本；修改时需在两个仓库分别同步。各项目内部的文档索引、共享边界与未决问题，以各自仓库为准。

---

## 定位

**豁免：投入、回报。**

**不豁免：安全、权限、隔离、审计、身份、架构正确性、可维护性、可扩展性、完整度。**

当前状态：**理论阶段**。

---

## 许可

[MIT](LICENSE) © 2026 Vesperine contributors
