# FB_IRRLICHT
Motor gráfico 3D para FreeBasic basado en Irrlicht ( https://irrlicht.sourceforge.io/ )

Esta compilación parte de una anterior 1.7.3 de su autor "Frank Dodd" que se actualizó a 1.8.3 en este foro:
https://www.blitzcoder.org/forum/topic.php?id=44

Y yo a su vez, he actualizado a la última version Irrlicht 1.8.5 actual.
Ademas, he actualizado la version de audio IrrKlang 1.4.0 a la última posible, la 1.6.0

Como novedad, he incluído un parámetro extra en el comando "iIrr3DAdvanced" que permite crear una ventana Windows Nativa y renderizar en ella, en lugar de la ventana gráfica por defecto. Eso permite integrar las ventanas en el entorno Windows. (ver ejemplo "14_Example_Win32_Window.bas")

Importante: el motor está compilado para el entorno x32 de windows, pero funciona en Win64
