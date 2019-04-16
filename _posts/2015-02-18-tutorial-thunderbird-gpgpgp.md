---
ID: 191
post_title: Tutorial Thunderbird + GPG/PGP
post_name: tutorial-thunderbird-gpgpgp
author: H Q
post_date: 2015-02-18 18:10:00
layout: post
link: >
  https://protege.la/tutorial-thunderbird-gpgpgp/
published: true
tags:
  - cómo encriptar correos
  - pgp
  - seguridad digital
categories:
  - Blog
---
## ¿Qué es Thunderbird? Thunderbird es un gestor de correos electrónicos desarrollado por la 

<a href="https://www.mozilla.org/en-US/foundation/" target="_blank" rel="noopener">Mozilla Foundation</a>. Al igual que programas como Outlook para Windows o Mail para Mac permite enviar y recibir información desde múltiples cuentas de correo sin la necesidad de tener abiertas las ventanas en navegador. Otra de las ventajas de sistemas como éste es contar con la información disponible para trabajar aun sin conexión a Internet (modo *offline*). La versión más reciente del gestor es la 31.4.0. **Instalación** Para instalar es necesario descargar el archivo ejecutable desde la dirección <a href="https://www.mozilla.org/en-US/thunderbird/all.html" target="_blank" rel="noopener">https://www.mozilla.org/en-US/thunderbird/all.html</a>. El programa está disponible para Windows, Mac y Linux en español y otros idiomas. 
1.  La instalación del programa no requiere mayor configuración que la de un programa tradicional. Sigue los pasos que se describen en la dirección: <a href="https://support.mozilla.org/es/kb/instalar-thunderbird" target="_blank" rel="noopener">https://support.mozilla.org/es/kb/instalar-thunderbird</a>

**Instalación en Windows ** Visita <a href="http://www.getthunderbird.com/" target="_blank" rel="noopener">la página de descargas de Thunderbird </a>desde cualquier navegador (por ejemplo Firefox o Microsoft Internet Explorer). La página te recomendará automáticamente la mejor versión de Thunderbird para tu sistema. ![Installing Thunderbird Win 1][1] Haz clic en el rectángulo verde para descargar el instalador de Thunderbird. Dependiendo de la velocidad de tu conexión, la descarga puede durar un par de minutos. Gracias por tu paciencia… ¡Merece la pena la espera! Comienza el proceso de instalación haciendo clic sobre el botón Ejecutar. ![click on run to install thunderbird][2] Después, sólo tienes que seguir los pasos (han hecho el proceso de instalación lo menos doloroso posible). ![Welcome to the Thunderbird Setup Wizard][3] ¡Listo, has terminado de instalar Thunderbird! Haz doble-clic sobre el icono de Thunderbird cada vez que quieras comunicarte. ![double click on the thunderbird icon][4] **Instalación en Mac** Antes de instalar Thunderbird, comprueba que tu equipo cumple los <a href="http://www.mozilla.com/Thunderbird/system-requirements" target="_blank" rel="noopener">requisitos del sistema</a>. Descarga el archivo de instalación desde la <a href="http://www.mozillamessaging.com/en-US/thunderbird/download/?product=thunderbird" target="_blank" rel="noopener">página de descargas de Thunderbird</a>. ![ae418611438d1ddc8b20d3c9ac1d45ae-1287636608-532-2.png][5] La página web detectará automáticamente la plataforma y el idioma que estás utilizando en el equipo y te recomendará cuál es la mejor versión de Thunderbird. Si quieres descargar Thunderbird en otro lenguaje distinto al propuesto, haz clic en “Otros sistemas e idiomas” para ver la lista de las diferentes ediciones disponibles. Haz clic en la instalación de OS X que desees para continuar. ![ae418611438d1ddc8b20d3c9ac1d45ae-1287636608-532-3.png][6] Una vez finalizada la descarga, la imagen de disco se puede abrir y montar por sí misma creando una nueva unidad que contiene la aplicación Thunderbird. Si no ves la unidad, haz doble clic sobre el icono del archivo de imagen .dmg de Thunderbird para abrirlo. Aparecerá una ventana de Finder con la aplicación Thunderbird. Arrastra el icono de Thunderbird a la carpeta Aplicaciones. En este punto puedes expulsar la imagen de disco, seleccionando en la ventana del Finder y presionando las teclas Comando+E o utilizando el menú Archivo del Finder y seleccionando Expulsar, tal y como se muestra más arriba. Si la imagen de disco de Thunderbird no se expulsa, puede que se deba a que un bug en Leopard evita la expulsión del disco una vez que has copiado los archivos de una unidad a otra. La opción de expulsar el disco mediante la herramienta Utilidad de discos debería funcionar sin problemas. Thunderbird ya está listo para su uso. Abre la carpeta Aplicaciones y haz doble clic en el icono de Thunderbird para iniciarlo. Puedes recibir una advertencia de seguridad que indica que Thunderbird ha sido descargado de Internet. Debido a que has descargado Thunderbird desde el sitio oficial, puedes hacer clic en el botón Abrir para continuar. La primera vez que ejecutes Thunderbird se te avisará de que no es la aplicación de correo electrónico predeterminada. (La aplicación de correo por defecto es el programa que se abre, por ejemplo, al hacer clic en una dirección de correo electrónico dentro de una página web). Si deseas que Thunderbird sea la aplicación de correo electrónico predeterminada, haz clic en el botón Sí. Si no es el caso (simplemente estás probando Thunderbird), haz clic sobre el botón No. 
## Configuración de una cuenta Configurar una nueva cuenta de correo con Thunderbird es fácil. Todo lo que necesitas hacer es proporcionar tu nombre de usuario y tu dirección de correo electrónico. A partir de esa información, Thunderbird intentará determinar los detalles de tu dirección de correo, como los datos de conexión (los puertos, nombres de los servidores, protocolos de seguridad,etc.), que encontrará buscando tu proveedor de correo electrónico en una base de datos que contiene la gran mayoría de proveedores de servicios de Internet (ISP). Después de que Thunderbird averigüe cuál es el proveedor de tu cuenta (la información que utiliza para esto es el texto especificado después de la “@” en tu dirección de correo), te mostrará los detalles de la cuenta. La primera vez que ejecutas una versión de Thunderbird recién instalada, se te pedirá que crees un nuevo perfil (cierra cualquier ventana que te proponga configurar un servicio de correo) y, posteriormente, se te pedirá que proporciones todos los detalles acerca de tu cuenta de correo en el cuadro de diálogo que se muestra a continuación. También verás el mismo cuadro de diálogo si añades una nueva cuenta de correo electrónico a través del menú 

