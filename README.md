# 📊 Cartera + Asesor Financiero

App web para tracking de inversiones + análisis financiero experto con 9 capacidades integradas.

**Funciona en desktop, tablet y mobile. Instálable como app nativa.**

---

## 🎯 CARACTERÍSTICAS

### 📄 Mi Cartera
- ✅ Agregar boletos manualmente (operaciones de compra/venta)
- ✅ Neto calculado automáticamente (Cantidad × Precio)
- ✅ Cálculo automático de días de tenencia, renta y TEA
- ✅ Panel de activos con precios actuales
- ✅ Dashboard con totales de cartera

### 🧑‍💼 Asesor Financiero Experto (9 Capacidades)
1. **📊 Análisis de Activos** - Fundamentos, fortalezas y riesgos
2. **📈 Análisis Técnico** - RSI, MACD, medias móviles, volumen
3. **🎯 Niveles Clave** - Soporte, resistencia, stop loss, take profit
4. **💡 Estrategias** - Recomendaciones según estado de la posición
5. **⚠️ Riesgo/Retorno** - Drawdown, Sharpe, tamaño de posición
6. **📰 Sentimiento** - Análisis de impacto de noticias
7. **🔮 Escenarios** - Optimista 🟢 Base 🟡 Pesimista 🔴
8. **💬 Conceptos** - Explicación de términos financieros
9. **🎲 Portafolio** - Diversificación y rebalanceo

---

## 🚀 INICIO RÁPIDO

### Local (sin internet)
1. Descargá `app.html`, `manifest.json`, `sw.js`, `index.html`
2. Ponelos en una carpeta (ej: `cartera-asesor`)
3. Abrí `app.html` en el navegador
4. ✅ Listo para usar

### GitHub Pages (accesible desde cualquier dispositivo)
Ver instrucciones abajo: **"Subir a GitHub"**

---

## 📱 INSTALAR COMO APP EN EL CELULAR

### iPhone (iOS)
1. Abrí la app en Safari
2. Tocá el icono de compartir (↗️ abajo)
3. Seleccioná "Agregar a Pantalla de inicio"
4. Confirmá con "Agregar"
5. ✅ App aparece en tu pantalla de inicio

### Android (Chrome)
1. Abrí la app en Chrome
2. Tocá el menú (⋮) arriba a la derecha
3. Seleccioná "Instalar app"
4. Confirmá con "Instalar"
5. ✅ App aparece en tu pantalla de inicio

### Desktop (Windows/Mac)
1. En Chrome: menú (⋮) → "Instalar Cartera + Asesor"
2. O en Edge: menú (•••) → "Aplicaciones" → "Instalar esta aplicación"
3. ✅ App aparece en tu menú de aplicaciones

---

## 📤 SUBIR A GITHUB Y USAR COMO APP

### PASO 1: Crear cuenta GitHub (si no la tenés)
1. Ve a https://github.com
2. Tocá "Sign up"
3. Completá con email, password, usuario
4. Verifica tu email
5. ✅ Cuenta lista

---

### PASO 2: Crear repositorio

#### Opción A: Usando GitHub Web (más fácil)

1. **Logueate en GitHub** y ve a https://github.com/new
2. **Nombre del repo:** `cartera-asesor` (o el que quieras)
3. **Descripción:** "Tracker de inversiones + Asesor financiero experto"
4. **Visibilidad:** ☑️ Public (para que sea accesible)
5. **Inicializar repo:** ☑️ Add a README file
6. Tocá **"Create repository"**
7. ✅ Repositorio creado

---

### PASO 3: Subir los archivos

#### Opción A: Subir directamente en GitHub Web

1. **En tu repositorio**, tocá **"Add file"** → **"Upload files"**
2. Arrastrá o seleccioná:
   - `app.html`
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Escribí mensaje: "Agregar app inicial"
4. Tocá **"Commit changes"**
5. ✅ Archivos subidos

#### Opción B: Usar Git (para desarrolladores)

```bash
# Clona el repositorio
git clone https://github.com/TU_USUARIO/cartera-asesor.git
cd cartera-asesor

# Copia los archivos
# (Ponés app.html, manifest.json, sw.js, index.html en esta carpeta)

# Sube los cambios
git add .
git commit -m "Agregar app inicial"
git push origin main
```

---

