# 📋 Matriz de Eisenhower PRO

Una aplicación web progresiva (PWA) moderna para gestión inteligente de tareas usando la Matriz de Eisenhower con integración de Inteligencia Artificial.

![Matriz de Eisenhower PRO](https://img.shields.io/badge/PWA-Ready-brightgreen) ![AI Powered](https://img.shields.io/badge/AI-Powered-blue) ![Responsive](https://img.shields.io/badge/Design-Responsive-orange)

## ✨ Características principales

### 🤖 Clasificación inteligente con IA
- Integración con OpenAI GPT-3.5 Turbo para clasificación automática de tareas
- Análisis contextual basado en información del proyecto
- Sugerencias de fechas límite inteligentes
- Razonamiento explicativo para cada clasificación

### 📊 Matriz de Eisenhower completa
- **Cuadrante 1**: Hacer ahora (Urgente + Importante)
- **Cuadrante 2**: Planificar (No urgente + Importante)
- **Cuadrante 3**: Delegar (Urgente + No importante)
- **Cuadrante 4**: Eliminar (No urgente + No importante)

### 🎯 Gestión avanzada de proyectos
- Configuración de contexto del proyecto
- Fechas de inicio y límite del proyecto
- Timeline visual con progreso en tiempo real
- Seguimiento de tiempo restante

### 🚀 Experiencia de usuario premium
- **PWA completa**: Instalable como app nativa
- **Diseño minimalista**: Interfaz moderna con fondo negro
- **Drag & Drop**: Reorganización intuitiva entre cuadrantes
- **Responsive**: Optimizado para móviles y desktop
- **Offline-ready**: Funciona sin conexión una vez instalada

### 📈 Análisis y seguimiento
- Barras de progreso por cuadrante
- Estadísticas detalladas de productividad
- Contador de tareas completadas vs pendientes
- Timeline del proyecto en tiempo real

### 🔄 Funciones inteligentes
- **Reorganización automática**: IA reorganiza tareas por prioridad dentro de cada cuadrante
- **Gestión de prioridades**: Sistema de numeración automática
- **Persistencia local**: Datos guardados automáticamente
- **Función compartir**: Comparte la app fácilmente

## 🛠️ Instalación y uso

### Requisitos previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- API Key de OpenAI (para funciones de IA)

### Instalación

#### Opción 1: Como PWA (Recomendado)
1. Abre la aplicación en tu navegador
2. Busca el banner de instalación o el ícono de "Instalar" en la barra de direcciones
3. Haz clic en "Instalar" para agregar la app a tu dispositivo
4. ¡Listo! Ahora puedes usarla como una app nativa

#### Opción 2: Como archivo local
1. Descarga el archivo `index.html`
2. Ábrelo directamente en tu navegador
3. Todas las funciones básicas estarán disponibles

### Configuración inicial

#### 1. Configurar OpenAI API
```
1. Ve a https://platform.openai.com/api-keys
2. Crea una nueva API Key
3. Copia la clave (formato: sk-...)
4. Pégala en la sección "Configuración IA" de la app
```

#### 2. Configurar proyecto
```
1. Ingresa el nombre de tu proyecto
2. Define fechas de inicio y límite (opcional)
3. Agrega contexto adicional para mejor clasificación de IA
4. ¡Comienza a agregar tareas!
```

## 📱 Uso de la aplicación

### Agregar tareas
1. Escribe la descripción de tu tarea en el campo "Nueva tarea"
2. Haz clic en "Clasificar con IA" o presiona Enter
3. La IA analizará y clasificará automáticamente la tarea
4. La tarea aparecerá en el cuadrante correspondiente

### Gestionar tareas
- **Completar**: Marca tareas como completadas
- **Eliminar**: Borra tareas individuales
- **Mover**: Arrastra tareas entre cuadrantes
- **Reorganizar**: Usa el botón 🤖 para reorganizar por prioridad

### Funciones avanzadas
- **Timeline**: Visualiza el progreso de tu proyecto
- **Estadísticas**: Monitorea tu productividad
- **Limpiar**: Elimina tareas por cuadrante o completas
- **Compartir**: Comparte la app con otros

## 🎨 Diseño y UX

### Interfaz minimalista
- **Fondo negro elegante** con elementos glassmorfismo
- **Tipografía moderna**: Inter + Anton para títulos
- **Colores temáticos** para cada cuadrante:
  - 🔴 Rojo: Hacer ahora
  - 🟢 Verde: Planificar  
  - 🟠 Naranja: Delegar
  - 🟣 Morado: Eliminar

### Responsive design
- **Desktop**: Layout de bento con sidebar
- **Tablet**: Adaptación automática de columnas
- **Móvil**: Stack vertical optimizado

## 🔧 Tecnologías utilizadas

- **HTML5**: Estructura semántica moderna
- **CSS3**: Flexbox, Grid, Variables CSS, Glassmorphism
- **Vanilla JavaScript**: Sin frameworks, máximo rendimiento
- **OpenAI API**: GPT-3.5 Turbo para clasificación inteligente
- **PWA**: Service Workers, Manifest, instalación offline
- **LocalStorage**: Persistencia de datos local

## 🚀 Características PWA

### Instalación nativa
- Agregar a pantalla de inicio en móviles
- Instalación desde escritorio en navegadores compatibles
- Iconos adaptativos para diferentes plataformas

### Funcionalidad offline
- Datos guardados localmente
- Interfaz completamente funcional sin internet
- Sincronización cuando se recupera la conexión

### Experiencia nativa
- Sin barras de navegador cuando está instalada
- Splash screen personalizada
- Iconos del sistema operativo

## 📋 Próximas características

- [ ] Sincronización en la nube
- [ ] Colaboración en equipo
- [ ] Notificaciones push
- [ ] Exportación a PDF/Excel
- [ ] Integración con calendarios
- [ ] Plantillas de proyectos
- [ ] Dashboard analítico avanzado
- [ ] Modo oscuro/claro
- [ ] Múltiples idiomas

## 🐛 Solución de problemas

### La IA no clasifica tareas
- Verifica que tu API Key de OpenAI sea válida
- Asegúrate de tener saldo en tu cuenta OpenAI
- Revisa la conexión a internet

### La app no se instala
- Verifica que uses HTTPS (o localhost para desarrollo)
- Prueba un navegador diferente
- Borra caché y recarga la página

### Datos perdidos
- Los datos se guardan automáticamente en LocalStorage
- Si cambias de navegador, los datos no se transfieren
- Para desarrollo futuro: considerar backup en la nube

## 🤝 Contribuir

Esta es una aplicación de código abierto. Sugerencias y mejoras son bienvenidas:

1. Reporta bugs o solicita características
2. Sugiere mejoras de UX/UI
3. Propón nuevas integraciones de IA
4. Comparte casos de uso interesantes

## 📄 Licencia

Esta aplicación es de uso libre para proyectos personales y comerciales.

## 🙏 Agradecimientos

- **OpenAI** por la API de clasificación inteligente
- **Google Fonts** por las tipografías Inter y Anton
- **Comunidad web** por estándares PWA y mejores prácticas

---

## 📞 Contacto y soporte

Para soporte, sugerencias o colaboraciones, no dudes en contactar.

**¡Gestiona tus tareas de manera inteligente con la Matriz de Eisenhower PRO!** 🚀
