# ⚖ Ранги и права

При помощи ранговой <mark style="color:purple;"></mark> системы можно изменять права жителей города, давая им возможность использовать команды, доступ к территории и тд.

## <mark style="color:purple;">Команды</mark>

* **/t rank perm <право> <ник>** - выдать/забрать право у жителя
* **/t rank add <ранг>** - выдать жителю ранг
* **/t set mayor <ник>** - передать владение городом другому жителю

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>

## <mark style="color:purple;">Ранги и права</mark>

Существует четыре ранга: <mark style="color:orange;">**Заместитель мэра**</mark>, <mark style="color:orange;">**обычный житель**</mark>, <mark style="color:orange;">**солдат и строитель**</mark>. Тем не менее мэр города может забирать и выдавать права жителям с любым рангом.

| Право                 | Значение                                                                                                                                                                                                                                      | Команда                                    |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| **ClaimRegions**      | Дает/Забирает право приватить регионы для города(**/t claim**)                                                                                                                                                                                | **/t rank perm ClaimRegions <игрок>**      |
| **DeleteRegions**     | Дает/Забирает право удалять регионы города(**/t unclaim**)                                                                                                                                                                                    | **/t rank perm DeleteRegions <игрок>**     |
| **DeletePlots**       | Дает/Забирает право удалять участки(**/plot unclaim**). Если ранг владельца участка выше, то удалить не получится                                                                                                                             | **/t rank perm DeletePlots <игрок>**       |
| **InviteResidents**   | Дает/Забирает право приглашать игроков в город(**/t invite**)                                                                                                                                                                                 | **/t rank perm InviteResidents <игрок>**   |
| **KickResidents**     | Дает/Забирает право кикать игроков из города(**/t kick**)                                                                                                                                                                                     | **/t rank perm KickResidents <игрок>**     |
| **Withdraw**          | Дает/Забирает право на снятие монет с бюджета города(**/t withdraw**)                                                                                                                                                                         | **/t rank perm Withdraw <игрок>**          |
| **LvlUp**             | Дает/Забирает право повышать уровень города(**/t lvlup**)                                                                                                                                                                                     | **/t rank perm LvlUp <игрок>**             |
| **BuyBuilding**       | Дает/Забирает право покупать здания в городе                                                                                                                                                                                                  | **/t rank perm BuyBuilding <игрок>**       |
| **BuildEverywhere**   | Дает/Забирает право строить/ломать/открывать сундуки во всем городе. Если попытаться сделать что-нибудь на участке у которого есть владелец с рангом выше, то ничего не получится.                                                            | **/t rank perm BuildEverywhere <игрок>**   |
| **SetFlags**          | Дает/Забирает право устанавливать флаги города(**/t flag set**)                                                                                                                                                                               | **/t rank perm SetFlags <игрок>**          |
| **SetSpawn**          | Дает/Забирает право менять точку городского спавна(**/t setspawn**)                                                                                                                                                                           | **/t rank perm SetSpawn <игрок>**          |
| **Rename**            | Дает/Забирает право менять название города(**/t rename**)                                                                                                                                                                                     | **/t rank perm Rename <игрок>**            |
| **ChangePlotPrice**   | Дает/Забирает право устанавливать цену участка(**/plot set price**). Обычный житель не может устанавливать цену учатка у которого есть владелец, а с этим право сможет                                                                        | **/t rank perm ChangePlotPrice <игрок>**   |
| **SetPlotForSale**    | Дает/Забирает право выставлять участок на продажу(**/plot set forsale**). Если у участка есть владелец у которого ранг выше, то ничего не получится. Обычный житель не может выставлять учаток с владельцем на продажу, а с этим право сможет | **/t rank perm SetPlotForSale <игрок>**    |
| **SetPlotType**       | Дает/Забирает право менять тип участка(**/plot set type**). Если у участка есть владелец у которого ранг выше, то ничего не получится. Обычный житель не может менять тип учатока с владельцем, а с этим право сможет                         | **/t rank perm SetPlotType <игрок>**       |
| **BuildingLvlUp**     | Дает/Забирает право на прокачку уровней зданий(**/b lvlup**)                                                                                                                                                                                  | **/t rank perm BuildingLvlUp <игрок>**     |
| **PublicVillagers**   | Дает/Забирает право на утсановку публичности НПС жителей(**/t flag set public\_villagers**)                                                                                                                                                   | **/t rank perm PublicVillagers <игрок>**   |
| **TakeTownInventory** | Дает/Забирает право на взятие предметов из городского инвентаря                                                                                                                                                                               | **/t rank perm TakeTownInventory <игрок>** |
| **SetAlienExp**       | Дает/Забирает право на установки запрета на получения опыта чужаками в городе(**/flag set alien\_exp**)                                                                                                                                       | **/t rank perm SetAlienExp <игрок>**       |
| **StartRaid**         | Дает/Забирает право на возможность начинать рейд                                                                                                                                                                                              | **/t rank perm StartRaid <игрок>**         |
| **JoinRaid**          | Дает/Забирает право на присоединение к рейду                                                                                                                                                                                                  | **/t rank perm JoinRaid <игрок>**          |
| **UnionInvite**       | Дает/Забирает право на приглашение городов в государство                                                                                                                                                                                      | **/t rank perm UnionInvite <игрок>**       |
| **FriendlyFire**      | Дает/Забирает право на включение урона по своим                                                                                                                                                                                               | **/t rank perm FriendlyFire <игрок>**      |

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>

## <mark style="color:purple;">Права рангов по умолчанию</mark>

| Право                 |             Заместитель мэра            |             Обычный житель            |                 Солдат                |               Строитель               |
| --------------------- | :-------------------------------------: | :-----------------------------------: | :-----------------------------------: | :-----------------------------------: |
| **ClaimRegions**      | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **DeleteRegions**     | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **DeletePlots**       | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **InviteResidents**   | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **KickResidents**     | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **Withdraw**          | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **LvlUp**             | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **BuyBuilding**       | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **BuildEverywhere**   | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **SetFlags**          | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **SetSpawn**          | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **Rename**            | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **ChangePlotPrice**   | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **SetPlotForSale**    | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **SetPlotType**       | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **BuildingLvlUp**     | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **PublicVillagers**   | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **TakeTownInventory** | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **SetAlienExp**       | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **StartRaid**         | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **JoinRaid**          | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **UnionInvite**       | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |
| **FriendlyFire**      | <mark style="color:green;">**+**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> | <mark style="color:red;">**-**</mark> |

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>
