## Diseña una Cancha de Baloncesto NBA desde Cero

Ha llegado el momento que estábamos esperando. Dejar atrás la teoría y poner manos a la obra con un proyecto real, paso a paso. Vamos a crear una ilustración de una cancha de baloncesto de la NBA, aplicando todo lo aprendido: composición, manejo de vectores en Inkscape, retoque en GIMP, uso de paletas de color, y principios de jerarquía visual.

![cancha_baloncesto.png](../../src/clase_practica/01_Nba-quiz-image.png)

Este ejercicio te llevará de la mano desde el primer trazo hasta el último detalle. No importa si es tu primera vez; sigue cada paso con calma y todo saldrá.

---

### 1. Inspiración y Referencias

Antes de empezar, recuerda lo que vimos en sesiones anteriores: **Behance** y **Pinterest** son tus mejores aliados para inspirarte. Busca "ilustración cancha baloncesto", "NBA court design", "minimalist basketball court". Fíjate en cómo otros diseñadores han resuelto la composición, los colores, las líneas. Toma notas mentales, pero no copies; crea tu propia versión.

![cancha_baloncesto.png](../../src/clase_practica/02_behance.jpg)

Nuestra meta: una ilustración simple, limpia, con una paleta de tres colores, que podría usarse como fondo de pantalla, publicación en redes o parte de un portafolio.

---

### 2. Configuración Inicial en Inkscape

Abre Inkscape. Verás la ventana de bienvenida. Vamos a crear un documento nuevo con las siguientes características:

- **Ancho:** 1080 píxeles
- **Alto:** 1920 píxeles (formato vertical, ideal para Stories o posters)
- **Unidades:** píxeles
- **DPI:** 72 (para pantalla)

![cancha_baloncesto.png](../../src/clase_practica/03_config_bienvenida.png)

Al hacer clic en "Aceptar", tendrás un lienzo en blanco de 1080x1920. Asegúrate de que la página esté visible (puedes ver el borde con sombra). Esto será nuestro encuadre final.

ve al menu archivo -> propiedades del documento y configura el tamaño de la pagina a 1080x1920 y 72 dpi, en unidades selecciona px

![cancha_baloncesto.png](../../src/clase_practica/04_archivo-propiedades_documento.png)

![cancha_baloncesto.png](../../src/clase_practica/05_orientacion_vertical.png)

cierra la ventana de propiedades

![cancha_baloncesto.png](../../src/clase_practica/06_lienzo_configurado.png)

---

### 3. Trazado de la Cancha: Figuras Básicas

La cancha de baloncesto está compuesta por rectángulos, círculos y líneas. Iremos construyéndola pieza por pieza.

**a) Rectángulo exterior de la cancha**

- Dibuja un rectángulo que ocupe la mayor parte del lienzo, dejando márgenes superior e inferior. No importa que no sea perfecto; lo ajustaremos después.

- Selecciona la herramienta **Rectángulo (R)** .
  ![cancha_baloncesto.png](../../src/clase_practica/07_rectangulo.png)
- En la barra de control superior, elige:
  - **Relleno:** transparente (icono de cuadrado blanco con línea roja)

    ![cancha_baloncesto.png](../../src/clase_practica/08_relleno.png)

  - **Trazo:** negro
    ![cancha_baloncesto.png](../../src/clase_practica/09_trazado_negro.png)

  - **Grosor del trazo:** 15 píxeles
    ![cancha_baloncesto.png](../../src/clase_practica/10_grosor_trazado.png)

  - Alineamos el rectangulo al centro de la pagina, ve al panel de alinear y distribuir y selecciona centrar en el eje horizontal y vertical asegurate que este marcada la opcion relativo a pagina

    ![cancha_baloncesto.png](../../src/clase_practica/11_alineacion_rectangulo.png)

    si no encuentras el panel de alinear y distribuir ve al menu objeto -> alinear y distribuir

    ![cancha_baloncesto.png](../../src/clase_practica/12_menu_objeto-alinear_distribuir.png)

**b) Círculo central**

- Herramienta **Elipse (F5)** .
- Dibuja un círculo (mantén **Ctrl** mientras arrastras para que sea perfecto).
  ![cancha_baloncesto.png](../../src/clase_practica/13_crear_circulo.png)
