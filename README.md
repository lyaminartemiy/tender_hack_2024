# Tender Hack 2024
## Создание функционала генерации наименования и характеристик СТЕ (Стандартной Товарной Единицы) в универсальном виде

Наше решение:
1. Предобработка входных данных: лемматизация, стемминг, очистка и т.д.
2. Парсинг дополнительных данных о характеристиках с маркетплейсов Ozon и различных медицинских сайтов.
3. `cointegrated/RU-BERT-TINY` для классификации входных наименований по категориям.
4. `IlyaGusev/saiga_mistral_7b` - GPT модель для генерации текста (результатов в виде JSON)
5. Все вспомогательные файлы лежат в гугле диске - https://drive.google.com/drive/folders/1nLaarTgCTdCdAUq5uUMumx1UutMkBKhI?usp=drive_link

## Архитектура нашей системы:
![alt text](https://github.com/lyaminartemiy/tender_hack_2024/blob/main/images/architecture.jpg)

## Пример генерации в web-интерфейсе:
![alt text](https://github.com/lyaminartemiy/tender_hack_2024/blob/main/images/photo_2024-04-07_12-55-58.jpg)
