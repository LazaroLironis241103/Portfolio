# Portfolio - Lázaro Lironis

## Estructura
public/
  index.html
  styles.css
  main.js
  manifest.json
  service-worker.js
  assets/

## Deploy en Firebase Hosting (pasos exactos)
1. Instalar Firebase CLI:
   npm install -g firebase-tools

2. Login:
   firebase login

3. Inicializar hosting dentro de la carpeta raíz del repo (asegúrate que exista `public/`):
   firebase init hosting
   - Selecciona o crea proyecto
   - Public directory: public
   - Configure as SPA: Yes (rewrites to index.html)

4. Deploy:
   firebase deploy --only hosting

## Verificaciones recomendadas
- Lighthouse: Performance >= 70, Accessibility >= 90, Best Practices >= 90, SEO >= 90
- Navegación solo con teclado: Tab, Shift+Tab y foco visible
- Contrastes WCAG AA (texto y CTAs)
- Comprimir imágenes en WebP/AVIF (opcional para mejorar performance)

## Reemplazar placeholders
- Sustituir imágenes en public/assets/
- Editar textos y enlaces en public/index.html
- Actualizar project cards con enlaces demo y repo
