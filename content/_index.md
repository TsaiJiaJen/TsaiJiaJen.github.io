---
# Leave the homepage title empty to use the site title
title: '張淑微老師實驗室'
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: '本實驗室隸屬於大葉大學藥用植物與食品保健學系，致力於結合微生物發酵、天然物萃取與生物製程技術，開發應用於食品、保健與美妝產業之高值化產品。'
      # Show a call-to-action button under your biography? (optional)
      button:
        text: '實驗室簡介'
        url: '#research'
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
   本實驗室致力於結合微生物發酵、天然物萃取與生物製程技術，開發應用於食品、保健與美妝產業之高值化產品。
   研究方向 Research Areas
  🌿 天然物與生技原料開發
     芳香精油生物合成技術
     保健生技原料開發
     妝品生技原料開發
     海洋資源生物製程開發
  🧫 微生物與發酵技術
     微生物逆境發酵技術
     生質能源開發
     功能性代謝產物生產
  ⚗️ 萃取與分析技術
     酵素輔助萃取技術
     同步萃取與合成技術
     食品與化妝品檢驗分析
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

        Please reach out to collaborate 😃
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
      text: ''
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
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown 
    content:
      title: '📢 加入我們的實驗室'
      text: |-
        歡迎對微生物研究有興趣的學生加入本實驗室。

      我們提供完整的實驗訓練與研究指導，適合對生物醫學與微生物有興趣的同學。
      
      📩 聯絡方式：請寄信至老師信箱或聯絡實驗室成員
---
