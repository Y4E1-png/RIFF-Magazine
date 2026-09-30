Español | [Read in English](README.md) 

# RIFF Magazine

Sitio web de una revista musical con diseño responsivo, desarrollado con HTML, CSS y Bootstrap.

Desarrollado como parte del programa de Desarrollo Front-End de EBAC para practicar diseños responsivos y componentes de Bootstrap.

El sitio incluye una página de inicio con contenido destacado y vistas previas de artículos, además de una página de contacto.

## Funcionalidades

- Navegación responsiva con un menú lateral en pantallas pequeñas.
- Carrusel para presentar contenido destacado.
- Tarjetas de artículos organizadas con el sistema de cuadrícula de Bootstrap.
- Acordeón con información sobre la revista.
- Ventana modal de suscripción con un campo de correo electrónico.
- Página de contacto con campos de nombre, correo electrónico y mensaje.
- Navegación y pie de página compartidos entre ambas páginas.

## Tecnologías

- **HTML5:** estructura y contenido de las páginas.
- **CSS:** estilos personalizados para las imágenes.
- **Bootstrap 5.3.3:** diseño responsivo, navegación, tarjetas, formularios y clases de utilidad.
- **Paquete JavaScript de Bootstrap:** interacción del carrusel, acordeón, ventana modal y menú lateral.

Los estilos y el JavaScript de Bootstrap se cargan mediante la CDN de jsDelivr.

## Cómo ejecutar el proyecto

### Requisitos

- Un navegador web.
- Git instalado para clonar el repositorio.
- Conexión a Internet para cargar Bootstrap desde la CDN.

### Instalación y uso

1. Clona el repositorio:

```bash
git clone https://github.com/Y4E1-png/RIFF-Magazine.git
cd RIFF-Magazine
```

2. Abre `index.html` en el navegador.

No es necesario instalar dependencias ni ejecutar un proceso de compilación.

## Ejemplo de uso

La interfaz del sitio está en español.

1. Abre la página de inicio.
2. Utiliza los controles del carrusel para cambiar entre las diapositivas destacadas.
3. Explora las tarjetas con vistas previas de artículos.
4. Despliega las preguntas del acordeón **Sobre RIFF**.
5. Presiona **Suscríbete** para abrir la ventana modal de suscripción.
6. Presiona **Contacto** para visitar la página de contacto.
7. Cambia el tamaño de la ventana del navegador para explorar la navegación responsiva.

## Alcance actual

- Las tarjetas muestran vistas previas de artículos. Sus enlaces **Leer más** son provisionales.
- El formulario de contacto y la ventana modal de suscripción son demostraciones de la interfaz. No están conectados a un backend ni a un servicio de correo electrónico.
- La página de inicio utiliza seis imágenes de una carpeta `img/`. Actualmente, estos archivos no están en el repositorio, por lo que las imágenes no aparecerán al ejecutar una copia recién clonada.

## Estructura del proyecto

```text
RIFF-Magazine/
├── index.html     Página de inicio
├── contacto.html  Página de contacto
└── .gitignore     Archivos excluidos del control de versiones
```

El CSS personalizado se encuentra dentro del elemento `<style>` de `index.html`. Bootstrap proporciona los demás estilos y componentes interactivos.

## Autor

Desarrollado por **Yael Aguilar** como parte del programa de Desarrollo Front-End de EBAC.

[Perfil de GitHub](https://github.com/Y4E1-png)
