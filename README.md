TODO: подумать над структурой

# Начало

* [Закон Дырявых Абстракций](http://russian.joelonsoftware.com/Articles/LeakyAbstractions.html)
* [Ричард Фейнман - Магниты и вопросы "почему?"](https://youtu.be/IPogLMRBZ4o)
* [Ментальное программирование](http://www.youtube.com/watch?v=eEEHWQNuCLQ)
* [Человеческий фактор или «соглашения не работают»](http://megamozg.ru/post/1240/)

# Styleguide

* [Github ruby styleguide](https://github.com/styleguide/ruby)
* [Ruby styleguide](https://github.com/bbatsov/ruby-style-guide)
* [Rails styleguide](https://github.com/bbatsov/rails-style-guide)

# Документация

* [rails guides](http://guides.rubyonrails.org/)
* [rusrails](http://rusrails.ru/)
* [api.rubyonrails.org](http://api.rubyonrails.org/)
* [apidock.com](http://apidock.com)
* [ru.wikibooks.org/wiki/Ruby](http://ru.wikibooks.org/wiki/Ruby)

# Ruby

* [Иерархия ошибок в Ruby](http://leonid.shevtsov.me/ru/ierarhiya-oshibok-v-ruby-a-takzhe-kakie-isklyucheniya-nuzhno-brosat-a-kakie-lovit)
* [Объектная модель в Ruby](http://7vn.ru/blog/2011/11/18/object-model/)
* [Введение в объектно-ориентированный Ruby](http://nashbridges.me/introducing-ruby-oop)
* [Вникаем в include и extend](http://habrahabr.ru/post/143483/)
* [Гномики и метапрограммирование в Ruby](http://rubyflow.ru/items/1130)
* [Unexpected Ruby Behaviour](http://greyblake.com/blog/2012/08/10/unexpected-ruby-behaviour/)
* [What Does Your Webserver Do When a User Hits Refresh?](http://www.shopify.com/technology/7535298-what-does-your-webserver-do-when-a-user-hits-refresh)

# Gems

* [Gem глазами потребителя](http://nashbridges.me/gem-for-end-user)
* [Learn how RubyGems works, and how to make your own](http://guides.rubygems.org/)
* [Bundler](http://bundler.io/)

# Rails

* [Иерархия контроллеров](http://habrahabr.ru/post/136461/)
* [Тестирование в стиле TSA](http://habrahabr.ru/post/143616/)
* [7 Ways to Decompose Fat ActiveRecord Models](http://blog.codeclimate.com/blog/2012/10/17/7-ways-to-decompose-fat-activerecord-models/)
* [Give Rails Autoloading a Boot to the Head](http://wondible.com/2011/12/23/give-rails-autoloading-a-boot-to-the-head/)
* [Что же такое Railtie, Engine и Plugin?](http://memo.undr.su/2011/04/01/chto-zhe-takoe-railtie-engine-i-plugin/)
* [Does My Rails App Need a Service Layer?](http://blog.carbonfive.com/2012/01/10/does-my-rails-app-need-a-service-layer/)
* [Rails is not your application](http://blog.firsthand.ca/2011/10/rails-is-not-your-application.html)
* [The 10 Most Underused ActiveRecord::Relation Methods](http://blog.mitchcrowe.com/blog/2012/04/14/10-most-underused-activerecord-relation-methods/)
* [About the composed_of removal](http://blog.plataformatec.com.br/2012/06/about-the-composed_of-removal/)
* [Where's Your Business Logic?](http://collectiveidea.com/blog/archives/2012/06/28/wheres-your-business-logic/)

* [asset-pipeline](http://rusrails.ru/asset-pipeline)

# Правила

* DateTime.current
* На функциональные баги пишется тест;
* Запросы к базе только в моделях, снаружи scopes или методы;
* Не используем default_scopes;
* Используем новый формат валидаторов (validators);
* Все константы (magic numbers, urls) подставляются через конфиги и не пишутся в коде;
* В шаблонах можно использовать числа: для вывода массива в 3 колонки;
* Строки через локали;
* Можно локализировать partial целиком;
* Покрытие контроллеров > 90%;
* Объекты получаем отдельно, используем отдельно;
* Извлекаем информацию из БД за постоянное число запросов(см. N+1);
* Не увлекаемся индексами: стало тормозить - добавили индекс;
* На уникальное поле - уникальный индекс (+ uniqueness).

# Git

* [Github flow](https://guides.github.com/introduction/flow/)
* [GitHub Flow: рабочий процесс Гитхаба](http://habrahabr.ru/post/189046/)
* [Git flow / Удачная модель ветвления для Git](http://habrahabr.ru/post/106912/)
* [Pro Git](http://git-scm.com/book/ru)
* [Думай как Git, руководство по Git](http://web.archive.org/web/20131019113913/http://git.geekjob.ru/epic-mode/)
* [Внтутреннее устройство Git](http://www.opennet.ru/base/dev/git_guts.txt.html)
* [Что скрывает от нас директория .git](http://habrahabr.ru/post/143079/)
* [Git Tips From the Pros](http://net.tutsplus.com/tutorials/tools-and-tips/git-tips-from-the-pros/)
* [tryGit](http://try.github.com/)
* [Learn Git Branching](http://pcottle.github.com/learnGitBranching/)

# Github

* [guides.github.com](https://guides.github.com/)

# Postgresql

* [полнотекстовый поиск](https://mkdev.me/posts/kak-delat-full-text-poisk-v-rails-pri-pomoschi-postgresql)

# Проектирование

* [Разделение получения и использования](http://mokevnin.github.io/blog/2012/06/03/razdelenie-polucheniya-i-ispolzovaniya/)
* [Принцип наименьшего удивления (ПНУ)](http://mokevnin.github.io/blog/2013/11/14/pnu/)
* [когда не использовать unless](http://37signals.com/svn/posts/2699-making-sense-with-rubys-unless)

* [value object](http://www.sitepoint.com/value-objects-explained-with-ruby/)
 
* [RESTful API для сервера – делаем правильно](http://habrahabr.ru/post/144011/)

* [GRASP](http://ru.wikipedia.org/wiki/GRASP)
* [Принцип одного уровня абстракции](http://habrahabr.ru/post/126227/)
* [Закон Деметры](http://msdn.microsoft.com/ru-ru/magazine/cc947917.aspx)
* [Принцип единственности ответственности](http://blog.byndyu.ru/2009/10/blog-post.html)
* [Принцип открытости/закрытости](http://blog.byndyu.ru/2009/10/blog-post_14.html)
* [Принцип замещения Лисков](http://blog.byndyu.ru/2009/10/blog-post_29.html)
* [Принцип разделения интерфейса](http://blog.byndyu.ru/2009/11/blog-post_19.html)
* [Принцип инверсии зависимостей](http://blog.byndyu.ru/2009/12/blog-post.html)
* [Command Query Separation](http://igor.quatrocode.com/2009/10/command-query-separation.html)
* [SOLID](http://igor.quatrocode.com/2008/09/solid-top-5.html)
* [Hexagonal/Onion Architecture - слоим приложения](http://igor.quatrocode.com/2009/07/hexagonalonion-architecture.html)
* [Корень агрегации](http://blog.byndyu.ru/2010/06/domain-driven-design-aggregation-root.html)
* [Репозиторий](http://blog.byndyu.ru/2011/01/domain-driven-design-repository.html)
* [Создание домена](http://blog.byndyu.ru/2010/05/domain-driven-design.html)
* [DDD подход к решению задачи сложной фильтрации данных](http://codemehanika.org/blog/2011-05-10-pattern-composite-in-filtering-tasks.html)
* [DDD: начало](http://zendframework.ru/forum/index.php?topic=4066.0)

# Паттерны

* [state_machine](http://www.ict.edu.ru/ft/003756/pattern.pdf)



# Библиотеки
* [awesome-ruby](https://github.com/markets/awesome-ruby)



# Блоги

* [Бындю](http://blog.byndyu.ru)
* [nashbridges.me](http://nashbridges.me/)
* [rubyflow.ru](http://rubyflow.ru/)
* [Технические заметки одного Евтуховича](http://evtuhovich.ru/)
* [solnic.eu](http://solnic.eu/)
* [Блог Леонида Шевцова](http://leonid.shevtsov.me/ru)

# Casts

* [railscasts](http://railscasts.com/)
* [asciicasts](http://asciicasts.com/)

# Статьи

* [Коды возврата & исключения](http://habrahabr.ru/post/131212/)
* [устройство индексов](http://www.sql.ru/articles/mssql/03013101indexes.shtml)
* [Defensive Design. Откуда берутся сбои](http://igor.quatrocode.com/2009/02/defensive-design.html)
* [TDD](http://wiki.agiledev.ru/doku.php?id=tdd)
* [REST](http://habrahabr.ru/post/144011/)
* [UML](http://habrahabr.ru/post/150041/)
* [CLI](http://habrahabr.ru/post/150950/)
* [Протокол HTTP](http://squadette.ru/blog/2012/01/19/high-scalability/)
* [Алгоритмы и структурыданных](http://squadette.ru/blog/2012/01/19/high-scalability-2/)
* [Анатомия ошибок](http://goblingame.blogspot.ru/2012/10/blog-post_12.html)
* [Экстремальное программирование – реальность и мифы](http://www.skipy.ru/philosophy/xp.html)

# Книги

## Совершенный код

* [Идеальный программист](http://www.ozon.ru/context/detail/id/7360633/) (Роберт Мартин)
* [Совершенный код](http://www.ozon.ru/context/detail/id/5508646/) (С. Макконнелл)
* [Программист-прагматик. Путь от подмастерья к мастеру](http://www.ozon.ru/context/detail/id/3353337/) (Э.Хант, Д.Томас)
* [Паттерны проектирования](http://www.ozon.ru/context/detail/id/6108824/) (Э. Фримен, Э. Фимен, К. Сьерра, Б. Бейтс)
* [Приемы объектно-ориентированного проектирования. Паттерны проектирования](http://www.ozon.ru/context/detail/id/2457392/) (Э.Гамма, Р.Хелм, Р.Джонсон, Дж.Влиссидес)
* [Чистый код](http://www.ozon.ru/context/detail/id/6733562/) (Роберт Мартин)
* [Принципы, паттерны и методики гибкой разработки на языке C#](http://www.ozon.ru/context/detail/id/5800704/) (Р.С.Мартин, М.Мартин)
* [Рефакторинг с использованием шаблонов](http://www.ozon.ru/context/detail/id/2909721/) (Джошуа Кериевски)
* [Архитектура корпоративных приложений](http://www.ozon.ru/context/detail/id/4884925/) (М. Фаулер)
* [Предметно-ориентированное проектирование (DDD). Структуризация сложных программных систем](http://www.ozon.ru/context/detail/id/5497184/) (Эрик Эванс)
* Джоэл о программировании (Джоэл Спольски)

## Базы данных

* [Оптимизация баз данных](http://www.ozon.ru/context/detail/id/1685709/) (Деннис Шаша, Филипп Бонне)
* [Рефакторинг sql приложений](http://www.ozon.ru/context/detail/id/4491539/)
* [Рефакторинг баз данных](http://www.ozon.ru/context/detail/id/3261793/) (Скотт В. Эмблер, Эмблер Прамодкумар Дж. Садаладж)

## UML

* [UML основы](http://www.ozon.ru/context/detail/id/6289616/) (М. Фаулер)

## Операционные системы

* [Код](http://www.ozon.ru/context/detail/id/125884/) (Чарльз Петцольд)
* [Операционные системы](http://www.ozon.ru/context/detail/id/1150703/) (Столлингс)
* [Операционная система UNIX](http://www.ozon.ru/context/detail/id/2419365/) (Андрей Робачевский, Сергей Немнюгин, Ольга Стесик)

## Администрирование

* [Руководство Администратора Linux](http://www.ozon.ru/context/detail/id/3285836/) (Эви Немет, Гарт Снайдер, Трент Хейн)

## Тестирование

* [Непрерывная интеграция](http://www.ozon.ru/context/detail/id/3851770/) (Поль М. Дюваль, Стивен Матиас и Эндрю Гловер)

## ПМ

* [Человеческий фактор. Успешные проекты и команды](http://www.ozon.ru/context/detail/id/2338486/) (Том Демарко и Тимоти Листер)
* [Мифический человеко-месяц](http://www.ozon.ru/context/detail/id/83760/) (Фредерик Брукс)

## Интересное

* [Как сдвинуть гору фудзи?](http://www.ozon.ru/context/detail/id/4780454/) (У. Паундстоун)



# Сервисы для изучения ruby

* [try ruby](http://tryruby.org/)
* [rubeque.com](http://rubeque.com/)
* [rubymonk.com](http://rubymonk.com/)
* [codecademy](http://www.codecademy.com/ru/tracks/ruby)


# Благодарности

Огромное спасибо команде [kaize](https://github.com/kaize/).


***







### Основные

* [configus](https://github.com/kaize/configus) - управление конфигурациями 
* [haml-rails](https://github.com/indirect/haml-rails)
* [pg](https://bitbucket.org/ged/ruby-pg) - PostgreSQL
* [unicorn](http://unicorn.bogomips.org) - web сервер
* [state_machine](https://github.com/pluginaweek/state_machine)
* [airbrake](https://airbrakeapp.com)
* [validates](https://github.com/kaize/validates) - частые валидации (email, slug)
* [simple_form](https://github.com/plataformatec/simple_form) - формы на стероидах
* [twitter-bootstrap-rails](https://github.com/seyhunak/twitter-bootstrap-rails) - интеграция tw в rails
* [kaminari](https://github.com/amatsuda/kaminari) - пейджинг
* [capi](https://github.com/kaize/capi) - полезняшки для деплоя (например управление запуском unicorn)
* [capistrano](https://github.com/capistrano/capistrano) - деплой
* [rvm-capistrano](https://github.com/wayneeseguin/rvm-capistrano) - интеграция RVM / Capistrano
* [capistrano-ext](https://github.com/jamis/capistrano-ext) - добавляем staging
* [minitest](https://github.com/seattlerb/minitest)
* [mocha](https://github.com/freerange/mocha) - stub/mock для тестирования
* [webmock](https://github.com/bblimke/webmock) - stub/mock для io
* [simplecov](https://github.com/colszowka/simplecov) - test coverage
* [ci_reporter](https://github.com/nicksieger/ci_reporter) - Генератор отчётов для тестов
* [factory_girl_rails](https://github.com/thoughtbot/factory_girl_rails) - Удобная замена фикстур
* [turn](https://github.com/TwP/turn) - A new look and feel for Test::Unit output
* [tconsole](https://github.com/commondream/tconsole) - тестовая консоль
* [ransack](https://github.com/ernie/ransack) - Object-based searching (бывший MetaSearch)

### Дополнителные

* [jquery-ui-rails](https://github.com/joliss/jquery-ui-rails) - jQuery UI Bootstrap
* [enumerize](https://github.com/brainspec/enumerize) - поле типа перечисление с поддержкой I18n и ActiveRecord/Mongoid
* [ya_acl](https://github.com/kaize/ya_acl) - управление правами на основе ACL
* [js-routes](https://github.com/railsware/js-routes) - генерирует javascript файл содержащий именованные пути из rake routes 
* [gon](https://github.com/gazay/gon) - Your Rails variables in your JS
* [resque](https://github.com/defunkt/resque) - Resque is a Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later.
* [thinking-sphinx](http://freelancing-god.github.com/ts/en/) - A Ruby connector between Sphinx and ActiveRecord.
* [whenever](https://github.com/javan/whenever) - Cron jobs in Ruby
* [carrierwave](https://github.com/jnicklas/carrierwave) - Classier solution for file uploads for Rails, Sinatra and other Ruby web frameworks
* [backup](https://github.com/meskyanichi/backup)
* [ancestry](https://github.com/stefankroes/ancestry) - Organise ActiveRecord model into a tree structure (MP)
* [breadcrumbs_on_rails](https://github.com/weppos/breadcrumbs_on_rails)
* [acts-as-taggable-on](https://github.com/mbleigh/acts-as-taggable-on) - A tagging plugin for Rails applications that allows for custom tagging along dynamic contexts
* [cocoon](https://github.com/nathanvda/cocoon) - Dynamic nested forms using jQuery made easy; works with formtastic, simple_form or default forms
* [money](https://github.com/RubyMoney/money) - Реализация паттерна [Money](http://martinfowler.com/eaaCatalog/money.html) для Ruby
* [omniauth](https://github.com/intridea/omniauth) - Масштабируемая система OAuth авторизации

### Black list

* device
* meta_search - устарел. Следует использовать ransak





### Библиотеки

* [JQuery](http://jquery.com/)
* [JQuery UI](http://jqueryui.com/) ([gem](http://github.com/jquery/jquery-ui))
* [Underscore.js](http://underscorejs.org/) ([gem](http://github.com/rweng/underscore-rails))
* [Underscore.string](http://epeli.github.com/underscore.string/) ([gem](https://github.com/jaimie-van-santen/underscore-string-rails))
* [Moment.js](http://momentjs.com/) ([gem](http://github.com/derekprior/momentjs-rails))
* [json2](https://github.com/douglascrockford/JSON-js)

### Фреймворки

* [Backbone](http://backbonejs.org/) ([gem](http://github.com/codebrew/backbone-rails))
* [Ember.js](http://emberjs.com/) ([gem](https://github.com/emberjs/ember-rails))

### Плагины

* [Chosen](http://harvesthq.github.com/chosen/) ([gem](http://github.com/tsechingho/chosen-rails))
* [select2](http://ivaynberg.github.com/select2/) ([gem](https://github.com/argerim/select2-rails))

### Полезное

* [http://superherojs.com/](http://superherojs.com/)
* [http://shichuan.github.com/javascript-patterns/](http://shichuan.github.com/javascript-patterns/)
* [http://killdream.github.com/blog/2011/10/understanding-javascript-oop/index.html](http://killdream.github.com/blog/2011/10/understanding-javascript-oop/index.html)
* [http://addyosmani.github.com/todomvc/](http://addyosmani.github.com/todomvc/)
* [http://github.com/madrobby/keymaster](http://github.com/madrobby/keymaster)




* [Rails Devops Cheatsheet](http://rubytune.com/cheat)















### Сервисы

* [ruby-toolbox](https://www.ruby-toolbox.com/)
* [airbrake](https://airbrakeapp.com/)
* [newrelic.com](http://newrelic.com/)
* [travis-ci](http://travis-ci.org/)
* [relishapp.com](https://www.relishapp.com/)
* [lucidchart.com](https://www.lucidchart.com/)
* [gemnasium.com](https://gemnasium.com/)
* [stillmaintained.com](http://stillmaintained.com/)

* [coderwall.com](http://coderwall.com/)
* [cloud9 IDE](http://c9.io/)
* [railsbp.com](http://railsbp.com/)
* [codeclimate.com](https://codeclimate.com)


### Полезное

* [braingames.ru](http://braingames.ru/)
* [bigocheatsheet](http://bigocheatsheet.com/)




### Setup

[rvm](https://rvm.io/)

### Ruby

http://nashbridges.me/gem-for-end-user

### Rails



title: "Twitter Bootstrap"
---
{% include JB/setup %}

* [Bootstrap, from Twitter](http://twitter.github.com/bootstrap/)
* [resources 1](http://bootsnipp.com/resources)
* [resources 2](http://bootstraphero.com/the-big-badass-list-of-twitter-bootstrap-resources)
* [Bootbox.js](http://bootboxjs.com/)
* [Bootswatch](http://bootswatch.com/)
* [Built With Bootstrap](http://builtwithbootstrap.com/)
* [WrapBootstrap](http://wrapbootstrap.com/)
* [Boot snipp](http://bootsnipp.com/)


title: "Vim"
category: vim
tags: [vim]
---
{% include JB/setup %}

* [Как пользоваться vim](http://ru.najomi.org/vim)
* [vimcasts](http://vimcasts.org/)
* [vimgolf](http://vimgolf.com/)
* [vimbits](http://vimbits.com/)
* [эффективное использование vim: «incredibly tips, part I»](http://habrahabr.ru/post/28155/)
* [эффективное использование vim: «from the very begining»](http://habrahabr.ru/post/28108/)
* [Graphical Cheat Sheet](http://habrahabr.ru/post/28200/)
* [vim-adventures](http://vim-adventures.com/)


---
layout: page
title: "Рабочее окружение"
---
{% include JB/setup %}

### gitflow

[Удачная модель ветвления](http://habrahabr.ru/post/106912/)

[git extension](https://github.com/nvie/gitflow.git)

[Getting Started – Git-Flow](http://yakiloo.com/getting-started-git-flow/)

### soft

* keepassx - password manager
* dropbox

### chrome extensions

[Ruby on Rails API Search](https://chrome.google.com/webstore/detail/ruby-on-rails-api-search/nbhhppofdccphcpbilanmljnlkmbgike)

[XV - XML Viewer](https://chrome.google.com/webstore/detail/eeocglpgjdpaefaedpblffpeebgmgddk)

[JSONView](https://chrome.google.com/webstore/detail/chklaanhfefbnpoihckbnefhakgolnmc)

[Advanced REST client Application](https://chrome.google.com/webstore/detail/hgmloofddffdnphfgcellkdfbfbjeloo/related?utm_source=chrome-ntp-icon)

[NewRelic + Airbrake](https://chrome.google.com/webstore/detail/newrelic-%2B-airbrake-for-g/emencamphkobkmeloepceomcacgejlnc)

### vim

[AkitaOnRails Vimfiles](https://github.com/akitaonrails/vimfiles)

### ~/.vimrc for akita

{% highlight vim linenos %}

    let mapleader = ","
    let g:ackprg="ack-grep -H --nocolor --nogroup --column"

    source ~/.vim/vimrc

    "explorer mappings
    nnoremap <f3> :TlistToggle<cr>
    nnoremap <f2> :NERDTreeToggle<CR>

{% endhighlight %}

### ~/.bashrc

{% highlight bash linenos %}

    export PS1='\w$(__git_ps1 "(%s)"): '
    PS1="\$(~/.rvm/bin/rvm-prompt i v p g) $PS1"

{% endhighlight %}

### ~/.gitconfig

{% highlight bash linenos %}

[color]
  branch = auto
  diff = auto
  interactive = auto
  status = auto
  ui = auto
  pager = true

[merge]
  summary=true

[alias]
  b = branch -v
  r = remote -v
  t = tag -l
  cp = cherry-pick -x
  co = checkout
  br = branch
  ci = commit
  st = status -sb
  ds = diff --staged
  amend = commit --amend -C HEAD
  undo = reset --soft HEAD^
	unstage = reset HEAD --
  uncommit = reset --soft HEAD^
	last = log -1 HEAD
	up = pull --rebase
	put = push origin HEAD
	latest = for-each-ref --sort=-committerdate --format='%(committerdate:short) %(refname:short) [%(committername)]'
  ls = log  --decorate --date=short
  graph = log --graph --pretty=format':%C(yellow)%h%Cblue%d%Creset %s %C(white) %an, %ar%Creset'

{% endhighlight %}

### ~/.caprc

{% highlight ruby linenos %}

    # gem install capistrano_colors
    # aptitude install libnotify-bin

    def notify(message, body, urgency, icon = :info)
      system("notify-send --urgency=#{urgency} --icon=#{icon} '#{message}' '#{body}'")
    end

    on :exit do
      notify('Capistrano Task: Finished', ARGV.join(' '), :low)
    end

    require 'capistrano_colors'

{% endhighlight %}
