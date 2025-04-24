# README

## Introducción
Este notebook utiliza la biblioteca Langchain y Langgraph para crear un agente de reacción orientado al análisis de ciberinteligencia.


Requisitos
- Python 3.x
- Variables de entorno: OPENAI_API_KEY

## Uso
1. Instalar las bibliotecas necesarias utilizando pip: `pip install langchain langgraph langchain_openai pydantic scapy python-dotenv`
2. Configurar la variable de entorno OPENAI_API_KEY con la clave de API de OpenAI.
3. Cargar las variables de entorno utilizando `load_dotenv()`.
4. Ejecutar el notebook para crear el agente de reacción y realizar consultas DNS.

## Funcionalidad
El agente de reacción se crea utilizando la función `create_react_agent` de Langgraph, que utiliza el modelo de lenguaje de OpenAI para generar respuestas a las consultas DNS. El agente utiliza la biblioteca Scapy para realizar las consultas DNS.

## Notas
- Asegurarse de tener instalada la biblioteca Scapy y configurada correctamente para realizar consultas DNS.
- La variable de entorno OPENAI_API_KEY debe estar configurada para utilizar el modelo de lenguaje de OpenAI.
