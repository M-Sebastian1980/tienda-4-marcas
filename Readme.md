# Tienda 4 Marcas - 2025

E-commerce estático de **4 marcas deportivas** (landing, catálogo por marca, detalle de producto y contacto) hecho con **HTML + CSS + Bootstrap 5**.

## 🚀 Objetivos
- Mostrar productos de 4 marcas (slides/carouseles por marca).
- Página de detalle con fotos, precio y descripción.
- Contacto con formulario + mapa embebido.
- Diseño **responsive** (SM/MD/LG) y accesible.

## 🛠️ Stack
- HTML5, CSS3
- Bootstrap 5.3.x (CDN)
- (Opcional) Íconos: Font Awesome / Bootstrap Icons

## 📁 Estructura sugerida
- /assets
- /img
- /css
- /pages
- styles.css
- index.html
- productos.html # grilla por marca
- detalle.html # detalle de producto
- contacto.html # formulario + mapa


## 🔧 Uso local
No requiere servidor: abrí `index.html` en el navegador.  
(Opcional) Si usás Live Server de VSCode, mejor para auto-refresh.

## 🌿 Flujo de trabajo (Git)
- Rama principal: `main`
- Rama de desarrollo: `dev`
- Feature branches: `feature/nombre-corto`
- Fix branches: `fix/descripcion`

**Pasos típicos:**
- bash
- git checkout -b feature/seccion-contacto
# ... cambios ...
- git add .
- git commit -m "feat(contacto): agrega formulario y mapa"
- git push -u origin feature/seccion-contacto
# abrir Pull Request → base: dev

## 🧾 Convención de commits

Usaremos prefijos para mantener un historial limpio y claro:

- `feat:` nueva funcionalidad  
- `fix:` corrección de errores  
- `chore:` tareas varias (estructura, configuración, limpieza)  
- `style:` estilos, maquetado o cambios visuales  
- `docs:` documentación o comentarios

---

## ✅ Checklist inicial

- [ ] Navbar con links a secciones  
- [ ] Carrusel/slider por cada marca  
- [ ] Cards de productos (SM=2, MD=4, LG=6 por slide)  
- [ ] Página de detalle con specs y CTA  
- [ ] Formulario de contacto con validación de Bootstrap  
- [ ] Footer con redes sociales

---

## 👥 Equipo

- **Owner:** @tuUsuario  
- **Colaboradores:** @user1, @user2, @user3  

> *(Reemplazá los nombres por los usuarios reales del equipo)*

---

## 📄 Licencia

Proyecto distribuido bajo la licencia **MIT**.  
Podés modificarla o reemplazarla si el equipo lo requiere.
