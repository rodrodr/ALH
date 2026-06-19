# Repositorio Público de Metadatos: América Latina Hoy (ALH)

Este repositorio contiene los metadatos y resúmenes estructurados de cada artículo y volumen de la revista científica **América Latina Hoy (ALH)**, editada por **Ediciones Universidad de Salamanca**.

## 🤖 Optimización para Modelos de IA (LLMs) y RAG
Este repositorio ha sido diseñado específicamente para ser fácilmente indexado, leído y comprendido por agentes de Inteligencia Artificial, herramientas de búsqueda MCP y utilidades de crawling web (como `webfetch`):

1. **Formatos Comprensibles**: Cada artículo cuenta con una versión en **Markdown (.md)** que combina un bloque de frontmatter YAML estructurado y el texto limpio en lenguaje natural, y un archivo **JSON-LD (.json)** compatible con Schema.org (`ScholarlyArticle`).
2. **Facilidad de Crawling**: Se ha incluido un archivo `llms.txt` en la raíz del repositorio que actúa como mapa del sitio optimizado para que los LLMs identifiquen rápidamente los artículos disponibles.
3. **Base de Datos Consolidada**: El archivo `catalog.json` recopila de forma unificada toda la información bibliográfica de la revista para permitir consultas rápidas sin recorrer archivos individuales.

## 📁 Estructura del Repositorio
```text
├── README.md               # Este archivo
├── llms.txt                # Mapa de contenidos para LLMs
├── catalog.json            # Base de datos global de artículos en JSON
└── volumes/
    └── v95/                # Carpeta por volumen
        ├── alh-v95-32518.md       # Metadatos del artículo y resumen en Markdown
        ├── alh-v95-32518.json     # Metadatos en JSON-LD (Schema.org)
        └── ...
```

## 📜 Licencia
Los artículos de la revista *América Latina Hoy* están disponibles bajo una licencia **Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)**.