- En el panel derecho, busca la pestaña **"Alinear y distribuir"** (si no aparece, actívala en `Objeto → Alinear y distribuir` o presiona **Ctrl + Mayús + A**).
- En el panel, asegúrate de que en la lista desplegable esté seleccionado **"Relativo a: Página"**.
- Haz clic en **"Centrar en el eje horizontal"** y luego en **"Centrar en el eje vertical"**. El círculo quedará exactamente en el centro del lienzo.

![cancha_baloncesto.png](../../src/clase_practica/14_alineacion_circulo.png)

**c) Línea divisoria central**

- Herramienta **Pluma (B)** .
- Mantén presionada la tecla **Ctrl** para restringir el ángulo a 0° (línea horizontal perfecta).
- Haz clic en el borde izquierdo del rectángulo y luego en el borde derecho doble clic para finalizar el trazado, a la misma altura del centro (aproximadamente donde está el círculo). Aparecerá una línea recta.
  ![cancha_baloncesto.png](../../src/clase_practica/15_linea_mitad_cancha.png)
- Con la línea seleccionada, vuelve al panel **Alinear y distribuir** y alínea al centro horizontal y vertical (esto la dejará justo en la mitad de la cancha).

![cancha_baloncesto.png](../../src/clase_practica/16_alinear_recta.png)

**d) Semicírculo superior (área de tiro libre)**

- Duplica el círculo central: selecciona el círculo y presiona **Ctrl + D**.
- Arrastra la copia hacia abajo, fuera del rectángulo principal (no importa si se sale del lienzo; luego lo ajustaremos).
  ![cancha_baloncesto.png](../../src/clase_practica/17_duplicado_circulo_central.png)
- Con la copia seleccionada, activa la herramienta **Nodo (F2)** .
  ![cancha_baloncesto.png](../../src/clase_practica/18_herramienta_nodo_circulo.png)
- Verás cuatro nodos en el círculo. Haz clic en el nodo izquierdo y arrástralo hacia el centro del círculo. Dependiendo de la dirección, obtendrás un arco. El objetivo es crear un semicírculo (medio círculo) que servirá como la línea de tiro libre.

![cancha_baloncesto.png](../../src/clase_practica/19_arco.png)

- para voltear el semicirculo hacia arriba usamos la herramienta de seleccion y giramos el semicirculo 180 grados en el panel superior usamos la opcion reflejar objetos verticalmente

![cancha_baloncesto.png](../../src/clase_practica/20_voltear_semicirculo.png)

**e) Rectángulo del área restringida**

- Vuelve a la herramienta **Rectángulo (R)** .
- Dibuja un rectángulo alargado y estrecho, justo debajo del semicírculo, de modo que se conecten visualmente.
  ![cancha_baloncesto.png](../../src/clase_practica/21_rectangulo_area.png)
- Con la ayuda del panel **Alinear**, centra este rectángulo horizontalmente (relativo a la página). Ajusta su posición vertical para que quede pegado al semicírculo.

![cancha_baloncesto.png](../../src/clase_practica/22_alinear_area_tiro.png)

**f) Semicírculo grande (área de tres puntos)**

- Duplica el semicírculo que acabas de crear (**Ctrl + D**).
- Necesitamos hacerlo más grande. Con la copia seleccionada, mantén presionadas las teclas **Ctrl + Shift** y arrastra desde la esquina inferior derecha (o desde el controlador de escala). Esto escalará el objeto de forma uniforme desde el centro.

![cancha_baloncesto.png](../../src/clase_practica/23_escalar_ctrl_shift.png)

- Agrándalo hasta que su arco sobrepase los límites del lienzo. No te preocupes, solo queremos la parte que se ve dentro de la cancha.

al escalarlo el grosor del trazado tambien aumenta por lo que necesitamos ajustar el grosor del trazado a 15 pixeles

![cancha_baloncesto.png](../../src/clase_practica/24_escalado_semicirculo.png)

**g) Ajuste del semicírculo grande al borde de la cancha**

- Con el semicírculo grande seleccionado, ve al menú **Trazado → Objeto a trazado** (esto convierte el arco en un trazado editable).

![cancha_baloncesto.png](../../src/clase_practica/25_convertir_trazado.png)

