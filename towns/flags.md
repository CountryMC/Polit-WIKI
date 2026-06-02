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

У каждого города есть определенные разрешения(флаги), которые можно регулировать.

## <mark style="color:$primary;">Области действия флагов</mark>

Все флаги работают одинаково, отличается только область их применения.

| Тип | Команды | Область действия |
|------|----------|------------------|
| Город | `/t flags`, `/t toggle` | Весь город |
| Участок | `/plot flags`, `/plot toggle` | Текущий участок |
| Группа участков | `/plot group flags`, `/plot group toggle` | Все участки в группе |
| Житель | `/res flags`, `/res toggle` | Настройки конкретного жителя |

## <mark style="color:$primary;">Команды</mark>

Для всех типов флагов используется одинаковый синтаксис:

* **`<команда> <флаг> on`** — включить флаг
* **`<команда> <флаг> off`** — отключить флаг
* **`<команда> <флаг>`** — переключить флаг на противоположное значение

### Примеры

* `/t toggle pvp on`
* `/plot toggle pvp off`
* `/plot group toggle pvp`
* `/res toggle pvp on`

## <mark style="color:$primary;">Меню настройки</mark>

Каждый тип флагов также имеет графическое меню настройки:

* **`/t flags`** — флаги города
* **`/plot flags`** — флаги участка
* **`/plot group flags`** — флаги группы участков
* **`/res flags`** — персональные флаги жителя

## <mark style="color:$primary;">Флаги</mark>

\*чужак - это любой игрок, который не является жителем твоего города

<table><thead><tr><th width="172" align="center" valign="top">Флаг</th><th width="177">Значение</th><th width="154">Команда</th><th width="99" align="center">Значение по умолчанию</th></tr></thead><tbody><tr><td align="center" valign="top"><strong>pvp</strong></td><td>Включить/отключить пвп в городе</td><td><strong>/t toggle pvp on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td align="center" valign="top"><strong>villager_trading</strong></td><td>Включить/отключить торговлю с жителями(мобами) только для чужаков города</td><td><strong>/t toggle villager_trading on/off</strong></td><td align="center"><mark style="color:$success;"><strong>+</strong></mark></td></tr><tr><td align="center" valign="top"><strong>explosions</strong></td><td>Включить/отключить урон и разрушения от взрывов</td><td><strong>/t toggle explosions on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td align="center" valign="top"><strong>fire_spread</strong></td><td>Включить/отключить распространение огня в городе</td><td><strong>/t toggle explosions on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td align="center" valign="top"><strong>friendly_fire</strong></td><td>Включить/отключить возможность наносить урон по своим</td><td><strong>/t toggle friendly_fire on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td align="center" valign="top"><strong>experience</strong></td><td>Включить/отключить возможность чужакам получать опыт внутри города</td><td><strong>/t toggle experience on/off</strong></td><td align="center"><mark style="color:$success;"><strong>+</strong></mark></td></tr><tr><td align="center" valign="top"><strong>spawner_breaking</strong></td><td>Включить/отключить возможность всем кроме мэра ломать спавнера внутри города</td><td><strong>/t toggle spawner_breaking on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td align="center" valign="top"><strong>open_town</strong></td><td>Включить/отключить возможность любому игроку вступить в город без приглашения</td><td><strong>/t toggle open_town on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td align="center" valign="top"><strong>public_spawn</strong></td><td>Включить/отключить возможность любому игроку телепортироваться  в город(<strong>/t spawn &#x3C;город></strong>)</td><td><strong>/t toggle public_spawn on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr></tbody></table>
