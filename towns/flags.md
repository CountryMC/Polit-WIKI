---
layout:
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
---

# ⚙️ Настройка разрешений

У каждого города есть определенные разрешения(флаги), которые можно регулировать.

## <mark style="color:purple;">Команды</mark>

* **/t flags** - меню настройки разрешений
* **/t flag** **<флаг>** - установить флаг города в определенное значение

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>

## <mark style="color:purple;">Флаги</mark>

| Флаг                           | Значение                                                                                                                                 | Команда                                |
| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| **allowPvp**                   | Включить/отключить пвп в городе                                                                                                          | **/t flag allowPvp**                   |
| **allowPublicVillagers**       | Включить/отключить публичных НПС жителей. Если флаг отлючен, то с жителями в городе могут торговать только игроки живущие в этом городе. | **/t flag allowPublicVillagers**       |
| **allowPublicNationVillagers** | Включить/отключить публичных НПС жителей для  жителей государства                                                                        | **/t flag allowPublicNationVillagers** |
| **allowPublicReg**             | Сделать все регионы без владельцев публичными для своих жителей(они смогут открывать сундуки, ломать, строить)                           | **/t flag allowPublicReg**             |
| **allowAlienExp**              | Включить/отключить возможность чужакам получать опыт в городе                                                                            | **/t flag allowAlienExp**              |
| **allowFriendlyFire**          | Включить/отключить возможность наносить урон по своим же жителям                                                                         | **/t flag allowFriendlyFire**          |
| **allowBuildInCamp**           | Включить/отключить возможность строить в лагере города                                                                                   | **/t flag allowBuildInCamp**           |
| **allowBreakSpawners**         | Включить/отключить возможность жителям ломать спавнера на территории города                                                              | **/t flag allowBreakSpawners**         |
| **allowPublicBeacon**          | Включить/отключить возможность чужакам получать эффекты от маяков в городе                                                               | **/t flag allowPublicBeacon**          |
| **allowMobDamage**             | Включить/отключить возможность любым  игрокам наносить урон по мирным мобам в городе                                                     | **/t flag allowMobDamage**             |
| **allowPublicVehicles**        | Включить/отключить возможность чужим игрокам пользоваться лодками и вагонетками(обычными без сунука, воронки и динамита) в городе        | **/t flag allowPublicVehicles**        |
| **allowPublicTp**              | Включить/отключить возможность чужим игрокам телепортироваться в город(**/t spawn <город>**)                                             | **/t flag allowPublicTp**              |

{% hint style="warning" %}
Подоходный налог не может быть меньше **1%** и больше **60%**
{% endhint %}

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>
