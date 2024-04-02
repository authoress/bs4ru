# bs4ru

Здесь лежат исходники и файлы перевода русскоязычной [документации Beautiful Soup](http://bs4ru.geekwriter.ru/). Перевод с английского мой (authoress), распространяется на условиях [лицензии MIT](https://github.com/authoress/bs4ru/blob/master/LICENSE.txt).

Для сборки локальной копии документации у вас должен быть установлен Python 3 и пакеты Sphinx и Sphinx-intl.

Чтобы собрать документацию последней версии, перейдите в папку проекта (*doc*) и запустите команду: 

`sphinx-build -b html -D language=ru -d _build/doctrees/ru/ . _build/html/`

Готовая документация будет в папке *doc/_build/html/*.

Для сборки документации к Beautiful Soup версии 4.11.0 и ранее перейдите в папку версии (*doc_bs4_<версия>*) и запустите команду: 

`make html`

Готовая документация будет в папке *doc_bs4_<версия>/_build/html/*.
