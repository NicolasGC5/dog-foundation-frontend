# 🐾 Dog Foundation - Frontend

Este es el frontend de una aplicación full stack desarrollada para una fundación de perritos. La interfaz está construida con **React** y **Next.js**, e incluye funcionalidades tanto para usuarios comunes como para administradores.

---

## 🖥️ Funcionalidades del frontend

### 👥 Usuario común

- 🏠 Landing page informativa con mapa de Google Maps
- 📬 Suscripción a newsletter
- 🐶 Visualización de perritos disponibles
- 💳 Donación a perritos usando Stripe
- 🧾 Página de perfil editable (foto, nombre, correo, etc.)

### 🛠️ Administrador

- 📊 Dashboard con métricas: cantidad de usuarios, perritos, productos
- ➕ Creación de nuevos perritos
- 🛍️ Asignación de productos específicos a cada perrito (para ser donados)
- 🚫 Ban de usuarios

---

## 🚀 Tecnologías usadas

- **React**
- **Next.js**
- **TypeScript**
- **Tailwind CSS**
- **Axios**
- **Stripe (Checkout)**
- **Cloudinary (para imágenes)**

---

## 🧪 Cómo correr el proyecto

1. Cloná el repositorio:

``bash
git clone https://github.com/NicolasGC5/dog-foundation-frontend.git
cd dog-foundation-frontend

2.Instalá las dependencias:

npm install

3. Configurá tus variables de entorno (.env.local)
Usá el archivo .env.example como guía.

Para el deploy este proyecto puede desplegarse fácilmente en Vercel u otra plataforma compatible con Next.js.

