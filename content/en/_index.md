---
title: "Damir Dzhumabaev"
type: landing

sections:
  - block: hero
    content:
      title: "Damir Dzhumabaev"
      text: "IT Student, RUDN University"
      primary_action:
        text: "About me"
        url: "/authors/me/"
        icon: hero/user
      secondary_action:
        text: "My posts"
        url: "/blog/"
        icon: hero/document-text

  - block: markdown
    content:
      title: "About me"
      text: |
        Student of Peoples' Friendship University of Russia named after Patrice Lumumba.
        Studying Information Technology at the Faculty of Physics and Mathematics.

        Interested in programming, Git, Linux, frontend development and mathematics.

  - block: collection
    content:
      title: "Latest posts"
    design:
      view: card
      columns: "2"
    filter:
      folders:
        - blog
---