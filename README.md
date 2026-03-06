# CBZ Reader

Lector de cómics en formato CBZ que funciona en el navegador.

## Deploy en Railway

### Opción A — Desde GitHub (recomendado)

1. Sube esta carpeta a un repositorio de GitHub
2. Ve a [railway.app](https://railway.app) → **New Project**
3. Selecciona **Deploy from GitHub repo**
4. Elige tu repositorio
5. Railway detecta automáticamente Node.js y hace el deploy

✅ Tu app estará en `https://tu-proyecto.up.railway.app`

### Opción B — Railway CLI

```bash
npm install -g @railway/cli
railway login
railway init
railway up
```

## Desarrollo local

```bash
npm install
npm start
# Abre http://localhost:3000
```
