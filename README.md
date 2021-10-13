# Калькулятор на Vue 3

Калькулятор расхода битумопроизводной продукции "БРИТ".

## Вспомогательные ресурсы

| [Google doc](https://docs.google.com/document/d/1k9Fo7ViuC7z_Y8eYO0Gh9_dTsJCbLxRgWSeP0bfh5Q0/edit) | [Lucid chart](https://lucid.app/lucidchart/b4ab593e-3906-4f82-ac74-6f64e487b6ac/edit?beaconFlowId=BF60F1D654728062&invitationId=inv_d8f14886-dca5-4b21-acaa-332be9c95224&page=0_0#) | [Figma board](https://www.figma.com/file/jbxAbxQtoclSNC52qPwZSk/Калькулятор-на-Vue-3?node-id=7%3A3) |
|-|-|-|

### Основные подпроцессы

1. Устройство деформационных швов в бетонных конструкциях.
2. Устройство щебеночно-мастичных деформационных швов мостовых сооружений.
3. Устройство напыляемой гидроизоляции.

### Ключевые шаги

1. Выбор данных из фильтров пользователем.
2. Ввод данных пользователем.
3. Вывод результата для пользователя.

---

### Установка проекта

```
npm install
```

### Компиляция и запуск сервера для разработки

```
npm run serve
```

### Компиляция и минификация для прода

```
npm run build
```

### Публикация в GitHub Pages

Создаете локальную ветку `gh-pages` с содержимым ветки `main`. Создаете файл `vue.config.js` в корневой папке со следующим содержимым:

```
module.exports = {
    publicPath: ''
}
```

Делаете `npm run build`. Из файла `.gitignore` удаляете строчку с `/dist`. Делаете коммит *локально*. Далее выполняете команду, которая загружает в ветку только содержимое папки `/dist`:

```
git subtree push —prefix dist origin gh-pages
```

Страница на GitHub Pages обновляется в течение пяти минут.