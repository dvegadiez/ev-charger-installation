# Tesla Charger Installer

Sitio web profesional para captar clientes interesados en la instalacion de cargadores para vehiculos electricos en Miami y areas cercanas.

El objetivo del proyecto es crear una experiencia rapida, clara y optimizada para dispositivos moviles que convierta visitantes en solicitudes de cotizacion mediante formulario, llamada telefonica o WhatsApp.

## Objetivo del sitio

El sitio esta pensado para promocionar servicios como:

- Instalacion de Tesla Wall Connector.
- Instalacion de cargadores EV residenciales y comerciales ligeros.
- Instalacion de tomas NEMA 14-50.
- Circuitos dedicados de 240V.
- Evaluacion de paneles electricos.

El publico objetivo incluye duenos de viviendas, townhouses, condominios y pequenos negocios que necesitan una solucion segura y profesional para cargar vehiculos electricos.

## Stack elegido

Este proyecto esta previsto como una aplicacion web frontend moderna basada en:

- Astro
- React
- TypeScript
- HTML semantico
- CSS responsive
- Datos estructurados para SEO local

Astro sera la base principal por su rendimiento, SEO y capacidad de generar paginas estaticas rapidas. React se usara solo donde aporte valor, por ejemplo formularios, componentes interactivos o estados dinamicos.

El proyecto contiene una estructura inicial minima con una pagina de "Hola mundo" para permitir trabajo paralelo en integracion continua, despliegue y futuras funcionalidades.

## Comandos previstos

```bash
npm install
```

Instala las dependencias del proyecto.

```bash
npm run dev
```

Inicia el servidor local de desarrollo.

```bash
npm run build
```

Genera la version optimizada para produccion.

```bash
npm run preview
```

Previsualiza localmente el build de produccion.

## Estructura esperada

Una vez inicializado el frontend, se espera una estructura similar a:

```text
tesla-charger-installer/
  public/
    images/
  src/
    assets/
    components/
    layouts/
    pages/
    data/
    styles/
    env.d.ts
  astro.config.mjs
  package.json
  tsconfig.json
  README.md
```

## SEO local

El contenido del sitio debe ayudar a Google a identificar claramente el servicio, la ubicacion y las areas atendidas.

Palabras clave objetivo:

- EV charger installation Miami
- Tesla Wall Connector installation Miami
- Tesla charger installation near me
- NEMA 14-50 outlet installation Miami

Buenas practicas previstas:

- Titulo y meta descripcion optimizados.
- Encabezados claros por servicio y ubicacion.
- URLs descriptivas si se agregan paginas internas.
- Texto alternativo en imagenes.
- Preguntas frecuentes orientadas a busquedas locales.
- Datos estructurados para negocio local.
- Llamadas a la accion visibles durante la navegacion.

## Conversion y lead generation

El sitio debe priorizar contacto rapido mediante:

- Request an Estimate
- Call Now
- Send Photos by WhatsApp

El formulario inicial debe ser corto e incluir:

- Nombre
- Telefono
- Ciudad o ZIP code
- Servicio requerido
- Urgencia del proyecto
- Mensaje opcional

## Configuracion futura

Cuando se implemente la aplicacion, conviene centralizar estos valores en variables de entorno o en un archivo de configuracion:

```text
PUBLIC_BUSINESS_NAME=
PUBLIC_PHONE=
PUBLIC_WHATSAPP_NUMBER=
PUBLIC_CONTACT_EMAIL=
PUBLIC_FORM_ENDPOINT=
PUBLIC_GOOGLE_BUSINESS_URL=
```

No se deben publicar datos sensibles en el repositorio. Los archivos `.env` locales deben quedar fuera de Git.

## Estado actual

Este repositorio contiene la documentacion inicial y un esqueleto Astro + React listo para instalar dependencias, ejecutar en local y conectar procesos de integracion continua.
