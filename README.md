practice
========

## Git

* [gitconfig](https://github.com/mokevnin/dotfiles/blob/master/gitconfig)
* [How to update GitHub forked repository?](http://stackoverflow.com/questions/7244321/how-to-update-github-forked-repository)
* [статья про гит](https://github.com/mokevnin/coursify/wiki/Git)
* [документация как делать pull request](https://help.github.com/articles/using-pull-requests)
* [статья Хабр про пулл реквест](http://habrahabr.ru/post/125999/)
* [Git Rebase: руководство по использованию](http://habrahabr.ru/post/161009/)
* [Думай как Git, руководство по Git](http://web.archive.org/web/20131019113913/http://git.geekjob.ru/epic-mode/)
* [current branch in bash](http://stackoverflow.com/questions/4133904/ps1-line-with-git-current-branch-and-colors)

показывает текущую ветку git
~~~ shell
$ vi  ~/.bashrc
export PS1='[\u@\h \W$(__git_ps1 " (%s)")]\$ '
~~~

## Ruby

* [объектная модель Руби](http://7vn.ru/blog/2011/11/18/object-model/)
* [гем глазами потребителя(про структура гема)](http://nashbridges.me/gem-for-end-user)
* [GIL в Руби](http://habrahabr.ru/post/189320/)
* [10 «однострочников», которые произведут впечатление на ваших друзей](http://habrahabr.ru/post/120665/)
* [прокачка ruby](http://tony.pitluga.com/2011/08/08/destructuring-with-ruby.html)
* [Lazy](http://ruby-doc.org/core-2.0/Enumerator/Lazy.html)

## Clojure

* [Почему стоит изучить Clojure?](http://surfingbird.ru/surf/c1M84d7A5#.U62kknWSw8p)
* [введение в кложуре от Алекса](http://alexott.net/ru/clojure/clojure-intro/)
* [Кложуре](http://clojure.org/getting_started)
* [Гид по стилю Кложуре](https://github.com/bbatsov/clojure-style-guide)
* [пример контрактного программирования на кложуре](https://github.com/clojure/core.contracts)
* [кложуре скрипт Коаны](http://clojurescriptkoans.com)
* [нужные плагины для sublime text for clojure](https://github.com/clojure/clojurescript/wiki/Sublime-Text-2)
* [Clojure Alchemy: Reading, Evaluation, and Macros](http://www.braveclojure.com/read-and-eval/)
* [Замена стандартного вывода о ошибках](https://github.com/mmcgrana/clj-stacktrace)
* [Lazy](http://clojure.org/lazy)
* http://www.lighttable.com/


## Bash

* [Основы Linux от основателя Gentoo](http://habrahabr.ru/post/99041/)
* [bash (wikipedia)](http://ru.wikipedia.org/wiki/Bash)

Установка PATH
~~~ shell
env | grep LOAD
env | grep PATH
export PATH=$PATH:/home/vagrant/.linuxbrew/bin
env | grep PATH
~~~

### Vagrant

* [сборник боксов для вагранта](https://vagrantcloud.com/)

### Books

* [сборник книг от Кирилла](https://github.com/mokevnin/coursify/wiki/Books)

### Video

* [Runit](http://tv.kaize.ru/ulcamp/31.05.2013/runit_1440x1080.mp4)
* [доклад ментальное программирование(Кирилл)](http://www.youtube.com/watch?v=EEq1wdM2M2w)

### Сервисы

* [мониторинг ошибок](https://airbrake.io)
* [докер](http://docker.io/)
* [сервис, показывающий активность на гитхабе](https://coderwall.com/welcome)
* [сборник упражнений exercism](http://exercism.io/)
* [Тревис С](http://travis-ci.com/)
* [виртуальная IDE ](https://c9.io/)
* [виртуальная машина онлайн](https://www.nitrous.io/)
* [Покрытие кода](https://coveralls.io/)
* [Кодеклаймит](https://codeclimate.com/)

### Клава

* [тренировка горячих клавиш](https://www.shortcutfoo.com/)
* [тренажер](http://klava.org/)
* [клавагонки](http://klavogonki.ru/)

### Other

* [принципы ментального программирования](https://github.com/mokevnin/coursify/wiki/Code-Design)
* [онлайн курсы и лекции](https://hexlet.org/)
* [непрерывная интеграция(Википедия)](http://ru.wikipedia.org/wiki/Непрерывная_интеграция)
* [статья про Тревис](http://habrahabr.ru/post/140344/)
* [Гомология в компьютерных языках(Википедия)](http://en.wikipedia.org/wiki/Homoiconicity)
* [вывод типов(Википедия)](http://ru.wikipedia.org/wiki/Вывод_типов)
* [лямбда исчисления](http://habrahabr.ru/post/215807/)
* [чистота функции(Википедия)](http://ru.wikipedia.org/wiki/Чистота_функции)
* [персистентные структуры данных](http://habrahabr.ru/post/113585/)
* [монада Maybe](https://github.com/pzol/monadic)
* [изменяемое состояние](http://fprog.ru/2009/issue1/eugene-kirpichov-fighting-mutable-state/)
* [Персистентные структуры](http://habrahabr.ru/post/113585/)
* [Записки программиста](http://eax.me/)
* [блог от матерого c# программиста](http://sergeyteplyakov.blogspot.ru/)

#### Sublime

plugins:
* http://dev.clojure.org/display/doc/Getting+Started+With+Sublime+Text+2
* http://sublimerepl.readthedocs.org/en/latest/
* https://github.com/odyssomay/sublime-lispindent
* https://github.com/odyssomay/paredit
* https://github.com/jasongilman/SublimeClojureSetup
* EnhancedClojure
* BracketHighlighter
* https://github.com/odyssomay/paredit
* https://github.com/dakrone/lein-bikeshed
* https://github.com/circleci/clj-yaml
* https://github.com/xsc/lein-ancient

