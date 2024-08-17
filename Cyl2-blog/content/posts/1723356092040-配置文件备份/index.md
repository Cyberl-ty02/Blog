---
title: "配置文件备份"
date: 2024-08-11
draft: false
description: "本文用于存储部分软件的配置文件"
tags: ["artile", "tag"]
---
本文用于存储部分软件的配置文件

## doas.conf

```bash
# Do not require passwords for five minutes for all users in the wheel group
permit persist :wheel

# Allow a user to use the reboot command without a password
permit nopass kl cmd reboot
permit nopass kl cmd shutdown
permit nopass kl cmd eix-sync
```

## .zimrc

```bash
# Install p10k theme
zmodule romkatv/powerlevel10k
# Install dracula colour
zmodule dracula
```

## .zshrc

```bash
# Do not require passwords for five minutes for all users in the wheel group
permit persist :wheel

# Allow a user to use the reboot command without a password
permit nopass kl cmd reboot
permit nopass kl cmd shutdown
permit nopass kl cmd eix-sync
```
