# Руководство по установке n8n AI Automation Workflow

## Предварительные требования
- Установленный n8n (локально или в облаке)
- API-ключ OpenAI или Anthropic
- Учетные данные Google Sheets API (если используется Google Sheets)
- Токен Telegram-бота и ID чата (если используется Telegram)

## Установка
1. Установите n8n локально или зарегистрируйтесь в n8n cloud.
2. Импортируйте workflow из файла `workflows/sample_workflow.json`.
3. Настройте ноды, указав свои API-ключи и учетные данные.

## Конфигурация
- **OpenAI/Anthropic Node**: Укажите API-ключ в настройках учетных данных.
- **Google Sheets Node**: Введите ID таблицы и пройдите авторизацию.
- **Telegram Node**: Укажите токен бота и ID чата.

## Тестирование
Используйте пример входных данных из `examples/sample_input.json` для тестирования workflow через webhook.

## Использование
Отправьте POST-запрос на URL webhook с JSON-телом, содержащим описание задачи.
