## Установка и сборка

[Windows](https://tug.org/texlive/windows.html)

После установки перейти в репозиторий проекта, запустить

```
xelatex main
biber main
xelatex main
xelatex main
```

## Редактирование

Отчёт разбит на разные компоненты, которые можно найти в `components`.
Новые сабкомпоненты следует добавлять в `main.tex` соотвествующего компонента
