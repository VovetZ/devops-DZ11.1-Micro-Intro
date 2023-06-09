# Домашнее задание к занятию "Введение в микросервисы"

## Задача 1: Интернет Магазин

Руководство крупного интернет магазина у которого постоянно растёт пользовательская база и количество заказов рассматривает возможность переделки своей внутренней ИТ системы на основе микросервисов. 

Вас пригласили в качестве консультанта для оценки целесообразности перехода на микросервисную архитектуру. 

Опишите какие выгоды может получить компания от перехода на микросервисную архитектуру и какие проблемы необходимо будет решить в первую очередь.

---

## Ответ

Выгоды от перехода на микросервисную архитектуру: 

   - Архитектура. Отдельные компоненты в меньшей степени зависят друг от друга, их можно реализовывать на разных ЯП в зависимости от эффективности конкретного языка при решении конкретной задачи.
   - Масштабирование. Самые необходимые и нужные сервисы можно дополнить и расширить, когда появится такая необходимость. Вся система при этом остается прежней. Это особенно экономически эффективно при использовании облачной инфраструктуры.
   - Деплой. Более точечные релизы, не требующие простоя или перезапуска всей системы. 
   - Отказоустойчивость. При падении одного сервиса, все остальные продолжат работать. Таким образом, неполадки в отдельных сервисах меньше влияют на бизнес-процессы.
   - Гибкость. Возможно опробовать внедрение новых технологий меньшими усилиями. Это а) значительно быстрее, b) при неудаче, проще откатить изменения. Меняя один из сервисов, мы не рискуем работоспособностью всей системы.
   - Простота. Каждый отдельный сервис представляет собой цельную систему, поэтому не нужно разбираться в большом количестве деталей, не касающихся данной конкретной функции. Меньше кода - проще и быстрее разработчикам разобраться, что и как работает. 
    
Проблемы которые необходимо решить:

   - разделение системы на функциональные компоненты для оптимальной эффективности масштабирования и взаимодействия.
   - определение используемого технологического стека.
   - в момент перехода потребуются ресурсы на одновременную поддержку как исходной монолитной системы, так и новой системы на основе микросервисов.  А также (скорее всего) придется обеспечивать их взаимодействие между собой.
   - усложнение процесса разработки. Появление новых сервисов требует привлечения дополнительных сил на их разработку и контроль их взаимодействия с уже имеющимися сервисами


### Как оформить ДЗ?

Выполненное домашнее задание пришлите ссылкой на .md-файл в вашем репозитории.

---
