Task Manager — React приложение

Этот проект представляет собой простой менеджер задач, созданный с помощью React. Он позволяет пользователям создавать, управлять и отслеживать свои задачи.

Функциональность

• Добавление задач: Создание новых задач с названием и необязательным описанием.
• Отметка как выполненная: Изменение статуса выполнения задачи.
• Удаление задач: Удаление выполненных или невыполненных задач.

Используемые технологии

• React — это основная JavaScript библиотека для создания пользовательских интерфейсов.
• Vite — это инструмент сборки, который призван обеспечить более быструю и компактную разработку для современных веб-проектов.
• [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md).
• [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/).

Установка

1. Клонируйте репозиторий: git clone <адрес репозитория>
2. Перейдите в директорию проекта: cd TaskManager
3. Установите зависимости: npm install
4. Запустите сервер разработки: npm run start

Это откроет приложение в вашем браузере.

Использование

После запуска приложения вы увидите список задач (сначала он будет пустым). Вы можете добавлять новые задачи, используя предоставленные поля ввода. Отмечайте задачи как выполненные, используя флажок. Удаляйте задачи по мере необходимости.

Дальнейшее развитие

• Реализовать постоянное хранилище (localStorage или база данных на сервере).
• Добавить приоритезацию задач.
• Интеграция с календарными приложениями.
• Улучшить стиль и пользовательский интерфейс.
