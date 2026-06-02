---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# ⚙️ Настройка разрешений

Разрешения позволяют управлять различными возможностями на территории города, участка, группы участков или для участков конкретного жителя.

## <mark style="color:$primary;">Области действия рахрешений</mark>

Все разрешения работают одинаково, отличается только область их применения.

| Тип                              | Команды                                                     | Область действия                               |
| -------------------------------- | ----------------------------------------------------------- | ---------------------------------------------- |
| Городские участки(без владельца) | `/t flags`, `/t toggle`                                     | Все городские участки без владельца            |
| Участок                          | `/plot flags`, `/plot toggle`                               | Текущий участок на котором находится игрок     |
| Группа участков                  | `/plot group flags <группа>`, `/plot group <группа> toggle` | Все участки в группе                           |
| Участки житель                   | `/res flags`, `/res toggle`                                 | Настройки для всех участков конкретного жителя |

## <mark style="color:$primary;">Команды</mark>

Все разрешения используются похожим образом:

* **`<команда> <флаг> on`** — включить флаг
* **`<команда> <флаг> off`** — отключить флаг
* **`<команда> <флаг>`** — переключить флаг на противоположное значение

### <mark style="color:$primary;">Примеры</mark>

* `/t toggle pvp on`в городе
* `/plot toggle pvp off` - выключает ПВП в участке, в котором стоит игрок
* `/plot group malinovka toggle pvp` - переключает ПВП во всех участках, которые входят в группу `malinovka`
* `/res toggle pvp on` - включает ПВП во всех участках, которыми владеет игрок

## <mark style="color:$primary;">Меню настройки</mark>

Каждый тип разрешений также имеет графическое меню настройки:

* **`/t flags`** - разрешения городских участков
* **`/plot flags`** - флаги участка
* **`/plot group flags`** - флаги группы участков
* **`/res flags`** - персональные флаги жителя

## <mark style="color:$primary;">Флаги</mark>

\*чужак - это любой игрок, который не является жителем твоего города

<table><thead><tr><th align="center" valign="top">Флаг</th><th>Значение</th><th align="center">Значение по умолчанию</th></tr></thead><tbody><tr><td align="center" valign="top"><strong>pvp</strong></td><td>Включить/отключить пвп в городе</td><td align="center">❌</td></tr><tr><td align="center" valign="top"><strong>villager_trading</strong></td><td>Включить/отключить торговлю с жителями(мобами) только для чужаков города</td><td align="center">✅</td></tr><tr><td align="center" valign="top"><strong>explosions</strong></td><td>Включить/отключить урон и разрушения от взрывов</td><td align="center">❌</td></tr><tr><td align="center" valign="top"><strong>fire_spread</strong></td><td>Включить/отключить распространение огня в городе</td><td align="center">❌</td></tr><tr><td align="center" valign="top"><strong>friendly_fire</strong></td><td>Включить/отключить возможность наносить урон по своим</td><td align="center">❌</td></tr><tr><td align="center" valign="top"><strong>experience</strong></td><td>Включить/отключить возможность чужакам получать опыт внутри города</td><td align="center">✅</td></tr><tr><td align="center" valign="top"><strong>spawner_breaking</strong></td><td>Включить/отключить возможность всем кроме мэра ломать спавнера внутри города</td><td align="center">❌</td></tr><tr><td align="center" valign="top"><strong>open_town</strong></td><td>Включить/отключить возможность любому игроку вступить в город без приглашения</td><td align="center">❌</td></tr><tr><td align="center" valign="top"><strong>public_spawn</strong></td><td>Включить/отключить возможность любому игроку телепортироваться в город(<strong>/t spawn &#x3C;город></strong>)</td><td align="center">❌</td></tr></tbody></table>
