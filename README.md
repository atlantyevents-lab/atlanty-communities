# Сообщества для Атланты Сити

Публичный каталог бизнес-сообществ: поиск, фильтры, лидеры и ссылки на источники, география, условия участия и предварительная оценка приглашения на Атланты Сити.

Сайт: https://atlantyevents-lab.github.io/atlanty-communities/

Источник — каталог `communities/` приватного репозитория `atlantyevents-lab/atlanty-data`. Здесь публикуется только автономный HTML с открытыми сведениями; исходная база остаётся приватной.

## Обновление

В актуальной ветке `atlanty-data` обновите и проверьте данные, затем пересоберите сайт:

```sh
python ~/repos/atlanty-data/communities/build_site.py --out ~/repos/atlanty-communities/index.html
```

В `~/repos/atlanty-communities` закоммитьте `index.html` и запушьте в `main`. GitHub Pages публикует сайт из `main`, корень `/`. Файл `.nojekyll` отключает обработку Jekyll.
