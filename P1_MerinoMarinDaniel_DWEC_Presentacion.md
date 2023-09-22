---
marp: true
---

### Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente
[![javascript.jpg](https://i.postimg.cc/vHtszyYD/javascript.jpg)](https://postimg.cc/kBGzJktd)

---

## 1. Modelos de Programación en Entornos Cliente/Servidor
* #### Modelos cliente/servidor más comunes  
    * Cliente/Servidor de dos capas (2-Tier)  
    	La aplicación se divide en dos partes principales: el cliente y el servidor.    

    * Cliente/Servidor de tres capas (3-Tier)  
    	Agrega una capa intermedia entre el cliente y el servidor. 

    * Cliente/Servidor de n capas (n-Tier)  
    	Es una extensión del modelo de tres capas y puede tener múltiples capas intermedias según las necesidades de la aplicación.

    * Cliente/Servidor en la nube  
    	Implica que el cliente y el servidor se ejecutan en la nube (infraestructura remota) en lugar de en la infraestructura local del cliente.

---

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

---

### 2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web
* #### Estudio de cómo se ejecuta el código JavaScript en un navegador  
	1. Abrimos la consola del navegador (Ctrl + Shift + J, en Windows).
	2. Dentro de la consola vamos a Source > Snippets > New Snippet.
	3. Elegimos el nombre para el nuevo snippet.
	4. Una vez aquí escribimos el código y pulsamos Ctrl + Intro (Windows) para ejecutarlo.  

[![javascript-code.jpg](https://i.postimg.cc/PJNfCrvC/javascript-code.jpg)](https://postimg.cc/jn0Y9TXT)

---

* #### Evaluación de las diferencias de compatibilidad entre navegadores   
    Aunque se pueda pensar que hasta el código más simple se visualizará de la misma manera en cualquier navegador, tenemos que tener saber que esto no es cierto. Esto es debido, principalmente, a dos motivos:
    * Cada navegador tiene su propia interfaz o apariencia.
    * La ejecución de código en un navegador está ligada a su configuración de seguridad y al hecho de si JavaScript está o no activado.
    * El sistema operativo y el dispositivo que se use.

* #### Resolución de problemas de compatibilidad en una aplicación web  
	Las aplicaciones web pueden no funcionar correctamente en distintos navegadores, lo que requiere realizar pruebas funcionales y no funcionales, como pruebas de carga, de seguridad y de rendimiento, y recursos de desarrollo para garantizar la compatibilidad.

---

## 3. Lenguajes de Programación en Entorno Cliente
* #### Investigación de lenguajes como JavaScript, TypeScript, y otros  
	* JavaScript: (JS), es un lenguaje de programación ligero, interpretado y orientado a objetos con funcionalidades de de primera clase.

	* TypeScript: (TS) es un lenguaje de programación construido a un nivel superior que JavaScript. Es más limpio y sólido.

	* Otros
		Hay otros lenguajes que se utilizan en el entorno del cliente:  
		    - HTML y CSS. 
            - Python.
		    - Dart.
		    - Rust.  
		    - Elm.

---

* #### Comparación de sus características y aplicaciones
	##### Principales carácterísticas y aplicaciones de JavaScript:  
    * Interpretado.
	* Lenguaje de Scripting.  
	* Multiplataforma.
    * Desarrollo de Aplicaciones Web
    * Desarrollo de Juegos
	
	##### Principales carácterísticas y aplicaciones de TypeScript:
    * Tipado Estático.
    * Compilación.
    * Orientado a Objetos.
    * Desarrollo Back-End
    * Librerías y Frameworks
    
---

#### 4. Características de los Lenguajes de Script. Ventajas y Desventajas
* #### Análisis de las ventajas y desventajas de la programación en lenguajes de script sobre la programación tradicional  
	##### Principales ventajas de la programación de lenguajes de script:  
    	- Facilidad de aprendizaje.
    	- Desarrollo rápido.
		- Portabilidad.
		- Interpretación en tiempo real.
		- Dinamismo.
		- Integración con Web.

	##### Principales desventajas de la programación con lenguajes de script:
		- Rendimiento limitado.
		- Menor control de memoria.
		- Escalabilidad limitada.
		- Requisitos de interpretación.
		- Seguridad.
		- Menos adecuados para aplicaciones de bajo nivel.

---

### 5. Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML
* ##### Exploración de tecnologías como CSS y HTML5
    * HTML5: es la última versión del lenguaje de marcado HTML utilizado para crear la estructura de una página web. HTML (HyperText Markup Language) es un lenguaje de etiquetas que permite incluir o hacer referencia a todo tipo de información.    

	* CSS: (Cascading Style Sheets), significan «Hojas de Estilo en Cascada» y parten de un concepto simple pero muy potente: aplicar estilos (colores, formas, márgenes, etc...) a uno o varios documentos (generalmente documentos HTML) de forma automática y masiva. Se le denomina estilos en cascada porque se lee, procesa y aplica el código desde arriba hacia abajo y en el caso de existir ambigüedad, se siguen una serie de normas para resolver dicha ambigüedad.

---

* ##### Creación de una pequeña aplicación web integrando código JavaScript de diferentes maneras
	1. Todo el código dentro del mismo archivo .html:  
	[![calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-05.png](https://i.postimg.cc/7ZxpNPNh/calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-05.png)](https://postimg.cc/6ymjWXgx)

	2. El código JavaScript en un archivo .js aparte:  
	[![calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-12.png](https://i.postimg.cc/KjxNyjjg/calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-12.png)](https://postimg.cc/jw3NHszs) [![calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-18.png](https://i.postimg.cc/wvhVPLqp/calculadora-html-Tema-1-Visual-Studio-Code-22-09-2023-10-15-18.png)](https://postimg.cc/Kk8B3K3q)

---

#### 6. Herramientas de Programación
[![experiencia-programacion-persona-que-trabaja-codigos-computadora.jpg](https://i.postimg.cc/sXqMpNdf/experiencia-programacion-persona-que-trabaja-codigos-computadora.jpg)](https://postimg.cc/9RPX21Qs)

---

* ##### Uso de herramientas como Visual Studio Code, Chrome DevTools, etc.  
	* Visual Studio Code: es un editor de código fuente desarrollado por Microsoft que se ha vuelto extremadamente popular en la comunidad de desarrollo web debido a su rendimiento, extensibilidad y capacidad para admitir una variedad de lenguajes de programación y tecnologías web.

	* Chrome DevTools: es un conjunto de herramientas de desarrollo integradas en el navegador Google Chrome. Estas herramientas son esenciales para depurar y mejorar aplicaciones web.

	* Otras herramientas:  
		* Git.
		* Postman.
		* SASS/LESS.
		* Webpack.
		* Linter.