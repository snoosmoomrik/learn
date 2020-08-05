# WEB самообучение

## Документация
- https://developer.mozilla.org/ru/docs/Web/JavaScript - javascript
- https://learn.javascript.ru - javascript на русском с уроками
- https://www.typescriptlang.org/docs/home.html - typescript
- http://typescript-lang.ru/docs/ - typescript на русском (часть про jsx - какой-то трэш, но остальное можно почитать. в любом случае прошлая ссылка лучше)
- https://ru.reactjs.org/docs/getting-started.html - react
- https://github.com/kriasoft/universal-router/blob/master/docs/getting-started.md - universal router (библиотека для роутинга)
- https://mobx.js.org/intro/concepts.html - mobx (библиотека для стейт-менеджмента)
- https://dev.to/sirwanafifi/mobx-with-react-and-typescript-58bf - создание todoapp с использованием mobs
- https://cssinjs.org - jss (библиотека для стилизации компонентов)
- https://github.com/inversify/InversifyJS/tree/master/wiki - inversely (библиотека для DI)
- https://docs.npmjs.com - npm (пакетный менеджер)
- https://webpack.js.org/concepts - webpack (сборщик)

## Лекции
- https://www.youtube.com/watch?v=aQkgUUmUJy4&list=PLqKQF2ojwm3l4oPjsB9chrJmlhZ-zOzWT - серия лекций по javascript
- https://www.youtube.com/watch?v=Ti2Q4sQkNdU - javascript es6+ 2:08:52
- https://www.youtube.com/watch?v=SQMCtWnCxEA - javascript пдробнее про промисы 43:54
- https://www.youtube.com/watch?v=YJVj4XNASDk - javascript паттерны 1:54:30
- https://www.youtube.com/watch?v=xq13wiqvcTc - про SOLID
- https://www.youtube.com/watch?v=nyIpDs2DJ_c - typescript основы 1:07:59
- https://www.youtube.com/watch?v=7NU6K4170As - typescript подробнее про генерики и декораторы 2:14:00
- https://www.youtube.com/watch?v=OvLWWvjoi8s - лекция по React+typescript (основы c FunctionComponents + hooks вместо ClassComponents + mobs и css вместо jss) 1:18:00
- https://www.youtube.com/watch?v=SKy3vXLh8A8 - серия лекций по mobx (без typescript)
- https://www.youtube.com/watch?v=ETyltCwtQHs - серия лекций по DI. 1-3: теория, 4: примеры использования inversely
- https://www.youtube.com/watch?v=eSaF8NXeNsA - лекция по webpack (система сборки) 2:51:49
> ⚠️ По jss вменяемых лекций нет, так что курим документацию и смотрим как оно используется в прокете 

> ⚠️ В большинстве роликов в tsx используются FunctionComponents с хуками. Это сравнительно новый способ писать компоненты и так как проект мы начали довольно давно, у нас вместо них в основном используются классовые компоненты. Про них можно немного почитать тут https://reactjs.org/docs/components-and-props.html а кратко про разницу между ними тут https://medium.com/@Zwenza/functional-vs-class-components-in-react-231e3fbd7108


## Sandbox
- https://codesandbox.io - песочница, в которой можно попробовать все, что написано в документации и показано в лекциях. Выбираем Create Sandbox -> React Typescript и пробуем


## Расширения для chrome
- https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en - помогает ориентироваться в дереве реактовских компонентов и смотреть, что перерендеревается
- https://chrome.google.com/webstore/detail/instant-eyedropper/okkpedjcdhfkhjnfcbebpdpnhdhibeic/related?hl=en - колорпикер. бывает полезно
- https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?hl=en - показывает имя шрифта при наведении


## Расширения для VSCode
- debugger for chrome https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome - отладка внутри VSCode
- gitlens https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens - много полезного для работы с гитом
- git history https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory - показывает лог гита с ветками, как в больших идешках, позволяет черипикать, ребейзиться, ресетиться и много чего еще
- github pull requests https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github - интеграция с GitHub
- rest client https://marketplace.visualstudio.com/items?itemName=humao.rest-client работа с .http файлами. можно кидать запросики
- todo heighlight https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight подсвечивает тудушки
- bracket pair colorizer 2 https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2 - подсвечивает парные скобки
- live share extension pack https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack - расширение, которое работает почти как гугловские документы. можно вместе в одном vscode работать. сам не пользовался т.к. не с кем было, но может пригодиться
- чтобы красивее было material icon theme, one monokai theme

## Конфиг VSCode
```
{
  "files.autoSave": "afterDelay",
  "workbench.list.openMode": "doubleClick",
  "editor.tabSize": 2,
  "editor.minimap.enabled": false,
  "editor.fontFamily": "'Fira Code'",
  "editor.fontLigatures": true,
  "editor.fontSize": 16,
  "explorer.confirmDragAndDrop": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "One Monokai",
  "typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBraces": false,
  "typescript.updateImportsOnFileMove.enabled": "never",
  "gitlens.advanced.messages": {
    "suppressShowKeyBindingsNotice": true
  },
  "explorer.confirmDelete": false,
  "git.confirmSync": false,
  "explorer.openEditors.visible": 0,
  "git.enableSmartCommit": true,
  "dart.openDevTools": "flutter",
  "javascript.format.semicolons": "remove",
  "typescript.format.semicolons": "remove",
  "typescript.preferences.quoteStyle": "single",
  "javascript.preferences.quoteStyle": "single",
  "editor.renderControlCharacters": true,
  "npm.enableScriptExplorer": true,
  "editor.semanticHighlighting.enabled": true,
  "diffEditor.renderSideBySide": true,
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "files.exclude": {
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "workbench.tree.renderIndentGuides": "always",
  "bracket-pair-colorizer-2.highlightActiveScope": true,
  "diffEditor.ignoreTrimWhitespace": false,
  "gitlens.views.repositories.files.layout": "tree",
  "todo-tree.tree.showScanModeButton": false,
  "githubPullRequests.telemetry.enabled": false
}
```
	 