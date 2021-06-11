---
title: Home
sections:
  - type: hero_section
    title: Hidalgo Fútbol Club
    subtitle: null
    content: |
      Aquí una pequeña explicación acerca del proyecto, o una breve historia.
    actions:
      - label: Equipo
        url: /acerca
        style: primary
      - label: Información
        url: /info
        style: secondary
    image: images/transparent.webp
    image_alt: transparent
    media_position: left
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_image: images/3213298.jpg
  - type: grid_section
    title: Patrocinadores Oficiales
    subtitle: null
    align: center
    grid_items:
      - image: images/example.png
        image_alt: Patrocinaor 1
        image_align: center
      - image: images/example.png
        image_alt: Patrocinaor 2
        image_align: center
      - image: images/example.png
        image_alt: Patrocinaor 3
        image_align: center
      - image: images/example.png
        image_alt: Patrocinaor 4
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: grid_section
    title: ¿Qué contiene el servicio?
    subtitle: null
    grid_items:
      - title: Página web
        title_align: left
        content: >-
          Una página web rápida con protección ante hackeos, y diseños
          personalizados y reponsivos.
        content_align: left
        actions:
          - label: Learn More
            url: /info
            style: link
            has_icon: true
            icon: arrow-right
            icon_position: center
        actions_align: left
        image: images/classic/icon-2.svg
        image_alt: Section item 1 icon
        image_position: top
        image_align: left
        image_has_padding: true
      - title: Base de datos
        title_align: left
        content: >-
          Base de datos en la blockchain para administrar y monitorear a sus
          jugadores, además de registros sin límite de informacíon.
        content_align: left
        actions:
          - label: Learn More
            url: /info
            style: link
            has_icon: true
            icon: arrow-right
            icon_position: center
        actions_align: left
        image: images/classic/icon-3.svg
        image_alt: Section item 2 icon
        image_position: top
        image_align: left
        image_has_padding: true
      - title: Asistencia 24/7
        title_align: left
        content: >-
          Estamos con ustedes en todo momento, solucionamos cualquier
          problematica requerida, optimizamos, actualizamos y mejoramos los
          servicios con descuento o sin costo adicional.
        content_align: left
        actions:
          - label: Learn More
            url: /info
            style: link
            has_icon: true
            icon: arrow-right
            icon_position: center
        actions_align: left
        image: images/classic/icon-1.svg
        image_alt: Section item 3 icon
        image_position: top
        image_align: left
        image_has_padding: true
    grid_cols: three
    grid_gap_horiz: medium
    grid_gap_vert: small
    enable_cards: true
    align: center
    background_color: none
  - type: blog_feed_section
    title: Ultimas Noticias
    actions:
      - label: Ver todo
        url: /blog
        style: primary
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 3
    show_image: true
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
  - type: cta_section
    title: Título de ejemplo
    content: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.
    actions:
      - label: Botón
        url: /
        style: secondary
    actions_position: right
    actions_width: fourty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
  - type: form_section
    title: Subscríbete a nuestro boletín informativo.
    title_align: center
    content: null
    content_align: center
    form_position: bottom
    form_layout: inline
    form_id: subscribeForm
    form_action: /thank-you
    form_fields:
      - input_type: email
        name: email
        label: Email
        default_value: Escribe tu correo electrónico
        is_required: true
    submit_label: Subscribe
    padding_top: small
    padding_bottom: none
    has_border: true
    background_color: none
seo:
  title: Hidalgo Fútbol Club
  description: Hidalgo FC página de prueba.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Hidalgo Fútbol Club
      keyName: property
    - name: 'og:description'
      value: Hidalgo FC página de prueba.
      keyName: property
    - name: 'og:image'
      value: images/PicsArt_06-10-09.26.43.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Hidalgo Fútbol Club
    - name: 'twitter:description'
      value: Hidalgo FC página de prueba.
    - name: 'twitter:image'
      value: images/PicsArt_06-10-09.26.43.jpg
      relativeUrl: true
layout: advanced
---
