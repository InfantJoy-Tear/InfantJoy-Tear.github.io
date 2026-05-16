---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: me
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: 我的NUIST个人主页
          icon: academicons/arxiv
          url: https://faculty.nuist.edu.cn/tianwen/zh_CN/index.htm
        - text: IEEE主页
          icon: brands/ieee
          url: https://ieeexplore.ieee.org/author/37088370173
        - text: 课题组研究方向
          icon: hero/academic-cap
          url: /research/
---
