# 📚 Planificador Curricular Inteligente

> **Menos tiempo organizando. Más tiempo enseñando.**

El **Planificador Curricular Inteligente** es una aplicación web diseñada para apoyar a docentes de Educación General Básica en la creación de planificaciones semanales a partir de su propio **Mapeo de Contenidos**.

La plataforma permite cargar el Mapeo del docente, identificar los contenidos correspondientes a cada semana y generar automáticamente propuestas de actividades organizadas en cuatro momentos del ciclo de aprendizaje:

**Activación → Anticipación → Construcción → Consolidación**

El objetivo del proyecto no es reemplazar la planificación docente, sino **reducir tareas repetitivas y facilitar la creación, adaptación y organización de experiencias de aprendizaje**.

---

## 🎯 Problema

La planificación semanal requiere que el docente realice constantemente procesos como:

1. Revisar el Mapeo de Contenidos.
2. Identificar el tema correspondiente a la semana.
3. Diseñar actividades.
4. Organizar el ciclo de aprendizaje.
5. Realizar adaptaciones.
6. Seleccionar recursos.
7. Preparar la planificación final.

Aunque existen herramientas de inteligencia artificial capaces de generar actividades educativas, normalmente desconocen el **Mapeo específico de cada docente o institución**.

Esto puede producir propuestas generales o actividades que no corresponden exactamente al contenido que debe trabajarse esa semana.

---

## 💡 Nuestra solución

El Planificador Curricular Inteligente utiliza el **Mapeo de Contenidos del docente como fuente principal para organizar la planificación**.

El flujo propuesto es:

```text
MAPEO DEL DOCENTE
        ↓
SELECCIÓN DE SEMANA
        ↓
TEMA CORRESPONDIENTE
        ↓
CICLO DE APRENDIZAJE
        ↓
GENERACIÓN DE ACTIVIDADES
        ↓
REVISIÓN Y ADAPTACIÓN DOCENTE
```

De esta manera:

> **El Mapeo indica qué enseñar.  
> El docente decide cómo enseñar.  
> La tecnología conecta ambos mundos.**

---

# ✨ Funcionalidades

## 📤 Carga del Mapeo de Contenidos

El docente puede cargar su propio archivo de Mapeo.

Formatos contemplados:

- `.xlsx`
- `.xls`
- `.csv`
- `.json`

La aplicación procesa la información del archivo para utilizarla dentro de la planificación semanal.

---

## 📅 Planificación por semanas

La interfaz permite navegar entre las diferentes semanas del año lectivo.

Cada semana puede contener información como:

- Tema
- Unidad
- Fechas
- Trimestre
- Competencias
- Períodos
- Información curricular proveniente del Mapeo

El contenido semanal depende del archivo cargado por el docente.

---

## 🏫 Grados

Actualmente la aplicación está diseñada para trabajar desde:

- 3.º de EGB
- 4.º de EGB
- 5.º de EGB
- 6.º de EGB
- 7.º de EGB

Esto permite adaptar las propuestas según el nivel educativo seleccionado.

---

## 📚 Asignaturas

La plataforma contempla áreas como:

- Lengua y Literatura
- Matemática
- Ciencias Naturales
- Estudios Sociales
- Inglés
- Educación Cultural y Artística
- Educación Física

---

# 🧠 Ciclo de aprendizaje

Para cada tema semanal, la aplicación organiza propuestas en cuatro momentos.

### ⚡ Activación

Busca captar la atención de los estudiantes mediante actividades breves relacionadas con el contenido.

Puede incluir:

- retos rápidos;
- imágenes;
- preguntas detonantes;
- situaciones cotidianas;
- juegos breves;
- estímulos visuales.

### 🔮 Anticipación

Permite recuperar conocimientos previos y descubrir qué conocen los estudiantes antes de desarrollar el nuevo contenido.

Puede utilizar:

- preguntas;
- predicciones;
- lluvia de ideas;
- rutinas de pensamiento;
- organizadores;
- conversación en parejas.

### 🔨 Construcción

Corresponde al desarrollo del aprendizaje.

Puede incluir:

- modelado docente;
- ejemplos guiados;
- actividades manipulativas;
- resolución de problemas;
- organizadores visuales;
- trabajo colaborativo;
- práctica acompañada.

La aplicación incorpora la opción:

**✨ Generar actividad según el tema**

