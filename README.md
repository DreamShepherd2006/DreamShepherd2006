## Hi 👋 I'm DreamShepherd

Building [nanobot-legion](https://github.com/DreamShepherd2006/nanobot-legion) — 将单智能体 [NanoBot](https://github.com/HKUDS/nanobot) 扩展为多智能体协同指挥系统，支持 HF Spaces / ModelScope Studio 双平台部署。

### 🏗️ 仓库体系

| 仓库 | 角色 |
|---|---|
| [**cloud-agent-gateway**](https://github.com/DreamShepherd2006/cloud-agent-gateway) | 框架无关的云部署 pip 包（平台抽象、OAuth、中继、身份注入） |
| [**nanobot-legion**](https://github.com/DreamShepherd2006/nanobot-legion) | nanobot 专用部署层（gatekeeper、squad bridge、补丁、Dockerfile） |
| [nanobot](https://github.com/DreamShepherd2006/nanobot) | 上游 fork — 提交 PR 用 |
| [openclaw](https://github.com/DreamShepherd2006/openclaw) | openclaw fork |

### 🌐 在线演示

| 平台 | 空间 |
|---|---|
| HuggingFace | [DreamShepherd2006/nanobot-cloud-demo](https://huggingface.co/spaces/DreamShepherd2006/nanobot-cloud-demo) |
| ModelScope | [DreamShepherd/ms-nanobot-cloud-demo](https://www.modelscope.cn/studios/DreamShepherd/ms-nanobot-cloud-demo) |

### 🔗 上游贡献

- [PR #4139](https://github.com/HKUDS/nanobot/pull/4139) — `feat(ws): target_chat_id` 会话恢复
- [PR #4134](https://github.com/HKUDS/nanobot/pull/4134) — `fix(ws): permission denial error events`（已关 — 确认 token 是唯一安全边界）
- [PR #3908](https://github.com/HKUDS/nanobot/pull/3908) — `feat(ws): peers_update event`
- [PR #3869](https://github.com/HKUDS/nanobot/pull/3869) — `fix: DeepSeek message hardening`
- [Discussion #3925](https://github.com/HKUDS/nanobot/discussions/3925) — 单容器多智能体系统
