## Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente

***

### 1. Modelos de Programación en Entornos Cliente/Servidor

***

* #### Modelos cliente/servidor más comunes  
    * Cliente/Servidor de dos capas (2-Tier)  
    	La aplicación se divide en dos partes principales: el cliente y el servidor.  
		El cliente se encarga de la interfaz de usuario y el servidor gestiona los datos.  

    * Cliente/Servidor de tres capas (3-Tier)  
    	Agrega una capa intermedia entre el cliente y el servidor.  
		La capa de presentación (cliente) se encarga de la interfaz de usuario, la capa de lógica de negocio (aplicación) contiene la lógica empresarial, y la capa de datos (servidor) maneja la persistencia y el acceso a la base de datos.  

    * Cliente/Servidor de n capas (n-Tier)  
    	Es una extensión del modelo de tres capas y puede tener múltiples capas intermedias según las necesidades de la aplicación.  
		Cada capa tiene una función específica y se comunica con las capas adyacentes. Esto permite una mayor modularidad y escalabilidad.  

    * Cliente/Servidor en la nube  
    	Implica que el cliente y el servidor se ejecutan en la nube (infraestructura remota) en lugar de en la infraestructura local del cliente.  
		Los servicios en la nube ofrecen escalabilidad, disponibilidad y acceso desde cualquier lugar a través de Internet.

* #### Aplicaciones que utilizan cada modelo
    * Cliente/Servidor de dos capas (2-Tier)  
    	* Microsoft Outlook
    	* Cajeros automáticos (ATM)
    * Cliente/Servidor de tres capas (3-Tier)  
    	* Facebook
    	* Reservas de hoteles en línea
    * Cliente/Servidor de n capas (n-Tier)  
    	* Sistemas bancarios
    	* Sistemas de gestión de cadenas de suministro
    * Cliente/Servidor en la nube  
    	* Google Drive
    	* Microsoft Office 365

***

### 2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web

***

* #### Estudio de cómo se ejecuta el código JavaScript en un navegador  
	Para poder ejecutar JavaScript en un navegador, por ejemplo Google Chrome, deberemos realizar los siguientes pasos:  
	1. Abrimos la consola del navegador (Ctrl + Shift + J, en Windows).
	2. Dentro de la consola vamos a Source > Snippets > New Snippet.
	3. Elegimos el nombre para el nuevo snippet.
	4. Una vez aquí escribimos el código y pulsamos Ctrl + Intro (Windows) para ejecutarlo.  
