---
type: PostLayout
title: 'Citron 0.5: La Nueva Versión del Emulador de Nintendo Switch Ya Está Aquí'
date: '2025-02-25'
author: content/data/person1.json
excerpt: >-
  El 21 de febrero de 2025, el equipo de desarrollo de Citrón lanzó la versión
  0.5, una actualización repleta de mejoras en gráficos, rendimiento,
  compatibilidad y nuevas funciones. 
featuredImage:
  type: ImageBlock
  url: /images/nuevo-citron-0.5.webp
  altText: Citron 0.5 Ya Está Aquí
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
      text: Consulta la Guía
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: Guía Aun No Disponible
    text: >
      *En cuanto tengamos la guia visual disponible estará aqui publicada, por
      mientras disfruta del ultimo video de Citron.*
    actions: []
    media:
      type: VideoBlock
      title: Citron En Steam Deck 2025
      url: 'https://youtu.be/IwjPTUgB_OQ'
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
    hoverEffect: shadow-plus-move-up
    styles:
      self:
        justifyContent: center
slug: /citron-0.5-ya-disponible
isFeatured: false
isDraft: false
seo:
  type: Seo
  metaTitle: >-
    Citrón 0.5: La Nueva Actualización del Emulador de Nintendo Switch Llega con
    Mejoras Clave
  metaDescription: "El emulador Citrón 0.5 ya está disponible, con mejoras en gráficos, rendimiento y compatibilidad. Ahora con soporte para el Home Menu, optimización en Vulkan y nuevas funciones de red. Descubre todas las novedades de esta versión y cómo mejorar tu experiencia de emulación. \U0001F680\U0001F3AE"
  addTitleSuffix: true
  socialImage: /images/nuevo-citron-0.5.webp
  metaTags: []
colors: bg-dark-fg-light
styles:
  self:
    flexDirection: col
    textAlign: center
    borderRadius: large
---
El **21 de febrero de 2025**, el equipo de desarrollo de **Citrón** lanzó la versión **0.5**, una actualización repleta de mejoras en gráficos, rendimiento, compatibilidad y nuevas funciones. Si eres fanático de la emulación en **PC y Android**, esta versión trae avances significativos que mejorarán la experiencia al ejecutar juegos de **Nintendo Switch**.

A continuación, te contamos **todas las novedades** de esta versión.

## **Principales Mejoras de Citrón 0.5**

### **Gráficos y Renderizado**

*   **Mejoras en Vulkan**: Implementación de resolución MSAA nativa en la caché de texturas.

*   **Compatibilidad mejorada**: Correcciones para los drivers de Samsung, AMD y Qualcomm.

*   **Mejor conversión de formatos de texturas** para mejorar la fidelidad visual.

### **Interfaz y Funcionalidades**

*   **Soporte para el Home Menu**: Ahora puedes abrir el menú principal de la consola dentro del emulador.

*   **Gestión mejorada de pantallas y capas**.

*   **Overlay de uso de RAM** y mejoras en la visualización térmica.

*   **Nuevo logo de Citrón** en el menú "Acerca de".

*   **Eliminado el aviso de desencriptación de firmware**.

### **Seguridad y Gestión de Memoria**

*   **Verificación de licencia** en la aplicación de Android.

*   **Mejor seguridad en la asignación de memoria** y validación en la memoria del host.

*   **Correcciones en accesos no autorizados a la memoria** para mayor estabilidad.

### **Mejoras Técnicas**

*   **Implementaciones en NVDRV Service** para mejor compatibilidad con GPU.

*   **Limpieza en la implementación del sistema de audio**.

*   **Soporte para nuevos comandos en la API de sonido y mejoras en estabilidad**.

### **Red y Funciones Online**

*   **Optimización del manejo de interfaces de red**.

*   **Soporte mejorado para resolución de direcciones IP**.

*   **Nuevas funciones en los servicios de amigos de Nintendo**.

### **Rendimiento y Compatibilidad**

*   **Android**:

    *   Desactivado el overlay de RAM por defecto (tenía errores).

    *   Primera solución para el bug de **0.0 FPS** en algunos dispositivos.

*   **Actualización de dependencias**:

    *   Qt 6.8.2, fmt y SDL2 actualizados.

    *   Mejor gestión de compilación y dependencias.

### **Mejoras en Servicios**

*   **Integración con cuentas de Nintendo**.

*   **Validación de permisos mejorada**.

*   **Optimización en la gestión de configuraciones y servicios del emulador**.

## **Notas de Instalación**

*   Se recomienda una **instalación limpia** al actualizar desde versiones anteriores.

*   **Usuarios de Android** deben verificar la compatibilidad con su dispositivo.

*   Se han actualizado los requisitos de compilación para todas las plataformas.

## **Problemas Conocidos**

*   Algunas funciones de la GPU siguen en desarrollo.

*   Persisten regresiones gráficas en ciertos títulos.

*   Las funciones de red aún están en una etapa temprana.

*   Puede haber problemas específicos de renderizado en algunas plataformas.

*   En ciertos escenarios, podrían ocurrir violaciones de acceso a la memoria.

## **¿Qué Sigue para Citrón?**

El equipo de desarrollo ya tiene planes para las siguientes versiones, entre ellos:

*   **Mayor optimización del renderizado en GPU**.

*   **Mejoras en el soporte de red y funciones multijugador**.

*   **Más avances en la versión para Android**.

*   **Implementación de nuevos servicios** para mejorar la compatibilidad.

## **Conclusión**

Con **Citrón 0.5**, el emulador sigue evolucionando y consolidándose como una opción potente para la emulación de **Nintendo Switch**. Aunque aún hay desafíos, los avances en gráficos, rendimiento y compatibilidad muestran un futuro prometedor para este proyecto.

## **Descarga Citron 0.5**

[Android](https://git.citron-emu.org/Citron/Citron/releases/download/v0.5-canary-refresh/Citron-18f8a0f99-mainlineRelease.apk)

[Android Optimizado](https://git.citron-emu.org/Citron/Citron/releases/download/v0.5-canary-refresh/Citron-18f8a0f99-mainlineRelease_optimized.apk)

[Linux](https://git.citron-emu.org/Citron/Citron/releases/download/v0.5-canary-refresh/Citron-Linux-Canary-Refresh_0.5_compatibility.zip)

[Linux Steam Deck(Appimage)](https://git.citron-emu.org/Citron/Citron/releases/download/v0.5-canary-refresh/Citron-Linux-Canary-Refresh_0.5_steam_deck.zip)

[Windows](https://git.citron-emu.org/Citron/Citron/releases/download/v0.5-canary-refresh/Citron-Windows-Canary-Refresh_0.5.zip)



¿Ya probaste la nueva versión? ¡Cuéntanos tu experiencia en los comentarios!
