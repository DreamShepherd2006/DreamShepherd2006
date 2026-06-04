## Hi 👋 I'm DreamShepherd

Building AI agent cloud deployment infrastructure — from platform abstraction to multi-agent orchestration.

```
应用层   nanobot-legion (Squad 多智能体指挥系统)
          ▲
底层     cloud-agent-gateway (平台抽象 · OAuth · Relay, pip 包)
          ▲
框架     upstream nanobot (单智能体引擎)
```

### 🏗️ 仓库

| 仓库 | 角色 |
|---|---|
| [**cloud-agent-gateway**](https://github.com/DreamShepherd2006/cloud-agent-gateway) | 框架底层 — 平台探测、OAuth 代理、HTTP Relay 中继，pip 包 |
| [**nanobot-legion**](https://github.com/DreamShepherd2006/nanobot-legion) | 应用部署层 — Gatekeeper 网关、Squad 多智能体、补丁、五空间部署 |
| [nanobot](https://github.com/DreamShepherd2006/nanobot) | 上游 fork — PR 提交 |
| [openclaw](https://github.com/DreamShepherd2006/openclaw) | openclaw fork |

### 🌐 在线空间

| 空间 | 平台 | 层 |
|------|------|-----|
| [Nightly](https://huggingface.co/spaces/DreamShepherd2006/nanobot-multi-agent-nightly) | HF Spaces | 应用部署层 |
| [HF Staging](https://huggingface.co/spaces/DreamShepherd2006/Nanobot-Staging) | HF Spaces | 应用部署层 |
| [MS Staging](https://www.modelscope.cn/studios/Stone2006/nanobot-multi-agent-nightly) | ModelScope | 应用部署层 |
| [HF Cloud Demo](https://huggingface.co/spaces/DreamShepherd2006/nanobot-cloud-demo) | HF Spaces | 框架底层（直接使用） |
| [MS Cloud Demo](https://www.modelscope.cn/studios/DreamShepherd/ms-nanobot-cloud-demo) | ModelScope | 框架底层（直接使用） |

### 🔗 上游贡献

- [PR #4139](https://github.com/HKUDS/nanobot/pull/4139) — `feat(ws): target_chat_id` 会话恢复
- [PR #4134](https://github.com/HKUDS/nanobot/pull/4134) — `fix(ws): permission denial error events`（已关 — token 是唯一安全边界）
- [PR #3908](https://github.com/HKUDS/nanobot/pull/3908) — `feat(ws): peers_update event`
- [PR #3869](https://github.com/HKUDS/nanobot/pull/3869) — `fix: DeepSeek message hardening`
- [Discussion #3925](https://github.com/HKUDS/nanobot/discussions/3925) — 单容器多智能体系统