### PASO 4: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Tocá **"Settings"** (arriba a la derecha)
3. En el menú izquierdo, tocá **"Pages"**
4. **Source:** Seleccioná "Deploy from a branch"
5. **Branch:** `main` (o `master`)
6. **Folder:** `/ (root)`
7. Tocá **"Save"**
8. **Espera 1-2 minutos** a que se despliegue
9. Verás un mensaje: "Your site is published at: https://TU_USUARIO.github.io/cartera-asesor"
10. ✅ App publicada

---

### PASO 5: Acceder y usar

**Desde cualquier dispositivo:**
```
https://TU_USUARIO.github.io/cartera-asesor
```

**Ejemplo:** Si tu usuario es `ramso` y el repo es `cartera-asesor`:
```
https://ramso.github.io/cartera-asesor
```

---

## 🔧 CÓMO USAR LA APP

### Cargar boletos
1. **Tab "Mi Cartera"** → **"+ Agregar boleto"**
2. Completá: Operación, Ticker, ALyC (broker), Fecha, Cantidad, Precio
3. ✅ Se calcula neto automáticamente

### Actualizar precios
1. En el panel **"Activos"**, cargá el precio actual de cada ticker
2. ✅ Se recalculan ganancia y TEA automáticamente

### Analizar con el Asesor
1. **Tab "Asesor Experto"** → Seleccioná ticker del dropdown
2. O escribí un ticker manual y tocá "Analizar"
3. ✅ Recibirás análisis experto con 9 capacidades

### Guardar datos
- **Automático:** La app guarda en localStorage del navegador
- **Respaldar:** Abrí DevTools (F12) → Application → Local Storage → copia los datos
- **Restaurar:** Pegá los datos en el mismo lugar

---

## 💾 ESTRUCTURA DE ARCHIVOS

```
cartera-asesor/
├── index.html          (entrada, redirige a app.html)
├── app.html            (app principal)
├── manifest.json       (config PWA)
├── sw.js               (service worker offline)
└── README.md           (este archivo)
```

---

## 🔄 ACTUALIZAR LA APP

### Localmente
1. Descargá los nuevos archivos
2. Reemplazá los antiguos en tu carpeta
3. Recargá el navegador (Ctrl+F5 o Cmd+Shift+R)

### En GitHub
1. Ve a tu repositorio
2. Tocá en el archivo a editar (ej: `app.html`)
3. Tocá el icono de lápiz ✏️
4. Pegá el nuevo contenido
5. Tocá **"Commit changes"**
6. Esperá 1-2 minutos a que se despliegue

---

## 🐛 TROUBLESHOOTING

### "No se guardan mis datos"
- Asegurate que **localStorage no esté desactivado** en el navegador
- En incognito/privado no se guardan datos

### "No me deja instalar como app"
- Necesita **HTTPS** (GitHub Pages lo proporciona automáticamente)
- En local solo funciona en localhost con `python -m http.server`

### "El análisis del asesor no aparece"
- Asegurate de haber cargado el **precio actual** en el panel Activos
- Los datos se guardan automáticamente

### "Quiero sincronizar entre dispositivos"
- Actualmente usa localStorage (local al navegador)
- Alternativa: Exporter datos como JSON y importar en otro dispositivo

---

## 📚 REFERENCIAS

- **GitHub Pages:** https://docs.github.com/es/pages
- **PWA (Progressive Web App):** https://developer.mozilla.org/es/docs/Web/Progressive_web_apps
- **TradingView:** https://www.tradingview.com (para gráficos)
- **Yahoo Finance:** https://finance.yahoo.com (precios en tiempo real)

---

## 📝 NOTAS LEGALES

- **Disclaimer:** Análisis informativos. No constituyen asesoramiento financiero oficial.
- **Sin garantías:** No garantizamos retornos ni resultados específicos.
- **Riesgo:** Toda inversión conlleva riesgo de pérdida. Invierte solo lo que puedas perder.

---

## 👤 Créditos

Desarrollado como herramienta para inversores intermedio-avanzados en Argentina.

**Versión:** 1.0  
**Última actualización:** 2025

---

## 💬 Feedback

¿Encontraste un bug? ¿Sugerencias?  
Abrí un "Issue" en GitHub o contactame directamente.

**¡Que disfrutes la app! 🚀**
