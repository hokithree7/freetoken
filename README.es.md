# FreeToken.link — encuentra y verifica una ruta LLM con acceso gratuito

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [한국어](README.ko.md)

[![Resumen de FreeToken.link](assets/freetoken-overview.png)](https://freetoken.link/es)

**FreeToken.link ayuda a desarrolladores a comparar condiciones de acceso gratuito con fecha, seguir la ruta oficial para obtener una clave, verificar rutas compatibles desde el navegador y generar plantillas de configuración que omiten claves reales. También permite crear una Watchlist de cambios importantes.**

Versión en español: **[freetoken.link/es](https://freetoken.link/es)**

> Este repositorio público contiene documentación, materiales de lanzamiento y un canal de comentarios. No publica el código de producción, credenciales de proveedores, claves compartidas, datos privados del Vault ni secretos operativos.

## Usa FreeToken desde un asistente de IA

El **servidor MCP de FreeToken**, de solo lectura, ya está disponible y registrado como [`link.freetoken/catalog`](https://registry.modelcontextprotocol.io/v0.1/servers/link.freetoken%2Fcatalog/versions/1.0.0), versión **1.0.0**, en el MCP Registry oficial.

Añade **`https://freetoken.link/mcp`** a un cliente compatible con Streamable HTTP. No necesitas una cuenta ni una API key de FreeToken. Puedes buscar modelos publicados, consultar guías oficiales y precios con fecha, estimar costes, leer comprobaciones existentes y generar configuraciones sin claves reales. No ejecuta inferencias, pruebas de claves, comprobaciones de disponibilidad en tiempo real ni acceso al Vault privado. El texto de los resultados está actualmente en inglés; locale solo selecciona el idioma de los enlaces al sitio.

[Guía de conexión en español](https://freetoken.link/es/mcp-guide) · [Herramientas y límites (inglés)](docs/MCP.md)

## Qué puedes hacer

- [Buscar una API por requisitos (inglés)](https://freetoken.link/find)
- [Filtrar modelos y proveedores revisados](https://freetoken.link/es/models)
- [Seguir el proceso oficial para obtener una clave](https://freetoken.link/es/get-key)
- [Diagnosticar una clave directamente en el navegador](https://freetoken.link/es/doctor)
- [Probar un prompt sin un proxy de FreeToken](https://freetoken.link/es/playground)
- [Generar una configuración sin claves reales](https://freetoken.link/es/playground#tool-config)
- [Comparar referencias de precios](https://freetoken.link/es/pricing)
- [Consultar comprobaciones de disponibilidad existentes](https://freetoken.link/es/status)
- [Crear una Watchlist de cambios importantes](https://freetoken.link/es/watchlist)
- [Consultar las fuentes y el método de verificación](https://freetoken.link/es/sources)

## Confianza y privacidad

FreeToken separa lo que afirma la documentación oficial de las observaciones del Canary operado por FreeToken. En las comprobaciones compatibles con conexión directa, las claves y los prompts viajan desde el navegador al proveedor seleccionado. Los enlaces compartidos no contienen claves. FreeToken no distribuye claves extraídas, revendidas, compartidas o agrupadas.

Si encuentras un identificador de modelo incorrecto, una condición desactualizada o un enlace oficial roto, abre un issue de tipo Source correction con la fuente oficial y la fecha de comprobación. No publiques claves, tokens ni datos personales.

El producto y las páginas SEO canónicas permanecen en `https://freetoken.link/`. Este repositorio sirve para documentación transparente, referencias y feedback de desarrolladores.
