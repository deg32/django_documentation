Русская версия документации Django
==================================

Последнюю версию можно найти на http://djbook.ru/rel1.7/


Как помочь с переводом?
=======================

[Гайд](https://github.com/Alerion/django_documentation/wiki/%D0%9A%D0%B0%D0%BA-%D0%BF%D0%BE%D0%BC%D0%BE%D1%87%D1%8C-%D1%81-%D0%BF%D0%B5%D1%80%D0%B5%D0%B2%D0%BE%D0%B4%D0%BE%D0%BC%3F)


Как собрать документацию?
=========================

Для сборки документации выполните:

    $  ./translator.py create

Необходимые пакеты можно установить запустив:

    $ pip install -r djbook/requirements.txt

Список всех команад:

    $ ./translator.py --help

Проверка орфографии:

    $ ./translator.py spellcheck
