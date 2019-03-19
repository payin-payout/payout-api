# Для интеграции потребуется

1 Проверить наличие библиотеки openssl.

2 Cгенерировать ключи.

2.1 Запустить для *nix
   ./create_keys.sh

2.2 Запустить для WINDOWS
   create_keys.bat

3 Отправить публичный ключ из директории /keys в систему Payin-Payout на почту servicedesk@payin-payout.net

4 Дождаться ответа от системы об успешном прикреплении ключа и начинать пользоваться.
Полученный номер точки не забыть прописать в файле /request.php

`$gate->setPoint('номер точки') // обязательно в кавычках`

### Для разработчиков под Windows ###
Если все работало и вдруг перестало, а сервер отдает ошибку "Не прошел проверку подписи" код "107" проверте как создан файл с BOM или без BOM.<br/>
<b>Нам требуется без BOM</b>.

### Установка ###

```bash
composer require payin-payout/payout-api
```

[Документация](docs/README.md)

[Примеры кода](docs/RequestExample.md)

[Информация о использовании сервисов](docs/services.md)

Успехов!
