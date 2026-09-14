# 🍃 Control Verde Pro

> **Gestión financiera local, privada y eficiente.**  
> Una aplicación web ligera y autónoma para el control de finanzas personales, construida sin dependencias externas ni rastreadores.

![Version](https://img.shields.io/badge/version-1.2.0-10b981?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-064e3b?style=for-the-badge)
![Dependencies](https://img.shields.io/badge/dependencies-0%20(Vanilla%20JS)-047857?style=for-the-badge)
![Privacy](https://img.shields.io/badge/data-100%25%20Local-10b981?style=for-the-badge)

---

## 📌 Descripción

**Control Verde Pro** es una herramienta PWA-ready de presupuestación financiera diseñada bajo el principio de **Privacidad Primero (Privacy-First)**. Permite registrar ingresos, clasificar gastos por categorías y visualizar balances en tiempo real mediante renderizado dinámico en CSS sin frameworks pesados.

Toda la información permanece procesada y almacenada **exclusivamente en el navegador del usuario**, garantizando privacidad absoluta de los datos financieros.

---

## ✨ Características Principales

* **🔒 100% Local y Privado:** Sin bases de datos remotas ni APIs de terceros. Tienes el control total de tus datos.
* **📈 Visualización Dinámica:**
  * **Balance General:** Proporción de ingresos vs. egresos y saldo disponible.
  * **Desglose por Categorías:** Gráficos circulares en CSS nativo (`conic-gradient`) calculados en grados sexagesimales precisos.
* **📂 Respaldos y Migración:** Funcionalidad integrada para exportar e importar copias de seguridad en formato JSON.
* **⚡ Alta Eficiencia:** Construido en código ejecutable nativo en cualquier navegador moderno con consumo mínimo de recursos.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica accesible.
* **CSS3:** Variables CSS (`:root`), Grid/Flexbox para diseño responsivo y `conic-gradient` para renderizado de gráficos.
* **JavaScript (ES6+):** Lógica de cálculo financiero, manipulación del DOM y persistencia vía `localStorage`.

---

## 📊 Arquitectura de Datos y Cálculos

La aplicación procesa internamente los datos con las siguientes fórmulas matemáticas para garantizar coherencia en la interfaz:

* **Saldo Disponible:**  
  $$\text{Disponible} = \sum \text{Ingresos} - \sum \text{Gastos}$$

* **Proporción de Gráfico (Ángulo Cónico):**  
  $$\theta_c = \left( \frac{\text{Gasto Categoría}}{\text{Total Gastos}} \right) \times 360^\circ$$

---

## 🚀 Instalación y Uso

No requiere proceso de compilación (*build step*) ni servidores backend:

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/control-verde-pro.git](https://github.com/tu-usuario/control-verde-pro.git)
   ```
---

### ​📄 Licencia:

<div align="center">
Desarrollado con 💚 por <strong>Thaurock</strong>
</div>