Esto permite obtener otra propuesta de Construcción relacionada con el contenido que se está trabajando esa semana.

### 🎯 Consolidación

Busca comprobar y aplicar lo aprendido.

Puede incluir:

- retos;
- problemas;
- producciones;
- tickets de salida;
- actividades gamificadas;
- situaciones de transferencia;
- preguntas de comprobación.

También dispone de:

**✨ Generar actividad según el tema**

De esta manera el docente puede obtener diferentes alternativas antes de seleccionar la más adecuada para su grupo.

---

# ♿ DUA y necesidades educativas

La aplicación incorpora un espacio para considerar estrategias de apoyo relacionadas con **Diseño Universal para el Aprendizaje (DUA)** y necesidades educativas.

El objetivo es que estas recomendaciones funcionen como apoyo para la toma de decisiones del docente y puedan ser modificadas según las características reales de sus estudiantes.

La aplicación mantiene al docente como responsable de revisar y adaptar las propuestas.

---

# 🤖 Inteligencia Artificial

El proyecto contempla un asistente pedagógico basado en IA para apoyar procesos como:

- generación de actividades;
- propuestas de Activación;
- propuestas de Anticipación;
- actividades de Construcción;
- actividades de Consolidación;
- ideas para gamificación;
- estrategias DUA;
- generación de rúbricas;
- sugerencias de evaluación.

La IA funciona como **asistente**, no como reemplazo del criterio profesional del docente.

---

# 👩‍🏫 Flujo de uso

```text
1. El docente abre la aplicación
                ↓
2. Selecciona el grado
                ↓
3. Selecciona la asignatura
                ↓
4. Sube su Mapeo de Contenidos
                ↓
5. La aplicación procesa el archivo
                ↓
6. Selecciona una semana
                ↓
7. Visualiza el tema correspondiente
                ↓
8. Se generan actividades
                ↓
9. Revisa Activación
                ↓
10. Revisa Anticipación
                ↓
11. Revisa Construcción
                ↓
12. Revisa Consolidación
                ↓
13. Genera nuevas alternativas si lo necesita
                ↓
14. Edita y adapta la planificación
                ↓
15. Guarda o imprime el resultado
```

---

# 🖥️ Interfaz

La aplicación fue diseñada pensando especialmente en el trabajo docente desde:

- 💻 computadora;
- 📱 iPad;
- 🌐 navegador web.

La interfaz incluye:

- navegación por semanas;
- selector de grado;
- selector de asignatura;
- carga de Mapeo;
- visualización del contenido semanal;
- ciclo de aprendizaje;
- herramientas de generación;
- estrategias DUA;
- asistente pedagógico.

---

# 🛠️ Tecnologías

La versión actual utiliza principalmente:

```text
HTML5
CSS
JavaScript
Tailwind CSS
Font Awesome
SheetJS
```

### Tailwind CSS

Utilizado para el diseño responsivo y la interfaz.

### SheetJS

Utilizado para interpretar archivos Excel cargados por los docentes.

### JavaScript

Gestiona:

- navegación;
- procesamiento del Mapeo;
- generación de actividades;
- edición;
- almacenamiento local;
- interacción de la interfaz.

---

# 📂 Estructura actual

La aplicación puede ejecutarse principalmente desde:

```text
/
├── index.html
└── README.md
```

El archivo principal es:

```text
index.html
```

---

# 🚀 Ejecutar el proyecto

## Opción 1 — Abrir directamente

Descarga el proyecto y abre:

```text
index.html
```

en un navegador compatible.

## Opción 2 — Servidor local

También puedes ejecutar el proyecto utilizando una extensión como **Live Server** en Visual Studio Code.

Por ejemplo:

```text
1. Clonar el repositorio
2. Abrir la carpeta en VS Code
3. Ejecutar index.html con Live Server
```

---

# 🔐 Arquitectura futura

Una de las siguientes etapas del proyecto es incorporar autenticación y almacenamiento en la nube.

La arquitectura prevista es:

```text
DOCENTE
   ↓
LOGIN INSTITUCIONAL
   ↓
FIREBASE AUTHENTICATION
   ↓
UID DEL DOCENTE
   ↓
CLOUD FIRESTORE
   ↓
ESPACIO PERSONAL
   ├── Mapeos
   ├── Planificaciones
   ├── Documentos
   └── Configuración
```

