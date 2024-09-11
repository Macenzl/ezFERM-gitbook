---
description: Функциональные решения, предлагаемые ezFERM.
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

# 🚀 Обзор

Ферма мультиаккаунтов ezFERM - это система для разработчиков, в которой легко писать, тестировать и запускать проекты с тысячами аккаунтов легко и непринуждённо, увеличить продолжительность жизни драгоценных акков, сведя к минимуму количество вечных локов.&#x20;

В вашем распоряжении: менеджер задач, прокси менеджер, эмулятор жизнедеятельности аккаунтов LISA (life imitation system accounts), удобная Excel база данных, обработка забаненных аккаунтов, всесторонне логгирование, удобное ведение своих дополнительных Excel баз данных (синхронизированные таблицы) и многое другое.

Все что вам остаётся - добавить в систему свои задачи и подзадачи.

## <mark style="color:blue;">Создание ферм</mark>

Создавайте из коробки подготовленные и оснащенные всем необходимым личные фермы мультиаккаунтов без усилий, для работы с тысячами аккаунтов и выполняющую любой вид работ из сотен задач.

{% tabs %}
{% tab title="Личные фермы" %}
<figure><img src=".gitbook/assets/Папка с фермами" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="1 пример" %}
<figure><img src=".gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="2 пример" %}
<figure><img src=".gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="3 пример" %}
<figure><img src=".gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

Ферма ezFERM - клонируемая. Вы можете создать неограниченное количество личных ферм. Что бы создать новую ферму, нужно просто скопировать всю папку  "Шаблон" в директорию личных ферм.

{% tabs %}
{% tab title="Ферма-создатель" %}
<figure><img src=".gitbook/assets/Папка ферма.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Новая ферма 1" %}
<figure><img src=".gitbook/assets/Новая ферма 1.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Новая ферма 2" %}
<div data-full-width="true">

<figure><img src=".gitbook/assets/Новая ферма 2.png" alt=""><figcaption></figcaption></figure>

</div>
{% endtab %}
{% endtabs %}

{% hint style="info" %}
1. Ферма ezFERM - это папка с шаблоном по пути "ezFERM/ezFERM - создатель ферм/Шаблон". В папке все базовые файлы от фермы и сам шаблон.
2. После копирования папки, получается новая ферма. Разработка своей фермы всегда начинается с копирования этой папки, потому что в папке уже готовая ферма.
3. После копирования папки, открываете шаблон из папки и добавляете в него свои задачи и подзадачи.
{% endhint %}

## <mark style="color:blue;">Стандартизация разработки</mark>

Одинаковая файловая структура всех ферм и строгая структура файла проекта делает разработку стандартизированной и предсказуемой, а также ограждает функционал вашей фермы от разрастания в монолитную массу из кубиков и клубков запутанных связей.

{% tabs %}
{% tab title="Структура файла" %}
<figure><img src=".gitbook/assets/Дефолтная структура.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Файл "Новая ферма 1"" %}
<figure><img src=".gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Файл "Новая ферма 2"" %}
<figure><img src=".gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Без использования ezFERM" %}
<figure><img src=".gitbook/assets/плохой шаблон.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## <mark style="color:blue;">Менеджер задач</mark>

Ферма ezFERM создается для выполнения заданной работы в сети интернет (не только), наводняя целевую платформу/сайт большим количеством ботов, выполняющих действия не отличимые от действий реального человека.

Модульная система добавления задач и подзадач, упрощает разработку фермы, ее обслуживание и масштабирование. Появляются возможности:

* Включать и выключать каждую задачу и подзадачу отдельно, добавлять новые или удалять совсем.
* Выбор режимов выполнения: рандомно, по очереди, рандомно до конца, по очереди до конца.
* Распределение количества выполнений каждой задачи и подзадачи.
* Гибко управлять ходом выполнения и результатом каждой задачи/подзадачи: удачно, неудачно, заблокировать задачу/подзадачу, забанить профиль, закончить сессию, закончить все сессии, bad end (ошибка).&#x20;

&#x20; И также многое другое.

## <mark style="color:blue;">Задачи и подзадачи в ProjectMaker</mark>

Для предпочитающих писать кубиками.

{% tabs %}
{% tab title="Задачи" %}
<figure><img src=".gitbook/assets/Задачи.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Подзадачи" %}
<figure><img src=".gitbook/assets/Подзадачи (1).png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## <mark style="color:blue;">Задачи и подзадачи в VisualStudio</mark>

ezFERM будет обращаться в вашу сборку для вызова задач и подзадач. Для продвинутых пользователей, знающих язык программирования C#.&#x20;

{% tabs %}
{% tab title="Задача" %}
<figure><img src=".gitbook/assets/Задачи VS.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Подзадача" %}
<figure><img src=".gitbook/assets/image (27) (1).png" alt=""><figcaption></figcaption></figure>


{% endtab %}
{% endtabs %}

## <mark style="color:blue;">Эмуляция жизнедеятельности (LISA)</mark>

ezFERM расширяет встроенные в ZennoPoster антидетект фишки эмулятором жизнедеятельности. Гибкая настройка поведения аккаунта для максимальной схожести с поведением реального человека.

<div align="center">

<figure><img src=".gitbook/assets/Настройки эмуляции обзор.png" alt="" width="449"><figcaption></figcaption></figure>

</div>

## <mark style="color:blue;">Прокси менеджер</mark>

