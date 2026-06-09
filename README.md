# 🎵 Sistema de Gestión y Venta de Entradas para Conciertos

## 📖 Descripción

Este proyecto es una aplicación web desarrollada en Laravel que permite gestionar la venta de entradas para conciertos. El sistema facilita la selección de asientos, el registro de compradores, la generación de tickets en PDF y el envío automático de las entradas por correo electrónico.

---

## 🎯 Objetivo

Automatizar el proceso de venta y administración de entradas para eventos musicales, permitiendo un control eficiente de los asientos disponibles y vendidos.

---

## ⚙️ Funcionalidades

### 🎫 Reserva de Entradas

Los usuarios pueden:

- Visualizar los asientos disponibles.
- Seleccionar uno o varios asientos.
- Registrar sus datos personales.
- Confirmar la compra.

Una vez finalizada la compra, los asientos quedan marcados como vendidos.

---

### 👤 Registro de Compradores

El sistema almacena la información del comprador:

- Nombre
- Correo electrónico
- Teléfono
- Dirección

Estos datos quedan asociados a las entradas adquiridas.

---

### 📄 Generación de Tickets

Después de realizar la compra:

- Se genera automáticamente un ticket en formato PDF.
- El comprador puede descargar el ticket.
- El ticket contiene la información de la reserva realizada.

---

### 📧 Envío de Tickets por Correo

El sistema envía automáticamente un correo electrónico al comprador con:

- Confirmación de la compra.
- Ticket en PDF adjunto.

---

### 🛒 Venta Masiva de Entradas

Permite registrar múltiples asientos en una sola operación, facilitando la compra para grupos de personas.

---

### 🔐 Inicio de Sesión

El sistema cuenta con autenticación para administradores mediante usuario y contraseña.

---

### 📊 Panel Administrativo

Los administradores pueden:

- Consultar las ventas realizadas.
- Gestionar usuarios.
- Visualizar compradores registrados.
- Controlar los asientos vendidos y disponibles.
- Administrar recaudos y cobros.

---

## 🏗️ Arquitectura del Proyecto

El sistema fue desarrollado siguiendo el patrón de arquitectura **MVC (Modelo - Vista - Controlador)**.

### Modelos

Gestionan la información almacenada en la base de datos.

Principales entidades:

- Buyer
- Seat
- SeatSold
- Collection
- UserGmo

### Vistas

Proporcionan la interfaz gráfica para clientes y administradores.

### Controladores

Gestionan la lógica del negocio y la comunicación entre modelos y vistas.

---

## 🔄 Flujo de Funcionamiento

```text
Cliente ingresa al sistema
        ↓
Visualiza los asientos disponibles
        ↓
Selecciona los asientos deseados
        ↓
Ingresa sus datos personales
        ↓
Se registra la compra
        ↓
Los asientos cambian a estado vendido
        ↓
Se genera el ticket PDF
        ↓
Se envía el ticket por correo electrónico
```

## 🛠️ Tecnologías Utilizadas

- PHP
- Laravel
- MySQL
- HTML5
- CSS3
- JavaScript
- DomPDF
- SMTP para envío de correos

---

## 📂 Módulos del Sistema

### Módulo de Clientes

- Reserva de entradas.
- Consulta de disponibilidad.
- Descarga de tickets.

### Módulo de Ventas

- Venta individual.
- Venta masiva.
- Registro de compradores.

### Módulo Administrativo

- Gestión de usuarios.
- Gestión de ventas.
- Gestión de recaudos.
- Supervisión general del sistema.

---

## ✅ Beneficios

- Automatización del proceso de venta.
- Reducción de errores manuales.
- Generación automática de tickets.
- Envío inmediato de confirmaciones por correo.
- Administración centralizada de la información.

---

## 👨‍💻 Autor

Proyecto desarrollado como práctica académica para la gestión y venta de entradas de conciertos utilizando Laravel.