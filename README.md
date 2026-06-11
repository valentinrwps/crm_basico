# NexusCRM — El CRM que cierra más ventas

Landing page moderna y completa para un CRM empresarial 2026, construida en un solo archivo HTML con CSS y JavaScript embebidos. Sin dependencias de frontend, lista para desplegar en segundos.

## Vista previa

![NexusCRM](https://img.shields.io/badge/Estado-Producción-10B981?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-Embebido-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Railway](https://img.shields.io/badge/Deploy-Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)

---

## Módulos del CRM

### 🧑‍🤝‍🧑 Gestión de Clientes
- Base de datos centralizada con búsqueda avanzada
- Segmentación automática por comportamiento
- Historial completo de comunicaciones y notas
- Lead scoring con Inteligencia Artificial
- Alertas de seguimiento automático

### 🛒 E-Commerce Digital
- Catálogo de productos digitales ilimitado (cursos, ebooks, plantillas, software, membresías)
- Pasarela de pago multi-divisa — Stripe y PayPal
- Entrega automática por email tras la compra
- Upsells y cross-sells inteligentes
- Sistema de afiliados y comisiones automatizadas

### 📱 Social Media & Captación de Leads
- Integración directa con Meta Lead Ads (Facebook e Instagram)
- Captación de leads de LinkedIn y TikTok en tiempo real
- Programación y publicación multi-plataforma
- Bandeja de entrada unificada de mensajes directos
- Analytics de alcance, impresiones y conversiones por plataforma

### 🤖 Automatización con IA
- Constructor visual de flujos (drag & drop)
- Disparadores por comportamiento del usuario
- Secuencias automáticas de email y WhatsApp
- Chatbot de IA para atención 24/7
- Generación de propuestas y contratos con IA

### 📊 Analytics & Reportes
- Dashboard de KPIs en tiempo real
- Reporte de ingresos por producto y canal
- Análisis del funnel de conversión
- Predicciones de ventas con IA
- Exportación a PDF, Excel o Google Sheets

### 🎯 Pipeline de Ventas (Kanban)
- Tablero visual con etapas personalizables
- Arrastrar y soltar oportunidades entre etapas
- Recordatorios y tareas por oportunidad
- Forecast de ingresos automático
- Comisiones y cuotas por vendedor

---

## Integraciones nativas

| Plataforma | Uso |
|---|---|
| **Stripe** | Pagos, suscripciones y facturación |
| **WhatsApp Business** | Mensajes automatizados y atención |
| **Meta Business** | Facebook e Instagram Ads |
| **LinkedIn Ads** | Captación de leads B2B |
| **TikTok for Business** | Lead generation y analítica |
| **Zapier** | Conexión con +6,000 apps |
| **Mailchimp** | Sincronización de listas y email |
| **Google Analytics** | Atribución multicanal |

---

## Dashboard interactivo

La landing incluye una vista previa funcional con 4 pestañas navegables:

- **📊 Dashboard** — KPIs en tiempo real, gráficas de ingresos, distribución de leads por canal
- **🎯 Pipeline** — Tablero Kanban con oportunidades de venta en distintas etapas
- **📱 Social Media** — Leads captados, alcance por plataforma, publicaciones programadas
- **🛒 E-Commerce** — Catálogo de productos digitales y listado de pedidos recientes

---

## Planes de precios

| Plan | Precio | Contactos | Destacado |
|---|---|---|---|
| **Starter** | $49/mes | Hasta 1,000 | E-commerce básico, 2 redes sociales |
| **Growth** | $149/mes | Hasta 10,000 | Automatizaciones + Asistente IA |
| **Enterprise** | $499/mes | Ilimitados | API custom + Gerente dedicado |

Todos los planes incluyen **14 días de prueba gratuita** sin tarjeta de crédito.

---

## Estructura del proyecto

```
crm_basico/
├── index.html      # App completa (HTML + CSS + JS embebidos)
├── package.json    # Configuración del servidor estático para Railway
├── .gitignore
└── README.md
```

---

## Despliegue en Railway

Este proyecto está optimizado para despliegue inmediato en [Railway](https://railway.app).

### Pasos

1. Entra a [railway.app](https://railway.app) y crea un nuevo proyecto
2. Elige **Deploy from GitHub repo**
3. Selecciona el repositorio `crm_basico`
4. Railway detecta el `package.json` automáticamente y usa `serve` para servir el sitio
5. En menos de 1 minuto tendrás una URL pública

### Cómo funciona

```json
{
  "scripts": {
    "start": "serve . -p ${PORT:-3000}"
  }
}
```

Railway inyecta la variable `$PORT` automáticamente. El paquete `serve` expone el `index.html` en esa dirección.

### Variables de entorno

No se requieren variables de entorno para el funcionamiento básico. Railway asigna `PORT` de forma automática.

---

## Desarrollo local

```bash
# Instalar dependencias
npm install

# Iniciar servidor local
npm start
```

Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

También puedes abrir `index.html` directamente en el navegador sin ningún servidor.

---

## Tecnologías

- **HTML5** — Estructura semántica
- **CSS3** — Variables CSS, Grid, Flexbox, animaciones, glassmorphism
- **JavaScript** — Navegación entre tabs, animaciones por scroll (IntersectionObserver)
- **serve** — Servidor estático Node.js para producción

---

## Paleta de colores

| Token | Valor | Uso |
|---|---|---|
| `--bg` | `#0F172A` | Fondo principal |
| `--bg2` | `#1E293B` | Tarjetas y paneles |
| `--primary` | `#3B82F6` | Botones y elementos primarios |
| `--accent` | `#60A5FA` | Acentos y highlights |
| `--success` | `#10B981` | Estados positivos |
| `--text` | `#F1F5F9` | Texto principal |
| `--text2` | `#94A3B8` | Texto secundario |

---

## Licencia

MIT — libre para uso personal y comercial.
