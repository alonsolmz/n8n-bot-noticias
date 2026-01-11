# 🚀 AI News Curator Bot (n8n + Groq/Gemini + Telegram)

Este proyecto es una automatización inteligente que recopila noticias tecnológicas diariamente, las procesa mediante Inteligencia Artificial para generar resúmenes ejecutivos y los envía automáticamente a Telegram.

## 🛠️ Tecnologías Usadas
* **n8n**: Orquestador de la automatización (Self-hosted).
* **Groq / Llama 3.1**: IA para el procesamiento de lenguaje natural y resúmenes.
* **NewsAPI**: Fuente de datos para titulares globales.
* **Telegram Bot API**: Interfaz de entrega al usuario.

## 📸 Demo
![Captura de pantalla de mi flujo en n8n](./img/n8n-workflow.png)
*Descripción: Flujo de nodos que conecta la API de noticias con el agente de IA y el bot de Telegram.*

![Captura de pantalla de Telegram](./img/telegram-demo.jpg)
*Descripción: Ejemplo real del resumen recibido en el móvil.*

## 🚀 Cómo Replicar este Proyecto
1. Instala n8n localmente.
2. Importa el archivo `workflow.json` incluido en este repositorio.
3. Configura tus credenciales gratuitas para:
   - NewsAPI.org
   - Groq Cloud (API Key)
   - Telegram (vía @BotFather)
4. ¡Ejecuta y disfruta!

## 💡 Valor Agregado
Este flujo soluciona el exceso de información (infoxicación) permitiendo al usuario mantenerse informado en menos de 1 minuto al día mediante curaduría inteligente de contenido.
