[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/mutazen/gestion-citas-access-2007">
    <img src="readme-images/logo.png" alt="Logo" width="500" height="350">
  </a>

  <p align="center">
    <a href="https://https://github.com/mutazen/gestion-citas-access-2007"><strong>Ver documentación»</strong></a>
    <br />
    <br />
    <a href="https://github.com/mutazen/gestion-citas-access-2007/issues">Reportar Bug</a>
    ·
    <a href="https://github.com/mutazen/gestion-citas-access-2007/issues">Solicitar nueva funcionalidad</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Índice</summary>
  <ol>
    <li>
      <a href="#acerca-del-proyecto">Acerca del proyecto</a>
      <ul>
        <li>
          <a href="#restricciones-iniciales">Restricciones iniciales</a>
        </li>
        <li>
          <a href="#características">Características</a>
        </li>
      </ul>
    </li>
    <li>
      <a href="#preparando-la-aplicación">Preparando la aplicación</a>
      <ul>
        <li>
          <a href="#requisitos">Requisitos</a>
        </li>
        <li>
          <a href="#instalación">Instalación</a>
        </li>
        <li>
          <a href="#configuración">Configuración</a>
        </li>
      </ul>
    </li>
    <li>
      <a href="#guía-de-uso">Guía de uso</a>
      <ul>
        <li>
          <a href="#ver-citas">Ver citas</a>
          <ul>
            <li>
              <a href="#ver-citas-de-un-dia-en-concreto">Ver citas de un día en concreto</a>
            </li>
            <li>
              <a href="#ver-citas-de-la-semana-anterior-o-posterior">Ver citas de la semana anterior o posterior</a>
            </li>
            <li>
              <a href="#ver-citas-del-mes-anterior-o-posterior">Ver citas del mes anterior o posterior</a>
            </li>
            <li>
              <a href="#ver-citas-de-un-area-determinada">Ver citas de un área determinada.</a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#crear-cita">Crear cita</a>
        </li>
        <li>
          <a href="#modificar-cita">Modificar cita</a>
        </li>
        <li>
          <a href="#eliminar-cita">Eliminar cita</a>
        </li>
        <li>
          <a href="#copiar-cita">Copiar cita</a>
        </li>
        <li>
          <a href="#buscar-cita">Buscar cita</a>
          <ul>
            <li>
              <a href="#buscar-por-nombre">Buscar por nombre</a>
            </li>
            <li>
              <a href="#buscar-por-apellidos">Buscar por apellidos</a>
            </li>
            <li>
              <a href="#buscar-por-DNI">Buscar por DNI</a>
            </li>
            <li>
              <a href="#buscar-por-DNI">Buscar por NIE</a>
            </li>
            <li>
              <a href="#buscar-por-pasaporte">Buscar por pasaporte</a>
            </li>
            <li>
              <a href="#buscar-por-teléfono">Buscar por teléfono</a>
            </li>
            <li>
              <a href="#buscar-por-fecha">Buscar por fecha</a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#asignar-asistencia">Asignar asistencia</a>
        </li>
        <li>
          <a href="#designar-dia">Designar dia</a>
          <ul>
            <li>
              <a href="#designar-dia-para-atender-citas">Designar dia para atender citas</a>
            </li>
            <li>
              <a href="#designar-dia-como-festivo">Designar dia como festivo</a>
            </li>
            <li>
              <a href="#eliminar-designación">Eliminar designación</a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#reservar-hora">Reservar hora</a>
          <ul>
            <li>
              <a href="#crear-reserva">Crear reserva</a>
            </li>
            <li>
              <a href="#ver-reserva">Ver reserva</a>
            </li>
            <li>
              <a href="#modificar-reserva">Modificar reserva</a>
            </li>
            <li>
              <a href="#eliminar-reserva">Eliminar reserva</a>
            </li>
          </ul>
        </li>
        <li>
          <a href="#imprimir-ficha-de-gestión-de-citas">Imprimir ficha de gestión de citas</a>
        </li>
      </ul>
    </li>
    <li><a href="#cronología">Cronología</a></li>
    <li><a href="#contribuciones">Contribuciones</a></li>
    <li><a href="#licencia">Licencia</a></li>
    <li><a href="#contactis">Contacto</a></li>
    <li><a href="#conocimientos">Conocimientos</a></li>
    <li><a href="#agradecimientos">Agradecimientos</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Acerca del proyecto 

Conforme pasa el tiempo, queda más claro que las empresas deben digitalizar las herramientas que utilizan en el desarrollo de su actividad si quieren mejorar la calidad del servicio que proporcionan. No obstante, para las empresas más pequeñas, el costo de la adquisión del software y de la infraestructura de red que necesitan es inasumible.

Un ejemplo de empresa que se enfrenta a este tipo de problemas son las ONG más pequeñas, las cuales no cuentan con los recursos necesarios para poder digitalizar convenientemente los procesos que realizan en el desarrollo de su actividad. Y que en muchos casos, la infraestructura técnologica con la cuentan está desfasada.

Este proyecto surge para dar respuesta a esta problemática de una ONG en particular, desarrollando una solución para gestionar las citas de los usuarios adaptada al software y a la estructura de red disponible.

![Product Main Screen Shot][product-screenshot]

### Restricciones iniciales.

A la hora de desarrollar este proyecto se contaba con las siguientes restricciones:
* Utilizar software y la infraestructura tecnológica existente. 
 
En este caso, se decidió emplear Microsoft Access 2007 porque estaba presente en todos los equipos de la empresa y su implantación no implicaba excesiva modificación de la configuración de los equipos existente, que consistía en varios equipos de trabajo conectados en la misma red LAN.

* Se debe poder trabajar con la solución desde varios equipos de la red y al mismo tiempo.

Para poder permitir el trabajo simúltaneo, se controlan cuando los usuarios crean o modifican citas. Bloqueándo la hora en la que se asigna una cita durante su creación para que otros usuarios no puedan crear otra nueva. Y bloqueando el acceso a los datos de la cita, cuando otro usuario está modificando sus datos. 

### Características.

Para cumplir con su objectivo, esta solución es capaz de:
* Gestionar los datos de la citas: información personal de los usuarios, datos de contacto y anotaciones.
* Gestionar las horas y los dias en los que se pueden concertar citas y para que áreas.
* Llevar el control de la asistencia de los usuarios a sus respectivas citas.
* Asegurarse que los datos tengan el formato adecuado, controlando la entrada de datos cuando es posible.
* Buscar citas en función de los datos de la cita.

<!-- GETTING STARTED -->
## Preparando la aplicación
### Requisitos
Tener instalado Microsoft Access 2007. No funciona con versiones posteriores de Access.

### Instalación

1. Clona el repositorio.
   ```sh
   git clone https://github.com/mutazen/gestion-citas-access-2007.git
   ```
2. Ejecuta Citas.accdb

### Configuración

Antes de abrir el ejecutable de este proyecto, es preciso añadir al centro de confianza de Access la ubicación desde donde se va ejecutar dicho archivo. Con esto se evita que se muestre cada vez que se acceda a la solución. A continuación se describe como realizar esta configuración.

1. Abrimos Access 2007 directamente o hacemos abrimos un archivo de access mientras pulsamos la tecla "Shift". En pantalla principal de Access, hacemos clic en el logo de Office de la parte superior izquierda de la pantalla y en la nueva pantalla, accemos clic en el botón "Opciones de Access".

![acceder a configuracion de access][configuracion-1]

2. En la nueva pantalla, seleccionamos la opción "Centro de confianza" de la parte izquierda de la pantalla y en la parte derecha, hacemos clic en el botón "Configuración del Centro de Confianza".
 
![acceder a configuracion del centro de confianza][configuracion-2]

3. En este otra pantalla, pinchamos en "Ubicaciones de confiaza" en la columna de la parte izquierda de la pantalla y en la parte derecha, comprobamos si ya está registrada el directorio desde donde ejecutaremos el proyecto. En caso negativo, podemos agregar la el directorio haciendo clic en el botón "Agregar nueva ubicación ...". Si se quiere ejecutar el archivo desde otro ordenador, es necesario marcar la opción "Permitir ubicaciones de confianza que están en red" y después agregar la ubicación del directorio en red. 

![agragar ubicacion del directorio del proyecto][configuracion-3]

<!-- USAGE EXAMPLES -->
## Guía de uso
### Ver citas

Para poder ver las citas, partimos desde el menú principal de la solución. En él podemos indicar si quieremos ver las citas del turno de manaña o del turno de tarde.

![elegir turno en el menu principal][ver-cita-1]

Al hacer clic, se nos muestra la pantalla desde donde podemos ver las citas registradas para la semana actual.

![ver pantalla de citasl][ver-cita-2]

#### Ver citas de un día en concreto

Si se quiere ver las citas de un día en concreto, se puede utilizar el calendario que se encuentra en la parte superior de la izquierda de la pantalla en la que se muestran las citas. Este calendario cuenta tambien con dos controles que permiten seleccionar el mes y el año que se muestran en el calendario.

![ver controles de calendariol][ver-cita-3]

Si seleccionamos el mes y el año en los controles descritos anteriormente, el calendario cambiará para mostrar el mes del año indicado. Si hacemos clic en uno de los dias del calendario, se cambiarán las citas que se estaban mostrando para mostrar las citas de la semana al que pertenece el dia en el que se haya hecho clic en el calendario.

![modificar controles de calendariol][ver-cita-4]

#### Ver citas de la semana anterior o posterior

#### Ver citas del mes anterior o posterior

#### Ver citas de una area determinada

### Crear cita

### Modificar cita

### Eliminar cita

### Buscar cita

#### Buscar por nombre

#### Buscar por DNI

#### Buscar por NIE

#### Buscar por pasaporte

#### Buscar por teléfono

#### Buscar por fecha

### Asignar asistencia

### Designar dia

#### Designar dia para atender citas

#### Designar dia como festivo

#### Elimnar designación

### Reserva hora

#### Crear reserva

#### Ver reserva

#### Modificar reserva

#### Eliminar reserva

### Imprimir ficha de gestión de citas

<!-- ROADMAP -->
## Cronología

Vea [open issues](https://github.com/mutazen/gestion-citas-access-2007/issues) para ver una lista de las características propuestas y de los bugs conocidos.


<!-- CONTRIBUTING -->
## Contribuciones

Las contribuciones son lo que hace que la comunidad de "open source" sea un lugar increíble para aprender, inspirarse y crear. Cualquier contribución que se haga se **aprecia mucho**

1. Fork el proyecto.
2. Crear una nueva rama para la funcionalidad a añadir (`git checkout -b feature/AmazingFeature`)
3. Haz "commit" de los cambios realizados (`git commit -m 'Add some AmazingFeature'`)
4. Actualiza la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request



<!-- LICENSE -->
## Licencia

Distrubuido bajo la licencia  MIT. Vea `LICENCIA` para más información.

<!-- CONTACT -->
## Contactos
<p>
  Jeremy Camacho - https://www.linkedin.com/in/jeremycamacholugo/
</p>
<p>
  Project Link: https://github.com/mutazen/gestion-citas-access-2007
</p>


<!-- ACKNOWLEDGEMENTS -->
## Conocimientos
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)

## Agradecimientos

Quiero agredecer a @othneildrew por compartir la plantilla que se usó como base de este readme.

<p align="center">
  https://github.com/othneildrew/Best-README-Template
</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/mutazen/gestion-citas-access-2007.svg?style=for-the-badge
[contributors-url]: https://github.com/mutazen/gestion-citas-access-2007/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/mutazen/gestion-citas-access-2007.svg?style=for-the-badge
[forks-url]: https://github.com/mutazen/gestion-citas-access-2007/network/members
[stars-shield]: https://img.shields.io/github/stars/mutazen/gestion-citas-access-2007.svg?style=for-the-badge
[stars-url]: https://github.com/mutazen/gestion-citas-access-2007/stargazers
[issues-shield]: https://img.shields.io/github/issues/mutazen/gestion-citas-access-2007.svg?style=for-the-badge
[issues-url]: https://github.com/mutazen/gestion-citas-access-2007/issues
[license-shield]: https://img.shields.io/github/license/mutazen/gestion-citas-access-2007.svg?style=for-the-badge&
[license-url]: https://github.com/mutazen/gestion-citas-access-2007/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jeremycamacholugo/
[product-screenshot]: readme-images/image-1.png
[configuracion-1]: readme-images/configuracion/configuracion-1.png
[configuracion-2]: readme-images/configuracion/configuracion-2.png
[configuracion-3]: readme-images/configuracion/configuracion-3.png
[ver-cita-1]: readme-images/ver-citas/ver-cita-1.png
[ver-cita-2]: readme-images/ver-citas/ver-cita-2.png
[ver-cita-3]: readme-images/ver-citas/ver-cita-3.png
[ver-cita-4]: readme-images/ver-citas/ver-cita-4.png
