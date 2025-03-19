# Антибулінг Telegram-бот

Цей бот надає інформацію та ресурси для протидії булінгу в освітньому середовищі.

## Структура боту

```mermaid
flowchart TD
    A["/start command"] --> B[Головне меню]
    
    B -->|"ЩО РОБИТИ ЯКЩО"| C1[Розділ алгоритму дій]
    B -->|"ТЕЛЕФОНИ ДОВІРИ"| C2[Телефони гарячих ліній]
    B -->|"НОРМАТИВНА БАЗА"| C3[Документи МОН]
    B -->|"ПОСІБНИКИ"| C4[Категорії посібників]
    B -->|"КІБЕРБУЛІНГ"| C5[Розділ кібербулінгу]
    B -->|"КОРОБКА З МАТЕРІАЛАМИ"| C6[Категорії матеріалів]
    B -->|"КОРИСНЕ з ДІЯ.ОСВІТА"| C7[Курси на ДІЯ]
    B -->|"ГО «ТРИКУТНИК»"| C8[Контакти організації]
    B -->|"Зв'язок з розробником"| C9[Контактна інформація]
    
    %% Далі вставте решту блок-схеми...