[![Ejecutar-c-digo-Java-Script-en-Chrome-Google-Chrome-20-09-2023-10-23-26.png](https://i.postimg.cc/mZcnRwFM/Ejecutar-c-digo-Java-Script-en-Chrome-Google-Chrome-20-09-2023-10-23-26.png)](https://postimg.cc/rzkjN5jF)  

[Fuente](https://apuntes.de/javascript-estructuras-de-datos-y-algoritmos/ejecutar-codigo-javascript-en-chrome/#gsc.tab=0)

* #### Evaluación de las diferencias de compatibilidad entre navegadores  
Aunque se pueda pensar que hasta el código más simple se visualizará de la misma manera en cualquier navegador, tenemos que tener saber que esto no es cierto. Esto es debido, principalmente, a dos motivos:
    * Cada navegador tiene su propia interfaz o apariencia.
    * La ejecución de código en un navegador está ligada a su configuración de seguridad y al hecho de si JavaScript está o no activado.
    * El sistema operativo y el dispositivo que se use.
  
[Fuente](https://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=783:diferencias-de-navegadores-ante-javascript-firefox-explorer-chrome-safari-javascript-en-linea-cu01108e&catid=78&Itemid=206)

* #### Resolución de problemas de compatibilidad en una aplicación web  
	Las aplicaciones web pueden no funcionar correctamente en distintos navegadores, lo que requiere realizar pruebas funcionales y no funcionales, como pruebas de carga, de seguridad y de rendimiento, y recursos de desarrollo para garantizar la compatibilidad.

[Fuente](https://appmaster.io/es/blog/desarrollo-de-aplicaciones-web)

***

### 3. Lenguajes de Programación en Entorno Cliente

***

* #### Investigación de lenguajes como JavaScript, TypeScript, y otros  
	* JavaScript
		JavaScript (JS) es un lenguaje de programación ligero, interpretado y orientado a objetos con funcionalidades de de primera clase. Es uno de los lenguajes de programación más utilizados en el desarollo web.

	* TypeScript
		TypeScript (TS) es un lenguaje de programación construido a un nivel superior que JavaScript. Tiene carácterísticas adicionales que nos ayudan a poder escribir código con menos errores y que sea más sencillo, fácil de probar y coherente, es decir, más limpio y sólido.

	* Otros
		Aparte de JavaScript y TypeScript, hay otros lenguajes que se utilizan en el entorno del cliente, aunque no son tan comunes o dominantes. Algunos de ellos incluyen:  

		    - HTML y CSS: Aunque no son lenguajes de programación en el sentido tradicional,  
		    HTML y CSS son esenciales para la creación y el diseño de páginas web.
		    
		    - Python (con Brython): Python se puede ejecutar en el navegador utilizando Brython,  
		    una implementación de Python en JavaScript.
		    
		    - Dart: Desarrollado por Google, se utiliza en el framework Flutter para  
		    el desarrollo de aplicaciones móviles y web.
		    
		    - Rust (con WebAssembly): Rust se puede compilar a WebAssembly y ejecutarse  
		    en el navegador, lo que lo hace adecuado para aplicaciones de alto rendimiento en la web.
		    
		    - Elm: Un lenguaje funcional puramente orientado al desarrollo de  
		    aplicaciones web front-end, con un fuerte enfoque en la arquitectura de aplicaciones.

* #### Comparación de sus características y aplicaciones
	##### Principales carácterísticas de JavaScript:  

    * Interpretado: Es un lenguaje interpretado que se ejecuta directamente en los navegadores web, lo que lo hace ideal para la programación en el lado del cliente.
    
	* Lenguaje de Scripting: Se utiliza principalmente como un lenguaje de scripting para mejorar la interactividad y la dinámica en las páginas web.  
	
	* Multiplataforma: Es compatible con múltiples plataformas y sistemas operativos, lo que lo hace altamente portátil.  
	
	* Asincrónico: Es capaz de manejar operaciones asincrónicas, como solicitudes de red y eventos, utilizando el Event Loop, lo que permite una experiencia de usuario receptiva.  
	
	* Amplia Comunidad: Tiene una gran comunidad de desarrolladores y una gran cantidad de bibliotecas y frameworks, como React, Angular y Vue.js.
	
	##### Principales carácterísticas de TypeScript:

    * Tipado Estático: Permite definir tipos de datos para variables, parámetros de función y otros elementos, lo que ayuda a prevenir errores en tiempo de ejecución.

    * Compilación: El código se compila a JavaScript antes de ser ejecutado en el navegador, lo que permite usar las últimas características de JavaScript y asegurar la compatibilidad con versiones anteriores.

    * Orientado a Objetos: Admite programación orientada a objetos y ofrece características como clases, herencia e interfaces.

    * Auto-completado: Los entornos de desarrollo integrados (IDE) ofrecen un mejor auto-completado y herramientas de refactorizado gracias al sistema de tipado.
    
	##### Aplicaciones principales de JavaScript:

    * Desarrollo Web
    * Desarrollo de Aplicaciones Web
    * Desarrollo de Juegos
    * Automatización del lado del cliente

	##### Aplicaciones principales de TypeScript:
    
    * Aplicaciones Web
    * Desarrollo Back-End
    * Proyectos grandes
    * Librerías y Frameworks

***

### 4. Características de los Lenguajes de Script. Ventajas y Desventajas

***

* #### Análisis de las ventajas y desventajas de la programación en lenguajes de script sobre la programación tradicional  
	##### Principales ventajas de la programación de lenguajes de script:  

    	- Facilidad de aprendizaje: Los lenguajes de script suelen tener una sintaxis  
    	más sencilla y legible en comparación con lenguajes tradicionales.
    
    	- Desarrollo rápido:  Los lenguajes de script suelen permitir el desarrollo  
    	rápido de prototipos y aplicaciones debido a su sintaxis concisa y la  disponibilidad  
		de bibliotecas y frameworks que facilitan la implementación de funcionalidades comunes.
		
		- Portabilidad: Los scripts son portables, lo que significa que se pueden  
		ejecutar en múltiples plataformas sin cambios significativos.

		- Interpretación en tiempo real: Los lenguajes de script a menudo se interpretan
		en tiempo real, lo que facilita la depuración y la modificación del código  
		sin necesidad de volver a compilar.

		- Dinamismo: Los lenguajes de script suelen ser dinámicos y permiten la manipulación  
		de tipos de datos en tiempo de ejecución.

		- Integración con Web: JavaScript, en particular, es fundamental en el desarrollo web
		y es ampliamente compatible con navegadores.

	##### Principales desventajas de la programación con lenguajes de script:
		
		- Rendimiento limitado: Los lenguajes de script suelen ser más lentos que los  
		lenguajes compilados, lo que los hace menos adecuados para aplicaciones que  
		requieren un alto rendimiento.

		- Menor control de memoria: En lenguajes de script, el manejo de la memoria  
		se realiza de manera automática, lo que puede llevar a una gestión ineficiente  
		de recursos en aplicaciones intensivas en memoria.

		- Escalabilidad limitada: A medida que un proyecto crece en complejidad y tamaño,  
		los lenguajes de script pueden encontrar dificultades para mantener la escalabilidad  
		y la organización del código.

		- Requisitos de interpretación: Los lenguajes de script requieren un intérprete o  
		motor en el sistema de destino para ejecutar el código.

		- Seguridad: Los lenguajes de script a menudo se ejecutan en un entorno inseguro,  
		lo que los hace vulnerables a ataques como inyección de código,  
		si no se toman las precauciones adecuadas.

		- Menos adecuados para aplicaciones de bajo nivel: Para programación de sistemas o  
		aplicaciones de bajo nivel, los lenguajes de script no son la elección ideal debido  
		a su sobrecarga y falta de control directo sobre el hardware.

***

### 5. Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML

***

* ##### Exploración de tecnologías como CSS y HTML5
    * HTML5: es la última versión del lenguaje de marcado HTML utilizado para crear la estructura de una página web. HTML (HyperText Markup Language) es un lenguaje de etiquetas que permite incluir o hacer referencia a todo tipo de información.  
	
		HTML5 introduce nuevos elementos semánticos como `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`, que ayudan a describir mejor la estructura y el contenido de una página web. También, incluye elementos como `<audio>` y `<video>` que permiten la reproducción de contenido multimedia sin necesidad de plugins y proporciona elementos como `<canvas>` y compatibilidad con WebGL para dibujar gráficos y animaciones en el navegador.

		[Fuente](https://lenguajehtml.com/html/introduccion/que-es-html/#qu%C3%A9-es-html)  

	* CSS: (Cascading Style Sheets), significan «Hojas de Estilo en Cascada» y parten de un concepto simple pero muy potente: aplicar estilos (colores, formas, márgenes, etc...) a uno o varios documentos (generalmente documentos HTML) de forma automática y masiva. Se le denomina estilos en cascada porque se lee, procesa y aplica el código desde arriba hacia abajo y en el caso de existir ambigüedad, se siguen una serie de normas para resolver dicha ambigüedad.
		
		CSS utiliza selectores para aplicar estilos a elementos HTML específicos. Permite definir propiedades como color, font-size, margin, padding, etc., junto con valores para controlar la apariencia de los elementos. Proporciona sistemas de diseño como Flexbox y Grid Layout para controlar la disposición y alineación de elementos en una página. Con media queries, CSS puede adaptar el diseño de una página según las características del dispositivo, como el tamaño de la pantalla o la orientación.

		[Fuente](https://lenguajecss.com/css/introduccion/que-es-css/)

* ##### Creación de una pequeña aplicación web integrando código JavaScript de diferentes maneras
	1. Todo el código dentro del mismo archivo .html:  
	[![calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-05.png](https://i.postimg.cc/66H3xLV0/calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-05.png)](https://postimg.cc/fk9Zxdrt)

	2. El código JavaScript en un archivo .js aparte:  
	[![calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-12.png](https://i.postimg.cc/BQXvSLMG/calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-12.png)](https://postimg.cc/w7YzFBCW)  

		[![calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-18.png](https://i.postimg.cc/qqZMc4BY/calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-18.png)](https://postimg.cc/1VwQsxqc)

***

### 6. Herramientas de Programación

* ##### Uso de herramientas como Visual Studio Code, Chrome DevTools, etc.  
	* Visual Studio Code: es un editor de código fuente desarrollado por Microsoft que se ha vuelto extremadamente popular en la comunidad de desarrollo web debido a su rendimiento, extensibilidad y capacidad para admitir una variedad de lenguajes de programación y tecnologías web.  
	
		Ofrece funciones de edición avanzadas, como resaltado de sintaxis, autocompletado, refactorización y soporte para múltiples cursores. Es altamente personalizable mediante extensiones. Permite la depuración de aplicaciones web directamente desde el editor. Tiene una integración fluida con sistemas de control de versiones como Git. Ofrece una terminal integrada que te permite ejecutar comandos y scripts directamente desde VS Code. Es excelente para el desarrollo web, con soporte para HTML, CSS, JavaScript, TypeScript y frameworks populares como React, Angular y Vue.js.

	* Chrome DevTools: es un conjunto de herramientas de desarrollo integradas en el navegador Google Chrome. Estas herramientas son esenciales para depurar y mejorar aplicaciones web.  

		Permite inspeccionar y modificar el DOM (Document Object Model) de una página web en tiempo real. Puedes ver y editar HTML y CSS. Proporciona una consola interactiva para ejecutar comandos de JavaScript y mostrar mensajes de registro y errores. Ofrece información detallada sobre las solicitudes y respuestas de red, lo que facilita la depuración de problemas de carga de recursos. Permite la depuración de JavaScript en el navegador. Proporciona perfiles de rendimiento para identificar cuellos de botella y mejorar el rendimiento de tu aplicación web. Permite inspeccionar el almacenamiento local, las cookies, los Service Workers y otras características de la aplicación web. Realiza auditorías de rendimiento, accesibilidad y mejores prácticas para mejorar la calidad de tu sitio web.

	* Otras herramientas:  
		* Git: Un sistema de control de versiones que permite el seguimiento de cambios en el código y la colaboración en equipos de desarrollo.

		* Postman: Una herramienta para probar y depurar APIs web.

		* SASS/LESS: Preprocesadores de CSS que facilitan la escritura de estilos más eficientes y mantenibles.

		* Webpack: Un empaquetador de módulos que ayuda a administrar dependencias y a optimizar el rendimiento de las aplicaciones web.

		* Linter (por ejemplo, ESLint): Herramientas que analizan el código para identificar y corregir problemas de estilo y errores de programación.

***