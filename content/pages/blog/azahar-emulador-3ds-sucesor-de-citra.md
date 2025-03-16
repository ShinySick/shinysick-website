---
type: PostLayout
title: 'Azahar: El nuevo emulador de 3DS que une los mejores forks de Citra'
date: '2025-03-15'
author: content/data/person1.json
excerpt: >-
  Descubre Azahar, el emulador que fusiona los forks más avanzados de Citra
  (PabloMK7 y Lime3DS) para ofrecer más rendimiento, compatibilidad y una nueva
  base para la emulación de Nintendo 3DS.
featuredImage:
  type: ImageBlock
  url: /images/Citron-0.6-miniatura.webp
  altText: Citron 0.6 Ya Está Aquí
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
    hoverEffect: shadow-plus-move-up
    styles:
      self:
        justifyContent: center
slug: /azahar-emulador-3ds-sucesor-de-citra
isFeatured: false
isDraft: false
seo:
  type: Seo
  metaTitle: 'Azahar: El nuevo emulador de 3DS que une los mejores forks de Citra'
  metaDescription: >-
    Azahar es el nuevo emulador de Nintendo 3DS que toma lo mejor de los forks
    PabloMK7 y Lime3DS para crear una plataforma más rápida, estable y moderna.
    Con mejoras en rendimiento, cambios en el formato de archivos y optimización
    para Android, es el candidato perfecto para convertirse en la próxima gran
    alternativa a Citra. Conoce sus novedades y cómo ayudar a que llegue a la
    versión estable.
  addTitleSuffix: true
  socialImage: /images/Citron-0.6-miniatura.webp
  metaTags: []
colors: bg-dark-fg-light
styles:
  self:
    flexDirection: col
    textAlign: center
    borderRadius: large
---
El mundo de la emulación de Nintendo 3DS recibe un nuevo capítulo con el lanzamiento candidato de [**Azahar**](https://azahar-emu.org/), la esperada fusión de los populares forks [**PabloMK7**](https://github.com/PabloMK7/citra) y **Lime3DS**. Aunque aún está en fase de prueba, este prelanzamiento promete sentar las bases para un emulador más estable, eficiente y preparado para el futuro. ¡Vamos a desglosar qué hace tan especial a Azahar!

![](/images/azahar-logo.webp)

## 🌟 ¿Qué es Azahar y por qué es tan importante?

Azahar no es solo otro fork más de **Citra**. Es la evolución directa de dos de los forks más avanzados y queridos por la comunidad: **PabloMK7** (conocido por sus mejoras en rendimiento y compatibilidad) y **Lime3DS** (destacado por sus optimizaciones gráficas y estabilidad en Android). La meta principal de esta primera versión no es introducir cientos de nuevas funciones, sino construir una base sólida para futuras actualizaciones.

Este lanzamiento es un **Release Candidate** —es decir, un candidato a versión estable— que, si supera las pruebas de la comunidad sin errores graves, se convertirá en la primera versión oficial de Azahar. ¡Tu participación probando esta versión es clave para lograrlo!

![](/images/azahar-release-candidate-1.webp)

## 🔥 Novedades y cambios principales

### 🚀 Adiós a los métodos antiguos: Bienvenido Artic Setup Tool

*   El sistema para adquirir archivos esenciales de la 3DS ha sido renovado. Ahora es obligatorio tener una consola real y usar la **nueva herramienta** [**Artic Setup Tool**](https://github.com/azahar-emu/ArticSetupTool).

*   Se eliminaron los métodos antiguos de adquisición de archivos por seguridad y compatibilidad.

### 🎮 Mayor rendimiento y nuevas opciones

*   **Hack de rendimiento "Disable Right Eye Rendering"**: Desactiva el renderizado del ojo derecho (cuando el 3D no está en uso), aumentando el rendimiento hasta un **50%** en algunos juegos. ¡Eso sí, algunos títulos podrían mostrar glitches gráficos con esta opción!

*   **Modo LLE para funciones en línea**: Se añadió una opción para activar todos los módulos LLE necesarios para funcionalidad online.

### 🔒 Cambios en la gestión de archivos

*   **Adiós al formato .3ds**: Por razones técnicas y de compatibilidad, Azahar ahora usa **.cci** (el verdadero formato detrás de los archivos .3ds). ¿Tienes ROMs en .3ds? Solo necesitas **renombrarlas a .cci** y seguir jugando.

*   **Soporte para apps cifradas eliminado**: Ahora las aplicaciones deben estar en formato **descifrado**.

### 🛠️ Mejoras técnicas

*   **Dirección MAC virtual aleatoria**: Cada emulación genera una MAC diferente, mejorando la privacidad.

*   **Tema adaptativo en escritorio**: Ahora los íconos cambian a blanco cuando se usa el modo oscuro.

*   **Arranque más rápido en Android**: Se mejoró la carga de juegos y se redujeron los tirones.

## 🧠 ¿Por qué deberías probar esta versión?

Aunque no es una versión estable, esta build es crucial para el futuro de Azahar. Probarla ayuda a detectar errores y acelerar la llegada de una versión final más pulida. Si encuentras algún fallo, puedes **reportarlo directamente en su GitHub**.

Si prefieres esperar a la versión estable y no lidiar con posibles errores menores, también es válido. Pero si eres de los que les gusta estar a la vanguardia y ayudar a la comunidad, este es el momento perfecto para dar el salto a Azahar.

![](/images/Azahar-version.webp)

✨ **Azahar promete convertirse en el nuevo referente de la emulación de 3DS**. ¿Te unes a la revolución? 🎮



## ⬇️DESCARGA AZAHAR 

Recuerda que para conseguir este emulador puedes ir directamente al [sitio oficial de github](https://github.com/azahar-emu/azahar/releases/tag/2120-rc1)



O con los siguientes enlaces directos:

[Android](https://github.com/azahar-emu/azahar/releases/download/2120-rc1/azahar-2120-rc1-android-universal.apk)

[Linux (Appimage)](https://github.com/azahar-emu/azahar/releases/download/2120-rc1/azahar-2120-rc1-linux-appimage.tar.gz)

[MacOS](https://github.com/azahar-emu/azahar/releases/download/2120-rc1/azahar-2120-rc1-macos-universal.zip)

[Windows](https://github.com/azahar-emu/azahar/releases/download/2120-rc1/azahar-2120-rc1-windows-msvc-installer.exe)
