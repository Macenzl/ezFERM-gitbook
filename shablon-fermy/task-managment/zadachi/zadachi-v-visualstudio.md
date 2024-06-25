---
description: Методология создания задач в ezFERM внутри VisualStudio c помощью С#.
---

# Задачи в VisualStudio

## <mark style="color:blue;">Структура задачи</mark>

<figure><img src="../../../.gitbook/assets/Задачи VS.png" alt=""><figcaption></figcaption></figure>

## <mark style="color:blue;">Пишем задачи</mark>

1. Создаем папку "Actions".
2. Добавляем в нее классы, наследуем их от IAction, переименовываем их в имена своих задач.
3. Создаем метод RunAction возвращающий WorkResult.
4. Внутри метода пишем нужный нам функционал.

## <mark style="color:blue;">Готово</mark>

{% hint style="info" %}
* Задачи и подзадачи это всегда классы.&#x20;
* Класс задач наследует интерфейс "IAction".
* Имена классов должны иметь имена ваших задач.&#x20;
* Namespace произвольный, но одинаковый в рамках задач и подзадач.
* ezFERM.API.API дает доступ к instance и ptoject от ZennoPoster и доступ к публичным данным ezFERM.
{% endhint %}

## <mark style="color:blue;">Дополнительная информация по работе в VisualStudio</mark>

{% content-ref url="../../../dopolnitelnye-materialy/manualy/sozdaem-fermu-ot-a-z.md" %}
[sozdaem-fermu-ot-a-z.md](../../../dopolnitelnye-materialy/manualy/sozdaem-fermu-ot-a-z.md)
{% endcontent-ref %}

{% embed url="https://zennolab.atlassian.net/wiki/spaces/RU/pages/1375109121/Visual+Studio" %}
