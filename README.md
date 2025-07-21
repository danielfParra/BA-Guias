# Notas de Clase Business Analytics

Este repositorio contiene las notas de clase de **Business Analytics** para los posgrados de administración de la Pontificia Universidad Javeriana, desarrolladas como un libro interactivo utilizando Quarto.

## 📚 Contenido del Libro

### **Capítulo 1: Introducción**
Fundamentos del Business Analytics y su rol en la toma de decisiones empresariales.

### **Capítulo 2: Fundamentos de Variables y Visualización de Datos**
- **Clasificación de variables:** Categóricas vs. numéricas (discretas/continuas)
- **Datos categóricos:** Tablas de resumen, contingencia y visualizaciones (barras, torta, Pareto)
- **Datos numéricos:** Distribuciones de frecuencia, histogramas y gráficos de dispersión
- **Casos prácticos:** Ejemplos contextualizados en situaciones empresariales reales

### **Capítulo 3: Estadística Descriptiva**
Medidas de tendencia central, variabilidad y análisis exploratorio de datos.

## 🛠️ Tecnologías Utilizadas

- **[Quarto](https://quarto.org/):** Framework para documentación científica y técnica
- **R + ggplot2:** Visualizaciones de datos profesionales
- **Mermaid:** Diagramas conceptuales interactivos
- **HTML/CSS:** Presentación web responsive

## 📊 Características Destacadas

- ✅ **Visualizaciones interactivas** generadas con código R
- ✅ **Ejemplos contextualizados** en casos de negocio reales
- ✅ **Interpretaciones prácticas** con insights actionables
- ✅ **Diseño responsive** optimizado para web y móvil
- ✅ **Búsqueda integrada** y navegación intuitiva

## 🚀 Desarrollo y Compilación

### Prerrequisitos
- [Quarto CLI](https://quarto.org/docs/get-started/)
- R con las siguientes librerías:
  ```r
  install.packages(c("ggplot2", "dplyr", "tidyr", "viridis"))
  ```

### Comandos de desarrollo
```bash
# Vista previa en tiempo real
quarto preview book

# Compilar a HTML
quarto render book

# Compilar a PDF
quarto render book --to pdf
```

### Estructura del proyecto
```
├── book/                 # Archivos fuente del libro
│   ├── _quarto.yml      # Configuración principal
│   ├── index.qmd        # Página de inicio
│   ├── capitulo2.qmd    # Capítulo de visualización
│   └── img/             # Imágenes y recursos
├── docs/                # Salida HTML compilada
└── README.md            # Este archivo
```

## 📖 Ver el Libro

- **Versión web:** [Acceder al libro online](../docs/index.html) *(disponible después de compilar)*
- **Desarrollo local:** `quarto preview book` y navegar a `http://localhost:3000`

## 📝 Contribuciones

Para contribuir al contenido:

1. Edita los archivos `.qmd` en la carpeta `book/`
2. Previsualiza los cambios con `quarto preview book`
3. Compila la versión final con `quarto render book`

## 📄 Licencia

© 2025 Pontificia Universidad Javeriana. Este contenido está licenciado bajo [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## 👨‍🏫 Autor

**Daniel Parra**  
Pontificia Universidad Javeriana

---

*Parte del contenido ha sido desarrollado con asistencia de inteligencia artificial, combinando apuntes académicos y referencias bibliográficas especializadas.*