**Archivo | Nuevo | Cuenta de correo** o a través del cuadro de diálogo **Configuración de cuentas**. <figure>![image][7]</figure> Cuando presiones el botón Continuar, Thunderbird buscará la información del proveedor de servicios e intentará determinar la configuración de la cuenta automáticamente. <figure>![image][8]</figure> En el caso que te hemos mostrado, el nombre del proveedor de servicios se ha utilizado para rellenar los detalles de la cuenta y configurar los servicios que ofrece: 
*   Entrante: IMAP en <a href="http://imap.gmx.net/" target="_blank" rel="noopener">imap.gmx.net</a>, utilizando Secure Socket Layer (SSL)
*   Saliente: SMTP en <a href="http://mail.gmx.net/" target="_blank" rel="noopener">mail.gmx.net</a>, utilizando Secure Socket Layer (SSL) Tienes la opción de elegir entre IMAP y POP como protocolo de entrada de correo. IMAP y POP son los protocolos más habituales para obtener los correos de tu cuenta. IMAP, el protocolo más moderno, te permite guardar mensajes en el servidor de correo y en tu computadora de forma local (sin conexión a Internet) al mismo tiempo. El protocolo POP sólo te permite guardar los mensajes en tu equipo sin dejar un respaldo en Internet. Puede que los proveedores de correo te proporcionen acceso a un protocolo IMAP o a uno POP o incluso a ambos. Para obtener detalles más técnicos sobre ambos protocolos, consulta estos artículos: 

