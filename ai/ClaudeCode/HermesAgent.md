# Hermes Agent

## 项目地址

[GitHub][Hermes GitHub]

[Hermes GitHub]: https://github.com/nousresearch/hermes-agent "Hermes Agent"

## 安装

```bash
curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash
hermes model

# 开机自动启动
hermes gateway install
cd ~/.config/systemd/user/
cd ~/.config/systemd/user/default.target.wants/
hermes gateway start
hermes gateway setup

# 推出账号，服务不终止
sudo loginctl enable-linger "$(whoami)"
```

## 升级

```bash
hermes update
```
