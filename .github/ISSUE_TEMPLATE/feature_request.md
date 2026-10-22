---
name: 功能建议
description: 提出一个想法或改进
title: "[Feature] "
labels: enhancement
body:
  - type: markdown
    attributes:
      value: 欢迎分享你的想法！
  - type: textarea
    id: problem
    attributes:
      label: 你想解决什么问题？
      description: 描述你遇到的场景或痛点
    validations:
      required: true
  - type: textarea
    id: solution
    attributes:
      label: 你期望的方案
      description: 你希望拨叶怎么做
    validations:
      required: true
  - type: textarea
    id: alternatives
    attributes:
      label: 你考虑过的替代方案
      description: 现在你是怎么解决的？
  - type: textarea
    id: extra
    attributes:
      label: 附加信息
      description: 截图、参考产品等
