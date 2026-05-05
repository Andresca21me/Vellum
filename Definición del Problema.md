## 1. Descripción del Problema

Actualmente, las herramientas de edición de texto y toma de notas existentes presentan una división de sus funcionalidades principales.

- Por un lado, tenemos aplicaciones como Obsidian, en donde se permite la interconexión de ideas (notas) mediante enlaces bidireccionales y grafos de conocimiento, pero tienen limitaciones en la edición de texto enriquecido.
- Por otro lado, herramientas como Microsoft Word ofrecen esa edición de texto avanzada y flexible que le falta a Obsidian, pero carece de un sistema eficiente para relacionar información de forma estructurada. 

Como resultado, tenemos que los usuarios que trabajan con conocimiento complejo (estudiantes, investigadores, desarrolladores) deben alternar entre múltiples herramientas, generando fricción, poca centralización en el proceso de trabajo y baja eficiencia en la gestión de la información. 

---
## 2. Objetivo del Sistema

Desarrollar una aplicación de escritorio que permita a los usuarios:

- Crear y editar documentos con capacidades avanzadas de formato (similares a un procesador de texto).
- Alternar entre el formato de edición de texto avanzado con el formato Markdown según las necesidades del usuario.
- Establecer relaciones explícitas entre notas y documentos mediante enlaces internos. 
- Visualizar y navegar dichas relaciones como un sistema de conocimiento interconectado. 
- Mediante un buscador avanzado, acceder a una wiki personal basada en el grafo de conocimiento. 

El sistema buscará integrar estas capacidades en una única plataforma coherente, priorizando el control del usuario sobre su información y la profundidad en la edición y organización del contenido.

---
## 3. Stakeholders

| Stakeholder           | Tipo    | Poder | Interés  | Estrategia                         |
| --------------------- | ------- | ----- | -------- | ---------------------------------- |
| Estudiantes           | Externo | bajo  | Alto     | Priorizar usabilidad y simplicidad |
| Desarrollador         | Interno | Alto  | Alto     | Gestionar activamente              |
| Investigadores        | Externo | Bajo  | Muy alto | Validar estructura de conocimiento |
| Escritores            | Externo | Bajo  | Medio    | Mejorar experiencia de escritura   |
| Gestores Conocimiento | Externo | Bajo  | Muy alto | Optimizar organización y enlaces   |

---
## 4. Problemas Actuales

- Dificultad para conectar ideas en documentos largos
- Pérdida de contexto entre múltiples archivos
- Limitaciones en el formato de texto en apps de notas
- Dependencia de múltiples herramientas

---
## 5. Alcance Inicial

### Incluye

- Edición de texto
- Creación de notas
- Enlaces entre notas
- Visualización básica de relaciones
- Alternancia entre edición compleja y Markdown
- Versionado simple

### No Incluye

- Colaboración en tiempo real
- Sincronización en la nube
- Plugins
- IA
- Wiki personal

---
## Suposiciones

- El usuario trabajará en local
- No se requiere conexión a internet
- El volumen de datos será manejable en una máquina personal

---
## Restricciones

- Aplicación de escritorio
- Recursos limitados
