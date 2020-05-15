# Работа с тестовым стендом

Для тестирования работы с API без списания реальных средств можно использовать тестовый
стенд расположенный по адресу https://dev1.payin-payout.net/ .

Для данного сервера необходимо также как описано в текущей документации сгенерировать ключи,
 и предоставить их менеджеру с которым вы работаете.

Платежи имеющие чётную сумму к списанию будут успешно оплачиваться (при наличии тестовых денег на счету),
платежи с не чётной суммой будут падать в ошибку.

По поводу зачисления тестовых средств можно обратиться к менеджеру, либо произвести 
[тестовое зачисление средств](https://github.com/payin-payout/payin-api/blob/master/testing.md). 