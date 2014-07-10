### Настройка среды разработки [ ](#env-setup)

Под средой разработки понимаются инструменты, которые будут испльзованы в процессе создания программного продукта.
Прежде, чем приступать к выполнению задания необходимо установить следующий софт.

#### Основные инструменты [ ](#main-tools)

* Браузеры (Chrome, FF, Opera, Yandex Browser, IE10+)
* [GIT](http://git-scm.com/) + создать аккаунт на [GitHub](http://github.com) + создать репозиторий с именем вида `exadel-training-name`,<br/>
  где плейсхолдер `name` должен быть заменен на сокращение от вашего имени и фамилии, например Zosya Sinitskaya превратится в zsinitskaya
* IDE [WebStorm](http://www.jetbrains.com/webstorm/)
    * после установки LESS нужно будет создать для проекта watcher .less файлов ([инструкция](http://www.jetbrains.com/phpstorm/webhelp/using-file-watchers.html))

    >_На заметку:_ в поле «Output paths to refresh» нужно задать значение `$ProjectFileDir$/css/compiled/$FileDirPathFromParent(source)$/$FileNameWithoutExtension$.css`

    * после установки GIT нужно будет клонировать созданный репозиторий на локальную машину ([инструкция](http://www.jetbrains.com/webstorm/webhelp/cloning-a-repository-from-github.html))
* [NODE.js + NPM](http://nodejs.org/)
* [LESS](http://lesscss.org/)

#### Дополнительные инструменты [ ](#other-tools)

Устанавливать нужно будет по мере изучения.

* [BOWER](http://bower.io/)
* [GRUNT](http://gruntjs.com/)
* [YeoMan](http://yeoman.io/)

#### Рекомендованная структура проекта

Рекомендованная структура директорий для практических заданий в рамках стажировки выглядит так:

{% highlight javascript %}
project-folder/
|
|- images/
|  |── layout/
|  └── content/
|
|- css
|  |── source/
|  └── compiled/
|
|- templates/
|
|- js
|  |── libs/
|  └── app/
|
└── index.html
{% endhighlight %}
