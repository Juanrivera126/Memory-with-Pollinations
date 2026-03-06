# 🎮 Juego de Destapa Parejas - Memory Card Game

Un juego interactivo de memoria con imágenes generadas por IA, completamente personalizable y con múltiples temas.

![Juego de Destapa Parejas](https://img.shields.io/badge/Version-2.0-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![AI Powered](https://img.shields.io/badge/AI-Pollinations-purple)

## ✨ Características

- 🎨 **Paletas de colores dinámicas** con fondos degradados aleatorios
- 🌓 **Modo oscuro/claro** con transiciones suaves
- 🖼️ **Imágenes generadas por IA** usando Pollinations API
- 🎯 **Múltiples niveles de dificultad**: 8, 10, 12 o 15 parejas
- 🎭 **20+ estilos artísticos**: 3D, Realista, Cartoon, Anime, Pixel Art, y más
- 🔄 **Regeneración de imágenes** individual antes de jugar
- 📱 **Diseño responsive** adaptado a móviles y tablets
- 🌍 **Multiidioma**: Español, Inglés y Francés
- 🎵 **Efectos de sonido** sintetizados
- 💾 **Descarga del juego** completo en HTML

## 🚀 Demo en Vivo

[Ver Demo](https://tu-usuario.github.io/juego-parejas) _(Actualiza con tu URL)_

## 🎯 Cómo Usar

1. **Obtén tu API Key** de [Pollinations](https://pollinations.ai)
2. Abre `index.html` en tu navegador
3. Ingresa tu API Key
4. Selecciona:
   - Número de parejas (8-15)
   - Modelo de imagen (Flux.1, ZImage, Flux.2, GPT Image)
   - Tema del juego (animales, frutas, deportes, etc.)
   - Estilo artístico (3D, Anime, Realista, etc.)
5. Revisa y ajusta las imágenes generadas
6. ¡Juega y encuentra todas las parejas!

## 🎨 Características Visuales

### Paletas de Colores
- **10 paletas predefinidas** con degradados únicos
- Cambio aleatorio con el botón de paleta 🎨
- Transiciones suaves entre temas

### Estilos Artísticos Disponibles
- 3D, Realista, Cartoon, Pixar
- Anime, Ghibli Style, Pixel Art
- Barroco, Fotográfico, Acuarela
- Steampunk, Cyberpunk, Vaporwave
- Y muchos más...

## 🛠️ Tecnologías

- **HTML5** + **CSS3** (Variables CSS, Flexbox, Grid)
- **JavaScript** (ES6+, Fetch API, Web Audio API)
- **Tailwind CSS** (CDN)
- **Pollinations AI API** (Generación de texto e imágenes)

## 📋 Requisitos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexión a Internet
- API Key de Pollinations (gratuita)

## 🔧 Instalación Local

```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/juego-parejas.git

# Navega al directorio
cd juego-parejas

# Abre el archivo en tu navegador
# No requiere instalación de dependencias
```

## 📝 Configuración de API

### Obtener API Key de Pollinations

1. Visita [Pollinations.ai](https://pollinations.ai)
2. Regístrate o inicia sesión
3. Genera tu API Key (formato: `plln_sk_...`)
4. Ingresa la clave en el juego

### Migración a API POST

Este proyecto utiliza la nueva API de Pollinations con método POST para evitar errores de URL demasiado larga:

```javascript
// Endpoint: https://gen.pollinations.ai/v1/chat/completions
// Método: POST
// Headers: Content-Type: application/json, Authorization: Bearer {API_KEY}
```

## 🎮 Controles

- **Click/Tap**: Voltear carta
- **Botón Paleta** (🎨): Cambiar colores aleatorios
- **Botón Tema** (☀️/🌙): Alternar modo oscuro/claro
- **Jugar de Nuevo**: Reiniciar con las mismas imágenes
- **Otra Configuración**: Volver al menú principal

## 📊 Niveles de Dificultad

| Parejas | Grid | Total Cartas |
|---------|------|--------------|
| 8       | 4×4  | 16           |
| 10      | 5×4  | 20           |
| 12      | 6×4  | 24           |
| 15      | 6×5  | 30           |

## 🌟 Características Avanzadas

- **Revisión de imágenes**: Edita prompts y regenera imágenes individuales
- **Persistencia**: Guarda tema, idioma y API Key en localStorage
- **Validación visual**: Indicador verde cuando la API Key es válida
- **Notificaciones**: Toast messages para feedback del usuario
- **Animaciones 3D**: Efecto flip en las cartas
- **Audio dinámico**: Tonos generados con Web Audio API

## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add: AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver `LICENSE` para más información.

## 👨‍💻 Autor

**Juan Guillermo Rivera Berrío**

Diseñado con ❤️ usando las API de [Pollinations](https://pollinations.ai)

## 🙏 Agradecimientos

- [Pollinations.ai](https://pollinations.ai) por las APIs de generación de IA
- [Tailwind CSS](https://tailwindcss.com) por el framework CSS
- Comunidad de desarrolladores por el feedback

## 📞 Contacto

- GitHub: [@tu-usuario](https://github.com/tu-usuario)
- Email: tu-email@ejemplo.com

---

⭐ Si te gusta este proyecto, dale una estrella en GitHub!
