# Generador de Ideas con CrewAI

Bienvenido al proyecto Generador de Ideas, una aplicación creada con el poderoso framework CrewAI. Este sistema utiliza agentes inteligentes para analizar comentarios y generar ideas innovadoras de contenido que se alineen con los temas y las necesidades expresadas en los inputs proporcionados.

## Descripción

Esta aplicación está diseñada para convertir comentarios o texto proporcionado como entrada en una lista de ideas útiles y relevantes para crear contenido. A través del uso de un sistema multiagente, los comentarios son procesados y analizados por agentes especializados que colaboran para proponer las mejores ideas posibles.

## ¿Cómo funciona?

El proceso consta de tres pasos principales:

1. Entrada de Comentarios: Se proporciona una lista de comentarios como input.
2. Procesamiento por Agentes: Los agentes trabajan juntos para analizar los temas, el tono y el contexto de los comentarios.
3. Generación de Ideas: Basándose en el análisis, el sistema genera una lista de ideas claras y accionables para contenido.

## Instalación

Asegúrate de tener instalado Python (>= 3.10 <= 3.13) en tu sistema.

Primero, instala UV para manejar dependencias:

```bash
pip install uv
```

Luego, navega a la carpeta raíz del proyecto e instala las dependencias utilizando:

```bash
crewai install
```

## Configuración

1. Clave API de OpenAI: Añade tu OPENAI_API_KEY en el archivo .env.
2. Configuración de Agentes: Edita src/config/agents.yaml para personalizar los roles y capacidades de los agentes.
3. Tareas Personalizadas: Modifica src/config/tasks.yaml para definir tareas específicas.
4. Lógica Personalizada: Ajusta src/crew.py y src/main.py según las necesidades de tu proyecto.

## Uso

Para iniciar el sistema y generar ideas, ejecuta el siguiente comando desde la raíz del proyecto:

```bash
crewai run
```

El sistema analizará los comentarios proporcionados y generará una lista de ideas en un archivo de salida.

## Ejemplo de Salida

Dado un conjunto de comentarios como:

```
- "Me gustaría ver más contenido sobre productividad."
- "¿Podrían hablar sobre herramientas de IA para pequeños negocios?"
```

El sistema podría generar ideas como:

1. "Escribe un artículo sobre las 5 mejores herramientas de IA para aumentar la productividad."
2. "Crea una guía sobre cómo las pequeñas empresas pueden implementar IA de manera efectiva."

## Soporte

Si necesitas ayuda o tienes preguntas sobre este proyecto:

* Consulta la documentación de CrewAI
* Únete a nuestro Discord
* Explora el repositorio oficial de CrewAI

Con CrewAI, transformar comentarios en contenido inspirador nunca fue tan sencillo. ¡Comienza a generar ideas hoy! 🚀