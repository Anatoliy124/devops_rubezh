# Рубежный тест номер 1
##  Вариант 7
### бессерверные вычисления
Бессеверные вычисления- это когда облочный провайдер предоставляет усугу, где компания может писать и развёртывать код, не беспокоясь о базовой инфраструктуре, то есть компания, которая получает бэкенд-услуги от бессерверного поставщика, платит по факту за используемые ресурсы и не должна резервировать и оплачивать фиксированную пропускную способность или количество серверов, поскольку услуга автоматически масштабируется, вместо того, чтобы платить за фиксированный лимит, ведь обычно это дороже, так как компниии почти всегда берут чуть больше, чтобы приложение не рухнуло. Естественно, для предоставления клиенту бессерверных вычислений используются физические серверы, но разработчикам нет необходимости думать об их конфигурации, производительности, ядрах, памяти и прочем. Можно провести аналогию с тарифным плано мобильного оператора с фиксированным ежемесячным лимитом на тариф, где плата взимается только за каждый фактически использованный байт данных, вместо того как платить за фиксированное колличество байтов.
### Какие серверные службы могут быть представлены бессерверными вычислениями
Большинство бессерверных провайдеров предлагают своим клиентам услуги баз данных и хранилища, у многих есть платформы Function-as-a-Service. FaaS позволяет разработчикам выполнять небольшие фрагменты кода на границе сети. С помощью FaaS разработчики могут создавать модульную архитектуру, делая кодовую базу более масштабируемой, не тратя ресурсы на поддержку бэкенда
### Каковы преимущества бессерверных вычислений
   - Снижение затрат — бессерверные вычисления, как правило, выгодны, поскольку у многих крупных провайдеров облачных серверных услуг пользователь платит за неиспользуемое пространство или время простоя процессора.

  -  Упрощённая масштабируемость — разработчикам, использующим бессерверную архитектуру, не нужно беспокоиться о политиках для масштабирования своего кода. Бессерверный поставщик выполняет все масштабирование по запросу.

  -  Упрощённый внутренний код — с помощью FaaS разработчики могут создавать простые функции, которые независимо выполняют одну задачу, например, выполнение вызова API.

  -  Более быстрый оборот — бессерверная архитектура может значительно сократить время выхода на рынок. Вместо того, чтобы требовать сложного процесса развёртывания для исправления ошибок и новых функций, разработчики могут добавлять и изменять код по частям.

# Рубежный тест номер 2
## Вариант 4
### Способы экономить в облаке
1. Тарифы- нужно рассмотреть ситуации, когда выгоднее фиксированные тарифы, а когда — pay-as-you-go-концепция.
2. Хранение данных в Object Storage- когда приходится записывать терабайты данных, один из вариантов оптимизировать расходы — использовать объектное хранилище Object Storage для определённых типов данных вместо хранения на дисках ВМ. В частности, сервис позволяет сократить затраты на хранение бэкапов, видео- и аудиофайлов.
3. Пиковой нагрузка с автоскейлингом- автоматизация масштабирования в Instance Groups помогает при волатильном спросе на ВМ. Просто настраиваем правила и задаёте условия, и сервис автоматически включает или выключает машины. Снижается риск человеческой ошибки, вероятность что-либо недоглядеть или забыть запустить.
### Разница между использованием по требованию (on demand) и резервацией мощностей (reserved)
on-demand предоставляет мощную гибкость и подходит для краткосрочных задач с переменной нагрузкой, но он подороже. а резёрвед позволяет сэкономить при долгосрочных задачах, но ограничивает гибкость использования ресов. Выбор между  моделями зависит от вида нагрузки, длительности проекта и приоритетов по затратам.
### другие модели использования облака
1. Модель подписки- компания платит за фиксированный срок
2. Shared Tenancy- пользователь делит физические ресурсы с другими пользователями
3. Pay-as-you-go- класика, компания платит только за использованный объем ресурсов