El objetivo es que cada profesor pueda ingresar utilizando su **correo institucional**.

Cada usuario tendría acceso únicamente a sus propios documentos.

---

# 🔥 Firebase — Próxima integración

Se contempla utilizar:

### Firebase Authentication

Para gestionar:

```text
Correo institucional
        ↓
Autenticación
        ↓
UID único del profesor
```

### Cloud Firestore

Para almacenar información individual por docente.

Ejemplo:

```text
profesores
│
├── UID_DOCENTE_1
│   ├── perfil
│   ├── mapeos
│   └── planificaciones
│
├── UID_DOCENTE_2
│   ├── perfil
│   ├── mapeos
│   └── planificaciones
│
└── UID_DOCENTE_3
    ├── perfil
    ├── mapeos
    └── planificaciones
```

---

# 🔒 Privacidad

La visión del proyecto contempla que cada docente tenga un espacio independiente.

Un profesor debería poder:

```text
✅ Ver sus Mapeos
✅ Crear sus planificaciones
✅ Editar sus planificaciones
✅ Consultar sus documentos
```

pero no:

```text
❌ Ver documentos de otros profesores
❌ Modificar planificaciones de otros docentes
❌ Acceder a Mapeos ajenos
```

---

# 🔮 Roadmap

Entre las mejoras previstas se encuentran:

- [x] Navegación por semanas
- [x] Selección de asignatura
- [x] Selección de 3.º a 7.º de EGB
- [x] Importación del Mapeo
- [x] Lectura de Excel
- [x] Activación
- [x] Anticipación
- [x] Construcción
- [x] Consolidación
- [x] Generación de nuevas actividades
- [x] Estrategias DUA/NEE
- [x] Asistente pedagógico
- [ ] Firebase Authentication
- [ ] Inicio de sesión institucional
- [ ] Cloud Firestore
- [ ] Mapeo individual por profesor
- [ ] Historial de planificaciones
- [ ] Panel administrativo
- [ ] Sincronización entre dispositivos
- [ ] Exportación avanzada de planificaciones
- [ ] Dashboard institucional

---

# 🌱 Escalabilidad

La visión del proyecto no se limita a una herramienta individual.

La plataforma podría evolucionar hacia un sistema institucional donde:

```text
INSTITUCIÓN
      ↓
PLATAFORMA
      ↓
┌────────────┬────────────┬────────────┐
│ DOCENTE 1  │ DOCENTE 2  │ DOCENTE 3  │
├────────────┼────────────┼────────────┤
│ Su Mapeo   │ Su Mapeo   │ Su Mapeo   │
│ Sus planes │ Sus planes │ Sus planes │
└────────────┴────────────┴────────────┘
```

Cada profesor tendría una experiencia personalizada dentro de una misma plataforma.

---

# 🎯 Objetivo del proyecto

El Planificador Curricular Inteligente busca transformar este proceso:

```text
Mapeo
→ Buscar contenido
→ Diseñar actividades
→ Adaptar
→ Redactar
```

en:

```text
Mapeo
→ Seleccionar semana
→ Generar
→ Revisar
→ Adaptar
```

La intención no es automatizar el criterio pedagógico.

Es **automatizar parte del trabajo repetitivo para liberar tiempo para el trabajo pedagógico**.

---

# 💬 Nuestra idea central

> **El Mapeo indica qué enseñar.**

> **El docente decide cómo enseñar.**

> **La tecnología conecta ambos mundos.**

---

# 📌 Estado del proyecto

🚧 **Prototipo en desarrollo**

Actualmente el proyecto se encuentra en una etapa de prototipo funcional y continúa incorporando nuevas funcionalidades.

---

# 🤝 Contribuciones

Las sugerencias y contribuciones orientadas a mejorar la experiencia docente son bienvenidas.

Puedes:

1. Crear un `Issue`.
2. Proponer una mejora.
3. Realizar un `Fork`.
4. Crear una rama.
5. Enviar un `Pull Request`.

---

# 📄 Licencia

La licencia definitiva del proyecto está pendiente de establecerse.

Antes de reutilizar, distribuir o publicar comercialmente el proyecto, consulta la licencia que se incorpore al repositorio.

---

<div align="center">

## 📚 Planificador Curricular Inteligente

### Menos tiempo organizando. Más tiempo enseñando.

**Tecnología al servicio de la planificación docente.**

</div>
