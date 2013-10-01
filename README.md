Сайт использует Sphinx при генерации страниц.

Подробнее: http://sphinx.readthedocs.org/en/latest/

Где что лежит
-------------

* \*.rst - страницы сайта в формате [reST](http://docutils.sf.net/rst.html)
* sites/ - описания саньшовых плексов
* fits/ - фиты в текстовом формате EFT
* themes/raisa - html-шаблон, css-стили, статика

Как внести изменения
--------------------

Вы можете вносить изменения прямо через интерфейс Github. Для этого нужно найти
и открыть файл с расширением .rst (каждой странице на сайте соответствует такой
файл) и нажать кнопку "Edit". После сохранения файла система создаст Pull
Request, после принятия которого изменения появятся на сайте при его пересборке
людьми, ответственными за это.

Если вы состоите в списке ФК RAISA Shield и умеете обращаться с Git, Python и
Sphinx, то можете работать с этим репозиторием напрямую. Свяжитесь с Grim Altero
и вам дадут доступ.

TODO
----

* Запилить отображение фитов
* Добавить официальные фиты в fits/
* Описания сайтов в sites/
* Линки на видео, картинки и прочее для новичков
