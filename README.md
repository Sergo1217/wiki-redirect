## Wiki to Runi/Ruwiki Redirector

Этот скрипт для браузера направляет запросы с сайта Википедии (на русском языке) на соответствующую страницу на сайте Руниверсалис.

### Инструкции по установке

1. Установите [Tampermonkey](https://www.tampermonkey.net) для вашего браузера.
2. Откройте [ссылку](https://raw.githubusercontent.com/sergo1217/wiki-to-runi/master/wiki-to-runi.user.js) и нажмите установить
3. При первой переадресации скрипт попросить доступ к стороннему ресурсу. Необходимо выбрать "Всегда разрешить для домена"

### Как это работает

Когда вы открываете страницу на Википедии на русском языке, этот скрипт автоматически перенаправляет запрос на соответствующую страницу на сайте Руниверсалис.

Скрипт заменяет "ru.wikipedia.org/wiki" на "руни.рф/index.php" и отправляет HEAD-запрос на новый URL. Если запрошенная страница существует, скрипт перенаправит вас на эту страницу. В противном случае ничего не произойдет.

### Поддержка и обновления

Если у вас есть какие-либо вопросы или проблемы с этим скриптом, пожалуйста, посетите [страницу поддержки на GitHub](https://github.com/sergo1217/wiki-to-runi/issues)


