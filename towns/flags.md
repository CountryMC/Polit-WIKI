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

## <mark style="color:$primary;">Команды</mark>

* **`/t flags`** - меню настройки разрешений
* **`/t toggle <флаг> on/off` - включить/отключить разрешение города**
* **`/t toggle <флаг>` - переключить разрешение на противоположное значение**

## <mark style="color:$primary;">Флаги</mark>

\*чужак - это любой игрок, который не является жителем твоего города

<table><thead><tr><th width="172">Флаг</th><th width="177">Значение</th><th width="154">Команда</th><th width="99" align="center">Значение по умолчанию</th></tr></thead><tbody><tr><td><strong>pvp</strong></td><td>Включить/отключить пвп в городе</td><td><strong>/t toggle pvp on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td><strong>villager_trading</strong></td><td>Включить/отключить торговлю с жителями(мобами) только для чужаков города</td><td><strong>/t toggle villager_trading on/off</strong></td><td align="center"><mark style="color:$success;"><strong>+</strong></mark></td></tr><tr><td><strong>explosions</strong></td><td>Включить/отключить урон и разрушения от взрывов</td><td><strong>/t toggle explosions on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td><strong>fire_spread</strong></td><td>Включить/отключить распространение огня в городе</td><td><strong>/t toggle explosions on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td><strong>friendly_fire</strong></td><td>Включить/отключить возможность наносить урон по своим</td><td><strong>/t toggle friendly_fire on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td><strong>experience</strong></td><td>Включить/отключить возможность чужакам получать опыт внутри города</td><td><strong>/t toggle experience on/off</strong></td><td align="center"><mark style="color:$success;"><strong>+</strong></mark></td></tr><tr><td><strong>spawner_breaking</strong></td><td>Включить/отключить возможность всем кроме мэра ломать спавнера внутри города</td><td><strong>/t toggle spawner_breaking on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td><strong>open_town</strong></td><td>Включить/отключить возможность любому игроку вступить в город без приглашения</td><td><strong>/t toggle open_town on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr><tr><td><strong>public_spawn</strong></td><td>Включить/отключить возможность любому игроку телепортироваться  в город(<strong>/t spawn &#x3C;город></strong>)</td><td><strong>/t toggle public_spawn on/off</strong></td><td align="center"><mark style="color:$danger;"><strong>-</strong></mark></td></tr></tbody></table>

{% hint style="warning" %}
Подоходный налог не может быть меньше **1%** и больше **60%**
{% endhint %}
