

---
title: Главная
type: landing

sections:

  # Главный блок с логотипом RCCL
  - block: hero
    content:
      title: Лаборатория региональных изменений климата
      image:
        filename: rccl-main-logo.png
      text: |
        Regional Climate Change Laboratory (RCCL)

        Исследуем региональную изменчивость и изменения
        климата, атмосферные процессы и климатические риски
        для природных и социально-экономических систем.

  # Последние новости лаборатории
  - block: collection
    content:
      title: Последние новости
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  # Большая фотография лаборатории
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  # Последние научные препринты
  - block: collection
    content:
      title: Последние препринты
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  # Переход в раздел команды
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Наша команда →" %}}
    design:
      columns: '1'
---
