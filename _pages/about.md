---
layout: about
title: About
permalink: /
subtitle:  >

profile: false
  # align: right
  # image: prof_pic.jpg
  # image_circular: false # crops the image to make it circular
  # more_info: >
    # <p>555 your office number</p>
    # <p>123 your address street</p>
    # <p>Your City, State 12345</p>

selected_papers: 
  enable: true # includes a list of papers marked as "selected={true}"
  scrollabel: true
  limit: 3

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

service:
  enabled: true
---

<!-- 第一行：个人简介 + 联系方式（左） + 头像（右） -->
<div style="display: flex; gap: 2rem; align-items: center; margin-bottom: 2rem;">

  <!-- 左侧：简介 + 联系方式 -->
  <div style="flex: 3;">
    <p>
      I am currently a <strong>Postdoctoral Researcher</strong> at
      <a href="https://group-mmm.org/index.html">Group MMM</a>, National Institute of Informatics (NII), Tokyo,
      working with <a href="https://group-mmm.org/~ichiro/">Prof. Ichiro Hasuo</a>.
      I received my Ph.D. from the Institute of Software, Chinese Academy of Sciences (ISCAS),
      advised by <a href="https://lcs.ios.ac.cn/~znj/">Prof. Naijun Zhan</a>.
    </p>

    <p style="margin-top: 0.8rem; margin-bottom: 0.4rem;">
      My research focuses on:
    </p>
    <ul style="margin-top: 0.2rem; line-height: 1.55;">
      <li>
        <strong>Temporal-logic foundations for CPS</strong>:
        expressive specification languages, robust/quantitative semantics, and their algorithmic consequences
      </li>
      <li>
        <strong>Synthesis and optimization under specifications</strong>:
        controller synthesis and falsification as optimization/decision problems guided by logical constraints
      </li>
      <li>
        <strong>Runtime verification and enforcement</strong>:
        monitors and shields for real-valued signals, including systems with delays and stochastic effects
      </li>
    </ul>

    <div style="text-align: center; font-size: 0.8rem; margin-top: 0.6rem; font-weight: 600;">
      <a href="mailto:suhan@ios.ac.cn" style="margin: 0 8px;">Email</a> ·
      <a href="https://scholar.google.com/citations?user=7mBkXNMAAAAJ" target="_blank" style="margin: 0 8px;">Google Scholar</a> ·
      <a href="https://orcid.org/0000-0003-4260-8340" target="_blank" style="margin: 0 8px;">ORCID</a> ·
      <a href="https://dblp.org/pid/23/3419-3.html" target="_blank" style="margin: 0 8px;">dblp</a> ·
      <a href="{{ site.baseurl }}/assets/cv/main.pdf" target="_blank" style="margin: 0 8px;">CV</a>
    </div>
  </div>

  <!-- 右侧：照片 -->
  <div style="flex: 1;">
    <img src="{{ site.baseurl }}/assets/img/prof_pic.jpg" alt="Han SU" style="width: 160px; border-radius: 8px; margin-top: -2.5rem;" />
  </div>
</div>