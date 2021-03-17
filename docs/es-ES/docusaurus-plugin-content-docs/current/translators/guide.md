---
id: guide
title: Guía de traducción
sidebar_label: Guía de traducción
---

:::info
Vaya, has encontrado algo secreto :think:
:::

![Img](https://i.imgur.com/NYsAUU5.png)

## Páginas dentro de la categoría
### [Guía de traducción](guide.md).
### [Pautas de traducción](guidelines.md).

# Guía de traducción

Bienvenid@ a la guía de traducción para traductores, aquí estará explicada la plataforma de traducción que usamos, cómo traducir y cosas a tener en cuenta.

## Introducción
Estamos usando [Weblate](https://weblate.org) alojado por nosotros desde la cuál puedes acceder desde [weblate.discordsafe.com](https://weblate.discordsafe.com), esta ofrece una gran cantidad de ventajas para mantener la traducción estable y limpia, **échale un ojo a su propia [guía](https://docs.weblate.org/es/latest/user/translating.html) sobre cómo traducir si quieres conocer más.**

### Como funciona
Tú traduces una cadena y dejas la sugerencia, los coordinadores o administradores se encargar de revisarlas y decidir la mejor y si son aprobadas se envían al proyecto del código fuente donde ya estarán disponibles en las próximas versiones.

## Tener en cuenta
* Al traduccir aceptas el siguiente **[acuerdo](https://weblate.discordsafe.com/contributor-agreement/d-safe/commands/)**.
* Debes seguir las siguientes **[pautas de traducción](guidelines.md)**.

## Gestión del proyecto y componentes
Accediendo a la [página del proyecto](https://weblate.discordsafe.com/projects/d-safe/) podrás ver los componentes, es decir los distintos archivos de traducción del bot.

Están divididos en lo siguiente:
* `Commands`, respuestas de los comandos.
* `Common`, textos de uso común y generales.
* `Error`, respuestas de error del bot.
* `Events`, textos de los eventos del bot.
* `Meta`, descripciones y ejemplos de los comandos.

![Img](https://i.imgur.com/qoeKFwv.png)
  
Para traducir un componente haga click y entre en él, a continuación verá lo siguiente:

![Img](https://i.imgur.com/hnxp8gS.png)

Haga click en el idioma al que desea traducir.

![Img](https://i.imgur.com/JvMkG38.png)

Se les mostrará una serie de estados:
1. Todas las cadenas, todas las cadenas.
2. Cadenas traducidas, cadenas que ya han sido traducidas.
3. Cadenas sin traducir, cadenas que necesitan traducción.
4. Cadenas con comprobaciones fallidas, cadenas que no han conseguido superar las [comprobaciones](#comprobaciones)

A continuación entre a **cadenas sin traducir** para continuar con la traducción de esas cadenas. Desde aquí podrás moverte entre las cadenas y ver mucha información.

Rellene la traducción y dele a sugerir para sugerir esa traducción y que un coordinador del idioma se encargue de aprobarlas.

![Gif](https://i.imgur.com/IpqbQHH.gif)

**Dentro de la interfaz puede ver las siguientes cosas:** Recuerda

### Menú de movimiento
Desde donde puedes moverte y filtrar las cadenas.

![Img](https://i.imgur.com/ZfgMo6n.png)

### Traducción
Desde donde puedes ver la traducción de origen y sugerir, aprovar o guardar traducciones.

![Img](https://i.imgur.com/t1ArDnz.png)

### Cadenas cercanas
Desde donde puedes ver las cadenas cercanas a esta para tal vez entender mejor el contexto de donde se usa este texto.

![Img](https://i.imgur.com/N0kGNPv.png)

### Cadenas adyacentes
Desde donde puedes ver solo las cadenas que están dentro de este comando que estás traduciendo.

![Img](https://i.imgur.com/b2aCjg6.png)

### Sugerencias
Desde aquí podrás votar, sugerir o **aprobar sugerencias si eres un coordinador**.

![Img](https://i.imgur.com/1ekp8hs.png)

### Comentarios
Desde donde puedes dejarnos comentarios sobre preguntas a los coordinadores/administradores del proyecto.

![Img](https://i.imgur.com/DMA7Zj0.png)

### Automatización
De vez en cuando si varias cadenas tienen el mismo resultado, los bots automáticos la analizarán para sugerirte cambios para que uses los mismos términos.

![Img](https://i.imgur.com/GourF4m.png)

### Otros idiomas
Desde aquí podrás ver qué traducciones han hecho el resto del equipo en otros idiomas para ver si usan un término general que debes de respetar.

![Img](https://i.imgur.com/fqDbxp7.png)

### Historial
El historias de cambios.

### Lateral
En el lateral puedes encontrar opciones o información útil también, además **del modo zen para mejorar tu concentración o productividad**.

![Img](https://i.imgur.com/e99LX9q.png)

## Comprobaciones
Automáticamente los bots hacen comprobaciones en las cadenas para asegurar un buen ambiente de traducción, así te suele aparecer e informar de las comprobaciones que no se cumplen para que las arregles y sigas.

### Variables
Dentro de las traducciones te encontrarás con el contenido dentro de **{{ }}** resaltado, esto indica que debes dejar eso exactamente igual que en el origen ya que de cambiarlo seguramente rompas algo.

### Saltos de línea
Los saltos de línea con el siguiente ícono indica que el texto baja una línea y estos debes respetarlos.

![Img](https://i.imgur.com/4cUJLFV.gif)

