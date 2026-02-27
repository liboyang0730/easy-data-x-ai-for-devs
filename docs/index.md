---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "Easy Data X AI for Devs"
  text: "开发者友好的数据与 AI 入门教程"
  tagline: 开始学起来吧~
  image:
    src: /learning.GIF
    alt: Easy Data X AI
  actions:
    - theme: brand
      text: 开始学习
      link: /chapter1/

features:
  - title: 💥 前沿
    details: 紧跟技术发展输出最前沿的知识
  - title: 🎁 免费
    details: 无任何形式的收费
  - title: 🌐 开源
    details: 教程和代码源文件全部托管在 GitHub
---
<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    avatar: 'https://www.github.com/liboyang0730.png',
    name: 'liboyang0730',
    title: '项目维护者',
    links: [
      { icon: 'github', link: 'https://github.com/liboyang0730' },
    ]
  }
]
</script>


<h2 align="center">Team</h2>
<VPTeamMembers size="small" :members />
