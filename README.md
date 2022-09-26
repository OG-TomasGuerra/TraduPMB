# TraduPMB
Proyecto de traduccion de PMB completo en español.

# ¿Que es PMB?
PMB, por sus siglas, PHP My Bibli es un software integrado de gestion bibliotecaria de origen frances, de codigo abierto creado por la empresa PMB Services. Es utilizado alrededor del mundo por diversas bibliotecas de varios niveles para control de sus acervos, prestamo de los mismos, y diversas otras actividades debido a su gran cantidad de funciones.

# ¿Por que este proyecto?
PMB, como mencionaba antes, es de origen frances. El frances es ciertamente un idioma hermoso, pero como todos los idiomas, requiere saberlo como para poder utilizarlo. Si bien el frances en ciertos aspectos no presenta tanta dificultad en aprenderse para un hablante de español (no me citen al respecto de esto), aun asi resulta conveniente disponer del software completamente en español. Ahora bien, podriamos decir: "Pero... al instalarlo, el software nos ofrece la posibilidad de instalarlo en español..."

Y seria cierto, puesto a que efectivamente se instala en español. Sin embargo, requiere solo el intentar iniciar sesion para encontrarnos con la frugal pantalla de inicio que nos solicita nuestro nombre de "utilisateur" y nuestra "mot de passe"... se trata entonces, de una traduccion incompleta; en parte desde el punto de vista de la configuracion (el login puede ser alterado desde un archivo de configuracion cambiando un par de lineas) y por otro lado, desde el punto de vista del trabajo incompleto de traduccion propiamente dicha (se encuentra bastante contenido en frances dentro del archivo de la traduccion en español)

Con esto como justificacion, este proyecto tiene la intencion de servir como un esfuerzo conjunto por parte de la comunidad en español para obtener una traduccion completa libre para todos los que por una razon u otra, queremos tener el PMB completamente en español.

# ¿Como instalarlo?
Para instalar este parche actualmente la unica manera es reemplazando los archivos de los que hablaba antes :P

Clickea en el boton que dice "Main", y cambia hacia la branch "Administracion/Cuerpo" o "Opac CSS", una vez te encuentres en esa branch, clickea el boton verde que dice "Code" y luego "Download zip". 

Extrae el archivo que obtenes en una carpeta, y dentro vas a encontrar los archivos "config.inc.php", "es_ES.xml", "fr_FR.xml" y "README.md"

En el caso del cuerpo/administracion:

-Copia o move config.inc.php a tu carpeta "includes" del PMB... por ejemplo, si lo corres en XAMPP, lo pondrias en "C:\xampp\htdocs\pmb\includes".

-Copia o move es_ES.xml, es_ES_subst.xml y fr_FR.xml a tu carpeta messages del PMB... por ejemplo, si lo corres en XAMPP, lo pondrias en "C:\xampp\htdocs\pmb\includes\messages".

En el caso del Opac

-Copia o move es_ES.xml, es_ES_subst.xml y fr_FR.xml a tu carpeta messages del OPAC en el PMB... por ejemplo, si lo corres en XAMPP, lo pondrias en C:\xampp\htdocs\pmb\opac_css\includes\messages

Cuando tu sistema te pregunte si queres reemplazar los archivos en el destino, confirma esa accion. Luego, presiona F5 en el PMB funcionando (osea, cuando lo estes corriendo con localhost/pmb/ en tu navegador) para observar los cambios (o en su defecto, los vas a ver cuando inicies el PMB)

# ¿"Como" este proyecto?
Para traducir PMB, segun la investigacion realizada, hay unos archivos que nos interesan. Espero que podamos ir agregando más segun sea necesario ir agregando, pero basicamente son:

-El archivo "config.inc.php" ubicado en pmb/includes

-Los archivos "es_ES.xml" y "es_ES_subst.xml" (generado por nosotros) ubicado en pmb/includes/messages

-El archivo "fr_FR.xml" ubicado en pmb/includes/messages

Estos son facilmente editables mediante una aplicacion como Wordpad, aunque tambien se puede utilizar Visual Studio Code o algo similar si se requiere tener más claridad (con Wordpad, por ejemplo, todo es texto en blanco y negro... con VSC las tags tienen colorcitos que los distinguen del contenido de las mismas)

# ¿Como puedo aportar?
Extendiendo de la seccion anterior, lo que podes aportar es tu granito de arena para la traduccion. Hay varias formas en las que puedes hacer esto:

-Abri la branch "Administracion/Cuerpo" o "Opac" y modifica el archivo es_ES.xml, traduciendo lo que esta entre las tags en frances que encuentres, al español. Una vez hayas hecho eso, realiza un pull request. La chequeamos y le damos merge con la main.

-Sugiere cualquier tipo de idea que pueda ayudar a mejorar la traduccion. Por ejemplo, podes compartir archivos que deban ser traducidos, o partes del programa que aun no hayan sido traducidos (esto segun vaya progresando el trabajo)

-Chequea los archivos en distintas versiones de PMB.

-Descarga el archivo y utilizalo, compartilo con tus amigos, organiza una fiesta o tomate una cerveza en honor de este proyecto. 

