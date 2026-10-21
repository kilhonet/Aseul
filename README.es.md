# Aseul

**Herramienta gratuita para Windows que muestra de un vistazo, en la barra de tareas, cuánto has usado de Claude y Codex.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, la [versión en coreano](README.ko.md) es la que prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/aseul?lang=es)

![Pantalla de Aseul](images/aseul-en.png)

## Descripción general

Claude y Codex tienen un límite de 5 horas y un límite semanal. Seguramente alguna vez te has topado con uno en plena tarea, o has abierto una página de uso solo para ver cuánto te quedaba.

Aseul coloca un **pequeño indicador circular** en la barra de tareas, junto al reloj. Un círculo por servicio: el anillo exterior es el uso semanal y el interior, el uso de 5 horas. Cada anillo se llena en el sentido de las agujas del reloj desde las 12 a medida que lo usas, y pasa del verde al rojo conforme te acercas al límite. Con una mirada sabes si vas justo.

Haz clic en el indicador para abrir la ventana de estado con el uso exacto, el tiempo que falta para el siguiente reinicio y tu uso de los últimos 7 días. Al cerrar la ventana, el indicador sigue en la barra de tareas y se sigue actualizando.

## Funciones principales

- **Indicador circular en la barra de tareas** — un anillo doble por servicio (exterior = semanal, interior = 5 horas). El círculo de la izquierda es Claude y el de la derecha, Codex.
- **Cinco tramos de color** — cada anillo se divide en cinco tramos del 20 %: verde, verde lima, amarillo, naranja y rojo. Los tramos vacíos se ven tenues, así siempre sabes qué color viene después.
- **Actualización automática** — consulta el uso de Claude y Codex con regularidad para mantenerlo al día.
- **Cifras al pasar el ratón** — pasa el ratón por el indicador para ver una línea por servicio, como `Claude : 5% / 50%` (5 horas / semanal).
- **Ventana de estado** — barras de uso de 5 horas y semanal por servicio, con el tiempo que falta para cada reinicio.
- **Historial de 7 días** — una barra por día con el uso semanal y cuánto se usó ese día.
- **Se adapta al tema de la barra de tareas** — en una barra de tareas clara el indicador se apoya sobre un panel LED negro; en una oscura solo se ven los anillos. El cambio de tema se aplica al instante.
- **Solo los servicios que usas** — solo se dibujan círculos para los servicios con sesión iniciada. Si solo usas Codex, solo verás el círculo de Codex.
- **Ejecutar al iniciar** — se activa o desactiva desde el menú contextual. El instalador lo deja activado.
- **22 idiomas** — sigue el idioma de visualización de Windows.

## Descarga / Instalación

