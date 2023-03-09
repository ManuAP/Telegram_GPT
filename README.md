<!DOCTYPE html>
<html>

<body>
	<h1>Telegram_GPT.py</h1>
	<p>Este es un script en Python que utiliza la API de OpenAI para generar respuestas a mensajes de texto enviados a un bot de Telegram. Se utiliza el modelo de lenguaje GPT-3 de OpenAI para generar las respuestas.</p>
<h2>Uso</h2>
<p>Para utilizar este script, necesitas tener una cuenta en Telegram y crear un bot de Telegram. Una vez creado el bot, debes obtener su clave API (BOT_KEY) y la clave API de OpenAI (GPT_KEY).</p>
<p>El script escucha los mensajes de texto enviados al bot y utiliza la API de OpenAI para generar una respuesta a cada mensaje. La respuesta se envía de vuelta al usuario que envió el mensaje.</p>

<h2>Instalación de dependencias</h2>
<p>Este script requiere las siguientes dependencias:</p>
<ul>
	<li>telebot</li>
	<li>openai</li>
	<li>os</li>
</ul>
<p>Puedes instalar estas dependencias utilizando el siguiente comando:</p>
<pre><code>pip install telebot openai</code></pre>

<h2>Cómo utilizar el script</h2>
<p>Para utilizar este script, sigue los siguientes pasos:</p>
<ol>
	<li>Clona este repositorio en tu máquina local.</li>
	<li>Crea un bot de Telegram y obtén su clave API.</li>
	<li>Obtén la clave API de OpenAI.</li>
	<li>Define las variables de entorno BOT_KEY y GPT_KEY con las claves API correspondientes.</li>
	<li>Abre un terminal y navega hasta el directorio donde has clonado este repositorio.</li>
	<li>Ejecuta el siguiente comando:</li>
	<pre><code>python Telegram_GPT.py</code></pre>
	<li>Envía mensajes de texto al bot de Telegram y espera las respuestas generadas por el modelo de lenguaje GPT-3 de OpenAI.</li>
</ol>
