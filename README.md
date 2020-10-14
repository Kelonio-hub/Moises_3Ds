# Moises_3Ds

Moises_3Ds responde a un proceso de modificación de región.Con este proceso el juego aparecerá con Región Free y, con ello, evitaremos incompatibilidades con la eshop en nuestra consola 3Ds. Para la realización de este proceso podemos optar por dos vías alternativas pero complementarias que concluirán en el mismo punto:

-	Vía .3ds

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

-	Vía .cia

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



ENGLISH 

Moises_3Ds responds to a region modification process. With this process the game will appear with Free Region and, with this, we will avoid incompatibilities eshop on our 3Ds console.
For the realization of this process we can opt for two alternative but complementary ways that will conclude to the same point: 

-	Vía .3ds
The .3ds way will require 2 programs: GabrieloRomToolsGUI and HxD.

Step 1: Have a .3ds file, create a New Folder (you can rename it) and put the file inside.

Step 2: Open the GabrieloRomToolsGUI program. Go to the Extract 3ds tab, select the.3ds game in the first option and select the New Folder in the second option. Finally, we'll click Extract! With this, we will get in the New Folder a file called game.cxi

Step 3: Go to the Extract NCCH tab, select the game.cxi file in the first option and select the New Folder in the second option. Finally, we'll give Extract! With this, we will get several files but the most important one will be icon.icn (located in the exefs folder).

Step 4: Open the HxD program and drag the icon.icn file. Go to the "Search" tab and select the "Go to..." option. In "Position" we will write 2018 and give it to "OK". Next, we will modify the serial by FF FF FF 07. We will go to the "File" tab and select the "Save" option. With this, we will get: the icon.icn file (the edited one) and the icon.icn.bak file (we will have to remove it from the exefs folder or delete it).

Step 5: Go to the Rebuild NCCH tab inside GabrieloRomToolsGUI. Select the New Folder in the third option and give Rebuild. With this, we will get the edited.cxi file.

Step 6.1: (.cxi to .cia): Go to the Cia tools tab and select the New Folder in the first option. Then press the Add button, type edited.cxi, and hit OK. Finally, we'll hit Rebuild! With this, we will get the example.cia file (you can rename it).

Step 6.2: (.cxi to .3ds): Go to the Rebuild 3ds tab and select the New Folder in the first option. Then press the Add button, type edited.cxi, and hit OK. Finally, we'll hit Rebuild! With this, we will get the example.3ds file (you can rename it).

Step 7.1: Check that the game region.cia is Free Region by using the FBI.

Step 7.2: Check that the game region.3ds is Free Region by using Citra.

-	Vía .cia
The .cia way will require 3 programs: GabrieloRomToolsGUI,HxD and Godmode9.

Step 1: Install a game on your console (it will match your region). Do not open the game or enter the eshop to avoid baning.

Step 2: Open GodMode9 (Star+Power with console turned off). Go to the SYSNAND SD directory and simultaneously press the R+A button. A new option will appear on the lower screen, we'll select Search for titles. In this new menu will appear all the games and updates that we have installed on our console. We'll look for the game we want to convert to .cxi. Once found, we will give you the A, TMD file options... , Dump CXI/NDS file. Once the conversion is finished, we will put the Sd card on our computer. We will go to the gm9 folder, the Out Folder and there will be our .cxi game.

Step 3: Create a New Folder on your desktop and put the .cxi file in there. Then open the GabrieloRomToolsGUI program and go to the Extract NCCH tab, select the game.cxi file in the first option and select the New Folder in the second option. Finally, we'll give Extract! With this, we will get several files but the most important one will be icon.icn (located in the exefs folder).

Step 4: Open the HxD program and drag the icon.icn file. Go to the "Search" tab and select the "Go to..." option. In "Position" we will write 2018 and give it to "OK". Next, we will modify the serial by FF FF FF 07. We will go to the "File" tab and select the "Save" option. With this, we will get: the icon.icn file (the edited one) and the icon.icn.bak file (we will have to remove it from the exefs folder or delete it).

Step 5: Go to the Rebuild NCCH tab inside GabrieloRomToolsGUI. Select the New Folder in the third option and give Rebuild. With this we will get the edited.cxi file.

Step 6.1: (.cxi to .cia): Go to the Cia tools tab and select the New Folder in the first option. Then press the Add button, type edited.cxi, and hit OK. Finally, we'll hit Rebuild! With this, we will get the example.cia file (you can rename it).

Step 6.2: (.cxi to .3ds): Go to the Rebuild 3ds tab and select the New Folder in the first option. Then press the Add button, type edited.cxi, and hit OK. Finally, we'll hit Rebuild! With this, we will get the example.3ds file (you can rename it).

Step 7.1: Check that the game region.cia is Free Region by using the FBI. However, you can rewrite the installed game in the 1st Step or remove it before the new installation.

Step 7.2: Check that the game region.3ds is Free Region by using Citra.


