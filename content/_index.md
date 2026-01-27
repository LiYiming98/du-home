---
title: Research Group
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: <div style="user-select:none;">雷达目标识别</div>
        content: <div style="margin-top:60px; margin-bottom:40px; font-size:12pt; width:72%; min-width:150px; height:180px; color:#fff; text-indent:2em;"><div style="display:inline-block; position:relative; top:50%; -webkit-transform:translateY(-50%);user-select:none;"><p>雷达目标识别旨在实现雷达传感器精细化目标信息获取及智能化信息利用，是智能化雷达的核心技术。如何从探测到的众多情报信息中及时准确地判别目标属性，是长期困扰我国雷达装备的一大瓶颈难题。</p><p style="margin-top:-1.2vh;">课题组研究方向包括但不限于信号域和图像域物理特征提取、少量标注条件下的统计学习和深层网络学习、复杂场景开放感知与持续学习、视觉-语言大模型迁移学习等。</p></div></div>
        align: left
        background:
          image:
            filename: ai.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#fff'
          
      - title: <div style="user-select:none;">雷达成像</div>
        content: <div style="margin-top:60px; margin-bottom:40px; font-size:12pt; width:65%; height:180px; color:#fff; text-indent:2em;"><div style="display:inline-block; position:relative; top:50%; -webkit-transform:translateY(-50%);user-select:none;"><p>雷达成像旨在在复杂电磁环境与全天时条件下，高精度重构目标与场景的结构与散射特性，其研究方向涵盖成像机理建模、高分辨成像方法、复杂场景鲁棒成像以及智能化与多源协同成像技术。</p><p style="margin-top:-1.2vh;">课题组研究方向包括但不限于逆合成孔径雷达（ISAR）成像与识别、毫米波雷达感知技术以及雷达点云建模与智能分析。</p></div></div>
        align: left
        background:
          image:
            filename: radar.png
            filters:
              brightness: 0.7
          position: right
          color: '#fff'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '600px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 6000
      parallax: true

  - block: portfolio

    # Order that this section appears on the page.
    weight: 20

    content:
      title: <div style="margin-bottom:1em; margin-top:-0.5em;"><a href="../post/" style="color:black; text-decoration:inherit;">新闻</a></div>
      # Page type to display. E.g. project.
      # page_type: post

      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      filter_default: 0
      filters:
        folders:
          - post
        # All set tags: report, event, paper, internship, forum, contest， news
#        exclude_tags: [expired]
#        tags: [paper, internship, forum, contest, people, news]
        kinds:
          - page
      count: 9
      sort_by: 'date'
      sort_ascending: false


    design:
      columns: '1'
      view: masonry
      # view: card
      flip_alt_rows: true
      background: {}
      # spacing: {padding: [20px, 20px, 20px, 20px]}

#    design:
#      # Choose a listing view
#      view: Showcase
#      # Choose single or dual column layout
#      columns: '1'
#      flip_alt_rows: false
---
