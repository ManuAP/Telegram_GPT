import telebot
import openai
import os

GPT = os.environ['GPT_KEY']
BOT = os.environ['BOT_KEY']

bot = telebot.TeleBot(BOT)
openai.api_key = GPT


@bot.message_handler(content_types=["text"])
def handle_text(message):
  response = openai.Completion.create(
    engine="text-davinci-003",
    prompt=f"{message.text}",
    max_tokens=1024,
    n=1,
    stop=None,
    temperature=0.5,
  )
  bot.send_message(message.chat.id, response.choices[0].text)


bot.polling()
