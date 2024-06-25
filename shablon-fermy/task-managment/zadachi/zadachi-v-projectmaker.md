---
description: Методология создания задач в ezFERM внутри ProjectMaker c помощью кубиков.
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Задачи в ProjectMaker

## <mark style="color:blue;">Структура задачи</mark>

{% tabs %}
{% tab title="Кубик начала" %}
<figure><img src="../../../.gitbook/assets/Кубик начала.png" alt="" width="563"><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Тело" %}
<figure><img src="../../../.gitbook/assets/Тело задачи.png" alt="" width="235"><figcaption><p>К примеру пауза или любой другой функционал</p></figcaption></figure>
{% endtab %}

{% tab title="Кубик окончания" %}
<figure><img src="../../../.gitbook/assets/Окончание задачи" alt="" width="563"><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

## <mark style="color:blue;">Подготовка</mark>

Для удобства будем писать подзадачи слева. Удаляем все дефолтные задачи, если имеются, и оставляем только кубики начала и окончания задачи. Каждая задача начинается и заканчивается этими кубиками.

<figure><img src="../../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">Создаем первую задачу</mark>

1. Переименовываем кубик начала задачи, меняем имя задачи внутри кубика.
2. От "Выполнение работы - Задача" пускаем по <mark style="color:green;">**зеленой**</mark> связи к "Задача 1".
3. От "Задача 1" по <mark style="color:green;">**зеленой**</mark> к функционалу задачи/телу.
4. Переименовываем кубик конца задачи, выбираем один из вариантов WorkResult внутри кубика.
5. От кубика конца задачи по <mark style="color:green;">**зеленой**</mark> к  "ezFERM готовит работу".

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">Создаем вторую задачу</mark>

1. От "Задача 1" по <mark style="color:red;">**красной к**</mark> "Задача 2". Каждая новая задача друг к другу по <mark style="color:red;">**красной**</mark>.
2. Все как в первой - переименовываем, добавляем функционал.

<figure><img src="../../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">Создаем последнюю задачу</mark>

1. От "Задача 2" по <mark style="color:red;">**красной к**</mark> "Задача 3". Каждая новая задача друг к другу по <mark style="color:red;">**красной**</mark>.
2. От "Задача 3" по <mark style="color:red;">**красной**</mark> к "ezFERM готовит работу". Последняя задача завершающая связку задач всегда по <mark style="color:red;">**красной**</mark>  к "ezFERM готовит работу".
3. Все как в других задачах, переименовываем, добавляем функционал.

<figure><img src="../../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">Готово</mark>

{% hint style="info" %}
* Все задачи всегда в одной связке друг за другом.
* Количество задач неограниченно.
* Каждой задаче добавляется необходимый вам функционал между кубиками начала и окончания.
* Удалять задачи не обязательно, можно просто отключить задачу в базе на листе "Задачи".
{% endhint %}
