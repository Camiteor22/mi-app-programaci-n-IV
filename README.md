# 🚀 Taller Integrador - Programación IV

## 📋 Descripción del Proyecto

Este proyecto es una aplicación React funcional que implementa un componente de contador interactivo. Fue desarrollado como parte del Taller Integrador de la asignatura Programación IV, demostrando las habilidades en desarrollo frontend con React, gestión de estado, y buenas prácticas de programación.

## 🎯 Objetivos del Taller

- ✅ Crear un proyecto React funcional con Vite
- ✅ Implementar un componente Counter con estado funcional
- ✅ Configurar control de versiones con Git
- ✅ Realizar commits semánticos
- ✅ Subir el proyecto a GitHub
- ✅ Documentar el proyecto profesionalmente

## ✨ Características Implementadas

### 🔢 Componente Counter
- **Estado funcional**: Utiliza React Hooks (`useState`)
- **Funcionalidades**:
  - Incremento del contador
  - Decremento del contador
  - Reset del contador a cero
- **Interfaz intuitiva**: Botones con iconos y colores distintivos
- **Diseño responsivo**: Se adapta a diferentes tamaños de pantalla

### 🎨 Diseño y UX
- **Estilos modernos**: CSS con gradientes y efectos glassmorphism
- **Animaciones**: Transiciones suaves y efectos hover
- **Paleta de colores**: Esquema profesional y accesible
- **Responsive design**: Optimizado para móviles y desktop

### ⚡ Tecnologías Utilizadas
- **React 18**: Framework de interfaz de usuario
- **Vite**: Bundler rápido y moderno
- **CSS3**: Estilos avanzados con animaciones
- **Git**: Control de versiones
- **GitHub**: Repositorio remoto

## 🛠️ Instalación y Configuración

### Prerrequisitos
- Node.js (versión 16 o superior)
- npm (incluido con Node.js)
- Git

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone [URL_DEL_REPOSITORIO]
   cd app-progam-IV
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Ejecutar en modo desarrollo**
   ```bash
   npm run dev
   ```

4. **Abrir en el navegador**
   - La aplicación se abrirá automáticamente en `http://localhost:5173`
   - O navega manualmente a la URL mostrada en la terminal

### Scripts Disponibles

- `npm run dev` - Inicia el servidor de desarrollo
- `npm run build` - Construye la aplicación para producción
- `npm run preview` - Previsualiza la build de producción

## 📁 Estructura del Proyecto

```
app-progam-IV/
├── public/                 # Archivos estáticos
├── src/                   # Código fuente
│   ├── App.jsx           # Componente principal
│   ├── main.jsx          # Punto de entrada
│   └── style.css         # Estilos globales
├── index.html             # Página HTML base
├── package.json           # Dependencias y scripts
└── README.md             # Documentación del proyecto
```

## 🔧 Funcionalidades del Componente Counter

### Estado del Contador
- **Valor inicial**: 0
- **Rango**: Sin límites (enteros positivos y negativos)
- **Persistencia**: Se mantiene durante la sesión

### Botones de Control
1. **➕ Incrementar**: Aumenta el valor en 1
2. **➖ Decrementar**: Disminuye el valor en 1
3. **🔄 Resetear**: Vuelve el valor a 0

### Características Técnicas
- **Hooks de React**: `useState` para gestión de estado
- **Funciones puras**: Lógica de negocio separada
- **Event handlers**: Manejo eficiente de eventos
- **Re-renderizado optimizado**: Solo se actualiza cuando es necesario

## 🎨 Estilos y Diseño

### Principios de Diseño
- **Glassmorphism**: Efectos de transparencia y blur
- **Gradientes**: Colores modernos y atractivos
- **Sombras**: Profundidad visual con box-shadows
- **Animaciones**: Transiciones suaves y efectos hover

### Paleta de Colores
- **Primario**: Azul (#667eea) a Púrpura (#764ba2)
- **Éxito**: Verde (#48bb78) para incremento
- **Error**: Rojo (#f56565) para decremento
- **Advertencia**: Naranja (#ed8936) para reset
- **Texto**: Gris oscuro (#4a5568) y medio (#718096)

### Responsive Design
- **Breakpoints**: 768px para dispositivos móviles
- **Grid adaptativo**: Se ajusta automáticamente
- **Botones móviles**: Tamaño optimizado para touch
- **Tipografía**: Escalable según el dispositivo

## 🚀 Despliegue

### Desarrollo Local
```bash
npm run dev
```

### Producción
```bash
npm run build
npm run preview
```

### GitHub Pages (Opcional)
1. Construir el proyecto: `npm run build`
2. Subir la carpeta `dist/` a la rama `gh-pages`
3. Configurar GitHub Pages en la configuración del repositorio

## 📚 Aprendizajes y Conceptos Clave

### React Hooks
- **useState**: Gestión de estado local
- **Componentes funcionales**: Paradigma moderno de React
- **Re-renderizado**: Ciclo de vida del componente

### Gestión de Estado
- **Estado local**: Contenido en el componente
- **Inmutabilidad**: No modificar el estado directamente
- **Funciones de actualización**: Patrón recomendado

### CSS Moderno
- **Flexbox y Grid**: Layouts avanzados
- **Variables CSS**: Reutilización de valores
- **Media queries**: Diseño responsivo
- **Animaciones**: CSS transitions y keyframes

## 🔍 Próximas Mejoras

### Funcionalidades Adicionales
- [ ] Persistencia con localStorage
- [ ] Historial de cambios
- [ ] Límites configurables
- [ ] Temas de colores

### Mejoras Técnicas
- [ ] Tests unitarios con Jest
- [ ] TypeScript para tipado
- [ ] Tailwind CSS para estilos
- [ ] PWA capabilities

### Optimizaciones
- [ ] Lazy loading de componentes
- [ ] Memoización con React.memo
- [ ] Code splitting
- [ ] Bundle optimization

## 🤝 Contribuciones

Este proyecto es parte de un taller académico, pero las contribuciones son bienvenidas:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Estudiante de Programación IV**
- **Asignatura**: Programación IV
- **Universidad**: [Nombre de la Universidad]
- **Año**: 2024

## 🙏 Agradecimientos

- **React Team**: Por el increíble framework
- **Vite Team**: Por el bundler rápido
- **Comunidad CSS**: Por las técnicas de diseño moderno
- **Profesores**: Por la guía en el aprendizaje

## 📞 Contacto

- **GitHub**: [@tu-usuario](https://github.com/tu-usuario)
- **Email**: tu-email@ejemplo.com
- **LinkedIn**: [Tu Perfil](https://linkedin.com/in/tu-perfil)

---

⭐ **¡No olvides darle una estrella al proyecto si te gustó!** ⭐