<a href="https://support.mozilla.org/es/kb/tipos-de-cuentas" target="_blank" rel="noopener">Tipos de cuentas</a> y <a href="https://support.mozilla.org/es/kb/sincronizacion-imap" target="_blank" rel="noopener">Sincronización IMAP</a>. Para completar la configuración: 
*   Crear Cuenta: Presiona este botón para crear una nueva cuenta.
*   Cancelar: Modifica los datos de configuración del servidor que se está mostrando.
*   Configuración manual: Para configurar manualmente la cuenta de correo, Thunderbird creará una nueva cuenta con los detalles que se muestran y abrirá el cuadro de diálogo Configuración de las cuentas para que puedas hacer todos los cambios necesarios. (Puedes ver el artículo <a href="https://support.mozilla.org/es/kb/configuracion-manual-de-una-cuenta-de-correo" target="_blank" rel="noopener">Configuración manual de una cuenta de correo</a> para más información). Los círculos situados a la izquierda del servidor de correo entrante y del servidor de correo saliente indican el grado de seguridad de tu conexión con el servidor de correo electrónico: Si el círculo es de color verde, tu conexión con el servidor de correo está cifrada. Si el círculo es de color naranja, el servidor sólo aceptará tu nombre de usuario y tu contraseña sin cifrar, lo que significa que si tu conexión con el servidor es interceptada, podrían obtener información de tu cuenta de correo, así como tus datos de conexión. Después de esto, Thunderbird, te mostrará la nueva cuenta: <figure>

![image][9]</figure> Si tu cuenta no puede configurarse automáticamente, debes configurarla manualmente. Puedes configurarla mediante el cuadro de diálogo Configuración de las cuentas, al que puedes acceder desde el menú Herramientas. Tu proveedor de correo electrónico te proporcionará todos los detalles de configuración de tu cuenta (dicha información es probable que se encuentre disponible en su sitio web). Puedes ver “<a href="https://support.mozilla.org/es/kb/configuracion-manual-de-una-cuenta-de-correo" target="_blank" rel="noopener">Configuración manual de una cuenta de correo</a>” para obtener información completa sobre cómo configurar tu cuenta de correo. También puedes ver PUF<a href="https://support.mozilla.org/es/kb/puf-cambiar-de-imap-pop" target="_blank" rel="noopener">F - Cambiar de IMAP aPOP</a> si lo que necesitas es información sobre cómo cambiar tu servidor de correo entrante de IMAP a POP. **Encriptación** 
## ¿Qué es PGP? PGP son las siglas de “Pretty Good Privacy”, un sistema que sirve para cifrar y descifrar datos, de tal manera que sólo se pueda acceder a ellos mediante una “llave pública”, con el objetivo de ofrecer un mecanismo de “verificación entre usuarios” para algunas comunicaciones y mejorar la privacidad de las mismas. PGP combina varios procesos de cifrado: hashing, compresión de datos, cifrado de llave simétrica y cifrado de llave pública. Una llave pública siempre está asociada a un nombre de usuario o dirección de correo. Durante el proceso de cifrado, PGP comprime los datos y se genera un archivo que contiene “caracteres aleatorios únicos” que luego se utilizará para descifrar el mensaje realizando un proceso inverso del lado del receptor, garantizando así la seguridad del mensaje. 

## ¿Cómo instalar GPG/PGP? Usar GPG/PGP es algo muy sencillo, en Thunderbird existe un “complemento (Add-on)” que nos facilitan la vida, este complemento se llama “Enigmail” y para instalarlo únicamente debes: 

1.  En el menú superior de Thunderbird ve a “Tools” y luego a Add-ons
2.  Te abrirá una ventana con una lista de complementos
3.  En el campo de búsqueda escribe “Enigmail” y te aparecerá una lista Da clic en Instalar. <figure>

![image][10]</figure> 
*   Te va a pedir reiniciar Thunderbird, para esto sólo cierra el programa y ábrelo de nuevo. Con esto ya podrás usar GPG/PGP en tu Thunderbird, ahora sólo hay que generar una llave GPG/PGP para enviar y recibir los correo. 

## ¿Cómo generar una llave GPG/PGP? La forma más sencilla de generar una llave es seguir el asistente o “Setup Wizard” de Enigmail para eso sigue estos pasos: 

1.  En el menú superior de Thunderbird ahora aparece el menú “Enigmail”, da clic y selecciona “Setup Wizard”.<figure>

![image][11]</figure> 2. Te aparecerá una ventana preguntándote si quieres configurar con el wizard, selecciona “Yes, I would…” y clic a  “continuar”. <figure>![image][12]</figure> 3. Te preguntará si quieres que Enigmail configure todas las identidades, selecciona sí y continuar. 4. Ahora puedes seleccionar si quieres que todos los correos se encripten en automático, selecciona la opción de tu preferencia y “continuar”. <figure>![image][13]</figure> 5. Después preguntará si quieres que se firmen todos los mensajes por default, te recomiendo que actives esta opción. 6. Después te preguntará si quieres generar una llave o si ya cuentas con una, selecciona que quieres crear una y continuar. 7. Te va a pedir que selecciones para qué correo quieres la llave y un password. <figure>![image][14]</figure> 8. Te dará un resumen, sólo debes dar clic a continuar. 9. Generará tus llaves, esto puede tardar unos minutos. 10. Cuando termine de crear tu llave te dará la opción Genera un certificado de revocación. <figure>![image][15]</figure> 11. Listo ya tienes tu llave. 
## ¿Cómo enviar y recibir llaves públicas? Para recibir un mensaje cifrado de otras personas, primero debes enviarles tu llave pública: 

