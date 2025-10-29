# Loginom LLM Kit

* Версия: 1.0.0
* Проверено: Все редакции Loginom 7.2.9

Библиотека для работы с большими языковыми моделями (LLM).

## Установка

1. Определите рабочий каталог, где будут расположены ваши библиотеки:

   * Для серверных редакций — в рабочем каталоге Loginom Server (в папке пользователя или в общей папке пользователей);
   * Для настольных редакций — в любой папке на локальном диске.

2. Создайте в нем подкаталог **libs**.

3. Разместите папку **llm_kit** в каталоге **libs**.

4. Добавьте ссылку на пакет **loginom_llm_kit.lgp** в своем пакете и используйте компоненты библиотеки.

```
Рабочий каталог
└─ libs
   ├─ llm_kit
   │  └─ loginom_llm_kit.lgp
   ├─ llm_kit_demo
   ├─ silver_kit
   │  └─ loginom_silver_kit.lgp
   └─ json_kit
      └─ loginom_json_kit.lgp
```


## Требования

Для работы библиотеки **Loginom LLM Kit** необходимо:

* Установленное ПО Loginom. Версия не ниже 7.2.9
* Библиотека **Loginom Silver Kit** ([скачать на GitHub](https://github.com/loginom/loginom-silver-kit)). Версия не ниже 3.1.5.
* Библиотека **Loginom JSON Kit** ([скачать на GitHub](https://github.com/loginom/loginom-json-kit)). Версия не ниже 1.1.0.

## Список компонентов

### Компоненты

* [Новый проект](./docs/new-project.md)
* [Параметры. Структурированный ответ](./docs/parameters-structured-response.md)
* [Подключение. GigaChat](./docs/connection-gigachat.md)
* [Подключение. Ollama](./docs/connection-ollama.md)
* [Подключение. OpenRouter](./docs/connection-openrouter.md)
* [Подключение. LLM](./docs/connection-llm.md)
* [Промпт. Импорт](./docs/prompt-import.md)
* [Промпт. JSON](./docs/prompt-json.md)
* [Промпт. Список JSON](./docs/prompt-json-list.md)
* [Схема запроса. JSON](./docs/request-schema-json.md)
* [LLM. Запрос](./docs/llm-request.md)
* [LLM. Генерация признаков](./docs/llm-feature-generation.md)
* [LLM. Обогащение данных](./docs/llm-data-enrichment.md)

### Мета-компоненты

* [meta-Запрос к LLM](./docs/meta-llm-request.md)
* [meta-Промпты](./docs/meta-prompts.md)
* [meta-Промпты. Датасет](./docs/meta-prompts-dataset.md)
* [meta-GigaChat](./docs/meta-gigachat.md)
* [meta-LLM](./docs/meta-llm.md)
* [meta-Ollama](./docs/meta-ollama.md)
* [meta-OpenRouter](./docs/meta-openrouter.md)

## Кейсы использования

1. [Извлечение числовых фактов из неструктурированного текста](./docs/use-case-01.md)
2. [Обогащение данных о брендах](./docs/use-case-02.md)
3. [Генерация новых признаков](./docs/use-case-03.md)