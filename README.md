# Hyprland RVH Setup

Base system:
- Fedora 43
- KDE Plasma
- GPU: NVIDIA RTX 3060

Strategy:
- Hyprland as secondary session
- Dotfiles managed with Git

## Repositorios adicionales

- COPR: solopasha/hyprland

## Fase 1 - Instalación base

- Hyprland instalado desde COPR
- Sesión disponible en SDDM
- Primer arranque probado
- Sistema KDE intacto


# Hyprland RVH

Repositorio experimental para la configuración de un entorno de escritorio basado en Hyprland sobre Fedora.

---

## 🎯 Objetivo

Construir un entorno:

- Minimalista
- Reproducible
- Versionado con Git
- Adaptado a flujo de trabajo académico y técnico

---

## 🧠 Filosofía

Este proyecto sigue el principio de:

> "Configurar solo lo necesario, entender cada componente y versionar todo el proceso"

---

## 🖥️ Sistema base

- OS: Fedora 43
- Entorno principal: KDE Plasma (como respaldo)
- Entorno experimental: Hyprland
- GPU: NVIDIA RTX 3060

---

## 🧱 Arquitectura
Sistema (Fedora + KDE)
↓
Hyprland (sesión alterna)
↓
Dotfiles (Git)
↓
Configuración reproducible


---

## 📂 Estructura del repositorio


hyprland-rvh/
├── dotfiles/
│ ├── hypr/
│ ├── waybar/
│ └── wofi/
│
├── scripts/
│
├── assets/
│ └── wallpapers/
│
├── README.md

---

## 🚀 Fases del proyecto

### ✅ Fase 0 — Preparación
- Creación de repositorio
- Backup de configuración
- Documentación inicial

---

### ✅ Fase 1 — Instalación base
- Instalación de Hyprland (COPR)
- Configuración NVIDIA
- Validación como sesión alterna

---

### ✅ Fase 2 — Configuración base
- Creación de `hyprland.conf`
- Configuración mínima funcional
- Versionado en Git

---

### ✅ Fase 2.2 — Gestión con symlinks
- Integración de dotfiles con el sistema
- Uso de enlaces simbólicos (manual)
- Eliminación de duplicación

---

### ✅ Fase 3 — Entorno usable
- Integración de Waybar
- Notificaciones (Mako)
- Inicio automático

---

### ✅ Fase 3.2 — Personalización de Waybar
- Configuración modular
- Estilo visual consistente
- Resolución de errores JSON

---

### ✅ Fase 4 — Estética
- Tema oscuro coherente
- Bordes de ventanas
- Fondo de pantalla versionado

---

### ✅ Fase 4.2 — Flujo de trabajo
- Workspaces
- Navegación con teclado
- Recarga dinámica de configuración

---

### ✅ Fase 5 — Interacción avanzada
- Resize de ventanas
- Floating mode
- Fullscreen

---

### ✅ Fase 6 — Identidad visual
- Paleta de colores consistente
- Tipografía
- Mejora de legibilidad

---

### ✅ Fase 7 — Launcher
- Configuración de Wofi
- Estilo personalizado
- Acceso rápido a aplicaciones

---

### ✅ Fase 7.5 — Gestión de archivos
- Integración de Thunar
- Tema oscuro GTK
- Atajos de acceso rápido

---

## 🧰 Herramientas principales

- Hyprland — compositor Wayland
- Waybar — barra de estado
- Wofi — launcher
- Thunar — gestor de archivos
- Kitty — terminal
- Git — control de versiones

---

## 🔧 Configuración clave

### Teclado

```ini
input {
    kb_layout = es
}
```
## Autostart
exec-once = waybar
exec-once = mako
exec-once = swaybg -i ~/projects/hyprland-rvh/assets/wallpapers/tu_imagen.jpg -m fill

## 🧪 Estado actual

✔ Entorno completamente funcional
✔ Uso diario viable
✔ Configuración versionada
✔ Sistema reproducible

## 🔮 Próximos pasos
Scripts de automatización
Integración con flujo académico
Launcher avanzado
Reglas inteligentes por aplicación

## 📌 Notas

Este repositorio es experimental y evoluciona continuamente.

## 👤 Autor

Rubén Velázquez Hernández
Profesor universitario
Universidad Tecnológica de Querétaro