1.  Redacta un mensaje.
2.  Selecciona el menú EnigMail desde la barra de menú de Thunderbird y selecciona Key Management y te saldrá una ventana con tus llaves.<figure>

![image][16]</figure> 3. En el gestor de llaves busca tu correo y da clic derecho, en el menú emergente da clic a “Send Public keys by Email”. <figure>![image][17]</figure> 4. Envía el mensaje como lo haces usualmente. 
## Recibir una llave pública a través del correo Para enviar un mensaje cifrado a otras personas, debes recibir y almacenar su llave pública: 

1.  Abre el mensaje que contiene la llave pública.
2.  En la parte inferior de la ventana, haz doble clic en el adjunto que termina con la extensión en ’.asc’. (Este archivo contiene la clave pública).
3.  Thunderbird reconocerá automáticamente que es una llave PGP. Thunderbird mostrará un cuadro de diálogo, preguntando si quieres ‘Importar’ o ‘Ver’ la llave. Haz clic en el botón Import para importar la clave.<figure>

![image][18]</figure> 
1.  Verás un mensaje de confirmación indicando que la llave se ha importado correctamente. Haz clic en el botón OK para completar el proceso.
2.  NOTA: en caso de usar equipo mac este se abrirá automáticamente en “GPG keychain”.

## ¿Cómo cifrar un correo sin archivos adjuntos?

1.  Para cifrar revisa que los iconos en forma de “llave” y de “lápiz” estén coloreados (activados).
2.  Redacta el mensaje de la forma habitual.<figure>

![image][19]</figure> 
1.  Si tu dirección de correo electrónico está asociada a una llave PGP, el mensaje se cifrará con la llave. Si la dirección de correo electrónico no está asociada a una clave PGP, se te pedirá que selecciones una llave de una lista.
2.  Envía el mensaje tal y como lo haces habitualmente. Nota: Thunderbird no cifrará el asunto del mensaje. 

## ¿Cómo cifrar un correo con archivos adjuntos?

1.  Redacta el mensaje de forma habitual.
2.  Adjunta el archivo que desea enviar.
3.  Revisa que los iconos de la parte inferior derecha (llave y lápiz) estén activos (iluminados).<figure>

![image][20]</figure> 4. Cuando presiones el botón de enviar te saldrá un cuadro de opciones, debes seleccionar la opción “cifrar y firmar el mensaje en su totalidad y enviarlo mediante PGP/MIME”. <figure>![image][21]</figure> Nota: es posible te pida tu contraseña para firmar el correo. 
## Leer correo electrónico firmado digitalmente o cifrado Cuando recibes un mensaje cifrado, Thunderbird te pedirá que introduzcas tu contraseña secreta para descifrar el mensaje. Para determinar si el mensaje entrante se ha cifrado o firmado digitalmente, hay que buscar en la barra de información justo por encima del cuerpo del mensaje. Si Thunderbird reconoce la firma, mostrará una barra de color verde encima del mensaje (como se muestra a continuación). <figure>

![image][22]</figure> 
## ¿Cómo mudar o usar mi configuración en otros equipos? Si quieres tener tus llaves en otro equipo, ya sea por que cambiarás de equipo o trabajas con varios equipos debes seguir los siguientes pasos: 

**Exportar/respaldar mi llaves públicas y privadas** 
1.  En el menú de “Enigmail”, selecciona “Key Management”.<figure>

![image][23]</figure> 2. Verás todas tus llaves, selecciona todas las llaves y da clic derecho. 3. Da clic en “Export keys to File”. <figure>![image][24]</figure> 4. Te saldrá un cuadro de diálogo, selecciona la opción “Export Secret Keys”. <figure>![image][25]</figure> 5. Te va a generar un archivo “.asc” ponle un nombre y guardalo 6. Nota: esto te puede servir como respaldo. **Importar/restaurar mis llaves públicas y privadas** 
1.  En el nuevo equipo debes instalar Thunderbird con el complemento Enigmail.
2.  En el menú de “Enigmail”, selecciona “Key Management”.<figure>

