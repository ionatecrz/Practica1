# Práctica 1: Gestión de Repositorios con Git y Configuración de Entorno Java

## Descripción de la Práctica
Esta práctica tiene como objetivo familiarizarse con el uso de **Git** y **GitHub**, así como configurar un entorno de desarrollo en **Java**. Los pasos incluyen realizar un fork de un repositorio, ejecutar comandos básicos de Git y documentar la instalación de herramientas necesarias.

---

## Desarrollo de la Práctica

### 1. Uso de Git y GitHub

#### Fork del Repositorio
- Se realizó un fork del repositorio original:
  - URL: [https://github.com/gitt-3-pat/p1](https://github.com/gitt-3-pat/p1)

#### Comandos de Git

- **Clonar el repositorio:**
  ```bash
  git clone https://github.com/ionatecrz/p1.git
  ```
  Este comando descarga el repositorio forked a la máquina local.

- **Ver estado del repositorio:**
  ```bash
  git status
  ```
  Permite verificar los cambios realizados y el estado de los archivos.

- **Añadir archivos al staging:**
  ```bash
  git add nombre_del_archivo
  ```
  Prepara los archivos seleccionados para el commit.

- **Guardar cambios en el historial:**
  ```bash
  git commit -m "Descripción del cambio"
  ```
  Registra los cambios agregados al repositorio local.

- **Subir cambios al repositorio remoto:**
  ```bash
  git push origin main
  ```
  Envía los commits locales al repositorio de GitHub.

- **Cambiar de rama:**
  ```bash
  git checkout -b nueva-rama
  ```
  Crea y cambia a una nueva rama para trabajo paralelo.

#### Documentación de Comandos
- Se incluye el archivo `git.txt` donde se explica cada comando con capturas de pantalla y logs de la consola.

---

### 2. Configuración del Entorno de Desarrollo en Java

#### Software Instalado
- **Java 17**
- **Maven**
- **Editores de Código:** Visual Studio Code y/o IntelliJ IDEA

#### Evidencias de Instalación
- Se incluyen capturas de pantalla y logs en el archivo `entorno.txt`:
  - **Java:**
    ```bash
    java --version
    ```
  - **Maven:**
    ```bash
    mvn --version
    ```
  - **VSCode e IntelliJ:** capturas de sus interfaces.

---

## Entrega de la Práctica
La práctica se entregará subiendo el repositorio a GitHub y compartiendo el enlace en Moodle:

URL del repositorio: [https://github.com/ionatecrz/p1](https://github.com/ionatecrz/p1)

---

## Criterios de Evaluación

- **0 → 5:** Entrega a tiempo, repositorio funcional.
- **5 → 8:** Cumplimiento completo de los requisitos.
- **8 → 10:** Inclusión de mejoras adicionales (uso de README detallado, enlaces, imágenes, documentación extra).

**Nota:** Por cada día de retraso (máximo una semana), se restará 1 punto. Más de una semana de retraso será considerado como **no presentado**.

---

## Autor
- **Nombre:** Íñigo de Oñate Cruz  
- **Contacto:** [LinkedIn](https://www.linkedin.com/in/%C3%AD%C3%B1igo-de-o%C3%B1ate-cruz-855b55263/)

