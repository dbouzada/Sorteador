# 🎰 Sorteador · Almafuerte Pinturería

Plataforma de sorteos digitales para clientes de **Almafuerte Pinturería**. Permite cargar un archivo CSV con participantes, realizar sorteos aleatorios y revelar ganadores con animaciones.

---

## ✨ Features

- 📂 **Carga de CSV** — drag & drop o explorador de archivos
- 🔢 **Deduplicación automática** — cada número de compra participa una sola vez
- 🏆 **Sorteo aleatorio** — selección de 1 o múltiples ganadores
- 🎊 **Pantalla de revelación** — cuenta regresiva, efecto ruleta, confetti y typing effect
- 📸 **Exportar imagen** — captura la pantalla del ganador lista para compartir
- 📄 **Exportar CSV** — descargá la lista de ganadores
- 📋 **Historial persistente** — guarda todos los sorteos en el navegador (localStorage)
- 📱 **Responsive** — funciona en desktop y mobile
- ⚡ **100% client-side** — sin backend, sin base de datos, sin costo

---

## 📁 Formato del CSV

El archivo debe usar **punto y coma (`;`)** como separador y contener al menos estas dos columnas:

```
Numero;Cliente
0001-00019363;GARCIA, JUAN CARLOS
0001-00019362;LOPEZ, MARIA ELENA
0001-00019359;GIMENEZ, GABRIELA ESTEFANIA
```

> También podés descargar la plantilla directamente desde la app.

---

## 🚀 Deploy

El proyecto es un único archivo HTML estático. No requiere build ni dependencias.

### Vercel (recomendado)

1. Cloná o forkiá este repositorio
2. Importalo en [vercel.com](https://vercel.com) → **Add New Project**
3. Vercel detecta el `index.html` automáticamente
4. ✅ Deploy listo en ~30 segundos

### GitHub Pages

1. Settings → Pages
2. Source: `Deploy from a branch` → `main` → `/ (root)`
3. Save → URL disponible en `https://tu-usuario.github.io/nombre-repo`

### Netlify Drop

1. Entrá a [netlify.com/drop](https://netlify.com/drop)
2. Arrastrá el `index.html`
3. URL generada al instante

---

## 🛠️ Stack

| Tecnología | Uso |
|---|---|
| HTML / CSS / JS vanilla | Base de la app |
| [Tabler Icons](https://tabler-icons.io/) | Íconos |
| [Google Fonts — Inter](https://fonts.google.com/specimen/Inter) | Tipografía |
| [html2canvas](https://html2canvas.hertzen.com/) | Exportar imagen del ganador |
| localStorage | Historial persistente |

---

## 🎬 Animaciones incluidas

- **Fade in escalonado** al cargar la página
- **Contador animado** al cargar el CSV
- **Pulso suave** en el botón de sorteo
- **Cuenta regresiva 3... 2... 1...**
- **Efecto ruleta** antes de revelar el ganador
- **Typing effect** al mostrar el nombre
- **Confetti** al revelar ganadores
- **Slide in** en cards del historial

---

## 📍 Contacto

**Almafuerte Pinturería**  
🌐 [almafuertepinturerias.com.ar](https://almafuertepinturerias.com.ar)  
📍 Av. Almafuerte 1399 | Paraná | Entre Ríos  
✉️ info@almafuertepinturerias.com.ar  
📞 (343) 434-9496

---

> Desarrollado con ❤️ — 2026
