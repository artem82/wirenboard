## WIRENBOARD


###  Шаблоны хранятся на контроллере в директории

:white_check_mark: /usr/share/wb-mqtt-serial/templates  — папка с предустановленными шаблонами;

:white_check_mark: /etc/wb-mqtt-serial.conf.d/templates — папка для пользовательских шаблонов, которые имеют приоритет над предустановленными.

:ballot_box_with_check: Если вы добавили свой шаблон или изменили существующий, подождите 20 секунд, а потом перезагрузите страницу конфигуратора в веб-интерфейсе клавишами Ctrl+F5 или перезапустите сервис:
```yaml
systemctl restart wb-mqtt-confed
```
