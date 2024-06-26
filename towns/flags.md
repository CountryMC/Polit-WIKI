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
* **/t flag set** **<флаг>** - установить флаг города в определенное значение
* **/t flag gui** - удобное меню по управлению флагами города

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>

## <mark style="color:purple;">Флаги</mark>

| Флаг                       | Значение                                                                                                                                 | Команда                                |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| **pvp**                    | Включить/отключить пвп в городе                                                                                                          | **/t flag set pvp**                    |
| **public\_villagers**      | Включить/отключить публичных НПС жителей. Если флаг отлючен, то с жителями в городе могут торговать только игроки живущие в этом городе. | **/t flag set public\_villagers**      |
| **public\_gov\_villagers** | Включить/отключить публичных НПС жителей для  жителей государства                                                                        | **/t flag set public\_gov\_villagers** |
| **tax**                    | Установить подоходный налог города                                                                                                       | **/t flag set tax <число>**            |
| **reg**                    | Сделать все регионы без владельцев публичными для своих жителей(они смогут открывать сундуки, ломать, строить)                           | **/t flag set reg**                    |
| **alien\_exp**             | Включить/отключить возможность чужакам получать опыт в городе                                                                            | **/t flag set alien\_exp**             |
| **friendly\_fire**         | Включить/отключить возможность наносить урон по своим же жителям                                                                         | **/t flag set friendly\_fire**         |
| **build\_in\_camp**        | Включить/отключить возможность строить в лагере города                                                                                   | **/t flag set build\_in\_camp**        |
| **spawners\_break**        | Включить/отключить возможность жителям ломать спавнера на территории города                                                              | **/t flag set spawners\_break**        |
| **public\_beacon**         | Включить/отключить возможность чужакам получать эффекты от маяков в городе                                                               | **/t flag set public\_beacon**         |
| **mob\_damage**            | Включить/отключить возможность любым  игрокам наносить урон по мирным мобам в городе                                                     | **/t flag set mob\_damage**            |

{% hint style="warning" %}
Подоходный налог не может быть меньше **1%** и больше **60%**
{% endhint %}

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>
