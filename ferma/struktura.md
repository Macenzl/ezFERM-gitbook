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

# Структура шаблона фермы

Файл/шаблон проекта каждой фермы имеет одинаковую структуру.

{% tabs %}
{% tab title="Демонстрация 1" %}
<figure><img src="../.gitbook/assets/Шаблон части 1.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Демонстрация 2" %}
<figure><img src="../.gitbook/assets/Шаблон части 2.png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## <mark style="color:blue;">Структура интеграции ezFERM c ZennoPoster</mark>

Кубик для обработки Bad – End. После попадания в этот кубик система запоминает, какая задача или подзадача упала, после шаблон завершается, добавляется одно выполнение в ZP и перезапускается снова автоматически.

<div align="center">

<figure><img src="../.gitbook/assets/image (1).png" alt="" width="340"><figcaption></figcaption></figure>

</div>

Кубики внутренних настроек фермы. После двойного нажатия на кубик "ezFERM Settings" откроется меню управления фермой.

<figure><img src="../.gitbook/assets/image (2).png" alt="" width="341"><figcaption></figcaption></figure>

Кубик отсоединен, и предназначен только для отладки проекта в VS. Внутри кубика необходимо выбрать проект, сохраненный в папке "Проект VS".

<figure><img src="../.gitbook/assets/image (3).png" alt="" width="346"><figcaption></figcaption></figure>

Кубик запускает проект c задачами VS.

<figure><img src="../.gitbook/assets/image (4).png" alt="" width="341"><figcaption></figcaption></figure>

Во внутренних настройках фермы определите, где запускаем задачи, в проекте PM или VS. При запуске шаблона switch запустит задачи в нужном проекте.

<figure><img src="../.gitbook/assets/image (5).png" alt="" width="346"><figcaption></figcaption></figure>

{% hint style="info" %}
С этого момента остальные кубики относятся для работы задачами и подзадачами, написанных в ProjectMaker.&#x20;

**Особенность задач и подзадач в PM, им нужна регистрация в системе**. Поэтому при запуске, управление пройдет через каждую задачу и подзадачу, после этого система их зарегистрирует и начнет выполнять. Задачи удобнее всего расположить слева, а подзадачи справа.
{% endhint %}

Кубик начинает запуск и подготовку проекта c задачами PM.

<figure><img src="../.gitbook/assets/image (6).png" alt="" width="335"><figcaption></figcaption></figure>

Ядро ezFERM назначает задачу или подзадачу для выполнения.

<figure><img src="../.gitbook/assets/image (7).png" alt="" width="383"><figcaption></figcaption></figure>

После регистрации, имя назначенной задачи появится в переменной “sys\_name\_to\_run”, а тип в “sys\_type\_to\_run”.&#x20;

Задача - ведет к задачам. Подзадача - ведет к подзадачам. Когда задачи и подзадачи выполнены, управление переходит в “Работа завершена”. Тогда шаблон завершает работу.

<figure><img src="../.gitbook/assets/image (9).png" alt="" width="368"><figcaption></figcaption></figure>

Как вы могли понять, если задачи и подзадачи написаны в PM, то они будут выполняться внутри шаблона. Если написаны в VS, то поток зайдет в шаблон, и полностью уйдет в кубик “Проект VS”, то есть в dll файл вашего проекта с задачами.&#x20;

Если вы умеете программировать, то **рекомендуется** писать задачи в VS, работать будет быстрее и все приложение будет отказоустойчивее.

{% hint style="info" %}
* Системные переменные в шаблоне начинаются с sys.&#x20;
* Любое изменение переменных до или во время выполнения вызовет ошибку.
* Любое изменение в структуре шаблона, не описанных в документации вызовет ошибку.
{% endhint %}
