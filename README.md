# 🧾 Sistema POS con Laravel (Open Source)

Sistema de punto de venta (POS) desarrollado con **Laravel 7**, ideal para pequeños negocios que necesitan gestionar ventas, inventario y clientes de forma sencilla y eficiente.

---

## 🌐 Vista previa

![Sistema POS Laravel](https://parzibyte.me/blog/wp-content/uploads/2020/03/Inicio-Punto-de-venta-con-Laravel-usuarios-y-clientes.png)

---

## 🚀 Características

- ⚙️ Desarrollado con **Laravel 7**
- 🎨 Interfaz con **Bootstrap**
- ⭐ Iconos con **FontAwesome**
- 📱 Diseño **responsive** (móvil, tablet y escritorio)
- 📦 Control de inventario:
  - Precio de compra
  - Precio de venta
  - Utilidad
  - Existencias
- 🛒 Sistema de ventas:
  - Agregar productos fácilmente
  - Validación de stock
  - Actualización automática de inventario
- 🧾 Impresión de tickets en impresora térmica
- 📊 Reportes de ventas
- 🔐 Sistema de autenticación (login/registro)
- 📱 Aplicación móvil Android conectada al sistema

---

## 🖼️ Ejemplo de ticket

![Ticket de venta](https://parzibyte.me/blog/wp-content/uploads/2020/03/Ticket-de-venta-impreso-desde-PDV-con-Laravel.jpg)

---

## 📚 Tutorial

Puedes aprender a usar y configurar este sistema en los siguientes enlaces:

- 📖 [Tutorial completo](https://parzibyte.me/blog/2020/03/06/sistema-ventas-laravel-bootstrap-mysql-open-source/)
- 📖 [Parte 2 (clientes y usuarios)](https://parzibyte.me/blog/2020/03/10/laravel-pos-clientes-usuarios/)

---

## 📲 Aplicación móvil

Este sistema cuenta con una app que consume su API:

- 🤖 Android:  
https://github.com/parzibyte/sistema_ventas_laravel/raw/master/PuntoDeVenta1.0.apk  

- 🍎 iOS:  
No disponible (puedes usar la versión Android)

---

## 🧱 Tecnologías utilizadas

- **Laravel 7**
- **PHP**
- **MySQL**
- **Bootstrap**
- **JavaScript**
- **FontAwesome**

---

## ⚙️ Instalación

```bash id="posinstall02"
# Clonar repositorio
git clone https://github.com/tu-usuario/pos-laravel.git

# Entrar al proyecto
cd pos-laravel

# Instalar dependencias
composer install

# Configurar entorno
cp .env.example .env

# Generar clave
php artisan key:generate

# Ejecutar migraciones
php artisan migrate

# Iniciar servidor
php artisan serve
📌 Requisitos
PHP >= 7.2
Composer
MySQL o MariaDB
Servidor local (XAMPP, Laragon, etc.)
👨‍💻 Autor

Isai Reyes
