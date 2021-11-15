<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">MailerApp</h3>

  <p align="center">
    Una aplicación para enviar emails 💌
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de contenidos</summary>
  <ol>
    <li>
      <a href="#about-the-project">Acerca del proyecto</a>
      <ul>
        <li><a href="#built-with">Hecho con</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Inicio</a>
      <ul>
        <li><a href="#prerequisites">Pre-requisitos</a></li>
        <li><a href="#installation">Instalación</a></li>
      </ul>
    </li>
    <li><a href="#usage">Uso</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Acerca del proyecto


### Hecho con

- Python
- Flask
- HTML
- CSS
- SendGrid API

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Inicio

Para empezar el proyecto se necesita de algunas dependencias.

### Pre-requisitos

- Flask

  ```sh
  cd mailerapp
  py -3 -m venv venv
  source venv\Scripts\activate
  pip install Flask

  ```

- SendGrid
  ```sh
  pip install sendgrid
  ```
  
  
- SQLite3
  ```sh
  pip install sqlite
  ```
### Instalación

1. Las API key y el uso de la base de datos estarán en el archivo a entregar
2. git clone este repositorio
   ```sh
   git clone https://github.com/DiegoSE-FIME/MailerApp.git
   ```
3. Instala los modulos para python
   ```sh
   pip install -r requirements.txt
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Uso

   Para iniciar a usar la aplicación es necesario de una terminal con git y python instalados.

- Ingresar en la terminal los siguientes comandos para las variables de entorno.

  ```sh
  export FLASK_DATABASE_USER= *aquí iría la variable de entorno*
  export FLASK_DATABASE=
  export FLASK_DATABASE_PASSWORD=
  export FLASK_DATABASE_HOST=localhost
  export SENDGRID_API_KEY=
  ```

<p align="right">(<a href="#top">back to top</a>)</p>


