PORTAFOLIO WEB — GUÍA PARA PRINCIPIANTES
=======================================

ANTES DE PUBLICAR
1. Abre index.html con un editor de texto (recomendado: Visual Studio Code, gratuito).
2. Busca y reemplaza TODOS los textos entre corchetes: [Tu nombre completo], [Nombre de tu universidad], etc.
3. En la sección de contacto, reemplaza [TU-CORREO] por tu dirección real (sin corchetes) y actualiza el enlace de LinkedIn.
4. Coloca tu fotografía profesional en la carpeta assets y nómbrala exactamente: foto-perfil.jpg
   Recomendación: imagen JPG, vertical, bien iluminada y de tamaño razonable (idealmente menos de 500 KB).
5. En styles.css, al principio, modifica las variables --color-primary y --color-accent si deseas cambiar la paleta.
6. En index.html cambia las direcciones canonical, og:url, og:image y el bloque JSON-LD.
7. En sitemap.xml y robots.txt cambia [TU-USUARIO] y [TU-REPOSITORIO] por los valores reales.

PUBLICAR EN GITHUB PAGES
1. Entra a https://github.com/ y pulsa Sign up si aún no tienes cuenta.
2. Crea tu cuenta con correo, contraseña y nombre de usuario. Verifica tu correo.
3. Inicia sesión y pulsa el botón + (arriba a la derecha) > New repository.
4. Escribe un nombre, por ejemplo: portafolio-administracion-negocios.
5. Selecciona Public. No necesitas marcar README, .gitignore ni licencia para este proyecto.
6. Pulsa Create repository.
7. En el repositorio, pulsa Add file > Upload files.
8. Arrastra index.html, styles.css, script.js, sitemap.xml, robots.txt y la carpeta assets completa.
   Importante: index.html debe quedar en la raíz del repositorio, no dentro de otra carpeta.
9. Escribe un mensaje como "Publicar portafolio inicial" y pulsa Commit changes.
10. Abre Settings (pestaña del repositorio) > Pages.
11. En Build and deployment, selecciona Deploy from a branch.
12. En Branch elige main y carpeta /(root). Pulsa Save.
13. Espera unos minutos y vuelve a Settings > Pages. Allí aparecerá el enlace público.
    Normalmente será: https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/

COMPROBAR LA WEB
- Abre el enlace público en una ventana privada/incógnito.
- Comprueba navegación, fotografía, correo, LinkedIn y que se vea bien en un teléfono.
- Si aparece 404, confirma que index.html está en la raíz y que Pages está configurado en main / (root).
- Cada cambio posterior se publica al subir/confirmar los archivos actualizados.

SEO Y GOOGLE
1. Sustituye las URL provisionales en canonical, Open Graph, sitemap.xml y robots.txt por la URL pública exacta.
2. Entra a https://search.google.com/search-console/ e inicia sesión con tu cuenta Google.
3. Añade una propiedad. Para empezar, selecciona "Prefijo de URL" e introduce la URL pública exacta.
4. Sigue el método de verificación que Google te ofrezca. Si ofrece una etiqueta HTML, copia la etiqueta meta completa dentro de <head> en index.html, antes de </head>, y vuelve a subir el archivo. Después pulsa Verificar.
5. En Search Console abre Sitemaps, escribe sitemap.xml y pulsa Enviar.
6. Usa Inspección de URL, pega la URL principal y pulsa Solicitar indexación.
7. La indexación no es inmediata ni está garantizada. Google puede tardar días o semanas; no existe una forma legítima de garantizar aparecer en los primeros resultados.

CONSEJOS PARA QUE TE ENCUENTREN
- Usa tu nombre completo real de forma consistente en el título, H1 y texto de presentación.
- Completa el perfil de LinkedIn y enlázalo desde la web.
- Comparte el enlace en tu CV y perfiles profesionales.
- Mantén los proyectos y cursos actualizados.
- No publiques teléfono, dirección particular, documentos personales ni datos privados.
- No inventes cursos, docentes, experiencia ni certificaciones: elimina los bloques que no correspondan.

ESTRUCTURA
portafolio-administracion-negocios/
  index.html
  styles.css
  script.js
  sitemap.xml
  robots.txt
  assets/
    (coloca aquí foto-perfil.jpg)


DATOS YA PERSONALIZADOS
- Nombre: Ticona Chata Chiara Valentina
- Universidad: Universidad Católica San Pablo
- Carrera: Administración de Negocios
- Ciclo: IV ciclo
- Ciudad: Arequipa, Perú
- Correo: chiara.ticona@ucsp.edu.pe
- LinkedIn: https://www.linkedin.com/in/chiara-valentina-ticona-chata-7286a9451/

PENDIENTE ANTES DE PUBLICAR
- Añadir tu foto en assets/foto-perfil.jpg.
- Completar intereses, objetivos, cursos, docentes, proyectos, habilidades y experiencia.
- Sustituir [TU-USUARIO] y [TU-REPOSITORIO] en index.html, sitemap.xml y robots.txt
  por tu usuario y nombre real del repositorio de GitHub.
