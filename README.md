# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list
https://monosnap.com/file/K5G2ldii3zHkl0hhkIX8Ko4HEhRUmi

# Получаем контакт по id

node index.js --action get --id 5
https://monosnap.com/file/3RVYiDEUNx79xE8Vd2Czpt9Q3s2kWO

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/gLK4oHLOgAQjTf0YXTe2wxDLbw887U

# Удаляем контакт

node index.js --action remove --id=3
https://monosnap.com/file/hcnM3Jk3NtevIevEpuYUbZSV5OrlkT
