# PRODUCT.md — EduAlex • Enlaces

## Qué es
Hub de enlaces ("link in bio") de EduAlex en `edualex.uy`. Una sola página que reúne
todos los recursos, plataformas y herramientas digitales de EduAlex para potenciar
la educación media en Uruguay.

## Audiencia
Docentes y estudiantes de educación media en Uruguay, mayormente en móvil,
a menudo con una mano en el aula. Español (es-UY).

## Objetivo único
Que el visitante encuentre y toque el enlace que busca en segundos.

## Contenido
Fuente de verdad: `public/links.json` (`avatar`, `name`, `bio`, `links`).
Cada enlace: `title`, `url`, `icon` (lucide), `color` (tinte del icono), `desc`
(visible solo en desktop; mobile muestra solo título).

## Identidad visual
- Neobrutalismo con un único tema claro: fondo crema cuadriculado, superficies
  marfil, bordes negros y sombras sólidas sin desenfoque.
- Acentos en amarillo, azul y verde pastel; títulos de peso fuerte.
- Lista vertical en móvil y grilla uniforme de 2 columnas en desktop (≥640px).
- Buscador con filtro instantáneo (insensible a tildes), estado vacío y contador.
- Tipografía del sistema. Footer: `EduAlex · <año>`.
## Restricciones
- No agregar copy ni claims nuevos sin pedirlo; los textos viven en `links.json`.
- Mobile intocable en espíritu: simple, rápido, pulgar-amigable.
- Accesibilidad: foco visible, `prefers-reduced-motion`, contraste ≥4.5:1 en texto.
- Solo tema claro, definido en CSS y en los metadatos de color. Sin selector de tema ni preferencias de localStorage.