- Activa la herramienta **Nodo (F2)** .
- Verás los nodos del arco. Necesitamos cortar la parte que sobra fuera de la cancha. Para ello:
  - Añade un nodo en el punto exacto donde el arco se encuentra con el borde lateral de la cancha

![cancha_baloncesto.png](../../src/clase_practica/26_añadir_nodos.png)

- Selecciona los nodos que están fuera del rectángulo y elimínalos (selecciona y presiona **Supr**).
- Repite en el otro lado. El resultado será un arco limpio que termina justo en los bordes de la cancha.

![cancha_baloncesto.png](../../src/clase_practica/27_borrar_nodos.png)

![cancha_baloncesto.png](../../src/clase_practica/28_resultado_borrar_nodo.png)

---

### 4. Completar la Mitad Inferior

Ya tienes todos los elementos de la mitad inferior de la cancha. Agrupa estos objetos, usa la herramienta de seleccion y la tecla shift para seleccionar varios objetos, para facilitar su manejo: selecciona todos y presiona **Ctrl + G**.

![cancha_baloncesto.png](../../src/clase_practica/29_agrupar.png)

---

### 5. Crear la Mitad Superior por Simetría

Ahora vamos a generar la otra mitad de forma rápida y simétrica.

- Selecciona el grupo de la mitad inferior.
- Duplícalo (**Ctrl + D**).

![cancha_baloncesto.png](../../src/clase_practica/30_duplicado_grupo.png)

- Con el duplicado seleccionado, activa la herramienta de **Rotación** (haciendo clic nuevamente sobre el objeto; verás que las flechas cambian a rotación).
- Gira el grupo 180 grados. Puedes hacerlo manualmente con el ratón manteniendo **Ctrl** para ángulos fijos, o en la barra superior, en el campo de ángulo, escribe 180.
- Coloca esta copia en la parte superior del lienzo,

![cancha_baloncesto.png](../../src/clase_practica/31_voltear_grupo.png)

![cancha_baloncesto.png](../../src/clase_practica/32_volteado_grupo.png)

alineándola con el centro. Usa las teclas de flecha o el panel **Alinear** para centrarla horizontalmente.

![cancha_baloncesto.png](../../src/clase_practica/33_alinear_pagina.png)

¡Ya tienes la estructura completa de la cancha!

---

### 6. Aplicar Color a la Cancha

Vamos a usar una paleta de tres colores, inspirada en la NBA. Aquí están los códigos exactos:

| Color                         | Hex       | RGB               | HSL                |
| ----------------------------- | --------- | ----------------- | ------------------ |
| Azul oscuro (fondo de cancha) | `#1D428A` | rgb(29, 66, 138)  | hsl(220, 65%, 33%) |
| Azul claro (detalles)         | `#1A70DF` | rgb(26, 112, 223) | hsl(214, 79%, 49%) |
| Rojo (acentos)                | `#C8102E` | rgb(200, 16, 46)  | hsl(350, 85%, 42%) |

**a) Crear muestras de color (opcional)**

Dibuja tres pequeños rectángulos con la herramienta Rectángulo y asígnales estos colores de relleno. Así tendrás una paleta visual en el lienzo para usar con el cuentagotas.

![cancha_baloncesto.png](../../src/clase_practica/34_paleta_color.png)

**b) Colorear las formas**

no olvides desagrupar las formas para poder aplicar los colores

Selecciona cada elemento y aplica los colores en el panel de **Relleno y trazo** (**Ctrl + Mayús + F**):

- **Círculo central:** Rojo (`#C8102E`).
- **Semicírculos (áreas de tiro libre y tres puntos):** Azul oscuro (`#1D428A`).
- **Rectángulos de la zona restringida:** Rojo (`#C8102E`).
- **Fondo del rectángulo grande de la cancha:** Azul claro (`#1A70DF`).

![cancha_baloncesto.png](../../src/clase_practica/35_cuentagotas.png)

Recuerda que el relleno se aplica en la pestaña "Relleno". El trazo lo dejaremos en negro por ahora.

![cancha_baloncesto.png](../../src/clase_practica/36_coloreado.png)

**c) Cambiar el color del trazo a blanco**

