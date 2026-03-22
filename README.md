# Proyecto de TrackNenjoy (ProyectoMeliDani)

[![Licencia](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Un proyecto de ingeniería de software. Esta es una API de backend construida con .NET que permite a los usuarios gestionar una lista de deseos de contenido (como películas o series).

---

## 🚀 Características Principales

* **Gestión de Contenido:** Añadir, eliminar y actualizar contenido en la lista de un usuario.
* **Seguimiento de Estado:** Marcar contenido como "visto", "viendo" o "por ver".
* **Persistencia de Datos:** La información del usuario y sus listas se guardan en un archivo `usuarios.json`.
* **Pruebas Unitarias:** El proyecto incluye un conjunto de pruebas unitarias (`MtBackend.Tests`) para asegurar la calidad del código.

---

## 🛠️ Tecnologías Utilizadas

* **Backend:** .NET 10 (C#) / ASP.NET Core Web API
* **Pruebas:** MSTest
* **Almacenamiento de Datos:** Archivo plano JSON (`usuarios.json`)
* **Serialización:** Newtonsoft.Json

---

## 🏁 Empezando (Getting Started)

Sigue estos pasos para tener una copia local del proyecto funcionando.

### Prerrequisitos

Asegúrate de tener instalado lo siguiente:

* [SDK de .NET 10.0](https://dotnet.microsoft.com/es-es/download) (o la versión especificada en `global.json` o los archivos `.csproj`)
* [Git](https://git-scm.com/)

### 🔧 Instalación

1.  Clona el repositorio:
    ```sh
    git clone [https://github.com/AndresFrank0/ProyectoMeliDani.git](https://github.com/AndresFrank0/ProyectoMeliDani.git)
    ```

2.  Navega a la carpeta del proyecto:
    ```sh
    cd ProyectoMeliDani
    ```

3.  Restaura las dependencias de los proyectos (puedes hacerlo desde la raíz `pruebadelnet`):
    ```sh
    dotnet restore
    ```

---

## 🏃 Uso

1.  Navega a la carpeta del proyecto principal (el que contiene los controladores):
    ```sh
    cd TestProject
    ```

2.  Ejecuta la aplicación:
    ```sh
    dotnet run
    ```
    La API ahora estará corriendo, usualmente en `http://localhost:5000` o `http://localhost:5001`.

---

## 🧪 Pruebas

Este proyecto usa MSTest para las pruebas unitarias y de integración.

1.  Navega a la carpeta raíz de la solución (`pruebadelnet`) o a la carpeta de pruebas:
    ```sh
    cd TestProject/MtBackend.Tests
    ```

2.  Ejecuta las pruebas:
    ```sh
    dotnet test
    ```
    Verás un resumen en la terminal indicando cuántas pruebas pasaron o fallaron.

---

## 📜 Licencia

Este proyecto está bajo la Licencia MIT.
