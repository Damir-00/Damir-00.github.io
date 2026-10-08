---
title: "Джумабаев Дамир Айбекович"
type: landing

sections:
  - block: hero
    content:
      title: "Джумабаев Дамир Айбекович"
      text: "Студент направления ИТ, РУДН"
      image:
      filename: "authors/me.jpg"
      alt: "Джумабаев Дамир Айбекович"
      primary_action:
        text: "Обо мне"
        url: "/authors/me/"
        icon: hero/user
      secondary_action:
        text: "Мои посты"
        url: "/blog/"
        icon: hero/document-text

  - block: markdown
    content:
      title: "Обо мне"
      text: |
        Студент Российского университета дружбы народов имени Патриса Лумумбы.
        Обучаюсь на физико-математическом факультете по направлению ИТ.

        Интересуюсь программированием, Git, Linux, frontend-разработкой и математикой.

  - block: collection
    content:
      title: "Последние публикации"
    design:
      view: card
      columns: "2"
    filter:
      folders:
        - blog
---