Selecciona todos los elementos (puedes hacer **Ctrl + A** o selección a mano). En el panel **Relleno y trazo**, ve a la pestaña **"Trazo"** y cambia el color a **blanco**. Ajusta el grosor si es necesario (5-6 píxeles queda bien). Esto hará que las líneas resalten sobre los colores vibrantes.

![cancha_baloncesto.png](../../src/clase_practica/37_color_trazado_blanco.png)

---

### 7. Exportar desde Inkscape (SVG)

Antes de exportar, asegúrate de que la página (el lienzo) contenga solo la cancha y que los elementos auxiliares (como la paleta de colores) estén fuera del área de la página o en otra capa. En Inkscape, la "página" es el rectángulo que define el área de exportación.

- Ve al menú **Archivo → Guardar como...**.
- Elige formato **SVG estándar de Inkscape** (recomendado) o **SVG optimizado** si prefieres.
- Nómbralo, por ejemplo, `cancha_base.svg`.

![cancha_baloncesto.png](../../src/clase_practica/38_archivo-guardar_como.png)

![cancha_baloncesto.png](../../src/clase_practica/39_guardar_como.png)

![cancha_baloncesto.png](../../src/clase_practica/40_formato_svg.png)

Guarda el archivo. Este SVG lo usaremos en GIMP.

---

### 8. Abrir y Ajustar en GIMP

Ahora pasamos a GIMP para los toques finales.

- Abre GIMP.
- Crea un nuevo documento con las mismas dimensiones: **1080 x 1920 píxeles, 72 DPI**.
  ve a menu archivo -> nuevo

![cancha_baloncesto.png](../../src/clase_practica/41_archivo-nuevo.png)

![cancha_baloncesto.png](../../src/clase_practica/42_config_nuevo.png)

- Ve a **Archivo → Abrir como capas...** y selecciona el archivo `cancha_base.svg`. Aparecerá un cuadro de diálogo con opciones de importación. Acepta las que vienen por defecto. La cancha se importará como una nueva capa.

![cancha_baloncesto.png](../../src/clase_practica/43_abrir_como_capas.png)

![cancha_baloncesto.png](../../src/clase_practica/44_abrir_svg.png)

![cancha_baloncesto.png](../../src/clase_practica/45_opciones_por_defecto.png)

**a) Transformación de perspectiva (opcional)**

Para darle dinamismo, vamos a inclinar ligeramente la cancha como si la viéramos en perspectiva.

- Selecciona la capa de la cancha.
- Herramienta **Transformación combinada** (icono de cuatro flechas con cuadrados, atajo **Mayús + T**). Si no la ves, busca en el grupo de transformación.

![cancha_baloncesto.png](../../src/clase_practica/46_transformacion_combinada.png)

- En las opciones de herramienta (abajo a la izquierda), elige **"Perspectiva"**.
- Aparecerán tiradores en las esquinas de la capa. Arrastra las esquinas superiores ligeramente hacia adentro o hacia afuera para crear un efecto de perspectiva. No exageres; solo un toque para dar sensación de profundidad.
- Pulsa **Enter** para confirmar.

![cancha_baloncesto.png](../../src/clase_practica/47_transformacion_prespectiva.png)

**b) Rellenar el fondo**

- Añade una nueva capa debajo de la cancha (puedes llamarla "Fondo").
- Con la herramienta **Cubeta de pintura** (atajo **Mayús + B**), elige un color neutro (por ejemplo, un gris oscuro o el mismo azul oscuro pero más opaco) y rellena la capa.

![cancha_baloncesto.png](../../src/clase_practica/48_relleno_fondo.png)

**c) Importar elementos adicionales**

En los recursos compartidos (en la carpeta `examples` del GitLab) hay vectores de un balón de baloncesto y un logotipo de la NBA. Vamos a importarlos como capas:

- **Archivo → Abrir como capas...** y selecciona el archivo del balón.
- Repite para el logotipo.
- Usa la herramienta **Escalado (Mayús + S)** para ajustar el tamaño de estos elementos y colócalos sobre la cancha con la herramienta **Mover (M)** . Por ejemplo, el balón en el centro, el logo en una esquina.

![cancha_baloncesto.png](../../src/clase_practica/50_escalar_balon.png)

