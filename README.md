# 🏋️ FitTrack
### Tu compañero diario para llevar el control de tu bienestar

FitTrack es una aplicación web sencilla y elegante que te permite llevar un **registro diario** de tu peso, altura y cómo te sientes. La idea es muy simple: **anotar tus datos cada día** y poder ver tu evolución con el tiempo, todo desde un solo lugar.
> 💡 Piensa en FitTrack como un diario personal de tu cuerpo, pero con gráficos bonitos y estadísticas útiles.
---
## 📋 Funcionamiento
### 📝 Registrar datos del día
Cada día puedes ingresar:
- **📅 Fecha** — Se pone la fecha de hoy automáticamente, pero puedes cambiarla si quieres registrar un día anterior.
- **⚖️ Peso (kg)** — Tu peso del día.
- **📏 Altura (cm)** — Tu altura actual.
- **😊 Estado de ánimo** — Cómo te sientes: Excelente, Bien, Regular, Mal o Cansado.
- **📝 Notas del día** — Un espacio libre para escribir cómo te sentiste, qué comiste, si hiciste ejercicio, o lo que quieras anotar.
> ⚡ Mientras escribes, la app te muestra tu **IMC (Índice de Masa Corporal)** en tiempo real para que lo veas al momento.
### 📊 Historial
Aquí puedes ver todos tus registros pasados:
- **🔍 Buscar** — Filtra por texto en tus notas o estado de ánimo.
- **📅 Filtro por fecha** — Selecciona un rango de fechas para ver solo esos registros.
- **✏️ Editar** — Si te equivocaste o quieres actualizar algo, puedes editar cualquier registro.
- **🗑️ Eliminar** — Borra registros que ya no necesites.
- **📄 Paginación** — Si tienes muchos registros, se organizan en páginas para que todo se vea limpio.
### 📈 Estadísticas
La sección de estadísticas te muestra:
- **📊 Peso promedio, mínimo y máximo** — Un resumen rápido de tus datos.
- **📉 Cambio total** — Cuánto has subido o bajado desde tu primer registro.
- **📈 Gráficas de evolución** — Tres gráficos que muestran cómo ha cambiado tu peso, altura e IMC a lo largo del tiempo.
> 🎨 Los gráficos se dibujan directamente en el navegador, sin necesidad de librerías externas.
---
## 🎨 Diseño
FitTrack tiene un diseño **moderno y oscuro** pensado para que sea agradable usarlo cada día:
- **🌙 Tema oscuro** — Cómodo para la vista, con colores suaves de fondo.
- **🎨 Gradientes vibrantes** — Colores púrpura y turquesa que le dan energía a la interfaz.
- **📱 Responsive** — Se adapta perfectamente a pantallas de celular, tablet y computadora.
- **✨ Animaciones suaves** — Transiciones delicadas que hacen que la experiencia se sienta fluida.
- **🔔 Notificaciones** — Mensajes emergentes que te confirman cuando guardas un registro.
---
## 💾 Almacenamiento
Todo se guarda **directamente en tu navegador**:
- **🗄️ IndexedDB** — Tu base de datos local almacena todos tus registros de forma persistente.
- **🔄 Persistencia** — Los datos se mantienen incluso si cierras el navegador o apagas tu computadora.
- **🔒 Privacidad** — Tu información nunca sale de tu dispositivo. No hay servidores, no hay cuentas, no hay complicaciones.
---
## 🚀 Cómo usarlo
1. **Abre el archivo** `fittrack.html` en tu navegador (Chrome, Firefox, Edge, etc.).
2. **Registra tu primer dato** en la pestaña "Registrar".
3. **Revisa tu historial** para ver todos tus registros pasados.
4. **Consulta las estadísticas** para ver tu evolución con gráficos.
> ✅ No necesitas instalar nada, ni conexión a internet. Funciona 100% offline.
---
## 📱 Secciones de la app
| Sección | Icono | Descripción |
|---------|-------|-------------|
| **Registrar** | 📝 | Ingresa tus datos del día |
| **Historial** | 📊 | Ve y gestiona tus registros pasados |
| **Estadísticas** | 📈 | Analiza tu evolución con gráficos |
---
## ✨ Características destacadas
- ⚡ **Cálculo automático de IMC** — Con categorías visuales (Bajo peso, Normal, Sobrepeso, Obesidad).
- 🔍 **Búsqueda inteligente** — Encuentra registros por texto en notas o estado de ánimo.
- 📅 **Fecha automática** — Se pone el día de hoy por defecto, pero puedes cambiarla.
- 📝 **Contador de caracteres** — Hasta 2000 caracteres en las notas del día.
- 💪 **Recordatorio de datos** — Recupera tu último peso y altura registrados.
- 🎯 **Validación en tiempo real** — Te avisa si algo no está bien antes de guardar.
- 📊 **Gráficos personalizados** — Dibujados directamente con Canvas, sin dependencias.
---
## 📐 Tecnologías utilizadas
| Tecnología | Uso |
|------------|-----|
| HTML5 | Estructura de la aplicación |
| CSS3 | Diseño, gradientes y animaciones |
| JavaScript (ES6+) | Lógica y funcionalidad |
| IndexedDB | Base de datos local del navegador |
| Canvas API | Gráficos de evolución |
| localStorage | Almacenamiento temporal de datos |
---
## 🤝 Contribuir
FitTrack es un proyecto personal diseñado para ser simple y funcional. Si tienes ideas para mejorarlo o encuentras algún problema, ¡no dudes en compartirlo!
---
## 📄 Licencia
Este proyecto es de código abierto y puede ser usado, modificado y distribuido libremente.
---
<div align="center">
**Hecho con ❤️ para quienes quieren llevar un seguimiento simple de su bienestar**
*FitTrack — Tu diario personal de salud*
