<p align="center">
    <img src="https://github.com/AI-School-F5-P2/Scalianchat_SQL/blob/main/images/eva_01.gif" alt="EvaSQL" width="200" height="200">
</p>

# 🤖 ChatBot EvaSQL

## Planteamiento

🔍 Acceder y comprender la información de una base de datos SQL puede ser desafiante para aquellos sin experiencia técnica. Sin embargo, los modelos de lenguaje avanzados y las nuevas tecnologías de Inteligencia Artificial disponibles en la nube, nos permiten crear herramientas para solventar esta situación. 

💡 Por eso, nuestro ChatBot EvaSQL, tiene como objetivo facilitar el acceso a la información y la interpretación de los datos mediante la generación de consultas SQL y gráficos interactivos a partir de lenguaje natural. Todo esto se realiza a través de una interfaz amigable que simplifica la interacción con la base de datos, permitiendo a los usuarios realizar consultas y obtener respuestas de manera rápida y eficiente.

## Características Principales

- **Interfaz Intuitiva**: Conversa con el ChatBot como lo harías con un amigo, sin necesidad de comandos complicados.
- **Traducción a SQL**: Transforma consultas en lenguaje natural a consultas SQL comprensibles para la base de datos.
- **Generación de Gráficos**: Crea gráficos interactivos a partir de los resultados de las consultas para una visualización clara de los datos.
- **Soporte Multilingüe**: Accede al ChatBot en tu idioma preferido para una experiencia personalizada.
- **Servicio de Voz**: Formula consultas y recibe respuestas utilizando tu voz.
- **Versión Dockerizada**: Despliega el ChatBot fácilmente en cualquier entorno gracias a su versión dockerizada.
- **Despliegue en Azure**: Accede al ChatBot desde cualquier dispositivo autorizado mediante un enlace o código QR.

## Paso a Paso de Cómo Usarlo

1. **Clona o descarga el repositorio desde [GitHub](https://github.com/AI-School-F5-P2/Scalianchat_SQL.git):**
    ```bash
    git clone https://github.com/AI-School-F5-P2/Scalianchat_SQL.git
    ```
    
2. **Instala las dependencias necesarias:**
    ```bash
    pip install -r requirements.txt
    ```
    
3. **Crea el archivo .env con las API keys necesarias para establecer las conexiones con los servicios de Azure.**
   
4. **Ejecuta el script para iniciar la interfaz en Streamlit del ChatBot:**
    ```bash
    streamlit run str_interface.py
    ```

5. **Interactua con el ChatBot escribiendo tus consultas en lenguaje natural o activando el micrófono para hablar.**

6. **Visualiza los resultados de las consultas en forma de texto y/o gráficos interactivos.**

## Documentación Completa del Proyecto

[Notion ChatBot EvaSQL](https://past-alarm-18f.notion.site/Proyecto-pedag-gico-SCALIAN-Chatbot-SQL-2d78c4730d9c4d04a59279494481afaa?pvs=4)

[Presentación ChatBot EvaSQL](https://www.canva.com/design/DAF9bSfFLLY/o10dmMGBv_Ji5MPW1C5gJg/view?utm_content=DAF9bSfFLLY&utm_campaign=designshare&utm_medium=link&utm_source=editor)

## Descripción de los Archivos

- **data_cleaning.ipynb**: Notebook para la limpieza de datos del dataset original.
- **azure_db.py**: Script para la creación de tablas en Azure SQL Database y carga de datos.
- **json_emb_files_generator.ipynb**: Notebook para la generación de documentos JSON para Azure AI Search.
- **azure_search.ipynb**: Configura, crea el índice en Azure AI Search y sube los documentos JSON generados.
- **rag_openai.py**: Configuración de llamadas a la API de Azure OpenAI.
- **str_interface.py**: Programa principal e interfaz en Streamlit.
- **README.md**: Documentación detallada sobre el proyecto.
- **requirements.txt**: Dependencias necesarias para la versión dockerizada.
- Los demás archivos se explican detalladamente en la documentación de Notion [Notion ChatBot EvaSQL](https://past-alarm-18f.notion.site/Proyecto-pedag-gico-SCALIAN-Chatbot-SQL-2d78c4730d9c4d04a59279494481afaa?pvs=4)

## Desarrolladores

👩🏻‍💻 [Karla Lamus Oliveros](https://www.linkedin.com/in/karla-lamus/)

🧑🏽‍💻 [Miguel Mendoza Espinoza](https://www.linkedin.com/in/miguelmendozaespinoza9a010114a/)

👩🏻‍💻 [Sandra Gómez Santamaría](https://www.linkedin.com/in/sandragomezs/)

👩🏼‍💻 [Ana Gómez Giraldo](https://www.linkedin.com/in/ana-milena-gomez-giraldo/?locale=es_ES)


## Agradecimientos

Agradecemos especialmente a Scalian y Factoría F5 por su apoyo y acompañamiento durante el desarrollo de este proyecto.
