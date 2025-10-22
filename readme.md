# Template Repo

Template repo to fast make new $hyoo apps.

## After Make

- [ ] [Rename app then update index.html and CNAME](./app).
- [ ] [Update GitHub Workflow](.github/workflows).
- [ ] Update repo description and link to app at the GitHub.
- [ ] [Add this repo to $hyoo namespace](https://github.com/hyoo-ru/mam_hyoo/blob/master/hyoo.meta.tree).
- [ ] Rewrite this readme.



Сделать $mol_template_rich, который будет более расширенным и полезным. 

В нём будут добавлены: 
- файлик favicon (мол иконка), который вставлен в meta.tree и в index.html
- в index.html будет прописана og информация для сео. Нужно будет поправить на свою

- в /app будет создан app.view.tree с минимальным настроенным $mol_book2_catalog => $mol_page => $custom_button | $template_logo
- также там будет преднастроена переключение темы и $mol_source для ссылки на гитхаб
- также кнопка login/logout (в файлике .ts) - которая демонстрирует работу переключения страниц.

- создан компонент /ui/button (пока думаю какой конкретно?) и для него добавлен сторибук ($mol_demo). Может Hello world или ссылку на документация по молу/handbook, как это сделано для темплейтов для react/vue/nextjs.

- создан компонент logo и добавлена иконка в meta.tree (паблик файлы, /assets). Это должно показать, как правильно добавлять ресурсы в мол

- Добавить сторибук (mol_demo/mol_docs), добавить кастомный компонент (картинку лого и мб кнопку) и index.html, и добавить в meta.tree. Работать с сторибуком в моле легко - такая настройка даст огромный буст на старте.

- в deploy.yaml добавить строки, чтобы он из репозитория сразу создавал app и app/demo правильно. Тогда с gh_pages будет меньше вопросов, как развернуть 2 приложения в одном deploy.yaml

- Обновить readme.md в соответствии с расширенными компонентами. 

- демонстрация CSS и css-in-ts
- Hello world
