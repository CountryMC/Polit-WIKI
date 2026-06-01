---
hidden: true
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

# ⚙️ Настройка разрешений p

У каждого государства есть определенные разрешения(флаги), которые можно регулировать.

## <mark style="color:$primary;">Команды</mark>

* **`/nation flags`** - меню настройки разрешений
* **`/nation flag <флаг>`** - установить флаг государства в определенное значение

## <mark style="color:$primary;">Флаги</mark>

| Флаг                  | Значение                                                                                                  | Команда                            |
| --------------------- | --------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| **allowFriendlyFire** | Включить/отключить возможность наносить урон по союзникам(не влияей на городской флаг **friendly\_fire**) | **/nation flag allowFriendlyFire** |
| **allowCapTp**        | Включить/отключить возможность жителям государства телепортироваться в столицу(**/nation capital**)       | **/nation flag allowCapTp**        |
| **allowTownTp**       | Включить/отключить возможность жителям государства телепортироваться в союзные города(**/nation spawn**)  | **/nation flag allowTownTp**       |
