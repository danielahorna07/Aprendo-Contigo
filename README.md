# Aprendo-Contigo

### Versión 1 - 16/07/2024 - Analytics 180 DC

**Objetivo:** Extraer la información de los voluntarios que llega al correo de Aprendo Contigo

**Etapas:**
1. Clasificar datos del voluntario: Definir campos que llenan los voluntarios y llegan a los correos.
2. Extraer información de los correos: Entra a la bandeja de entrada de Outlook, verifica que la cuenta sea "psicologia@aprendocontigo.org" y extrae todos los correos cuyo asunto sea "WEB-FORMULARIO VOLUNTARIADO". Separa los datos, campo por campo, y lo agrega a una tabla (dataframe)
3. Limpieza de datos: Se limpian los 23 campos. Quitar espacios en blanco, nulos, caracteres sucios y data extra.
4. Exportar al excel: La tabla limpia se extrae a un excel llamado "Base de Datos - Voluntarios".

**Observación:** Se utilizan 5 bibliotecas durante todo el proceso. Si es la primera vez que se ejecuta el código, correr la primera linea para instalarlas (pip install)
