# 🔍 OSINTkit — Consola OSINT y SOCMINT

> Caja de herramientas de inteligencia de fuentes abiertas (OSINT) y SOCMINT en un único archivo HTML. Sin backend, sin instalación y sin dependencias externas en tiempo de ejecución.

![Estado](https://img.shields.io/badge/estado-activo-brightgreen)
![Licencia](https://img.shields.io/badge/licencia-MIT-blue)
![Single File](https://img.shields.io/badge/single--file-100%25-cyan)
![Dark Mode](https://img.shields.io/badge/tema-dark-0a0a0a)

---

## ✨ Características

- 🕵️ Búsqueda de usuarios en múltiples plataformas (SOCMINT)
- 🔎 Google Dorks preconfigurados y personalizables
- 🌐 Consultas DNS (A, MX, TXT, NS, CNAME)
- 🧭 Enumeración de subdominios
- 📇 WHOIS / RDAP de dominios
- 🗺️ GeoIP y geolocalización de IPs
- 📧 Análisis de email (formato, MX, dominio)
- 📱 Análisis de teléfonos (formato, país, prefijo)
- 🎨 Interfaz dark-mode moderna
- 📦 Todo en un único archivo `.html` — portable, sin instalación

---

## 🚀 Uso rápido

### Opción 1 — Abrir directamente
Abre `OSINTkit-single.html` en tu navegador. No hace falta backend ni dependencias.

### Opción 2 — Servir localmente
```bash
python3 -m http.server 8000
```
Luego abre:

```text
http://localhost:8000/OSINTkit-single.html
```

---

## 🧠 Nota importante

Este proyecto usa APIs públicas del navegador para consultar información disponible en Internet. Algunas consultas pueden depender de CORS o de la disponibilidad del servicio y no garantizan resultados en todas las redes.

---

## 📌 Estructura

```text
OSINTkit-single.html
README.md
```

---

## 🛡️ Seguridad y ética

Usa esta herramienta solo con fines legales, éticos y autorizados. Las consultas públicas no sustituyen la validación de cumplimiento legal ni la revisión del contexto del ejercicio.

