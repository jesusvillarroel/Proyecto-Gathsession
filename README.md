# 📸 gathsession

Proyecto creado para poner en práctica la maquetación web moderna utilizando **Vite** como empaquetador de módulos y **Sass** con arquitectura modular.

🚀 **[Ver el sitio web en vivo aquí](https://jesusvillarroel.github.io/Proyecto-Gathsession/)**

## 📂 Arquitectura del Proyecto (Sass 7-1)
Los estilos del sitio están organizados de forma modular bajo una variante de la arquitectura 7-1 de Sass, facilitando el mantenimiento y la escalabilidad del código:

* **`abstracts/`**: Variables globales, funciones y mixins (herramientas sin salida de CSS directo).
* **`base/`**: Estilos globales, normalización (reset) y reglas tipográficas.
* **`layout/`**: Estructura de las secciones principales del sitio, incluyendo el diseño asimétrico del **Hero** (con la session  fotografíca en el lado derecho).
* **`components/`**: Elementos de UI reutilizables como botones.

> 🛠️ **Inyección de estilos**: Toda la arquitectura se centraliza en un archivo `main.scss`, el cual es importado directamente desde el módulo principal de JavaScript (`main.js`) conectado al `index.html`.

## 🛠️ Tecnologías Utilizadas
* **Vite** - Frontend Tooling de última generación.
* **Sass (SCSS)** - Preprocesador con arquitectura modular.
* **Vanilla JavaScript** - Lógica nativa (ECMAScript Modules).
* **GitHub Pages & Actions** - Automatización de despliegue continuo (CI/CD).

## 🚀 Instalación Local

Si deseas clonar este proyecto y ejecutarlo en tu computadora, sigue estos pasos:

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/jesusvillarroel/Proyecto-Gathsession.git
   ```
2. Entrar a la carpeta del proyecto:
   ```bash
   cd Proyecto-Gathsession
   ```
3. Instalar las dependencias locales (incluyendo Vite y Sass):
   ```bash
   npm install
   ```
4. Iniciar el servidor de desarrollo:
   ```bash
   npm run dev
   ```