Все прокси хранятся в базе прокси, автоматически устанавливаются каждому аккаунту. Во время работы аккаунтов прокси проходят постоянные проверки на доступность, осуществляются баны прокси, замены для бесперебойной работы аккаунтов. Глубоко настраиваемая работа с прокси позволяет настроить проксификацию под себя.&#x20;

## <mark style="color:blue;">База данных Excel</mark>

Для каждой фермы личная база данных, хранящая информацию об аккаунтах, забаненых аккаунтах, прокси, настройках эмулятора, задачах и подзадачах, синхронизированных таблицах. Используется для записи и чтения данных как системой ezFERM, так и пользователем одновременно.

{% tabs %}
{% tab title="Аккаунты" %}
<figure><img src=".gitbook/assets/Аккаунты.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Прокси" %}
<figure><img src=".gitbook/assets/Прокси лист 2.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Забаненые аккаунты" %}
<figure><img src=".gitbook/assets/Бан аккаунты.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Эмуляция" %}
<figure><img src=".gitbook/assets/Эмуляция.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Задачи" %}
<figure><img src=".gitbook/assets/Задачи лист.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Подзадачи" %}
<figure><img src=".gitbook/assets/Подзадачи лист.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Синх. таблицы" %}
<figure><img src=".gitbook/assets/синх таблицы.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## <mark style="color:blue;">Синхронизированные таблицы</mark>

Лист "Аккаунты" хранит данные об аккаунтах. На каждый аккаунт отдельная строка. Так как лист хранит системную и информацию и добавление своих столбцов не предусмотрено, всегда можно создать таблицы, синхронизированные с ключевым столбцом "Профили". Добавление или удаление аккаунтов будет как в Базе, так и в ваших таблицах.

{% tabs %}
{% tab title="Аккаунты" %}
<figure><img src=".gitbook/assets/База.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Синх. таблица 1" %}
<figure><img src=".gitbook/assets/Синх таблица 1.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Синх. таблица 2" %}
<figure><img src=".gitbook/assets/Синх таблица 2.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## <mark style="color:blue;">Логгирование</mark>

Общий лог выполнения и расширенные логи по каждому аккаунту и прокси.

{% tabs %}
{% tab title="Общий лог" %}
<figure><img src=".gitbook/assets/Общий лог 1.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Еще общий лог" %}
<figure><img src=".gitbook/assets/Общий лог 2.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Логи аккаунтов" %}
<figure><img src=".gitbook/assets/Лог аккаунты.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Логи прокси" %}
<figure><img src=".gitbook/assets/Лог прокси.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## <mark style="color:blue;">Настройки фермы</mark>

Интерфейс для управления поведением фермы в целом, так и каждой ее части отдельно. Настройки делятся на внутренние, доступные только для разработчику во время проектирования и внешние, доступные как разработчику так и клиенту.

### Внешние

{% tabs %}
{% tab title="Режимы" %}
<figure><img src=".gitbook/assets/Внешние общие.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Прокси" %}
<figure><img src=".gitbook/assets/Прокси 1.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Еще прокси " %}
<figure><img src=".gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Внутренние

{% tabs %}
{% tab title="Общие" %}
<figure><img src=".gitbook/assets/Общие внутренние.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Аккаунты" %}
<figure><img src=".gitbook/assets/Настройки аккаунты.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Задачи" %}
<figure><img src=".gitbook/assets/Настройки задачи.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Подзадачи" %}
<figure><img src=".gitbook/assets/Подзадачи.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Синх.таблицы" %}
<figure><img src=".gitbook/assets/Настройки синх.таблицы.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## <mark style="color:blue;">Инсталлятор среды ezFERM</mark>

Все фермы, создаваемые сообществом, работают в общей среде, устанавливаются и обновляются через единый инсталлятор. Среда - это директория установки ezFERM.&#x20;

<div align="center">

<figure><img src=".gitbook/assets/Root папка.png" alt="" width="490"><figcaption></figcaption></figure>

</div>

Вне этих директорий фермы работать не будут.&#x20;

## <mark style="color:blue;">Монетизируйте создаваемые фермы</mark>&#x20;

Если после создания фермы появится желание ее продать, или сделать публичной, есть возможность вписать ферму в инсталлятор, после чего ваши личные фермы будут автоматически устанавливаться и обновляться по мере доработки у других пользователей в папке "Поставляемые фермы". Также фермы, разрабатываемые другими пользователями и добавленные в единый инсталлятор, будут установлены у вас с автоматическим получением обновлений. Поставляемые фермы активируется уникальными ключами. Система лицензирования, предоставляемая ezFERM в вашем распоряжении.

## <mark style="color:blue;">Прочий функционал</mark>

* Ассистирование разработки. Ферма всегда подскажет, что сделать развернутыми комментариями.
* Настройки многопоточности. Запущенный поток может обслуживать как один аккаунт, так и большое количество без простоев.
* Авто перезапуск после bad end.
* Неограниченное количество создаваемых ферм.
* Одновременная разработка ферм.
* Одновременный запуск ферм.
* Отладка ферм.

## <mark style="color:blue;">Узнайте больше о ezFERM в теме на форуме zenno.club</mark>

{% embed url="https://zenno.club/discussion/threads/ezferm-shablon-dlja-sozdanija-ferm-multiakkauntov-besplatnaja-licenzija.121022/" %}