![image][26]</figure> 3. Notarás que cuando abre el gestor de llaves (Key Management) aparece un nuevo menú en la parte superior, en ese menú da clic en “File” y luego a “Import keys for File”. <figure>![image][27]</figure> 4. Selecciona el archivo “.asc” (el de tu respaldo) y dale a “abrir”. 5. y listo ya tienes tus llaves en tu nuevo dispositivo. 
## ¿Por qué se encriptan en automático mis correos? Si tus mensajes se encripta automáticamente es porque está configurado para que esto pase, para cambiar esta configuración sólo debes seguir estos pasos: 

1.  En el menú superior de Thunderbird  selecciona “Edit” y luego “Properties”.<figure>

![image][28]</figure> 2. Verás una ventana donde de lado izquierdo salen tus correos y algunas opciones, selecciona la opción “OpenPGP Security” del correo que quieras modificar. 3. Desactiva las casillas “Encrypt messages by default” y “Sing messages by default” y despues “Ok”. <figure>![image][29]</figure> Nota: verás que puedes dejar el auto encriptado en un correo y en otros desactivarlo, puedes configurarlo según tus necesidades 
## Recomendaciones para móviles Algunas recomendaciones para descifrar correos en equipos móviles son: 

*   Android APG disponible desde <a href="https://play.google.com/store/apps/details?id=org.thialfihar.android.apg&hl=es" target="_blank" rel="noopener">Play Store</a> (gratuita)
*   Iphone iPGMail disponible desde la <a href="https://itunes.apple.com/us/app/ipgmail/id430780873?mt=8&ls=1" target="_blank" rel="noopener">App Store</a>(con cobro) Referencias 

