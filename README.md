1. Установка virtualenv

```
pip install virtualenv
```

2. Создание виртуальной среды virtualenv

```
virtualenv venv
```

3. Установка зависимостей

```
pip install mkdocs mkdocs-material
```

4. Добавить GitHub Action для сборки и деплоя проекта в `.github/workflows/`

5. В репозитории GitHub перейти в Settings > Pages, в секции Build and deployment выбрать Source - Deploy from a branch, Branch - gh-page

6. Ресурсы для собственной темы расположены в директории `mydocs/custom_theme`

7. Для валидации сборка происходит в `strict` режиме

8. Для минификации разметки и стилей используется плагин `mkdocs-minify-plugin`
