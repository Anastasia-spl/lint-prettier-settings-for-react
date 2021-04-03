Установка зависимостей Установить в проект следующие пакеты.

npm install --save-dev prettier husky lint-staged Интерграция плагинов Ссылки на
документацию по интеграции плагинов в популярные редакторы.

Prettier editor integration ESLint editor integration Настройки VSCode Для
комфортной работы, после установки плагинов, нужно добавить несколько настроек
редактора для автосохранения и форматирования файлов.

{ "files.autoSave": "onFocusChange", "editor.formatOnSave": true,
"editor.codeActionsOnSave": { "source.fixAll.eslint": true } }
