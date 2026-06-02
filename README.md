# FORE! Golf Scorecard

App de scorecard de golf para celular. Modalidades: Colombiana, 2·0·(−2), Stroke Play.

## Deploy en 3 pasos

### 1. Subir a GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/fore-golf.git
git push -u origin main
```

### 2. Conectar con Vercel

1. Entra a [vercel.com](https://vercel.com) → **Add New Project**
2. Importa el repo `fore-golf` desde GitHub
3. Settings: deja todo por defecto (es HTML estático)
4. Click **Deploy** → listo en ~30 segundos

### 3. Instalar en el celular (PWA)

**iPhone (Safari):**
- Abre la URL de Vercel en Safari
- Toca el botón Compartir → **"Añadir a pantalla de inicio"**
- Ponle nombre: FORE!

**Android (Chrome):**
- Abre la URL en Chrome
- Toca los tres puntos → **"Añadir a pantalla de inicio"**

---

## Funcionalidades

- **Colombiana** — puntos individuales acumulables, rotación de parejas cada 6 hoyos (R3 se calcula automáticamente), handicap diferencial, bonos (greenie, sandy, birdie, águila)
- **2·0·(−2)** — ranking por hoyo entre 3 jugadores, con o sin handicap
- **Stroke Play** — tarjeta con scorecard visual tipo PGA Tour
- **LocalStorage** — todo se guarda automáticamente en el celular. Nueva ronda borra los scores, mantiene jugadores y configuración
- **PWA** — funciona offline, instalable en la pantalla de inicio

## Cancha preconfigurada

Club de Polo (Santiago) — par, índice hdcp y yardas por hoyo.
Editable desde el ícono ⚙️ en la app.
