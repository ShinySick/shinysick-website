---
type: PostLayout
title: ¿Un MALWARE podría estar afectando RYUJINX 1.2 o solo es HISTERIA COLECTIVA?
date: '2024-10-28'
author: content/data/person1.json
excerpt: >-
  Si tienes una batería o guitarra de wii y quieres utilizarlas en PC, este
  tutorial te ayudará. CONECTA TU WIIMOTE A PC WINDOWS 11
featuredImage:
  type: ImageBlock
  url: /images/ryujinx-1.2-tiene-virus.webp
  altText: Wii Guitar Clone Hero Tutorial Miniatura
  elementId: ''
  styles:
    self:
      padding:
        - pt-0
        - pl-0
        - pb-0
        - pr-0
bottomSections:
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
      type: TitleBlock
      text: Consulta el Vlog
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: ¿Ryujinx 1.2 tiene Virus o no?
    text: >
      Si la información escrita no es tu fuerte y prefieres ver o escuchar lo
      sucedido pues checa el **video** a continuación para enterarte más a
      detalle de la noticia.
    actions: []
    media:
      type: VideoBlock
      title: >-
        ¿Un Malware podría estar afectando Ryujinx 1.2 o solo es histeria
        colectiva?
      url: 'https://youtu.be/_pwYJmlDRow'
      autoplay: false
      loop: false
      muted: true
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
    colors: bg-neutral-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
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
  - type: RecentPostsSection
    title:
      type: TitleBlock
      text: Posts Recientes
      color: text-dark
      styles:
        self:
          textAlign: center
    recentCount: 3
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        justifyContent: center
    hoverEffect: shadow-plus-move-up
slug: ryujinx-1.2-tiene-virus
isFeatured: false
isDraft: true
seo:
  type: Seo
  metaTitle: >-
    ¡Desmontando Mitos! Ryujinx: Emulador de Nintendo Switch SIN Virus - Prueba
    Irrefutable con VirusTotal
  metaDescription: >-
    Descubre cómo demostramos que el emulador Ryujinx está libre de virus
    utilizando VirusTotal. Asegúrate de descargar y jugar con confianza gracias
    a nuestra guía detallada y análisis exhaustivo. ¡Garantiza tu seguridad
    mientras disfrutas de tus juegos favoritos!
  addTitleSuffix: true
  socialImage: /images/ryujinx-1.2-tiene-virus.webp
  metaTags: []
colors: bg-light-fg-dark
styles:
  self:
    flexDirection: col
    borderRadius: large
---
Desde la salida del emulador **Ryujinx 1.2** ha habido un sin fin de quejas de la gente diciendo que **TIENE VIRUS** o **MALWARE**, cosa la cual es totalmente **FALSA**.

<br>

Ésto ha raíz de que ésta versión del emulador no era publica y muchas personas desconfian de ella al mas minimo error.

Pero no hay nada de que preocuparse porque aquí en ShinySick hicimos pruebas a sus versiónes publicadas en el [github de Greemdev](https://github.com/GreemDev/Ryujinx/releases) y tuvimos resultados satisfactorios.

<br>

### Haciendo pruebas con VIRUSTOTAL

Se sabe que la pagina de **VirusTotal** es uno de los principales escaneres de todo tipo de contenido en la red para verificar si algun **archivo** o **URL** tienen contenido malicioso y tambíen es el favorito de la gente.

Nosotros realizamos pruebas a algunas de las versiones y estos fueron los resultados:

**Ryujinx 1.2.59:**![](/images/Captura%20de%20pantalla%202024-10-28%20042628.png)

**Ryujinx 1.2.57:**![](/images/Captura%20de%20pantalla%202024-10-28%20042724.png)

**Ryujinx 1.2.31:**![](/images/Captura%20de%20pantalla%202024-10-28%20042847.png)

<br>

### El problema con Ryujinx 1.2 y VirusTotal

Si bien estos resultados son Satisfactorios, a los mas minuciosos y detallistas les puede llamar la atención que en un apartado es donde podemos encontrar **4 banderas rojas** para el archivo ejecutable del emulador Ryujinx.exe:

![](/images/Captura%20de%20pantalla%202024-10-28%20043154.png)

**¡PERO TRANQUILO!** porque estas advertencias **NO SON PELIGROSAS**.

La primera se trata del error **FileRepMalware \[Misc]** detectada por el antivirus Avast y la segunda **W64.AIDetectMalware** detectada por un motor generado por Inteligencia Artificial.

![](/images/Captura%20de%20pantalla%202024-10-28%20043451.png)

Y para terminar de eliminar tu preocupación, **Avast** genera una cantidad de "**confianza**" en cada app mientras más personas vayan usando algún software nuevo, por ende al no tener una cantidad suficiente de personas *(aún)* que hayan permitido la ejecución del emulador es que marca a Ryujinx 1.2 como si fuera un Malware.

La detección de **BkavPro** impulsada por **IA** tambíen podria fallar tal y como cualquier motor/aplicación impulsado por Inteligencia Artificial, de hecho si googleas **W64.AIDetectMalware** encontrarás **MUCHOS** post de gente hablando sobre Falsos Positivos bajo este nombre.

Y si te preguntas de porqué solo mencioné 2 advertencias y no las 4 mostradas... Pues porque VirusTotal no logró hacer nada con 2 de sus busquedas...

![](/images/Captura%20de%20pantalla%202024-10-28%20044213.png)

Con esto podemos concluír que Este emulador **NO TIENE NINGUN TIPO DE VIRUS O MALWARE ESCONDIDO EN SU CÓDIGO**, unicamente esas advertencias inofensivas las cuales son **FALSOS POSITIVOS.**

<br>

Si quieres información aún mas detallada, revisa el video de abajo!
