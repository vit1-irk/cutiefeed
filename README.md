iicli-modular
=============
Это простой клиент для сетей ii, что я написал для себя на python2. 
Графический интерфейс написан на tkinter.

Особенности:
* Фетчер отдельно, мейлер отдельно, написание сообщений (во внешнем редакторе) отдельно, читалка отдельно. Любой компонент при желании можно заменить другим, так как код простой и читаемый, а привязки к python минимальны.
* Фетчер (webfetch.py) свой, портирован с webfetch.php из ii-php, имеет поддержку экономии трафика через /x/t (в конфиге значение xtenable)
* Конфиг в json, там всё просто и понятно.