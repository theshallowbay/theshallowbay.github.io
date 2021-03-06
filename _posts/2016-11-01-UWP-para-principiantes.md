---
layout: post
title: Plataforma Universal de Windows (UWP) para principiantes
date: 2016-11-01 12:32:18
summary: La eterna promesa de la convergencia por fin se está haciendo realidad (pasito a pasito). Antes de empezar a publicar cosas por aquí, debemos dejar claro la naturaleza de las mismas. Universal Windows Platform es el cimiento fundamental sobre el cual haremos todo lo demás. Vamos a explicar como empezar, así que manos a la obra. Sinceramente esperamos que esto sea el inicio de la motivación para realizar tus metas.
categories: UWP
---

La Plataforma Universal de Windows (UWP para los amigos) es el término utilizado para describir el conjunto de herramientas y APIs que permiten construir aplicaciones que pueden correr universalmente en cualquier dispositivo con Windows.

Lo bello de todo esto es que puedes escribir código una sola vez y luego verlo bien en todas las distintas resoluciones y factores de forma que ofrecen estos dispositivos.

![UWP](https://i-msdn.sec.s-msft.com/en-us/windows/uwp/layout/images/1894834-hig-device-primer-01-500.png)

## Antes de empezar

Es importante recalcar que vamos a tratar de hacerlo todo de la forma más sencilla de entender incluso para los principiantes. Por lo menos, debes tener conocimientos en 4 aspectos fundamentales:

 - C#, el lenguaje de programación usado en el *code-behind*
 - XAML, el lenguaje de marcado usado para diseñar la *Interfaz de Usuario (UI)*
 - Visual Studio
 - Inglés, sí, la lengua extranjera

No es necesario ser un experto en todo lo anterior, simplemente necesitas tener nociones básicas. Allá afuera hay muchos y mejores recursos para aprenderlos, sin embargo haremos una recopilación de los más destacados.

## Inglés
Sí, tal vez sea lo más importante de la lista. **Debes** saber inglés antes de todo lo demás. A estas alturas del paseo ya debiste pasar por mínimo 10 años de cursos de inglés en el colegio. La gran mayoría de documentación y las mejores guías de programación estarán en ese idioma, por lo que es fundamental conocerlo. Si eres de los que se les dificulta el idioma, hay muchísimos recursos disponibles allá afuera a los que puedes acceder totalmente gratis. Es solo cuestión de perseverancia por aprender. En un post futuro hablaremos de cómo mejorar las técnicas de aprendizaje de esta lengua.

##  'C#'

Los siguientes tutoriales te enseñarán lo básico en la programación con C#, además de algunos otros conceptos avanzados relacionados a este lenguaje.

 - [**C# fundamental for absolute beginners**](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Lvld4EQIC_2706218949) (MVA, en inglés). Dictado por el mismísimo [Bob Tabor](https://twitter.com/bobtabor), uno de los mejores evangelistas que te enseñará las cuestiones fundamentales de la programación con este lenguaje. Son 8 horas de vídeo a través de 24 módulos. Tiene subtítulos en inglés, por lo que si tienes problemas con el *listening* siempre puedes optar por el *reading* a la vez que mejoras tu inglés.
 - [**Curso de Visual C# 2012**](https://www.youtube.com/playlist?list=PLEtcGQaT56chI8fDX4d2spoaJYfPWEO-k) (Youtube). Dictado por Jesús Conde. Aunque ya tiene un par de años, sigue siendo vigente y muy recomendado. De hecho, muchos conceptos importantísimos lo entendimos gracias a este curso. Son 24 vídeos con una duración de entre 30 a 50 minutos cada uno. Su canal de Youtube tiene un montón de cursos más donde enseña otros lenguajes.
 - [**Jump Start de programación en C#**](https://mva.microsoft.com/es-es/training-courses/jump-start-de-programacin-en-c-14254?l=7Apxu5LkB_3100115888) (MVA, con subtítulos en español). Para usuarios de nivel intermedio que ya sepan programación en otro lenguaje. Presentado por Jerry Nixon y Daren May, ofrecen varios ejemplos para mostrarte técnicas sencillas y complejas. se adapta a desarrolladores de experiencia media a experimentados que buscan mejorar en C# o que buscan repasar los conceptos y características básicos.

## XAML
 Este lenguaje de marcado es fundamental para el desarrollo en UWP. Con XAML se crean las interfaces de las aplicaciones.

 - [**Windows 10 Development for absolute beginners**](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=cWn0dxwqB_4305632527) (MVA, en inglés). Otra vez Bob Tabor. Este curso se explica cómo empezar en el desarrollo de aplicaciones universales, pero primero hace una parada importante en explicar en qué consiste XAML, por lo que una vez hayas aprendido C# puedes continuar por aquí.

## UWP
Es una arquitectura de aplicación común. Cuando construyes una aplicación sobre este *framework* debes saber que puedes hacerla correr en múltiples dispositivos con diferentes factores de forma y modalidades de entrada.

![UWP](https://i-msdn.sec.s-msft.com/es-es/windows/uwp/get-started/images/universalapps-overview.png)

 - [**Building Blocks: Universal Windows Platform**](https://mva.microsoft.com/en-US/training-courses/building-blocks-universal-windows-platform-16064?l=DsmNM1kDC_206218949) (MVA, en inglés). Este es el punto de inicio ideal. Presentado por el popular Jerry Nixon y Chris Harrison, explican los fundamentos de UWP. Explora qué es UWP y lo que eso significa, mira cómo diseñar una aplicación en UWP, conoce las herramientas disponibles y empieza a escribir código en Visual Studio.
 - [**Developing Universal Windows Apps with C# and XAML**](https://mva.microsoft.com/en-US/training-courses/developing-universal-windows-apps-with-c-and-xaml-8363?l=8pXSyBGz_3904984382) (MVA, en inglés). Dictada por Jerry Nixon y Daren May. Aprende directamente de los expertos de Microsoft. Explora una amplia gama de características cubriendo escenarios que van desde el consumidor final hasta el de la empresa.
 - [**A Developer's Guide to Windows 10**](https://mva.microsoft.com/en-US/training-courses/a-developers-guide-to-windows-10-12618?l=IV8HDBpRB_9005095281) (MVA, en inglés). Con Windows 10 se le facilita la vida al desarrollador. Mira lo fácil que es crear experiencias de usuario fantásticas y adaptadas a un amplio rango de dispositivos. Presentado por Andy Wigley y Shen Chauhan.

## Manos a la obra
Esperamos que te sirvan de ayuda todos estos cursos. Puedes empezar cuando quieras, debes organizar tu tiempo y dedicarle por lo menos una hora al día. Lleva un cuaderno o agenda donde vayas anotando lo más importante. No te agobies si sientes que no vas avanzando a buen ritmo, esto es de coger práctica y eso no se hace de la noche a la mañana. Una vez logres entenderlo, verás que puedes aprender lo que quieras y el límite será tu imaginación.

Tenemos en el horno unos *posts* de las aplicaciones que estamos preparando para un futuro cercano, manténte informado.

Comparte tu opinión en la sección de comentarios, dinos qué opinas del tema y si conoces otros recursos que también puedan servir de ayuda, compartelos. 

Happy coding!


