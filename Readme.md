# Проект <a>«Седона»</a>

# Руководство по работе с проектом

## Структура проекта

---

_Не удаляйте и не изменяйте папки и файлы:_
_`.editorconfig`, `.gitattributes`, `.gitignore`, `package.json`._

---
### source

В директории размещаются `html`- файлы с версткой и папки:
`fonts` - Папка для шрифтов,
`img` - Папка для изображений,
`js` - Папка для скриптов,
`saas` Папка для файлов препроцессора Sass.

Структура директории `source` может быть произвольной.

## Сценарии

После создания проекта вам доступны следующие сценарии.

### Запуск проекта

```bash
npm start
```

После запуска, приложение доступно для просмотра в браузере по адресу [http://localhost:3000](http://localhost:3000).

При сохранении изменений, проект перезапускается и обновляется в браузере. Таким образом, вы можете следить за разработкой проекта в режиме реального времени.

### Проверка линтером

```bash
npm run lint
```

Запуск проверки проекта анализаторами кода **EditorConfig** и **StyleLint**.

Анализ кода производится только в файлах, которые находятся в директории `source`.

**Обратите внимание**, при запуске данной команды, ошибки выводятся в терминал.

### Сборка проекта

```bash
npm run build
```

Запуск сборки приложения.

В процессе сборки приложения, код приложения оптимизируется и минимизируется, для достижения наилучшей производительности.

Во время выполнения инструкций по сборке проекта, в корне проекта создается директория `build`, в которую будут помещены результирующие файлы. После сборки проект готов к публикации.
