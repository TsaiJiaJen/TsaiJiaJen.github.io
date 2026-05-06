---
# Leave the homepage title empty to use the site title
title: '張淑微老師實驗室'
summary: '酵素暨生技應用實驗室'
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: lab
      text: '本實驗室隸屬於大葉大學藥用植物與食品保健學系，致力於結合微生物發酵、天然物萃取與生物製程技術，開發應用於食品、保健與美妝產業之高值化產品。'
      button:
        text: '實驗室簡介'
        url: '#research'
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '📚 研究方向'
      text: |-
        本實驗室隸屬於大葉大學藥用植物與食品保健學系，致力於結合微生物發酵、天然物萃取與生物製程技術，開發應用於食品、保健與美妝產業之高值化產品。

        🔬 研究方向 Research Areas

        🌿 天然物與生技原料開發
        - 芳香精油生物合成技術
        - 保健生技原料開發
        - 化妝品生技原料開發
        - 海洋資源生物製程開發

        🧫 微生物與發酵技術
        - 微生物逆境發酵技術
        - 生質能源開發
        - 功能性代謝產物生產

        ⚗️ 萃取與分析技術
        - 酵素輔助萃取技術
        - 同步萃取與合成技術
        - 食品與化妝品檢驗分析
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent News
      page_type: blog
      count: 10
      order: desc
      filters:
        exclude_featured: false
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    content:
      title: '📢 加入我們的實驗室'
      text: |-
        歡迎對微生物研究有興趣的學生加入本實驗室。

        我們提供完整的實驗訓練與研究指導，適合對生物醫學與微生物有興趣的同學。

        📩 聯絡方式：請寄信至老師信箱或聯絡實驗室成員
    design:
      columns: '1'
---
