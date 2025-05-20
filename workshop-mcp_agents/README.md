# 🤖 Workshop: Multi-Agent Systems y MCPs

Este workshop explora diferentes implementaciones de sistemas multi-agente y patrones de coordinación multi-agente (MCPs) utilizando distintos frameworks.

## 📚 Contenido

### 1. CrewAI SEO 🎯

Un sistema multi-agente para generación de contenido SEO optimizado utilizando CrewAI.

**Agentes:**

- 🔍 **Senior SEO Analyst**: Especializado en investigación de palabras clave y análisis de competencia
- ✍️ **SEO Content Strategist**: Experto en creación de contenido optimizado para SEO

**Flujo de trabajo:**

```ascii
┌────────────────────────────────────────────────────────────────┐
│                     CrewAI SEO Workflow                        │
├────────────────────────────────────────────────────────────────┤
│  Usuario → Topic → CrewAI Manager → [Researcher → Writer]      │
│                                    → Contenido SEO Final       │
└────────────────────────────────────────────────────────────────┘
```

### 2. Geometry Agent 📐

Un agente especializado en cálculos geométricos implementado con el patrón ReAct.

**Características:**

- 🧮 Utiliza el prompt ReAct de Langchain Hub
- 🔄 Implementa memoria de conversación
- 🛠️ Herramientas especializadas para cálculos de áreas

**Herramientas disponibles:**

- Cálculo de área de círculo
- Cálculo de área de cuadrado

### 3. LangGraph Research Assistant 📚

Un sistema multi-agente avanzado para investigación automatizada utilizando LangGraph.

**Componentes principales:**

- 🤝 Sistema multi-agente con analistas especializados
- 🔄 Flujo de trabajo paralelo con map-reduce
- 👤 Capacidad de interacción humana (human-in-the-loop)
- 📊 Generación de reportes personalizados

**Estados del sistema:**

- `GenerateAnalystsState`: Gestión de analistas
- `InterviewState`: Control de entrevistas
- `ResearchGraphState`: Estado general de la investigación

## 🚀 Características Destacadas

1. **Patrones de Implementación**

   - CrewAI: Coordinación basada en roles y tareas
   - ReAct: Razonamiento y acción para resolución de problemas
   - LangGraph: Flujos de trabajo complejos con estados tipados

2. **Capacidades Multi-Agente**

   - 👥 Colaboración entre agentes especializados
   - 📈 Procesamiento paralelo de tareas
   - 🔄 Gestión de estado compartido

3. **Interacción y UI**
   - 💻 Interfaces Streamlit para CrewAI y Geometry
   - 📓 Notebook interactivo para Research Assistant
   - 👤 Capacidades de human-in-the-loop

## 🛠️ Tecnologías Utilizadas

- **Frameworks**:
  - CrewAI
  - LangChain
  - LangGraph
- **Interfaces**:
  - Streamlit
  - Jupyter Notebooks

## 📦 Requisitos

Cada proyecto tiene sus propios requisitos específicos. Consulta los archivos `requirements.txt` en cada directorio.

## 🎓 Aprendizajes Clave

1. **Patrones de Diseño Multi-Agente**

   - Coordinación basada en roles
   - Flujos de trabajo paralelos
   - Gestión de estado compartido

2. **Mejores Prácticas**

   - Tipado fuerte para estados
   - Modularización de agentes
   - Manejo de contexto y memoria

3. **Casos de Uso**
   - Generación de contenido SEO
   - Cálculos matemáticos
   - Investigación automatizada

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar los ejemplos o agregar nuevos patrones, no dudes en crear un pull request.
