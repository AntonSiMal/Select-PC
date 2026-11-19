# 🖥️ Guía Fácil para Elegir e Identificar tu Laptop Ideal

Una herramienta web interactiva, gratuita y sin necesidad de instalación que te ayuda a elegir la laptop perfecta según tus necesidades reales, decodificar especificaciones técnicas complejas y evaluar ofertas en tiempo real. Diseñada tanto para principiantes como para usuarios que buscan evitar malas compras.

🔗 **Enlace al proyecto**: [Select-PC en GitHub](https://github.com/AntonSiMal/Select-PC)

## 🚀 Características Principales

- **📝 Cuestionario Inteligente**: Responde 5 preguntas sencillas sobre tu uso diario, movilidad, multitarea y longevidad esperada. La herramienta elegirá por ti el Sistema Operativo, CPU, RAM y GPU ideales.
- **🛒 6 Niveles de Compra Dinámicos**: Desde la "Opción Inicial" (mínimo funcional real) hasta la "Opción Doble Diamante" (estación de trabajo extrema). Incluye botones que generan búsquedas directas en Google Shopping con los términos exactos.
- **🔍 Decodificador de Hardware**: Introduce o selecciona un modelo de procesador (Intel, AMD, Apple) o tarjeta gráfica (NVIDIA, AMD, Intel, Qualcomm) y descubre al instante su gama real, generación, arquitectura y para qué tareas es capaz.
- **🚦 Evaluador de Ofertas ("¿Esta laptop me sirve?")**: ¿Ves una laptop en la tienda? Ingresa sus especificaciones y la herramienta te dirá con semáforos (🟢🟡🔴) si es compatible con los programas que necesitas, advirtiendo sobre cuellos de botella o incompatibilidades de arquitectura (ej. ARM vs x86).
- **📚 Guía Educativa Interactiva**: 
  - Simulador de consumo de RAM en tiempo real (activa/desactiva tus apps habituales).
  - Calculadora de almacenamiento SSD con margen de seguridad del 20%.
  - Tablas de equivalencia Intel vs AMD y guía de terminaciones (U, V, H, HX, etc.).
  - Checklist paso a paso para revisar salud de batería, tipo de disco y pantalla frente a la PC.
- **🖨️ Listo para la Tienda**: Genera un resumen de texto copiable al portapapeles o imprimible en PDF para llevar contigo o enviar a un vendedor.

## 🛠️ Tecnologías Utilizadas

- **HTML5** & **JavaScript (Vanilla)**: Sin frameworks pesados, sin dependencias de backend ni procesos de compilación. Todo corre de forma segura y rápida en el navegador del cliente.
- **Tailwind CSS (v3.4)**: Para un diseño moderno, limpio, totalmente responsivo (móvil y escritorio) y con estilos optimizados para impresión (`@media print`).
- **Google Fonts**: Tipografía *Inter* para máxima legibilidad en pantallas.

## 📖 Cómo Usar

No necesitas instalar Node.js, ni configurar entornos de desarrollo. Funciona directamente:

1. Descarga o clona este repositorio:
   ```bash
   git clone https://github.com/AntonSiMal/Select-PC.git
   ```
2. Navega a la carpeta del proyecto:
   ```bash
   cd Select-PC
   ```
3. Abre el archivo `index.html` con cualquier navegador web moderno (Chrome, Firefox, Edge, Safari):
   ```bash
   # En macOS
   open index.html
   # En Windows
   start index.html
   # En Linux
   xdg-open index.html
   ```
4. ¡Listo! Comienza con la pestaña "1. Cuestionario" o explora las herramientas de las demás pestañas.

## 💻 Programas y Escenarios Soportados

La herramienta evalúa compatibilidad nativa, requisitos oficiales y sugiere alternativas libres para:
- **Ingeniería y CAD**: SOLIDWORKS 2026/2027, AutoCAD, FlexSim, Datamine Studio.
- **Ofimática y Datos**: Microsoft Office 365, ONLYOFFICE, Minitab, JASP/jamovi.
- **Diseño y Multimedia**: Adobe Photoshop, Premiere, After Effects, DaVinci Resolve, Blender 5.x, ArtCraft Studio.
- **Desarrollo e IA**: Visual Studio Code, Ollama, LM Studio (Modelos LLM locales cuantizados de 3B a 70B+).
- **Gaming y Emulación**: GTA V, Fortnite, Warzone/Apex/PUBG, Minecraft, Roblox, PCSX2, Emuladores N64.

## 📸 Capturas de Pantalla

*(Sugerencia: Reemplaza estas rutas con capturas reales de tu aplicación)*

| Cuestionario Personalizado | Decodificador de CPU/GPU |
| :---: | :---: |
| ![Cuestionario](https://via.placeholder.com/400x250?text=Captura+del+Cuestionario) | ![Decodificador](https://via.placeholder.com/400x250?text=Captura+del+Decodificador) |
| **Evaluador de Ofertas** | **Catálogo de Programas** |
| ![Evaluador](https://via.placeholder.com/400x250?text=Captura+del+Evaluador) | ![Programas](https://via.placeholder.com/400x250?text=Captura+del+Catalogo) |

## 🤝 Contribuciones

¿Encontraste un error tipográfico, una especificación desactualizada o quieres agregar un nuevo programa al catálogo? ¡Las contribuciones son muy bienvenidas!

1. Haz un **Fork** del repositorio.
2. Crea una rama para tu característica (`git checkout -b feature/nuevo-programa`).
3. Realiza tus cambios y haz commit (`git commit -m 'Agrega requisitos de XYZ'`).
4. Sube tu rama (`git push origin feature/nuevo-programa`).
5. Abre un **Pull Request** describiendo tus cambios.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

Desarrollado con ❤️ por **AntonSiMal**.  
Si esta herramienta te resulta útil para evitar malas compras, ¡no olvides dejar una ⭐ en el repositorio!

