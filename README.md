# scoop-xmel

[![Tests](https://github.com/igorxmel/scoop-xmel/actions/workflows/ci.yml/badge.svg)](https://github.com/igorxmel/scoop-xmel/actions/workflows/ci.yml) [![Excavator](https://github.com/igorxmel/scoop-xmel/actions/workflows/excavator.yml/badge.svg)](https://github.com/igorxmel/scoop-xmel/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for [ZapretXmel](https://github.com/igorxmel/ZapretXmel) —
a Windows GUI for zapret in the Flowseal bundle.

Бакет [Scoop](https://scoop.sh) для [ZapretXmel](https://github.com/igorxmel/ZapretXmel).

## Установка / Install

```powershell
scoop bucket add xmel https://github.com/igorxmel/scoop-xmel
scoop install xmel/zapretxmel
```

Обновление — `scoop update zapretxmel`. Встроенное обновление в программе, поставленной
через Scoop, выключено, чтобы Scoop знал, какая версия стоит. Ядро zapret, настройки и
прокси для Telegram лежат в `persist` и переживают обновления.

Манифест обновляется сам: Action `Excavator` раз в четыре часа сверяется с релизами
ZapretXmel и берёт хеш из опубликованного `.sha256`. Вопросы — на
[форуме в Telegram](https://t.me/XmelNet).
