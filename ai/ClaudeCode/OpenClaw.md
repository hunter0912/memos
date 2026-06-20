# OpenClaw

## 项目地址

[GitHub][OpenClaw GitHub]

[OpenClaw GitHub]: https://github.com/openclaw/openclaw "OpenClaw"

## 安装

```bash
curl -fsSL https://openclaw.ai/install.sh | bash
openclaw onboard --install-daemon
openclaw gateway status
openclaw gateway restart

openclaw status
openclaw dashboard

# 推出账号，服务不终止
sudo loginctl enable-linger "$(whoami)"
```

## 升级

```bash
openclaw update
```
