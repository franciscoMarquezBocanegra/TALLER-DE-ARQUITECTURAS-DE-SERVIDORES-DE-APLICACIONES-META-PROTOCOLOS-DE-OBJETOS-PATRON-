# TALLER 4: TALLER DE ARQUITECTURAS DE SERVIDORES DE APLICACIONES, META PROTOCOLOS DE OBJETOS, PATRÓN IOC, REFLEXIÓN


Para este taller los estudiantes deberán construir un servidor Web (tipo Apache) en Java. El servidor debe ser capaz de entregar páginas html e imágenes tipo PNG. Igualmente el servidor debe proveer un framework IoC para la construcción de aplicaciones web a partir de POJOS. Usando el servidor se debe construir una aplicación Web de ejemplo. El servidor debe atender múltiples solicitudes no concurrentes.

Para este taller desarrolle un prototipo mínimo que demuestre capcidades reflexivas de JAVA y permita por lo menos cargar un bean (POJO) y derivar una aplicación Web a partir de él. 

Debe entregar su trabajo al final del laboratorio. Luego puede complementar para entregarlo en 8 días. Se verificara y compararán el commit del día de inicio del laboratorio y el dela entrega final.

### Prerequisitos

Para elaborar este proyecto se requirio de : 


Maven: Apache Maven es una herramienta que maneja el ciclo de vida del programa.



Git: Es un sistema de control de versiones distribuido (VCS).



Java 17: Java es un lenguaje de programación de propósito general orientado a objetos, portátil y muy versátil.



### Instalación

Clonamos el repositorio

```
    git clone https://github.com/franciscoMarquezBocanegra/TALLER-DE-ARQUITECTURAS-DE-SERVIDORES-DE-APLICACIONES-META-PROTOCOLOS-DE-OBJETOS-PATRON-

```
Se accede a la carpeta principal del repositorio repositorio que acabamos de clonar

	 cd TALLER-DE-ARQUITECTURAS-DE-SERVIDORES-DE-APLICACIONES-META-PROTOCOLOS-DE-OBJETOS-PATRON-

Hacemos la construccion del proyecto

	 mvn package
---
### Corriendo
Corremos los siguientes comando
	
	 mvn clean package install
	 mvn clean install

Ahora corremos el servidor
	
**Windows**

	 java -cp "target\classes" edu.escuelaing.arep.ASE.app.main


**Linux/MacOs**

	 java -cp target/classes edu.escuelaing.arep.ASE.app.main


Por ultimo accedemos a nuestro navegador  siguiente URL

	 http://localhost:35000/

Aqui nos debera de cargar la siguiente pagina, con la cual podemos empezar a hacer las busquedas que necesitemos

![image](https://github.com/franciscoMarquezBocanegra/TALLER-DE-ARQUITECTURAS-DE-SERVIDORES-DE-APLICACIONES-META-PROTOCOLOS-DE-OBJETOS-PATRON-/assets/98216991/67050245-f204-45ef-9250-8422bba24a95)


# Documentos HTML

![image](https://github.com/franciscoMarquezBocanegra/TALLER-DE-ARQUITECTURAS-DE-SERVIDORES-DE-APLICACIONES-META-PROTOCOLOS-DE-OBJETOS-PATRON-/assets/98216991/96a5fa17-4e87-441e-8ffa-9eeca808ae08)




# Documentos PNG

![image](https://github.com/franciscoMarquezBocanegra/TALLER-DE-ARQUITECTURAS-DE-SERVIDORES-DE-APLICACIONES-META-PROTOCOLOS-DE-OBJETOS-PATRON-/assets/98216991/5e028c17-1ea5-465e-984c-4bb517559db7)









# ¿Como el desarrollador crearia una aplicacion con este marco de trabajo?


Es simple, considere los siguientes pasos

1. Cree una clase dentro del los archivos edu.escuelaing.arep.ASE.app

   ![image](https://github.com/julianCS21/AREP04/assets/96396177/5941d148-b0e6-4085-a1a9-eaae581d10af)


2. Cree los metodos que considere necesarios, pero a su vez percatese de colocar la etiqueta RequestMapping(cabe aclarar que deben ser static y deben retornar string)

   ![image](https://github.com/julianCS21/AREP04/assets/96396177/1856cc79-be9c-4b56-b674-09e14a53ff95)


3. corra el servidor y revise que desde el navegador funcione lo implementado

   ![image](https://github.com/franciscoMarquezBocanegra/TALLER-DE-ARQUITECTURAS-DE-SERVIDORES-DE-APLICACIONES-META-PROTOCOLOS-DE-OBJETOS-PATRON-/assets/98216991/90cdaaab-9292-4153-b1a3-d889ee79c709)



---
### Corriendo test

Ejecutamos el comando

	mvn test
	
---





## Construido con

* [Maven](https://maven.apache.org/): Apache Maven es una herramienta que estandariza la configuración del ciclo de vida del proyecto.
* [Git](https://rometools.github.io/rome/):  Es un sistema de control de versiones distribuido (VCS).
* [Intellj](https://www.jetbrains.com/es-es/idea/): IntelliJ IDEA es un IDE que ayuda a los desarrolladores a escribir, depurar y administrar código de manera más eficiente y efectiva, con muchas características que facilitan el proceso de desarrollo de software.
* [Java 19](https://www.java.com/es/): Lenguaje de programación de propósito general con enfoque a el paradigma de orientado a objetos, y con un fuerte tipado de variables.
* [Html](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/HTML_basics): es un lenguaje de marcado que estructura una página web y su contenido.
* [JavaScript](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/What_is_JavaScript): lenguaje de programación que los desarrolladores utilizan para hacer paginas web dinamicas.
* [CSS](https://developer.mozilla.org/es/docs/Web/CSS) Lenguaje para darles estilos a paginas web.


## Autor
* Francisco Marquez
