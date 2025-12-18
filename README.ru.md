# UniversalGPT (форк DuckDuckGPT)

**Уведомление о форке / Fork notice**

Этот репозиторий — форк проекта [KudoAI/duckduckgpt](https://github.com/KudoAI/duckduckgpt). Первоначальный проект создан **KudoAI**. Этот форк изменён и поддерживается **Processor** (https://github.com/Processori7).

**Первоначальный автор / Original author:** KudoAI — **Данная версия / This version:** Processor (https://github.com/Processori7)

---

## Что такое UniversalGPT? 🚀

UniversalGPT добавляет ответы, сгенерированные ИИ, прямо на страницы результатов поиска различных поисковых систем. Это форк DuckDuckGPT с расширенной поддержкой сайтов и UI-улучшениями.

Основные функции:
- Панель с ответами ИИ справа на странице поиска
- Поддерживаемые поисковые системы: Yandex, DuckDuckGo, Brave, Google, Bing, Rambler, Mail.ru, Yahoo, Ecosia, Startpage
- Скрытие рекламы, удаление футера и автоматическая прокрутка
- Значения по умолчанию: **Proxy API включён**, **Автопрокрутка включена**
- Фиксированная правая панель с адаптивным размером
- Увеличенное поле ввода чата, улучшенный стиль и доступность
- Много настроек в модальном окне настроек

---

## Установка

1. Установите менеджер userscript (Tampermonkey, ScriptCat, Violentmonkey и т.д.)
2. Установите userscript, расположенный в `greasemonkey/universalgpt.user.js` (или установите скрипт из релиза)
3. Откройте поисковый сайт — панель UniversalGPT появится справа

---

## Использование

- Нажмите кнопку настроек (⚙️) в панели, чтобы изменить поведение (стриминг, proxy mode, сводки)
- Proxy mode использует прокси API для получения ответов GPT-4o без учётной записи ChatGPT (включено по умолчанию)
- Вводите вопросы или запросы на сводки в поле чата

---

## Благодарности и лицензия

- Первоначальный проект: **KudoAI** — https://github.com/KudoAI/duckduckgpt
- Этот форк: **Processor** — https://github.com/Processori7/universalGPT

Лицензия MIT — см. `LICENSE.md`