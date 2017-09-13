# Lets Go - quick start template

## Используемые технологии:
* Gulp 4.0
* Pug(Jade)
* Sass(Scss)
* JS+jQuery

## Для старта:
1. install node.js
2. clone this repo
3. cd path/to/
4. npm i gulpjs/gulp-cli -g  // Install the latest Gulp CLI tools globally
5. npm i
6. run "gulp" command to start

## Npm-пакеты/плагины:

**devDependencies**

Name                                                    | Description
--------------------------------------------------------|----------------------
gulp "git+https://git@github.com/gulpjs/gulp.git#4.0"   | Галп в 4-ой версии
gulp-pug                                                | рендеринг pug-файлов 
gulp-prettify                                           | "причесывание" html
gulp-sass                                               | рендеринг scss-файлов
gulp-concat-css                                         | для конкатенации файлов стилей
gulp-autoprefixer                                       | проставляем префиксы
gulp-sourcemaps                                         | создание sourcemaps
gulp-csso                                               | для минификации файлов стилей
gulp-css-url-adjuster                                   | для замены путей в scss при компиляции
gulp-svg-sprite                                         | склеивает svg в спрайты
gulp-svgmin                                             | минифицирует svg
gulp-cheerio                                            | для удаления лишних атрибутов из svg
gulp-concat                                             | для конкатенации js
gulp-uglify                                             | для минификации js
gulp-eslint                                             | для проверки моих линтингов
gulp-imagemin                                           | минификация картинок
gulp-pngquant                                           | минификация PNG картинок (для gulp-imagemin)
gulp-newer                                              | для изменения только новых картинок (можно использовать для любых типов файлов)
browserify                                              | для сборки модулей из app.js
vinyl-buffer                                            | дополнение к browserify
vinyl-source-stream                                     | дополнение к browserify
browser-sync                                            | вывод проекта в браузер + показ изменений в Css3 без перезагрузки страницы
gulp-load-plugins                                       | для автоматического подключения плагинов для gulp (тех которые начинаются с "gulp-")
gulp-notify                                             | вывод/показ ошибок
gulp-replace                                            | правка/изменение путей и другого содержимого в процессе сборки (использую в sprite.svg.js)
rimraf                                                  | для удаления папки build при старте проекта


**dependencies**

Name             | Description
-----------------|------------
animate.css      |
jquery v.2.2.4   | 
normalize.css    | 
slick slider     | 


## Структура шаблона:
* fonts
* img
* js
* php
* pug
    * elements (мелкие элементы, например кнопки или пагинация)
    * sections (крупные элементы, например header, footer, секции главной страницы)
    * pages
* sprite
* style
  * core (базовые стили)
    * fonts
    * variables
    * mixins
    * base
  * elements (мелкие элементы, например кнопки или пагинация)
  * sections (крупные элементы, например header, footer и секции главной страницы)
  * pages (стили для страниц сайта)
* vendors (сюда заливаем все чего нет в NPM и подключаем его в файлы foundation)
* video
