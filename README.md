# ИИ-ассистент для компании Пресскиоск

Ссылка на проект - @PressKiosk_bot

## Скриншоты

Готовый бот в Telegram и его ответы
![Скриншот 1](https://github.com/dr-vadim-pp/ai_presskiosk_bot/blob/main/f1.jpg?raw=true)
Запись событий в Google Календаре

![Скриншот 2](https://github.com/dr-vadim-pp/ai_presskiosk_bot/blob/main/f2.jpg?raw=true)

Настройки в Савви
![Скриншот 3](https://github.com/dr-vadim-pp/ai_presskiosk_bot/blob/main/f3.jpg?raw=true)

## Описание проекта

Проект направлен на создание интеллектуального ассистента для компании **Пресскиоск**, который будет взаимодействовать с клиентами через Telegram. Ассистент способен осмысленно вести диалог, отвечать на вопросы на основе базы знаний компании, записывать клиентов на встречи и автоматически добавлять записи в Google Календарь.

Цель проекта — улучшить качество обслуживания клиентов, автоматизировать рутинные процессы и обеспечить удобный способ коммуникации между клиентами и компанией.

---

## Функционал

1. **Осмысленное ведение диалога**  
   - Использование нейросети для естественного общения с клиентами через Telegram.
   - Понимание контекста вопросов и предоставление точных ответов.

2. **Ответы на вопросы на основе базы знаний**  
   - Создание системного промпта и базы знаний компании для корректной обработки запросов.
   - Интеграция с базой данных компании для актуализации информации.

3. **Запись на встречу**  
   - Возможность записи клиента на встречу через бота.
   - Автоматическое добавление встречи в Google Календарь.

---

## Используемые сервисы

1. **Qwen**  
   - Для создания системного промпта и формирования базы знаний.
   - Обеспечивает высокую точность ответов на вопросы клиентов.

2. **Савви (Suvvy.ai)**  
   - Платформа для разработки ИИ-ассистента.
   - Предоставляет инструменты для интеграции с другими сервисами.

3. **Telegram**  
   - Платформа для взаимодействия с клиентами.
   - Бот позволяет вести диалог, отвечать на вопросы и записывать на встречи.

4. **Google Календарь**  
   - Интеграция для автоматического добавления встреч в календарь.

---

## Установка и настройка

### Предварительные требования
- Учетная запись Telegram.
- Доступ к API Qwen и Suvvy.ai.
- Учетная запись Google с доступом к Google Calendar API.

### Шаги по установке
1. **Создайте Telegram-бота**  
   - Перейдите к [BotFather](https://t.me/BotFather) в Telegram.
   - Создайте нового бота и получите токен.

2. **Настройте базу знаний**  
   - Используйте Qwen для создания системного промпта и загрузки базы знаний компании.

3. **Настройте Suvvy.ai**  
   - Зарегистрируйтесь на платформе [Suvvy.ai](https://suvvy.ai/).
   - Подключите Telegram-бота и настройте его поведение.

4. **Интеграция с Google Календарем**  
   - Включите Google Calendar API в [Google Cloud Console](https://console.cloud.google.com/).
   - Настройте доступ для добавления событий в календарь.

5. **Запуск системы**  
   - Разверните проект на сервере или локальной машине.
   - Убедитесь, что все сервисы работают корректно.

---

## Пример использования

### Сценарий 1: Ответы на вопросы
- **Клиент**: "Какие издания вы предлагаете?"  
- **Ассистент**: "Мы предлагаем более 7000 периодических изданий различных тематик, включая бизнес, право, медицину, образование и многое другое. Вы можете ознакомиться с полным каталогом на нашем сайте."

### Сценарий 2: Запись на встречу
- **Клиент**: "Хочу записаться на встречу."  
- **Ассистент**: "Когда вам удобно встретиться? Укажите дату и время."  
- **Клиент**: "15 октября, 14:00."  
- **Ассистент**: "Вы успешно записаны на встречу 15 октября в 14:00. Встреча добавлена в ваш календарь."

---

## Лицензия

Этот проект распространяется под лицензией MIT. Подробнее см. файл [LICENSE](LICENSE).

---

## Авторы

- https://github.com/dr-vadim-pp (ссылка на профиль GitHub)

---

## Ссылки

- [Qwen](https://qwen.com)
- [Suvvy.ai](https://suvvy.ai/)
- [Telegram Bot API](https://core.telegram.org/bots/api)
- [Google Calendar API](https://developers.google.com/calendar/api)

---

## Контакты

Если у вас есть вопросы или предложения по улучшению проекта, свяжитесь с нами:

- Email: pp.vadim.pp@gmail.com
- Телефон: +7 (981) 938-04-78