| Tipo | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/aseul?lang=es) |
| Portátil (ZIP) | [Descargar](https://down.kilho.net/aseul?lang=es&nosetup) |

El instalador inicia Aseul en cuanto termina y activa Ejecutar al iniciar. Para la versión portátil, descomprime el ZIP y ejecuta `Aseul.exe`.

## Uso

### Primeros pasos

1. Comprueba que has iniciado sesión en **Claude Code** o en **Codex**. Aseul lee tu uso a través de esa sesión (consulta "Requisitos" más abajo).
2. Ejecuta Aseul. Al cabo de un momento aparece un **indicador circular** en la barra de tareas, justo a la izquierda del área de notificación.
3. Mira el indicador. El anillo exterior es el uso semanal y el interior, el de 5 horas. Cuanto más lleno y más cerca del rojo, menos te queda.
4. Para ver cifras exactas, **pasa el ratón** por el indicador o **haz clic** en él para abrir la ventana de estado.
5. Cierra la ventana de estado con su botón de cerrar o con **Esc**. El indicador se queda y sigue actualizándose.

### Elementos de la pantalla

**Indicador de la barra de tareas**

| Elemento | Significado |
|---|---|
| Círculo izquierdo / derecho | Claude / Codex (solo servicios con sesión iniciada) |
| Anillo exterior | Uso semanal |
| Anillo interior | Uso de 5 horas |
| Color del anillo | 0–20 % verde, 20–40 % verde lima, 40–60 % amarillo, 60–80 % naranja, 80–100 % rojo |
| Pasar el ratón | `% de 5 horas / % semanal` por servicio |
| Clic | Abrir la ventana de estado |
| Clic derecho | Menú (tabla siguiente) |

**Menú contextual**

| Menú | Qué hace |
|---|---|
| **Abrir ventana de estado** | Abre la ventana de estado — igual que hacer clic en el indicador |
| **Ejecutar al iniciar** (casilla) | Se inicia automáticamente al iniciar sesión en Windows |
| **Creado por Kilho Oh** | Abre el sitio web |
| **Salir** | Pregunta "¿Seguro que desea salir?" y se cierra |

**Ventana de estado**

| Elemento | Significado |
|---|---|
| Nombre del servicio | Claude, Codex |
| Barras **5 h** · **Semanal** | Uso — con los mismos colores que el indicador, más intensos según se llena |
| % | Uso actual |
| **Se reinicia en …** | Tiempo que falta para que ese límite vuelva a 0 |
| Gráfico de 7 días | Aparece en su lugar al pasar el ratón por un servicio |

### Consejos para situaciones habituales

**Comprobar lo que queda antes de una tarea larga**
Pasa el ratón por el indicador para ver al instante el uso de 5 horas / semanal, como `Claude : 35% / 72%`. Si el uso semanal se acerca al tramo rojo, puedes dejar los trabajos grandes para después del reinicio.

**Saber cuándo se reinicia un límite**
Haz clic en el indicador para abrir la ventana de estado. A la derecha de las barras 5 h y Semanal verás el tiempo que falta, como **Se reinicia en 2 d 21 h**.

**Ver qué días de esta semana usaste más**
En la ventana de estado, pasa el ratón por un servicio (Claude o Codex) para mostrar el gráfico de los últimos 7 días. Hay una barra por día, con hoy a la derecha del todo. La altura de la barra es el uso semanal de ese día; la parte superior más intensa es lo que subió ese día. Pasa el ratón por una barra para ver la fecha, el uso semanal y el aumento de ese día, como `10/15(jue.) · 56% (+12%)`.

**Usar solo Claude o solo Codex**
No hay nada que configurar. Solo los servicios con sesión iniciada tienen un círculo en el indicador y una sección en la ventana de estado.

**Usar una barra de tareas clara**
Detrás del indicador aparece un panel LED negro para que los colores de los anillos se vean bien. Cambia a oscuro y el panel desaparece, dejando solo los anillos. Los cambios de tema se aplican al instante.

**Cambiar el tamaño de la barra de tareas**
Cuando cambia la altura de la barra de tareas, por ejemplo con botones pequeños o una barra de dos filas, el indicador se vuelve a dibujar al momento para ajustarse. Los círculos tienen el tamaño de un icono de la bandeja, así que se ven nítidos en monitores de alta resolución.

**Mostrar el indicador cada vez que se enciende el PC**
Clic derecho en el indicador → marca **Ejecutar al iniciar**. El instalador ya lo deja activado. Vuelve a hacer clic para desactivarlo.

**Después de volver a iniciar sesión en Claude Code o Codex**
No hay que hacer nada en Aseul. La siguiente comprobación recoge los nuevos valores y el indicador continúa. Mientras tanto, la ventana de estado muestra atenuados los últimos valores recibidos.

**Ejecutar Aseul antes de iniciar sesión**
Si no has iniciado sesión ni en Claude Code ni en Codex, Aseul muestra "No hay ninguna IA con sesión iniciada." y se cierra. Inicia sesión en cualquiera de los dos y vuelve a ejecutarlo.

**Volver a encontrar la ventana de estado**
La ventana de estado no añade su propio botón a la barra de tareas. Al hacer clic en el indicador se abre en el centro del monitor donde está el indicador, o pasa al frente si ya estaba abierta. Ejecutar Aseul una segunda vez también abre la ventana de estado en lugar de iniciar otra copia.

**Cerrar Aseul por completo**
Clic derecho en el indicador → **Salir** → **Sí**. Cerrar solo la ventana de estado no cierra el programa; el indicador se queda.

## Configuración

No hay ventana de configuración. La única opción es **Ejecutar al iniciar** en el menú contextual; todo lo demás sigue al sistema automáticamente.

| Elemento | Sigue a |
|---|---|
| Ejecutar al iniciar | Activado en el instalador, desactivado en la portátil — se cambia desde el menú contextual |
| Servicios mostrados | Servicios con sesión iniciada (Claude, Codex) |
| Aspecto del indicador | Tema claro / oscuro de la barra de tareas |
| Tamaño del indicador | Tamaño de icono de la bandeja (escala de la barra de tareas) |
| Ventana de estado | Siempre oscura |
| Idioma de la interfaz | Idioma de visualización de Windows (22 idiomas; en otro caso, inglés) |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- Debes haber iniciado sesión en **Claude Code** o en **Codex**.
  - Claude: sesión iniciada en Claude Code con una cuenta de Claude
  - Codex: sesión iniciada en Codex con una cuenta de ChatGPT (el inicio de sesión con clave de API no tiene datos de uso, así que no se muestra)
- Se necesita conexión a Internet para obtener el uso.
- No se necesita ningún runtime adicional. El instalador usa permisos de administrador solo durante la instalación.

## Actualizaciones

Aseul **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y muestra un aviso; al pulsar **Sí** se abre la página de descarga y el programa se cierra. Las nuevas versiones se publican manualmente tras una verificación interna y se anuncian en la [página de Aseul](https://kilho.net/aseul). Consulte el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

## Licencia

Aseul es **freeware**. Puede usarse en cualquier lugar —en la oficina, en casa, en organismos públicos o en la escuela— de forma gratuita y sin restricciones, y puede redistribuirse libremente.

## Enlaces

- Sitio web: <https://kilho.net/aseul>
- Foro: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