*   <a href="https://support.mozilla.org/es/kb/instalar-thunderbird-en-windows" target="_blank" rel="noopener">https://support.mozilla.org/es/kb/instalar-thunderbird-en-windows</a>
*   <a href="https://support.mozilla.org/es/kb/instalar-thunderbird-en-mac-os" target="_blank" rel="noopener">https://support.mozilla.org/es/kb/instalar-thunderbird-en-mac-os</a>
*   <a href="https://www.gnupg.org/" target="_blank" rel="noopener">https://www.gnupg.org/</a>
*   <a href="https://es.wikipedia.org/wiki/GNU_Privacy_Guard" target="_blank" rel="noopener">https://es.wikipedia.org/wiki/GNU_Privacy_Guard</a>
*   <a href="https://securityinabox.org/es/thunderbird_principal" target="_blank" rel="noopener">https://securityinabox.org/es/thunderbird_principal</a>

 [1]: https://lh5.googleusercontent.com/SfadgHkwUz-o1HBD1gX0Y6o_t0H87GdMrRWW81KhkjHP8mBIBxQyfvopbPwWHDlAZrPPjBja5hJ2XNMW8fIIlbfl3dJCLxQL0l6UXvll9ZnK4UOIY9eqEjd9XnMVOaM9FTE
 [2]: https://lh5.googleusercontent.com/5Di8gNv10Zc7GfnflFVAynqaYrxyMniCe-hnde7hE5VDQBwx50QA5RvGlrTTG1H1MjVqMsBVoNpDQ7LrKcG9C1RMxUUgvq8r1wZVfasmiCWxsPiTiZ4vBp_bulqOcbMYP18
 [3]: https://lh5.googleusercontent.com/vxprqZ6xXY-KuTzlpVT7ToXLyJHKigcuNQmMRBfrgjZWwXXJMtN1uD6VhKM0D8Vts_aDlBfs4_nc9Un822D3Y1DXVPi8lMtVAgurWMIarmqQYA9rexRGjUxP5YNM-4NojSw
 [4]: https://lh6.googleusercontent.com/X-h2P-usIqBZIEV7yWtZonex2SOZaxaj7tlxvr-ctclKpvR3lO1DkpmC4pdlqnZUKy-WvUYDRVoq-f_fjUtVRYkIQYW6-RDPLNgFmYf2kjE9a_gMizIqevLHXRpeAFjXAIs
 [5]: https://lh6.googleusercontent.com/OtkARJcK5OKB0Aa8Us5axQLlfmVdgfTE0BuRqeTp8M0bBp_n8ivoqsGvaxalq8H7sPHB8-xeiMC1kOh4CdKf_NefOVbeJi0z7dGolmnvbPUU3wDZ05DhD3MpA1Vs_N44QtA
 [6]: https://lh5.googleusercontent.com/z84OcgU1ibTDYTh_4B4X_asrLgW544xo8eK8DB9pWnbWr8ONkoogjbxDD6VeVCiisMB-KJBkH8yPUDtx6ovmdJa9Y2q-o2dKAp8iLO3ghAXq8tdhUyL2ee-pOD8Oa1SMlOM
 [7]: https://78.media.tumblr.com/2209a628217263fcf90b02d8b1fdc1d6/tumblr_inline_njy387IHQP1rgohgc.png
 [8]: https://78.media.tumblr.com/61282e798eabc7c901040fd42baefe79/tumblr_inline_njy38kOnrm1rgohgc.png
 [9]: https://78.media.tumblr.com/2c287a954bdf7a383ad295c5a247f1c3/tumblr_inline_njz73yRxUG1rgohgc.png
 [10]: https://78.media.tumblr.com/1efa02cf5e606ff84fab3d4ceecb1d38/tumblr_inline_njz7iuL2DQ1rgohgc.png
 [11]: https://78.media.tumblr.com/63bcda2a9c38ea670c7ea1fb7575798f/tumblr_inline_njz7lm8mkU1rgohgc.png
 [12]: https://78.media.tumblr.com/c9721566937cb499ac873c565665b924/tumblr_inline_njz7n6DVSD1rgohgc.png
 [13]: https://78.media.tumblr.com/8a7e7802b1c482ac1dc26c7185a6288f/tumblr_inline_njzaftYFB71rgohgc.png
 [14]: https://78.media.tumblr.com/937c39fa990a66a86f1527e1042aaf99/tumblr_inline_njzak66b291rgohgc.png
 [15]: https://78.media.tumblr.com/854c9ae4c29bc5d8f01d8165625bb3b7/tumblr_inline_njzan4ElDT1rgohgc.png
 [16]: https://78.media.tumblr.com/e8c7641e4c4b24c5f1185cbd1145cb22/tumblr_inline_njzapzBL6W1rgohgc.png
 [17]: https://78.media.tumblr.com/33cd2af64872606d15e3cef73027b5db/tumblr_inline_njzas6Hp951rgohgc.png
 [18]: https://78.media.tumblr.com/0c3eacf202c7b639d7fcf0bcb2b87820/tumblr_inline_njzaucx2XY1rgohgc.png
 [19]: https://78.media.tumblr.com/0d2788f7bd7d31d74ea2fcd42dc3d8bd/tumblr_inline_njzawiZtoQ1rgohgc.png
 [20]: https://78.media.tumblr.com/55651b25a467fb305f7abb854e38962d/tumblr_inline_njzayfDnxe1rgohgc.png
 [21]: https://78.media.tumblr.com/9b4ad923426b34eae5c434c5b32a00a9/tumblr_inline_njzb0sRtki1rgohgc.png
 [22]: https://78.media.tumblr.com/eeaed353492df7963015b3800bf9d646/tumblr_inline_njzb2tjP7A1rgohgc.png
 [23]: https://78.media.tumblr.com/430ef5cb0a78f4330ab107be85306c42/tumblr_inline_njzb5sNd9N1rgohgc.png
 [24]: https://78.media.tumblr.com/b65d4ddee61472371521391a930bb940/tumblr_inline_njzb7bNN141rgohgc.png
 [25]: https://78.media.tumblr.com/045a64dd79944cd20e39b77bb9e243e0/tumblr_inline_njzb8la6K31rgohgc.png
 [26]: https://78.media.tumblr.com/7354a80272abbac632f35373f8b4472c/tumblr_inline_njzbb4kH5y1rgohgc.png
 [27]: https://78.media.tumblr.com/35e900b7b60bbe68d5f7c76e3e5fcdd3/tumblr_inline_njzbcyb0Fq1rgohgc.png
 [28]: https://78.media.tumblr.com/52a7c421c080a764e73eb44e814fe336/tumblr_inline_njzbhgwuSY1rgohgc.png
 [29]: https://78.media.tumblr.com/a67fefb3135a3a615f7b0c0600e73f02/tumblr_inline_njzbj14NcV1rgohgc.png