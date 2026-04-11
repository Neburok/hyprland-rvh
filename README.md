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
│ ├── wofi/
│ └── kitty/
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

### ✅ Fase 2.2 — Gestión de dotfiles
- Uso de symlinks (manual)
- Integración repo ↔ sistema
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
- Transparencias (Kitty + Hyprland)
- Blur del compositor

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

### ⏸️ Fase 8 — Automatización (pendiente)
- Scripts personalizados
- Modos de trabajo
- Automatización basada en flujo real

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

```ini
 exec-once = waybar
exec-once = mako
exec-once = swaybg -i ~/projects/hyprland-rvh/assets/wallpapers/tu_imagen.jpg -m fill
```

## Transparencia (Kitty)
background_opacity 0.5
background #1e1e2e
enable_wayland true

## 🧪 Estado actual

✔ Entorno completamente funcional
✔ Uso diario viable
✔ Configuración versionada
✔ Sistema reproducible
✔ Estética consistente
✔ Flujo híbrido teclado + mouse

## Decisiones clave
No automatizar prematuramente
Priorizar uso real antes de optimización
Mantener KDE como entorno seguro
Configurar de forma incremental

## 🔮 Próximos pasos
Automatización basada en uso real
Scripts de entorno (modo trabajo, clase, etc.)
Integración con flujo académico
Mejora del launcher
Reglas inteligentes por aplicación

## 📌 Notas

Este repositorio es experimental y evoluciona conforme al uso real del entorno.

## 👤 Autor

Rubén Velázquez Hernández
Profesor universitario
Universidad Tecnológica de Querétaro
