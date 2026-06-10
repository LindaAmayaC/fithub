# 💪 FitHub

Mi hub personal de entrenamiento y nutrición. Construido en HTML/CSS/JS puro, sin frameworks, todo guardado en `localStorage` del navegador.

🔗 **Demo:** [https://tu-usuario.github.io/fithub/](https://tu-usuario.github.io/fithub/)

## ✨ Qué incluye

- **🍑 Rutina semanal de Linda** — 4 días de fuerza con foco en glúteos y abdomen, calculadora de calorías personalizada
- **💪 Rutina semanal de Alan** — 5 días de fuerza centrados en pecho/brazos/pierna, con registro de PRs
- **🥗 Plan de comidas antiinflamatorio** — 17 comidas con macros, días tipo con comparativa contra metas personales
- **📊 Registros semanales** — historial de peso, medidas y tendencias

## 🎯 Funcionalidades

- ✅ Calculadora dinámica de macros (Mifflin-St Jeor)
- ✅ Checklist de ejercicios con barra de progreso
- ✅ **Modo edición** para cambiar ejercicios de la rutina
- ✅ Comparativa automática entre días tipo y metas reales
- ✅ Historial semanal con tendencias (peso, medidas, PRs)
- ✅ 100% responsive (móvil + desktop)
- ✅ Imprimible (`Ctrl + P` → guarda como PDF)
- ✅ Sin servidor: corre 100% en el navegador

## 📁 Estructura

```
fithub/
├── index.html              # Menú principal
├── rutina_semanal.html     # Rutina de Linda
├── rutina_alan.html        # Rutina de Alan
├── plan_comidas.html       # Plan de alimentación
├── registros.html          # Historial semanal
└── README.md               # Este archivo
```

## 🚀 Cómo usarlo

1. Abre `index.html` en cualquier navegador moderno
2. Cada uno entra a su rutina y llena su perfil (peso, altura, edad, actividad)
3. Abre el plan de comidas y dale a "🔄 Sincronizar" para cargar los datos
4. Cada lunes en ayunas, ve a **Registros** y agrega un nuevo registro

## 🌐 Publicar en GitHub Pages

1. Crear repositorio en GitHub (puede ser privado)
2. Subir todos los archivos al repo
3. En el repo → Settings → Pages → Source: `main` branch → Save
4. Tu sitio estará en `https://tu-usuario.github.io/nombre-del-repo/`

## 🔒 Privacidad

Todos los datos (peso, medidas, PRs) se guardan SOLO en el `localStorage` del navegador. **No se envía nada a internet**. Si limpias el caché del navegador, perderás los datos — exporta manualmente si quieres backup.

## 🛠️ Stack

- HTML5 + CSS3 (gradientes, grid, flexbox, print styles)
- JavaScript vanilla
- localStorage para persistencia
- Cero dependencias

## 📝 Notas

- Esta aplicación es un proyecto personal de aprendizaje + uso real, no es asesoría médica.
- La rutina de Alan considera molestia leve de rodilla (sustituye ejercicios de alto impacto).
- El plan de comidas prioriza alimentos antiinflamatorios SIN renunciar a carbohidratos.

---

Hecho con 💜 por Linda Amaya · Junio 2026
