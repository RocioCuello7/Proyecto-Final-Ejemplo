# Fragments of You

**Integrantes:** Rocío Abril Cuello, Valentino Dacal

## Descripción
El proyecto, “Fragments of You”, surge como una propuesta para la materia de LPOO. El juego se centra en Glenn,
personaje protagonista que atraviesa el duelo por la pérdida y el asesinato de su abuela. A través de una narrativa metafórica y sentimental, el 
jugador deberá superar enemigos que representan los sentimientos durante el duelo, buscando que la jugabilidad no sea solamente un desafío 
técnico, sino también una experiencia psicológica.

## Tecnologías
* **Lenguaje:** Java 21 (JDK 21 LTS)
* **Framework:** LibGDX (v1.14.2.0)
* **Físicas:** Box2D
* **Iluminación:** Box2DLights
* **Persistencia:** SQLite y JDBC (Tecnologías previstas para etapas posteriores).
* **Plataforma:** Escritorio (LWJGL3)


## Cómo compilar y ejecutar
Para compilar y ejecutar el proyecto, es necesario tener instalado **JDK 21** en el sistema.

1. Clona este repositorio en tu equipo local.
2. Abre la carpeta raíz del proyecto en **IntelliJ IDEA**.
3. El proyecto será reconocido automáticamente como un proyecto Gradle.
4. Una vez sincronizado, abre una terminal posicionada en la **carpeta raíz** del proyecto y ejecuta el comando correspondiente según tu sistema operativo:

   * **Windows:** `gradlew.bat lwjgl3:run`
   * **Linux/macOS:** `./gradlew lwjgl3:run`

## Estado actual
* **Pre-entrega N°1:** Inicialización del entorno de desarrollo y estructura base del proyecto mediante LibGDX Liftoff. Se encuentran configuradas las dependencias de Box2D y Box2DLights en el módulo `core`.

## Documentación
El historial de cambios y la propuesta formal del proyecto se encuentran en la Wiki y en el archivo CHANGELOG.md.

**Enlace a la Wiki del Proyecto (Propuesta Detallada):**
[Ver la Propuesta Completa del Proyecto](https://github.com/RocioCuello7/Proyecto-Final-Fragments-of-You/wiki/Propuesta-del-Proyecto-%E2%80%90-Fragments-of-You)