![cancha_baloncesto.png](../../src/clase_practica/49_escalar_logo.png)

**d) Crear una capa a partir de lo visible**

Una vez que tengas todo en su sitio, vamos a fusionar la apariencia para aplicar efectos globales.

- En el panel de capas, haz clic derecho sobre cualquier capa y selecciona **"Nuevo a partir de lo visible"**.

![cancha_baloncesto.png](../../src/clase_practica/51_clic_derecho.png)

![cancha_baloncesto.png](../../src/clase_practica/52_nuevo_visible.png)

Esto creará una nueva capa con la composición actual fusionada (las capas originales permanecen intactas abajo).

![cancha_baloncesto.png](../../src/clase_practica/53_visible.png)

**e) Añadir ruido para textura**

Selecciona la nueva capa (la visible). Ve al menú **Filtros → Ruido → Ruido RGB...** (o simplemente **Ruido** si tienes versiones diferentes). Ajusta los valores para añadir un granulado sutil (por ejemplo, 0.150 en cada canal). Activa la vista previa para ver el efecto. Esto dará un aspecto más texturizado, como si la cancha tuviera un acabado rugoso.

![cancha_baloncesto.png](../../src/clase_practica/55_ruido_0.150.png)

**f) Sombra del balón**

Por último, para dar realismo, añade una sombra al balón.

- Crea una nueva capa (vacía) debajo de la capa del balón (o encima del fondo). Nómbrala "Sombra".
- Con la herramienta **Rutas (B)** , dibuja un trazado con forma de sombra (una elipse aplanada, en la dirección opuesta a la fuente de luz imaginaria). Puedes hacerlo a mano alzada o con la herramienta de selección elíptica y luego convertir a ruta.
- En el panel de rutas, haz clic en **"Ruta a selección"** .

![cancha_baloncesto.png](../../src/clase_practica/56_sombra_balon.png)

- Rellena la selección con negro (herramienta Cubeta).
- En el panel de capas, baja la opacidad de la capa "Sombra" a un 60 - 80%.
- Desenfoca ligeramente la sombra para que sea más real: **Filtros → Difuminar → Desenfoque gaussiano**, con un radio pequeño (5-10 píxeles).
- Ajusta la posición de la sombra con la herramienta Mover si es necesario.

![cancha_baloncesto.png](../../src/clase_practica/57_efecto_sombra.png)

![cancha_baloncesto.png](../../src/clase_practica/58_desenfoque.png)

---

### 9. Exportación Final

Ya tenemos nuestra pieza terminada. Vamos a exportarla.

- Si quieres conservar las capas por si necesitas retoques, guarda el proyecto en formato **XCF** (nativo de GIMP): **Archivo → Guardar como...**.
- Para compartir o usar en web, exporta como **PNG** o **JPG**: **Archivo → Exportar como...** (Ctrl + Mayús + E). Elige formato PNG para mantener la transparencia si la hay, o JPG con calidad 90% para un archivo más ligero.

![cancha_baloncesto.png](../../src/clase_practica/59_guardar_como.png)

---

### 🧠 Reflexión Final

Lo has logrado. Has construido una ilustración completa desde cero, utilizando Inkscape para la parte vectorial y GIMP para los acabados. En el proceso has aplicado:

- Composición y alineación (panel Alinear)
- Uso de formas básicas para crear figuras complejas
- Duplicación y rotación simétrica
- Selección de paleta de color coherente
- Transformación de perspectiva
- Importación de elementos externos
- Filtros de ruido para textura
- Creación de sombras con rutas

Este flujo de trabajo (vector + mapa de bits) es el que utilizan muchos profesionales: la precisión de los vectores para las formas, y la libertad expresiva de los píxeles para los efectos.

---

### 🚀 Tu Reto Personal

Ahora que conoces el proceso, te propongo un desafío:

**Crea tu propia versión de una cancha temática.** Puede ser de tu equipo favorito, con sus colores, o incluso de un deporte distinto (fútbol, tenis). Aplica los mismos pasos, pero varía la paleta, añade elementos decorativos (como afición, luces, etc.) y experimenta con diferentes perspectivas.

Comparte tu resultado en tu portafolio. Estoy seguro de que sorprenderás.

---
