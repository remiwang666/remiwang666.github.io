---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 自我介绍
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
  #   design:
  #     columns: '1'
  - block: experience
    content:
      title: 教育经历
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: 2006 Jan
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        # - title: 智能驾驶算法研发实习
        #   company: 理想汽车
        #   company_url: ''
        #   company_logo: li2
        #   location: 北京
        #   date_start: '2023-07-21'
        #   date_end: ''
        #   description: |2-
        #       为自动驾驶中的感知、预测、规划等任务预研端到端的智能算法

        - title: 硕士研究生
          company: 北京航空航天大学
          company_url: ''
          company_logo: buaa
          location: 北京
          date_start: '2022-09-01'
          date_end: '2024-06-01'
          description: 硕士毕设研究题目：网络攻击下的多无人机协同编队追击方法研究

        - title: 通用工程师
          company: 巴黎萨克雷大学（巴黎中央理工-高等电力学院）
          company_url: ''
          company_logo: cs
          location: 巴黎
          date_start: '2020-09-01'
          date_end: '2022-06-01'
          description: GPA：4.25 / 4.33，排名：前5% / 900 <br>
                        年均32门课，涵盖数学、控制、机器人、人工智能等众多领域

        - title: 本科生
          company: 北京航空航天大学
          company_url: ''
          company_logo: buaa
          location: 北京
          date_start: '2017-09-01'
          date_end: '2020-06-01'
          description: GPA：3.83 / 4.00，排名：2 / 102，多次获国家奖学金 <br>
                        主修数学物理与控制理论（法语授课）
    design:
      columns: '2'


  - block: portfolio
    id: posts
    content:
      title: 科研经历
      filters:
        folders:
          - post
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false


  # - block: portfolio
  #   id: posts
  #   content:
  #     title: 科研经历
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     columns: '2'

  - block: collection
    id: projects
    content:
      title: 项目经历
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card

  - block: collection
    content:
      title: 科研成果
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1'
      view: citation


  - block: markdown
    id: skills
    content:
      title: 技能
      text: |
      * **语言**：英语 - 流利 - IELTS 7.5，法语 - 流利 - DELF B2
      * **软件**：Python，MATLAB，C/C++，PyTorch，Git，OpenCV，ROS，Linux，AE，PS
      * **硬件**：算法在无人机/车上的部署，OptiTrack系统，UWB系统，机床操作，焊接
      * **业余**：海报与视频制作（学院宣传部副部长），乒乓球（北航院级赛季军）
    design:
      columns: '2'
      view: showcase
      
---
