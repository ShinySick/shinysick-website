---
title: Menú Inicial
slug: /
sections:
  - type: GenericSection
    title:
      text: WELCOME!
      color: text-light
      type: TitleBlock
    subtitle: EL MUNDO DE LA EMULACIÓN TE ESPERA
    text: >
      Aquí encontraras los mejores emuladores y sus configuraciones para que
      puedas disfrutarlos en tus dispositivos.
    actions:
      - label: Únete a la comunidad
        altText: Únete a Discord
        url: 'https://discord.gg/bbyG99mbQF'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Link
      - label: Discord
        altText: Botón Discord
        url: 'https://discord.gg/bbyG99mbQF'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    media:
      url: /images/emuladores-titulo.webp
      altText: Minniatura Inicial de Emuladores de PC
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-neutral
      type: Badge
    elementId: ''
    colors: bg-dark-fg-light
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
    backgroundImage:
      type: BackgroundImage
      altText: Emulacion Background
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/webapp-center-banner.webp
  - type: FeaturedPostsSection
    title:
      type: TitleBlock
      text: Featured posts
      color: text-dark
      styles:
        self:
          textAlign: center
    posts:
      - content/pages/blog/citron-0.6-ya-disponible.md
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: big-list
    colors: bg-light-fg-dark
    hoverEffect: thin-underline
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
  - type: FeaturedItemsSection
    title:
      text: Emuladores Populares
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Listas de Reproducción con todo el Contenido en YT.
    items:
      - title: Ryujinx
        subtitle: Nintendo Switch
        text: >
          Destaca por su excelente rendimiento y precisión, interfaz amigable y
          estable.
        image:
          url: /images/ryujinx-logo.webp
          altText: Ryujinx Logo
          elementId: ''
          type: ImageBlock
        actions:
          - type: Button
            label: Ver
            altText: Ryujinx Lista de Reproducción
            url: >-
              https://www.youtube.com/playlist?list=PLRZYnOrbeoT28MnQEgre8DwMuaR0ywPCu
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - type: FeaturedItem
        title: Citron
        subtitle: Nintendo Switch
        text: |
          Emulador de Nintendo Switch que procedió al extinto Uzuy.
        image:
          type: ImageBlock
          url: /images/citron_icono.ico
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Ver
            altText: Citron Lista de Reproduccion
            url: >-
              https://www.youtube.com/playlist?list=PLRZYnOrbeoT05OyoBkMcIhPKCrBIWWmR7
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Yuzu
        subtitle: Nintendo Switch
        text: |
          Fue el MEJOR emulador de Nintendo Switch de código abierto.
        actions:
          - type: Button
            label: Ver
            altText: Yuzu Lista de Reproducción
            url: >-
              https://www.youtube.com/playlist?list=PLRZYnOrbeoT088dUT0fvPbfjWU1-TMwyP
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        elementId: null
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Yuzu Logo
          elementId: ''
          url: /images/yuzu-logo.webp
          styles:
            self:
              borderRadius: x-large
      - type: FeaturedItem
        title: Cemu
        subtitle: Nintendo Wii U
        text: |
          Emulador de Nintendo Wii U para Windows y Linux de código abierto.
        image:
          type: ImageBlock
          url: /images/cemu-logo.webp
          altText: Cemu Logo
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Ver
            altText: Cemu Lista de Reproducción
            url: >-
              https://www.youtube.com/playlist?list=PLRZYnOrbeoT2xdv1ypbawWPm82Hvj12Ky
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: RPCS3
        subtitle: Playstation 3
        text: >
          Emulador multiplataforma de Playstation 3 de codigo abierto escrito en
          C++.
        image:
          type: ImageBlock
          url: /images/rpcs3-logo.webp
          altText: RPCS3 Logo
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Ver
            altText: Rpcs3 Lista de Reproducción
            url: >-
              https://www.youtube.com/playlist?list=PLRZYnOrbeoT1qvdAxluGdER7lXqeJKEmZ
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Uzuy
        subtitle: Nintendo Switch
        text: |
          Emulador de Switch para Android con un rendimiento superior a Yuzu.
        image:
          type: ImageBlock
          url: /images/uzuy.webp
          altText: Uzuy Logo
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Ver
            altText: Uzuy Lista de Reproducción
            url: >-
              https://www.youtube.com/playlist?list=PLRZYnOrbeoT3A0HY_ufJ3BwUnXhGjW4SV
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Suyu
        subtitle: Nintendo Switch
        text: >
          Fué la continuación del emulador más popular de la Nintendo Switch,
          Yuzu.
        image:
          type: ImageBlock
          url: /images/suyu-logo.webp
          altText: Suyu Logo
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions:
          - type: Button
            label: Ver
            altText: Suyu Lista de Reproducción
            url: >-
              https://www.youtube.com/playlist?list=PLRZYnOrbeoT0J-vLlgrfNF60KnZrM7vvq
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
    actions:
      - label: Ver Más
        altText: Vér más emuladores
        url: /emuladores
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - posts:
      - content/pages/blog/guias-completas.md
      - content/pages/blog/tutoriales.md
      - content/pages/blog/vlogs.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
    title:
      type: TitleBlock
      text: LAS SECCIONES MÁS POPULARES
      color: text-dark
      styles:
        self:
          textAlign: center
          fontWeight: 400
  - subtitle: Manejamos TODOS los estados de ánimo.
    images:
      - url: /images/shiny bless.png
        altText: ShinyBless
        type: ImageBlock
      - url: /images/bye chainy.png
        altText: shiny bye
        type: ImageBlock
      - url: /images/feliv3.png
        altText: shiny feli
        type: ImageBlock
      - url: /images/GG chainy 2.png
        altText: shiny gg
        type: ImageBlock
      - url: /images/laughting chainy.png
        altText: shiny XD
        type: ImageBlock
      - url: /images/PopCorn chainy.png
        altText: shiny palomitas
        type: ImageBlock
      - url: /images/Sad chainy.png
        altText: shiny sad
        type: ImageBlock
    motion: move-to-left
    colors: bg-neutral-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - title: Divider
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: DALE UN VISTAZO
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Emulando Nintendo Switch en Meta Quest 2
    text: >+
      <div style="text-align: center">En este canal nos gusta **experimentar**
      con cosas diferentes para **salir de la monotonía**.</div>

    media:
      title: Uzuy en Meta Quest 2
      url: 'https://youtu.be/NxmtJP-YNn8'
      controls: true
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
      autoplay: false
      loop: false
      muted: false
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-neutral-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
  - type: GenericSection
    title:
      text: Tutoriales de Interés
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: Completos y Detallados
    text: >
      Si alguna vez sentiste que 2 minutos no son suficientes para explicar y
      entender lo que necesitas hacer, este es el canal para ti.


      Con **instrucciones claras, fáciles y detalladas** para no perderte y
      fallar en el intento.
    actions:
      - type: Button
        label: Ver en YT
        altText: Ir al Video
        url: >-
          https://www.youtube.com/playlist?list=PLRZYnOrbeoT2tCC1C8XJbA4GY_azsoO05
        showIcon: true
        icon: youtube
        iconPosition: left
        style: primary
        elementId: ''
    media:
      title: Como configurar lossless scaling
      url: 'https://youtu.be/NxmtJP-YNn8'
      autoplay: false
      loop: true
      muted: false
      controls: true
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
    elementId: null
    colors: bg-neutral-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - type: GenericSection
    title:
      type: TitleBlock
      text: Videos Informativos
      color: text-light
      styles:
        self:
          textAlign: left
    subtitle: Entérate de las noticias más recientes.
    text: >
      Vlogs de **calidad** y con información relevante en el mundo de la
      **emulación** y el **gaming**.
    actions:
      - type: Button
        label: Ver en YT
        altText: Ir al video
        url: >-
          https://www.youtube.com/playlist?list=PLRZYnOrbeoT1NUvAOssK_xyYxnVvYYu5C
        showIcon: true
        icon: youtube
        iconPosition: left
        style: secondary
        elementId: ''
    media:
      type: VideoBlock
      title: No actualices al Firmware 19.0.0
      url: 'https://youtu.be/UxyfzpzD0hw'
      autoplay: false
      loop: true
      muted: false
      controls: true
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    colors: bg-dark-fg-light
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - title: Divider
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: ¿Quieres apoyar de otras maneras?
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: 'Siguenos, Suscribete o Convierete en Miembro de Canal.'
    items:
      - title: YouTube
        tagline: Suscripción
        subtitle: Suscríbete al Canal
        text: >+
          <div style="text-align: left">Si encontraste lo que necesitabas, te
          ayudé con tus dudas o te gustó el contenido, **suscribete al canal de
          YT**.</div>

        image:
          url: /images/suscripcion-youtube.webp
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Button
            label: Suscríbete
            altText: Boton de Suscripción
            url: 'https://bit.ly/35ODAvb'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
      - title: YouTube
        tagline: Membresia de Canal
        subtitle: Únete a los Miembros
        text: >
          Al ser **miembro** de canal recibes **ventajas exclusivas, acceso
          anticipado, menciones y sugerencias de contenido**.
        image:
          url: /images/membresia-youtube.webp
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Button
            label: Únete
            altText: Boton Membresias YouTube
            url: 'https://bit.ly/48mqCTG'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
      - title: Twitch
        tagline: Sígueme
        subtitle: Sígueme en Stream
        text: >
          A veces pasar el tiempo conviviendo **en vívo** es la mejor manera de
          **comunicarnos, descansar y divertirnos**.
        image:
          url: /images/follow-twitch.webp
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Button
            label: Sígueme
            altText: Boton de Follow Twitch
            url: 'https://www.twitch.tv/shinysick'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
seo:
  metaTitle: ShinySick | Emulación de Consolas y Preservación de Videojuegos
  metaDescription: >-
    Descubre en ShinySick tu fuente principal para emulación de consolas y
    preservación de videojuegos. Guías, tutoriales y las últimas noticias en el
    mundo de los videojuegos retro.
  socialImage: /images/emulacion-videojuegos.webp
  type: Seo
  addTitleSuffix: true
  metaTags:
    - type: MetaTag
      property: 'og:title'
      content: ShinySick | Emulación de Consolas y Preservación de Videojuegos
type: PageLayout
---
