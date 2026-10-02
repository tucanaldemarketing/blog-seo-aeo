# Blog SEO + AEO: skill para Claude

Una skill que escribe artículos de blog pensados para **posicionar en Google y para que las IA (ChatGPT, Gemini, Perplexity) los citen**. Sirve para cualquier negocio y cualquier sector.

## Qué hace

1. **La primera vez te entrevista** (unos 10 minutos): tu negocio, tu lector, tu forma de hablar, los datos que puedes demostrar y el editor donde publicas. Lo guarda en `perfil-blog.md` y no vuelve a preguntarlo.
2. **Por cada artículo** te hace unas pocas preguntas, investiga en la web con fuentes y te presenta un **brief**. No escribe nada hasta que lo apruebas.
3. **Te entrega el artículo campo a campo** (título, URL, meta title, meta description, cuerpo en bloques, preguntas frecuentes), listo para pegar en tu CMS.

**Lo que no hace:** no publica, no se conecta a tu web y no se inventa datos. Si una cifra no tiene origen, la quita.

## Instalación

**Claude Code:** copia la carpeta `blog-seo-aeo` (con su `SKILL.md`) en `.claude/skills/` de tu proyecto.

**App de Claude:** descarga el repositorio como ZIP (botón verde *Code → Download ZIP*), y en *Ajustes → Capacidades* sube la carpeta `blog-seo-aeo` comprimida. Si tu plan no permite subir skills, pega el contenido de `SKILL.md` al empezar la conversación.

Después escribe: *"escribe un artículo para mi blog"*.

## Créditos

Creada por **Camilo Díaz Arbeláez** · [@marketingconcamilo](https://www.instagram.com/marketingconcamilo/) · [marketingconcamilo.com](https://marketingconcamilo.com).
Adapta ideas de proyectos abiertos citados al final de `SKILL.md`.
