# SmsSender
<em>
<p><a href="https://github.com/Azimjonm2333/SmsSender">SmsSender v3.0.0</a> - скрипт предназначен для бесплатной отправки SMS на любой номер и с любым текстом. Возможны небольшие баги, в скором времени исправлю.</p>

<h1>Документация.</h1>
<p>Обновляем пакеты:</p>
<p><pre><code>pkg upgrade</code></pre></p>

<p>Устанавливаем Git и Python:</p>
<p><pre><code>pkg install -y git python</code></pre></p>

<p>Скачиваем сам скрипт:</p>
<p><pre><code>git clone https://github.com/Azimjonm2333/SmsSender</code></pre></p>

<p>Переходим в директорию с скриптом:</p>
<p><pre><code>cd SmsSender</code></pre></p>

<p>Обязательно перед запуском устанавливаем необходимые либы/библиотеки:</p>
<p><pre><code>pip install -r requirements.txt</code></pre></p>

<p>Запускаем скрипт:</p>
<p><pre><code>python main.py</code></pre></code>

<p>Дальше вводим номер с текстом и готово !</p>

<h1>Новое</h1>
<p>В новой версии смс отправляются через прокси сервер(http, US), который парсятся в файле <strong>proxy.py</strong></p>
