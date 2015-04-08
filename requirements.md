Правила программирования
========================

* [Ментальное программирование(Слайды)](http://www.slideshare.net/profyclub_ru/07-19946378)
* [Ruby styleguide](https://github.com/bbatsov/ruby-style-guide)
* [Rails styleguide](https://github.com/bbatsov/rails-style-guide)
* [Иерархия контроллеров](http://habrahabr.ru/post/136461/)
* [Тестирование в стиле TSA](http://habrahabr.ru/post/143616/)
* [Github flow](https://guides.github.com/introduction/flow/)


* DateTime.current
* На функциональные баги пишется тест;
* Запросы к базе только в моделях, снаружи scopes или методы;
* Не используем default_scopes;
* Используем новый формат валидаторов (validators);
* Все константы (magic numbers, urls) подставляются через конфиги или константы;
* В шаблонах можно использовать числа: для вывода массива в 3 колонки;
* Строки через локали;
* Можно локализировать partial целиком;
* Покрытие контроллеров > 90%;
* Объекты получаем отдельно, используем отдельно;
* Извлекаем информацию из БД за постоянное число запросов(см. N+1);
* Не увлекаемся индексами: стало тормозить - добавили индекс;
* На уникальное поле - уникальный индекс (+ uniqueness);
* SOLID;
* Принцип одного уровня абстракции;
* Тесты через rspec;

## Черный список гемов

* device
* active_admin
* can_can
* paperclip
* carrierwave => refile (в новых проектах)
* decent_exposure
