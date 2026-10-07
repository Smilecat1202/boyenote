---
name: Bug 报告
description: 报告一个可复现的问题
title: "[Bug] "
labels: bug
body:
  - type: markdown
    attributes:
      value: 感谢反馈！请尽量填写完整，这能帮我更快定位问题。
  - type: textarea
    id: what
    attributes:
      label: 问题描述
      description: 发生了什么？你期望发生什么？
      placeholder: 简要描述你遇到的问题
    validations:
      required: true
  - type: input
    id: version
    attributes:
      label: 应用版本
      placeholder: 例如 0.4.23
    validations:
      required: true
  - type: dropdown
    id: platform
    attributes:
      label: 平台
      options:
        - macOS
        - Android
        - Windows
        - 其他
    validations:
      required: true
  - type: textarea
    id: repro
    attributes:
      label: 复现步骤
      description: 如何稳定复现这个问题
      placeholder: |
        1. 打开 ...
        2. 点击 ...
        3. 出现 ...
  - type: textarea
    id: logs
    attributes:
      label: 日志 / 截图
      description: 可粘贴相关日志或拖入截图
