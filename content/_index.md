---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-01-05
type: landing

sections:
  # 1. 主视觉模块（已为你定制为学术/数据分析方向，保留酷炫打字机特效）
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "你好，我是"
      show_status: false
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "我关注"
        strings:
          - "经济学数据分析"
          - "计量经济学建模"
          - "学术研究与数据可视化"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: 查看我的项目
          url: "#projects"
          icon: arrow-down
        - text: 取得联系
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]
  
  # 2. 项目展示模块（未来用来存放你的计量模型或研究成果）
  - block: portfolio
    id: projects
    content:
      title: "研究与项目 | Featured Projects"
      subtitle: "学术研究与数据分析成果展示"
      count: 0
      filters:
        folders:
          - projects
      buttons:
        - name: 全部
          tag: '*'
      default_button_index: 0
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # 3. 联系方式模块
  - block: contact-info
    id: contact
    content:
      title: "保持联系 | Get In Touch"
      subtitle: "欢迎学术交流与项目合作"
      text: |-
        如果你对我的研究方向感兴趣，或者有任何想交流的想法，欢迎随时通过邮件与我联系！
      email: "your-email@example.com" # 👈 记得在网页端顺手改成你自己的邮箱
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
---

Welcome to my personal website! 
这里可以写一段你想对所有访客说的简短欢迎词（如果你想让主页更干净，第二组 --- 下方直接保持留空即可）。
