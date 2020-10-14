# Moises_3Ds

Moises_3Ds responde a un proceso de modificación de región.Con este proceso el juego aparecerá con Región Free y, con ello, evitaremos baneos de eshop en nuestra consola 3Ds. Para la realización de este proceso podemos optar por dos vías alternativas pero complementarias que concluirán en el mismo punto:

--Vía .3Ds--

La manera .3Ds precisará de 2 programas: GabrieloRomToolsGUI y HxD.﻿

1º Paso: Tener un archivo .3ds, crear una Nueva Carpeta (podréis renombrarla) y meter el archivo en su interior.

2º Paso: Abrir el programa GabrieloRomToolsGUI. Acudir a la pestaña Extract 3ds, seleccionar el juego .3ds en la primera opción y seleccionar la Nueva Carpeta en la segunda opción. Por último, daremos a Extract! Con ello, obtendremos en la Nueva Carpeta un archivo llamado game.cxi

3ºPaso: Acudir a la pestaña Extract NCCH, seleccionar el archivo game.cxi en la primera opción y seleccionar la Nueva Carpeta en la segunda opción. Por último, daremos a Extract! Con ello, obtendremos varios archivos pero el más importante será icon.icn (ubicado en la carpeta exefs).

4º Paso: Abrir el programa HxD y arrastrar el archivo icon.icn. Acudir a la pestaña “Buscar” y seleccionar la opción “Ir a…”. En “Posición” escribiremos 2018 y le daremos a “Aceptar”. A continuación, modificaremos el serial por FF FF FF 07. Acudiremos a la pestaña “Archivo” y seleccionaremos la opción “Guardar”. Con ello, obtendremos: el archivo icon.icn (el editado) y el archivo icon.icn.bak (deberemos sacarlo de la carpeta exefs o eliminarlo).

5º Paso: Acudir a la pestaña Rebuild NCCH dentro de GabrieloRomToolsGUI. Seleccionar la Nueva Carpeta en la tercera opción y dar a Rebuild. Con ello, obtendremos el archivo edited.cxi.

6.1º Paso (.cxi a .cia): Acudir a la pestaña Cia tools y seleccionar la Nueva Carpeta en la primera opción. Acto seguido, presionar el botón Add, escribir edited.cxi y darle a Aceptar. Por último, le daremos a Rebuild! Con ello, obtendremos el archivo example.cia (podéis renombrarlo).

6.2º Paso (.cxi a .3ds): Acudir a la pestaña Rebuild 3ds y seleccionar la Nueva Carpeta en la primera opción. Acto seguido, presionar el botón Add, escribir edited.cxi y darle a Aceptar. Por último, le daremos a Rebuild! Con ello, obtendremos el archivo example.3ds (podéis renombrarlo).

7.1º Paso: Comprobar que la región del juego.cia es Región Free mediante el uso del FBI.

7.2º Paso: Comprobar que la región del juego.3ds es Región Free mediante el uso de Citra.

--Vía .cia--

La manera .cia precisará de 3 programas: GodMode9, GabrieloRomToolsGUI y HxD.

1º Paso: Instalar un juego en la consola (dará igual su región). No abrir el juego ni entrar a la eshop para evitar baneo.﻿

2º Paso: Abrir GodMode9 (Star+Power con la consola apagada). Acudir al directorio SYSNAND SD y pulsar simultánemente el botón R+A. En la pantalla inferior saldrán una nuevas opciones, seleccionaremos Search for titles. En este nuevo menú aparecerán todos los juegos y updates que hayamos instalado en nuestra consola. Buscaremos el juego que queremos convertir a .cxi. Una vez encontrado, le daremos a la A, TMD file options… , Dump CXI/NDS file. Una vez termine la conversión meteremos la tarjeta Sd en nuestro ordenador. Acudiremos a la Carpeta gm9, a la Carpeta out y ahí estará nuestro juego .cxi.

3ª Paso: Crear una Nueva Carpeta en el escritorio y meter ahí el archivo .cxi. A continuación, abrir el programa GabrieloRomToolsGUI y acudir a la pestaña Extract NCCH, seleccionar el archivo game.cxi en la primera opción y seleccionar la Nueva Carpeta en la segunda opción. Por último, daremos a Extract! Con ello, obtendremos varios archivos pero el más importante será icon.icn (ubicado en la carpeta exefs).

4º Paso: Abrir el programa HxD y arrastrar el archivo icon.icn. Acudir a la pestaña “Buscar” y seleccionar la opción “Ir a…”. En “Posición” escribiremos 2018 y le daremos a “Aceptar”. A continuación, modificaremos el serial por FF FF FF 07. Acudiremos a la pestaña “Archivo” y seleccionaremos la opción “Guardar”. Con ello, obtendremos: el archivo icon.icn (el editado) y el archivo icon.icn.bak (deberemos sacarlo de la carpeta exefs o eliminarlo).﻿

5º Paso: Acudir a la pestaña Rebuild NCCH dentro de GabrieloRomToolsGUI. Seleccionar la Nueva Carpeta en la tercera opción y dar a Rebuild. Con ello, obtendremos el archivo edited.cxi.

6.1º Paso (.cxi a .cia): Acudir a la pestaña Cia tools y seleccionar la Nueva Carpeta en la primera opción. Acto seguido, presionar el botón Add, escribir edited.cxi y darle a Aceptar. Por último, le daremos a Rebuild! Con ello, obtendremos el archivo example.cia (podéis renombrarlo).

6.2º Paso (.cxi a .3ds): Acudir a la pestaña Rebuild 3ds y seleccionar la Nueva Carpeta en la primera opción. Acto seguido, presionar el botón Add, escribir edited.cxi y darle a Aceptar. Por último, le daremos a Rebuild! Con ello, obtendremos el archivo example.3ds (podéis renombrarlo).

7.1º Paso: Comprobar que la región del juego.cia es Región Free mediante el uso del FBI. No obstante, podéis reinscribir el juego instalado en el 1º Paso o eliminarlo antes de la nueva instalación.

7.2º Paso: Comprobar que la región del juego.3ds es Región Free mediante el uso de Citra.
