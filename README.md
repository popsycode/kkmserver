# KkmServer.js

Js-библиотека для взаимодействия со специальным сервером(KkmServer), посредством
Ajax запросов. Дополнительные библиотеки не требуются.
 
## Кратко о KkmServer
 
- Программа предназначена для печати и регистрации фискальных/не фискальных чеков на Контрольно-кассовой технике оборудованной фискальным накопителем (далее ККТ).
- Программа является маленьким HTTP web-сервером и имеет встроенные драйвера ККТ (кроме драйверов Usb-Com).
- Позволяет печатать/регистрировать чеки с мобильных устройств / планшетов или с настольного ПК из 1с одновременно.
- Позволяет печатать/регистрировать чеки на KKM подключенных к другим ПК.
- Есть возможность печати этикеток с штрих-кодами на принтерах этикеток.
- Так-же возможно использовать ККТ в качестве принтера этикеток.
- Технология использования - HTTP(Ajax/REST) запрос, данные передаются через JSON;
- [Страница программы](https://kkmserver.ru/KkmServer)
 
## Пример использования

Смотрите в ./example/

## Благодарность автору 

Выразить благодарность и стимулировать дальнейшее развитие библиотеки можно добровольным пожертованием
[на яд-кошелек 410013790927405](https://money.yandex.ru/to/410013790927405) 

## History

### Альфа версии
- 0.2.0 - Извините еще один полный рефакторинг (предыдущий вариант плохо документировался и не получалось сделать автокомплит)   
- 0.1.0 - Переработан полностью набор методов. Добавлена документация.   
- 0.0.2 - Первая публичная версия 

