<!-- markdownlint-disable MD033 MD036 MD041 -->

<div align="center">

<a href="https://v2.nonebot.dev/store">
  <img src="https://raw.githubusercontent.com/A-kirami/nonebot-plugin-template/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo">
</a>

<p>
  <img src="https://raw.githubusercontent.com/lgc-NB2Dev/readme/main/template/plugin.svg" alt="NoneBotPluginText">
</p>

# nonebot-plugin-githubmodels

_✨ API调用GitHub models大语言模型 ✨_

</div>

<p align="center">
  <a href="https://raw.githubusercontent.com/kexue-z/nonebot-plugin-heweather/master/LICENSE">
    <img src="https://img.shields.io/github/license/kexue-z/nonebot-plugin-heweather.svg" alt="license">
  </a>
  <a href="https://pypi.org/project/nonebot-plugin-heweather/">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-heweather" alt="pypi">
  </a>
  <img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">
</p>

# 安装

使用nb-cli  
```shell
nb plugin install nonebot-plugin-githubmodels
```

# 指令

“AI xxx”  询问AI
例如“AI 嗨”

”AI 重置“  重置上下文记忆

# 配置

## GitHub token 必须配置 环境配置

```
GITHUB.TOKEN = "xxxx"
```

## 所使用的模型 可选配置 环境配置

gpt-4o

gpt-4o-mini

默认值为gpt-4o-mini

```
AI.MODEL.NAME = gpt-4o-mini
```

## 记忆的上下文数量 可选配置 环境配置
默认值为20

```
MAX.CONTEXT.LENGTH = 20
```


