# ⚔ Рейды

Рейды позволяют напасть на жителей другого города на определенное время.

## <mark style="color:purple;">Команды</mark>

* **/t raid <город>** - начать рейд на город
* **/t raidjoin <сторона>** - присоединить свой город к рейду
* **/t raidtime** - информация о кулдаунах на рейды
* **/t raidend** - оставшееся время до конца рейда

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>

## <mark style="color:purple;">Обьявление рейда</mark>

Для объявления рейда необходимо иметь определенное кол-во монет в бюджете города и купленное здание [**Тренировочный лагерь**](buildings.md#trenirovochnyi-lager):

* **/t raid <город>** - начать рейд на город

После обявления рейда, сторонам дается **5 минут** на подготовку и поиск союзников. После окончания этого времени жители атакующего города могут наносить урон жителям защищающегося в их городе. Рейд длится **15 минут**.

Атакующая сторона может **ограбить** город. Для этого нужно, чтобы хотя бы один игрок из атакующих городов встал на городской центр защищающегося города, после чего нужно находится в этом регионе **45 секунд**, чтобы ограбить бюджет города на **3%**(награбленное пойдет в бюджет города, который начал рейд). Грабить можно до тех пор, пока не закончится время рейда.

{% hint style="info" %}
Рейдить можно только города выше **I уровня**, а также спустя **5 дней** после основания города. Также на новые города действует защита от рейдов на протяжении **5 дней**, независимо от уровня города. Также для начала рейда необходимо, чтобы в обороняющемся городе было как минимум **2** жителя онлайн.
{% endhint %}

{% hint style="info" %}
После рейда, у защищавшегося города устанавливается защита от рейдов на **24 часа**, а у нападавшего запрет на следующий рейд в течении **12 часов**.
{% endhint %}

{% hint style="warning" %}
Нельзя рейдить города, находящиеся с твоим городом в одном союзе.
{% endhint %}

{% hint style="danger" %}
Во время рейда у жителей защищающегося города отключена возможность ставить\ломать блоки в своем городе и доступ к важным городским командам, а у жителей атакующего города включена возможность открывать/ломать двери, люки и калитки.
{% endhint %}

{% hint style="danger" %}
На сервере одновременно может проходить только **один** рейд.
{% endhint %}

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>

## <mark style="color:purple;">Участие в рейдах других городов</mark>

В ожидании завершения запрета на рейды, твой город может участвовать в рейдах, начатых другими городами. Для этого нужно как и с обычным рейдом иметь определенное кол-во монет в бюджете города:

* **/t raidjoin <сторона>** - присоединиться к рейду, начатому другим городом

В этом случае можно выбрать два варианта: присоединиться к городу, который нападает и к городу, который защищается.

<figure><img src="../.gitbook/assets/Screenshot from 2022-11-30 08-06-53.png" alt=""><figcaption><p>Обьявление о начале рейда</p></figcaption></figure>

{% hint style="warning" %}
Присоединиться к рейду можно только в течении **5 минут** с момента обьявления рейда.
{% endhint %}

{% hint style="info" %}
Если ты выбрал помощь стороне защиты, то присоединится можно будет только если защищающийся город находится в одном союзе с твоим городом .
{% endhint %}

{% hint style="info" %}
После присоединения к рейду за атакующую сторону на город накладывается запрет на следующее присоеденении в течении **4 часов**, а если за обороняющуюся, то запрета нет.
{% endhint %}

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>

## <mark style="color:purple;">Кулдауны</mark>

Чтобы не приходилось запоминать сколько времени осталось ждать до того или другого рейда была создана команда:

* **/t raidtime** - информация о кулдаунах на рейды

<figure><img src="../.gitbook/assets/Screenshot from 2022-11-30 10-20-14.png" alt=""><figcaption><p>Информация о кулдаунах в чате</p></figcaption></figure>

Также информацию о них можно посмотреть в меню города:

* **/t** - меню города

<figure><img src="../.gitbook/assets/Screenshot from 2022-11-30 08-06-24.png" alt=""><figcaption><p>Информация о городе</p></figcaption></figure>

<figure><img src="../.gitbook/assets/gitlab_hr7.svg" alt=""><figcaption></figcaption></figure>