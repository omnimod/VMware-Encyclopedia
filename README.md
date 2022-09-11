На данной странице приведено краткое описание продуктов и сервисов компании VMware.

Advanced Monitoring powered by Control Up
------------------------------------------------

VMware Advanced Monitoring собирает, анализирует и отображает информацию о работе хостов, виртуальных рабочих столов, серверов Horizon и активных сессиях пользователей. VMware Advanced Monitoring позвляет обнаружить и устранить причины длительного входа пользователя в сессию, определить запущенные приложения, которые создают наибольшую нагрузку на рабочие столы, а также оптимизировать потребление ресурсов для неактивных рабочих столов. 
 
VMware Advanced Monitoring позволяет централизованно запускать произвольные сценарии внутри рабочих столов вручную, или при срабатывании определенного тригера, что позволяет упростить и ускорить выполнение типовых операций по обслуживанию VDI инфраструктуры.

VMware Advanced Monitoring лицензируется по пользователям или конкурентным подключениям и доступен по модели подписки в виде облачного сервиса, а также для установки внутри существующей инфраструктуры.

Описание сценариев использования VMware Advanced Monitoring: https://blogs.vmware.com/euc/2020/09/vmware-advanced-monitoring-for-horizon-powered-by-controlup.html

Видео с демонстрацией возможностей VMware Advanced Monitoring: https://www.youtube.com/watch?v=l1ClNdH76_8 

App Volumes
-----------
App Volumes - ПО для автоматической доставки и обновления приложений на виртуальных рабочих станциях и терминальных серверах. App Volumes поддерживает два варианта доставки приложений: App Stacks и Writable Volumes. App Stacks позволяет администраторам упаковать приложение в контейнере (виртуальном диске VMDK или VHD), который затем можно подключить к множеству виртуальных машин или физических ПК без необходимости устанавливать приложения в каждой ОС по отдельности. Writable Volumes подключает к ВМ постоянный диск для сохранения изменения гостевой ОС. На постоянный диск записываются данные приложений, документы и настройки пользователей, которые остаются даже в случае удаления или отката изменений в самих ВМ.

Основные функциональные возможности и преимущества использования App Volumes:
 - Доставка, установка и удаление приложений для виртуальных рабочих станций или терминальных серверов в реальном времени.
 - Назначение приложений на объект компьютера, пользователя, группу или организационное подразделение в Active Directory. При назначении на пользователя или группу пользователей, App Volumes автоматически подключит и зарегистрирует приложение в гостевой ОС момент входа пользователя в систему.
 - Поддержка временных (non-persistent) виртуальных рабочих станций (Instant Clones и Linked Clones). App Volumes позволяет стандартизировать эталонные образы ВМ и уменьшить их количество.
 - Уменьшение требований к дисковому пространству за счет подключения одного App Stack к множеству ВМ.
 - Возможность управления пользовательским окружением с помощью Dynamic Environment Manager. Лицензия на DEM входит в состав App Volumes. DEM позволяет настраивать рабочие столы и приложения, с которыми работают пользователи, а также синхронизировать настройки с файловым сервером без использования перемещаемых профилей Windows.

Дополнительная информация о App Volumes: https://www.vmware.com/files/ru/pdf/appvolumes/vmware-appvolumes-datasheet.pdf

Короткое видео о App Volumes: https://www.youtube.com/watch?v=iDidOZKqLOk

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме App Volumes:
 - HOL-2251-01-DWS - VMware Horizon - Getting Started with App and Desktop Virtualization (https://labs.hol.vmware.com/HOL/catalogs/lab/10192https://labs.hol.vmware.com/HOL/catalogs/lab/10192)

App Volumes входит в состав лицензии VMware Horizon Enterprise, Horizon Apps Universal Subscription и Horizon Universal Subscription, а также может приобретаться отдельно по количеству подключений (Concurrent License) или по пользователям (Named User License). App Volumes доступен в следующих редакциях:
 - Standard – предоставляет базовые возможности по доставке приложений (App Stack и Writable Volume) для виртуальных сред на базе VMware Horizon, Citrix XenApp/XenDesktop или Microsoft RDS, а также позволяет управлять пользовательским окружением при помощи Dynamic Environment Manager.
 - Advanced –  добавляет интеграцию с ThinApp благодаря чему приложения могут упаковываться в изолированные контейнеры и доставляться на рабочие станции пользователей при помощи App Stacks в реальном времени. 

Дополнительная информация приведена по ссылке: https://www.vmware.com/products/appvolumes.html

Bitfusion
---------
Bitfusion - технология для ускорения AI/ML вычислений, использующих библиотеки CUDA и TensorFlow. Bitfusion перехватывает и перенаправляет по сети CUDA запросы от приложений, запускаемых на клиентских устройствах, на серверы с установленными ускорителями для проведения расчетов. Bitfusion предоставляет следующие возможности:
- Поддержка различных типов клиентских устройств: виртуальные машины, физические рабочие станции и контейнеры.
- Разделение одного ускорителя между несколькими клиентами. Bitfusion позволяет установить ограничение на объем памяти ускорителя, доступной клиентскому приложению.
- Автоматический выбор свободных ускорителей из серверного пула, возможность выделения клиентскому приложению нескольких ускорителей с одного сервера.
- Интеграция с консолью vSphere Client для первичной настройки и мониторинга клиентов, серверов и текущей утилизации ускорителей.

Bitfusion используется в связке с vSphere Enterprise Plus и лицензируется по числу физических процессоров серверов виртуализации (https://kb.vmware.com/s/article/80353).

Технический проспект по Bitfusion: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/solutionbrief/vmw-bitfusion-solution-brief.pdf 

Видео с демонстрацией работы Bitfusion: https://www.youtube.com/watch?v=BAlYp-XtRnw 

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме Bitfusion:
- HOL-2247-02-ISM - Using Bitfusion GPU virtualization in vSphere (https://labs.hol.vmware.com/HOL/catalogs/lab/10897)

Bitnami Application Catalog / VMware Cloud Marketplace
------------------------------------------------------
VMware Cloud Marketplace - это открытый репозиторий Open Source приложений для развертывания в виртуальных инфраструктурах, облачных сервисах или контейнерах.

Предоставляет доступ к более чем 100 приложений (СУБД, серверы приложений, веб-серверы, CRM системы и т.д.). Приложения подготовлены к развертыванию в виде пакетов, образов ВМ или контейнеров для:
- Платформ виртуализации VMware vSphere, VMware Workstation.
- Публичных облаков на базе vCloud Director
- Публичных облаков VMware Cloud on AWS
- Публичных облаков Amazon Web Services, Microsoft Azure, Google Cloud Platform.
- Инфраструктур контейнеров Docker, Kubernetes, Enterprise PKS.
- Операционных систем Windows, Linux и, MacOS.

Преимущества использования репозитория:
- Доверенный, защищенный репозиторий приложений.
- Интеграция со средствами разработки и развертывания приложений: kubeapps, vCenter Content Library и др.
- Быстрая загрузка и установка приложений.
- Оперативное обновление приложений/выпуск новых дистрибутивов приложений.

Дополнительная информация приведена по ссылке: https://marketplace.cloud.vmware.com

Carbon Black Cloud Endpoint
----------------------------------
Carbon Black Cloud Endpoint - это облачный сервис, обеспечивающий защиту конечных устройств от вредоносного ПО и атак злоумышленников.

Cloud Endpoint доступен в трех основных редакциях: Standard, Advanced Enterprise:
- Standard включает в себя антивирусную защиту нового поколения (Next Generation Antivirus) и базовые функции по обнаружению угроз (EDR). CB Cloud Endpoint Standard использует механизмы поведенческого анализа и репутационные фильтры для обнаружения вредоносных процессов на компьютерах и серверах. Поддерживаются ОС семейства Microsoft Windows и Apple MacOS. Анализ процессов выполняется в облаке (CB Predictive Security Cloud), благодаря чему агент CB требует меньших вычислительных ресурсов по сравнению с типовыми антивирусными агентами, а также позволяет оперативно определять и устранять новые угрозы, эксплуатирующие уязвимости нулевого дня.
- Редакция CB Cloud Endpoint Advanced включает в себя средство инвентаризации Carbon Black Audit and Remediation (ранее LiveOps). С помощью CB Audit and Remediation администраторы ИБ в режиме реального времени могут получать информацию о защищаемых устройствах: версиях операционных систем и прикладного ПО, установленных обновлениях, параметрах реестра и настройках системы, а также обнаруживать артефакты, влияющие на безопасность конечных устройств: файлы, цифровые сертификаты, пароли, ключи безопасности и пр. CB Audit and Remediation поддерживает ОС Windows, Linux и MacOS.
- В редакции Enterprise добавляется Carbon Black Enterprise EDR (ранее CB ThreatHunter). CB Enterprise EDR предоставляет функции сбора и хранения событий ИБ с конечных устройств. Enterprise EDR записывает действия пользователей и ПО и предоставляет средства визуализации собранных данных, позволяющих обнаруживать потенциальные угрозы ИБ. Благодаря функциям исторического анализа, администраторы ИБ могут определить источник и способ распространения вредоносного ПО или атаки злоумышленника и устранить уязвимость.

Cloud Endpoint предоставляется по моделям подписки на 1, 3 или 5 лет, и лицензируется по числу защищаемых устройств: физических ПК, серверов или виртуальных машин.

Дополнительная информация приведена по ссылкам.
- Carbon Black Endpoint Solutions FAQ: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/workspace-one/vmw-carbon-black-endpoint-solutions-faq.pdf
- VMware Carbon Black Cloud Endpoint Standard Datasheet: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/docs/vmwcb-datasheet-endpoint-standard.pdf 
- VMware Carbon Black Audit and Remediation: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/docs/vmwcb-datasheet-audit-remediation.pdf
- VMware Carbon Black Enterprise EDR: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/docs/vmwcb-enterprise-edr-datasheet.pdf

Лабораторные работы на сайте https://labs.hol.vmware.com по теме Carbon Black:
- Carbon Black Endpoint Standard Simulation (HOL-2236-01-ISM) (https://labs.hol.vmware.com/HOL/catalogs/lab/10096)

Cloud Director
---------------------
Cloud Director – это ПО для создания публичного IaaS сервиса, которое могут использовать организации-провайдеры для предоставления услуг хостинга конечным заказчикам. Cloud Director доступен провайдерам в рамках программы VSPP (VMware Service Provider Program).

Дополнительные материалы по Cloud Director: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/vcloud/vmware-vcloud-director-data-sheet.pdf

Лабораторные работы на сайте https://labs.hol.vmware.com по теме Cloud  Director:
- Using VMware Cloud Director and VMware Cloud Foundation on VxRail (HOL-2260-01-ISM) (https://labs.hol.vmware.com/HOL/catalogs/lab/9387)

Cloud Availability
--------------------------
VMware Cloud Availability - сервис катастрофоустойчивой защиты для ВМ, работающих на платформе виртуализации vSphere или в публичных облаках сервис провайдеров (VMware Service Provider Program).
Возможности vCAv:
- Настройка защиты ВМ в различных сценариях (On Premise <-> Cloud и Cloud <-> Cloud), управление защитой и восстановлением ВМ из единой консоли.
- Интеграция консоли vCAv в интерфейс vSphere Client и vCloud Director, поддержка функций Self-Service для аварийного восстановления или миграции ВМ.
- Встроенный механизм репликации vSphere Replication с минимальным RPO в 5 минут.
- Функция тестового восстановления для проверки корректности DR плана и репликации ВМ.

Основные сценарии использования CAv:
- Миграция ВМ из on-premise инфраструкруктуры в публичное облако и обратно, миграция ВМ между публичными облаками различных провайдеров. vCAv позволяет оперативно перенести ВМ между разными площадками с минимальными трудозатратами и минимальным простоем.
- Реализация Disaster Recovery сценария для защиты ВМ. vCAv обеспечивает репликацию и автоматизированное восстановление ВМ на резервной площадке/в облаке. vCAv поддерживает смену сетевых настроек при восстановлении ВМ.

CAv доступен в качестве дополнительной услуги в облаках сервис провайдеров VSPP.

Дополнительная информация о vCloud Availability приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/vcloud/vmw-vcloud-availability-3.0-datasheet.pdf

Короткое видео по теме: https://www.youtube.com/watch?v=H3h78GjqpHE

Лабораторные работы на сайте https://labs.hol.vmware.com по теме vCloud Availability:
- Mware Cloud Provider Platform - DR and Migration using VMware Cloud Director Availability (HOL-2282-01-HBD) (https://labs.hol.vmware.com/HOL/catalogs/lab/12207)

Cloud Disaster Recovery
------------------------------
VMware Cloud Disaster Recovery - это облачный сервис, обеспечивающий защиту и аварийное восстановление ВМ на VMware Cloud on AWS. VMware Cloud DR может использоваться как для защиты нагрузок, работающих внутри ЦОД организации, так и в облаках VMware Cloud on AWS, работающих в разных регионах.

Преимущества VMware Cloud DR:
- Повышение готовности. VMware Cloud DR упрощает развертывание и обслуживание резервной площадки благодаря использованию стандартного набора технологий для запуска ВМ, хранения данных и обеспечения сетевых сервисов, что позволяет администраторам, имеющим опыт в эксплуатации продуктов vSphere, vSAN и NSX в on-prem инфраструктуре, использовать те же инструменты и навыки для управления облаком.
- Уменьшение ошибок и влияния человеческого фактора. VMware Cloud DR имеет встроенные механизмы проверки здоровья компонентов, тестирования аварийного восстановления и создания отчетов о работе инфраструктуры.
- Снижение совокупной стоимости владения. VMware Cloud DR предоставляется по модели подписки и не требует предварительного развертывания всех хостов виртуализации. Требуемые ресурсы могут быть выделены из облака в момент восстановления, без необходимости оплачивать их, пока они не требуются для запуска нагрузок.

Дополинтельная информация о VMware Cloud DR доступна по ссылке: https://www.vmware.com/products/cloud-disaster-recovery.html

Видео о принципах работы VMware Cloud DR: https://www.youtube.com/watch?v=Yz9v3C3_6WY 

Cloud Foundation
-----------------------
VMware Cloud Foundation – стек продуктов для построения частного облака.  Cloud Foundation включает в себя ПО для виртуализации серверов (vSphere), построения программно-определяемого хранилища (vSAN) и сетевой инфраструктуры (NSX), централизованного управления и мониторинга всей инфраструктуры (vRealize Suite). Также в состав Cloud Foundation входит SDDC Manager, который выполняет централизованное развертывание и настройку всех необходимых компонентов  программного ЦОД в соответствии с рекомендациями VMware, а также занимается их обновлением. SDDC Manager решает задачи по автоматическому развертыванию программно-определяемой инфраструктуры и частного облака, включая создание и настройку кластеров виртуализации vSphere, развертывание и конфигурирование компонентов. SDDC Manager обеспечивает централизованное автоматическое обновление всех компонентов инфраструктуры: серверов ESXi, служебных ВМ vCenter Server, ESXi, PSC, vRealize Suite, NSX-T, NSX for vSphere и vRealize Suite Lifecycle Manager. Видео с демонстрацией возможностей SDDC Manager: https://www.youtube.com/watch?v=EG6jnGyJXyo 

Cloud Foundation доступен в нескольких редакциях и лицензируется по числу физических процессоров. Информация о составе и функциональных возможностях Cloud Foundation приведена по ссылке: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/cloud-foundation/vmw-vcf-4-edition-matrix.pdf

Для всех редакций VMware Cloud Foundation кроме Started доступна подписка Tanzu Add-On для запуска контейнеризованных приложений на базе Kubernetes. Заказчики могут выбирать один из двух вариантов развертывания Kubernetes: Hybrid Infrastructure Services и Tanzu Kubentes Grid.
 
Hybrid Infrastructure Services (ранее известный как Pacific) позволяет запускать контейнеры Kubernetes непосредственно на инфраструктуре vSphere с минимальными накладными расходами и с возможностью централизованного управления кластерами и контейнерами Kubernetes из консоли vSphere. Данный вариант предназначен для запуска контейнеров в производственной среде, в инфраструктурах, где требуется запускать контейнеры вместе с ВМ, а также если требуется обеспечить максимальную безопасность и производительность контейнерных приложений. Tanzu Kubentes Grid – решение по запуску кластера Kubernetes внутри гостевых ВМ. TKG предназначается для сред разработки и тестирования, когда требуется развернуть upstream версию Kubernetes.
 
Видео с демонстрацией возможностей Hybrid Infrastructure Services: https://www.youtube.com/watch?v=l7NY-fVRRVE 

Дополнительная информация о Cloud Foundation: https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/datasheet/products/vmware-cloud-foundation-datasheet.pdf
 
Видео с демонстрацией быстрого развертывания нового программно-определяемого ЦОД и частного облака с помощью Cloud Foundation: https://www.youtube.com/watch?v=EG6jnGyJXyo 
 
Лабораторные работы на сайте https://labs.hol.vmware.com  по теме Cloud Foundation:
- VMware Cloud Foundation - SDDC Manager Operations (HOL-2244-01-ISM) (https://labs.hol.vmware.com/HOL/catalogs/lab/10817)

CloudHealth by VMware / VMware Aria Cost powered by CloudHealth
---------------------
Aria Cost powered by CloudHealth (ранее CloudHealth by VMware) – облачный сервис для оценки стоимости и оптимизации затрат в различных публичных облачных сервисах (AWS, Microsoft Azure, Google Cloud Platform).

На сайте доступна 30-дневная тестовая версия: https://cloudhealth.vmware.com/

Dynamic Environment Manager
---------------------------
Dynamic Environment Manager управляет пользовательским окружением - позволяет выполнять настройки операционных систем и приложений и синхронизировать их в реальном времени между различными физическими, виртуальными рабочими станциями, а также терминальными серверами, с которыми работают пользователи. Также DEM управляет принтерами, сетевыми дисками, перенаправляемыми папками, позволяет запускать скрипты и выполнять различные настройки без необходимости использования групповых политик Microsoft Windows.

DEM доступен в двух редакциях: Standard и Enterprise. DEM Standard входит в состав любой редакции Horizon. DEM Enterprise входит в состав Horizon Enterprise, а также App Volumes.
 
DEM Standard поддерживает следующие функции:
- Personalization
- Folder Redirection
- ConditionsSets
- Printer Mapping
- Logon/logoff Tasks
- Optional Tools (Application Profiles, Helpdesk Support Tool)

DEM Enterprise поддерживает:
- All DEM Standard Functionality
- ADMX-Based Settings
- Application Blocking
- Environment Variables
- File Type Associations
- Files and Folders
- Privilege Evaluation
- Registry Settings
- Shortcuts
- SyncTool
- Triggered Tasks
- Windows Settings
- User-based and computer-based Horizon Smart Policies

Дополнительная информация о DEM: https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/user-environment-manager/vmware-user-environment-mngr-datasheet.pdf

Видео: https://www.youtube.com/watch?v=kX66x-xPR5U

Harbor
------
Harbor - это реестр корпоративного уровня для хранения образов контейнеров. Harbor позволяет управлять и распространять образы для контейнерных сред Docker и Kubernetes. Harbor - решение с открытым исходным кодом, доступное для загрузки и использования без необходимости приобретения дополнительных лицензий.

Harbor предоставляет следующие возможности:
- Графический Web интерфейс для управления реестром, поддержка REST API для автоматизации и интеграции со сторонними системами.
- Интеграция с LDAP каталогами, возможность аутентификации с использованием корпоративных учетных записей Microsoft Active Directory.
- RBAC модель доступа, поддержка нескольких типов ролей (Guest, Developer, Admin), имеющих разные уровни доступа.
- Репликация образов между репозиториями Harbor.
- Сканирование образов, хранящихся в реестре, на наличие известных уязвимостей (используются данные из общедоступных источников: Debian Sec Bug Tracker, Ubuntu CVE Tracker, Red Hat Security Data, Oracle Linux Sec Data, Alphine SecDB и NIST NVD).
- Валидация и подписывание образов, загружаемых из реестра (Notary).
- Ведение журналов аудита событий и выполняемых действий.

HCX
---
VMware HCX - сервис, предназначенный для создания гибридных облачных сред, который позволяет мигрировать нагрузки между несколькими ЦОД и публичными облачными сервисами. HCX доступен в двух редакциях: Advanced и Enterprise.

Основные сценарии использования HCX:
- Миграция ВМ между ЦОД/облаками. HCX обеспечивает потоковую миграцию (Bulk Migration) большого количества ВМ с минимальным простоем, используя функции репликации данных и WAN-оптимизации для снижения требований к каналам. Для критичных ВМ поддерживается миграция без прерывания сервиса (облачный vMotion). В HCX Enterprise доступна функция Replication assisted vMotion, сочетающая преимущества потоковой и непрерывной миграции ВМ.
- Организация L2VPN туннелей для обеспечения сетевой связности между ВМ на разных площадках и сохранения сетевых настроек ВМ при миграции.
- Обеспечение катастрофоустойчивой защиты виртуальной инфраструктуры. Для ВМ может быть настроена периодическая репликация в облако/удаленный ЦОД с возможностью восстановления ВМ в случае аварии на основной площадке. В HCX Enterprise поддерживается интеграция с VMware SRM для автоматизации процедуры аварийного восстановления.
- Перенос ВМ с других платформ виртуализации: Microsoft Hyper-V и KVM (требуется HCX Enterprise).

HCX Advanced доступен по модели подписки, в облаках сервис-провайдеров, работающих по программе VMware Service Provider Program, а также в облаке VMware Cloud on AWS. Также HCX Advanced входит в состав NSX Data Center Enterprise Plus. HCX Enterprise доступен в качестве Add-On позиций к NSX DC Enterprise Plus и лицензируется по процессорам серверов виртуализации.
 
Дополнительная информация по HCX доступна по ссылке: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/nsx/vmware-hcx-data-sheet.pdf 

Видео с описанием возможностей HCX: https://www.youtube.com/watch?v=edOReTjecPk
Видео демонстрации работы HCX: https://www.youtube.com/watch?v=4kdoOstLuQg 

Лабораторные работы на сайте https://labs.hol.vmware.com по теме VMware HCX:
- VMware HCX - Getting Started with Cross-Cloud Mobility (HOL-2281-01-HBD) (https://labs.hol.vmware.com/HOL/catalogs/lab/10288)

Horizon
-------
VMware Horizon - решение, позволяющее развернуть инфраструктуру виртуальных рабочих станций (VDI) в организациях.

Основные сценарии использования Horizon:
- Обеспечение мобильности сотрудников. Пользователи могут подключаться к своим виртуальным станциям из офиса или из дома и работать со своими приложениями и получать доступ к своим данным с любого устройства (ПК, планшет, мобильный телефон, смартфон).
- Упрощение поддержки рабочих мест. Horizon позволяет сократить трудозатраты на развертывание и обновление рабочих мест пользователей за счет использования технологии Instant Clone, позволяющей создать сотни виртуальных десктопов из единого образа за минуты, и средств автоматической доставки приложений и настроек пользователей (App Volumes и Dynamic Environment Manager).
- Повышение безопасности и доступности рабочих мест. В VDI инфраструктурах все данные хранятся в ЦОД и для них гораздо проще обеспечивать резервирование и хранение в соответствии с требованиями ИБ. Для виртуальных рабочих станций реализуется катастрофоустойчивая защита на случай аварии.
- Централизация ИТ-сервисов. Для большой филиальной сети можно полностью заменить ИТ инфраструктуру в филиалах, заменив рабочие места пользователей на тонкие клиенты, и предоставив пользователям производительный и безопасный доступ к ИТ-сервисам в ЦОД. 

VMware Horizon лицензируется по числу пользователей (Named User) или числу одновременных подключений (Concurrent) и доступен в виде постоянных (perpetual license) лицензий или по подписке (subscription / term license).

Perpetual лицензии доступны в трех редакциях: Standard, Advanced и Enterprise:
- Standard содержит лицензии на брокер подключений и ПО виртуализации vSphere Desktop и vCenter Server Desktop, необходимые для построения VDI инфраструктуры.
- В Advanced редакции Horizon может публиковать приложения с терминальных серверов Microsoft RDS, а также предоставлять пользователям доступ к каталогу с опубликованными приложениями и сервисами.
- В редакции Enterprise добавлены средства Dynamic Environment Manager Enterprise и App Volumes, упрощающие развертывание и управление виртуальными рабочими станциями в крупных организациях, а также поддерживается работа с виртуальными рабочими столами и терминальными приложениями на Linux.

Дополнительная информация о VMware Horizon приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/horizon/vmware-horizon-8-datasheet.pdf 

Сравнение функциональных возможностей редакций и подписок VMware Horizon: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/horizon/vmware-horizon-perpetual-feature-comparison.pdf и https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/horizon/vmware-horizon-subscription-feature-comparison.pdf 

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме DEM:
	• HOL-2251-01-DWS - VMware Horizon - Getting Started with App and Desktop Virtualization (https://labs.hol.vmware.com/HOL/catalogs/lab/10192)

Horizon Apps
------------
Horizon Apps - этот продукт построенный на базе Horizon (используются те же компоненты), в задачи которого входит организация доступа к терминальным серверам и публикация терминальных приложений без предоставления выделенных виртуальных рабочих столов (без VDI).

Horizon Apps доступен в двух редакциях: Standard и Advanced. Advanced редакция включает в себя расширенные функциональные возможности: vSphere Desktop, vCenter Desktop, Instant Clones, App Volumes, Dynamic Environment Manager. Horizon Apps может лицензироваться по пользователям (Named User) или конкурентным/одновременным подключениям (Concurrent).

Дополнительная информация по Horizon Apps:
https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/product/horizon-apps/vmware-horizon-apps-datasheet.pdf 

Руководство по лицензированию и составу редакций Horizon Apps: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/horizon/vmware-horizon-pricing-packaging-guide.pdf 

Horizon Cloud
--------------------
VMware Horizon Cloud - это облачный сервис, предоставляющий доступ к виртуальным рабочим столам и терминальным приложениям.

К плюсам VMware Horizon Cloud относится:
- Переход к OPEX модели затрат за счет универсальной подписки – Horizon Universal License. Horizon Universal License позволяет использовать VDI и терминальные сервисы внутри организации и в публичных облаках. Модель подписки также позволяет легко масштабировать сервис удаленных рабочих столов, начав с небольшой группы пользователей, и затем увеличивая или уменьшая кол-вол подписок по мере необходимости.
- Снижение капитальных затрат за счет работы Horizon Cloud с публичными облаками VMware Cloud on AWS, Microsoft Azure и IBM Cloud. Служебные компоненты, виртуальные машины пользователей и терминальные серверы располагаются в публичных облаках и позволяют заказчикам обойтись без собственных ЦОД и серверного оборудования.
- Упрощение развертывания и обслуживания инфраструктуры. Horizon Cloud автоматически создает и удаляет рабочие столы и терминальные серверы в зависимости от количества активных подключений, что позволяет снижать затраты на вычислительные ресурсы в облаках и быстрее предоставлять пользователям доступ к своим рабочим столами.
- Поддержка производительного и безопасного протокола Blast. Пользователи могут подключаться к своим рабочим столам из корпоративной сети или напрямую из Интернет с любого клиентского устройства: компьютера, тонкого клиента, мобильного телефона. Horizon Cloud поддерживает работу с принтерами, сканерами, USB накопителями, гарнитурами и web-камерами. Пользователи могут работать с приложениями и периферийными устройствами в VDI или терминальных серверах также, как если бы они работали на локальных компьютерах.
 
Стоимость владения Horizon Cloud в облаке складывается из стоимости подписки Horizon Universal License и стоимости аренды вычислительных ресурсов. Horizon Universal License лицензируются по числу пользователей (Named User) или числу одновременных подключений (Concurrent). Вариант с Concurrent выгоднее, если пользователи работают в несколько смен, или одновременно работает менее 50% пользователей. Доступны варианты приобретения подписок с ежемесячной оплатой и в виде предоплаченных контрактов на 1, 2, 3, 4 и 5 лет.
 
Дополнительная информация:
	1. Сравнение различных вариантов использования Horizon и Horizon Cloud: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/horizon/vmware-horizon-cloud-and-horizon7-comparison-matrix.pdf 
	2. Брошюра о VMware Horizon Cloud on AWS: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/vmw-deploy-horizon-seven-on-vmware-cloud-on-aws.pdf
	3. Брошюра о VMware Horizon Cloud on Azure: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/horizon/vmw-horizon-cloud-on-microsoft-azure-datasheet.pdf
	4. Видео с демонстрацией работы Horizon Cloud Service on Microsoft Azure: https://www.youtube.com/watch?v=XPl_vgP1Vmc

NSX Advanced Load Balancer
--------------------------
NSX Advanced Load Balancer – решение по балансированию и публикации доступа для высоконагруженных приложений. 
 
Основные преимущества NSX Advanced Load Balancer:
- Снижение затрат на обслуживание благодаря развертыванию, управлению и обновлению инфраструктуры балансировщиков из единой консоли управления.
- Различные варианты развертывания: физические (bare metal) и виртуальные балансировщики, балансировщики в контейнерах и в публичных облачных сервисах.
- Широкие функциональные возможности: Active-Active балансирование, GSLB, Web Application Firewall, Application Performance Monitoring, Autoscaling и многое другое.
- Интеграция с различными программно-определяемыми сетевыми решениями (VMware NSX, Cisco ACI/APIC, Nuage VSP, Juniper Contrail), ПО автоматизации (Ansible, Terraform, Swagger, Python SDK, Go SDK) и мониторинга (Splunk, Cisco Tetration, Cisco AppDynamics, Graphite, Datadog, Logstash, Elasticsearch, InfluxDB, Syslog, Prometheus, Zabbix).

NSX Advanced Load Balancer доступен для приобретения в виде постоянных лицензий или по подписке.

Дополнительная информация o NSX Advanced Load Balancer: https://info.avinetworks.com/hubfs/Avi_Website_Resource_Center/avi-vantage-platform-data-sheet.pdf

Видео с демонстрацией работы Advanced Load Balancer: https://www.youtube.com/watch?v=9h5mpJ7EoWw

Лабораторные работы на сайте https://labs.hol.vmware.com по теме VMware HCX:
- VMware NSX Advanced Load Balancer (Avi Networks) - Getting Started ( HOL-2337-01-NET) (https://labs.hol.vmware.com/HOL/catalogs/lab/11980)

NSX Cloud
---------
NSX Cloud - решение по организации сетевой связности и гетерогенной сетевой инфраструктуры для виртуальных нагрузок, размещаемых в публичных облаках Amazon Web Services и Microsoft Azure.

NSX Cloud предоставляет следующие функциональные возможности для публичных облаков:
- Управление сетевой инфраструктурой нескольких облаков из единой консоли.
- Маршрутизация, балансирование нагрузки и обеспечение сетевой связности для ВМ.
- Микросегментация сетевого трафика. Интеграция со сторонними решениями защиты для дополнительной инспекции трафика (service insertion).
- Построение Site-to-Site VPN для организации сетевой связности между несколькими площадками

NSX Cloud входит в состав NSX Data Center в редакции Advanced или Enterprise Plus и лицензируется по числу виртуальных процессоров ВМ, размещенных в публичном облаке.

Дополнительная информация о NSX Cloud приведена по ссылке: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/nsx/vmware-nsx-cloud-product-package-data-sheet.pdf

На сайте https://labs.hol.vmware.com доступны лабораторные работы по теме NSX Cloud:
- NSX Cloud Consistent Networking and Security across Enterprise, AWS & Azure Lightning Lab (HOL-2227-91-ISM) (https://labs.hol.vmware.com/HOL/catalogs/lab/11145)

NSX
---
NSX  позволяет построить программно-определяемую сеть (SDN), работающую поверх различных виртуальных инфраструктур (VMware vSphere, KVM) и облачных сред (Amazon Web Services, Microsoft Azure, VMware Cloud). С помощью NSX возможно реализовать все необходимые сетевые функции: коммутацию, маршрутизацию, межсетевое экранирование, балансирование нагрузки, VPN и мониторинг сети программными средствами без использования специализированного сетевого оборудования. NSX позволяет унифицировать сетевую инфраструктуру и снизить затраты на её обслуживание, обеспечить необходимый уровень производительности сетевой фабрики, решив проблему узких мест, а также повысить скорость внесения изменений за счет встроенных средств автоматизации.

Основные сценарии использования NSX:
- Обеспечение безопасности за счет микросегментации сети. NSX предоставляет функции распределенного L2-L4, L7 межсетевого экрана, который может фильтровать весь трафик между конечными узлами в сети: ВМ, физическими серверами, контейнерами без необходимости выносить их в отдельные сетевые сегменты, а также позволяет перенаправлять трафик для дополнительного анализа на устройства безопасности сторонних производителей (service chaining).
- Построение распределенной сетевой инфраструктуры между несколькими ЦОД или публичными облаками для сценариев катастрофоустойчивой защиты и для создания гибридных облачных сред. NSX позволяет реализовать распределенную сетевую фабрику (L2 overlay сети, маршрутизацию, МСЭ), а также автоматически переносить сетевые сервисы на резервную площадку при аварии на основной площадке.
- Автоматизация инфраструктуры. NSX интегрируется с различными системами управления конфигурациями и порталами самообслуживания и позволяет быстро развертывать требуемую сетевую инфраструктуру, например, для задач тестирования и разработки, без необходимости внесения изменений в физическую сеть.
 
NSX доступен в трех основных редакциях: Professional, Advanced, Enterprise Plus.
- В редакции Professional предоставляет базовые возможности по виртуализации сетевых функций, такие как создание overlay сетей и маршрутизация трафика, микросегментации трафика (L2-L4 Firewall) и созданию VPN (IPSec VPN, Client SSL VPN, L2 VPN).
- В Advanced добавляются функции L7 фильтрации трафика, балансировки сетевой нагрузки (L4-L7 балансировщик), интеграции с публичными облачными сервисами, а также перенаправление трафика на сторонние устройства защиты, предоставляемые партнерами (Palo-Alto Networks, Check Point, Fortinet и другие).
- Enterprise Plus предоставляет возможности по расширенному мониторингу и траблшутингу виртуальной сети с помощью vRealize Network Insight Advanced, созданию гибридных облачных сред средствами VMware HCX Advanced и объединению нескольких инсталляций NSX Data Center для централизованного управления (Federation).
 
Для редакций Advanced и Enterprise Plus также доступен сервис IDS/IPS в виде дополнительной подписки.

Описание функциональных возможностей и сравнение редакций NSX доступно по ссылке: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/nsx/vmware-nsx-datasheet.pdf

Обзорные видео по NSX:
https://www.youtube.com/watch?v=AUbMqcIAg1g
https://www.youtube.com/watch?v=L_QtlSXaxkE

Демо ролики по NSX: https://www.regalixdigital.com/nsx-2018/
 
Лабораторные работы на сайте https://labs.hol.vmware.com по теме VMware NSX:
- NSX Distributed Firewall Lightning Lab (HOL-2226-91-SEC) (https://labs.hol.vmware.com/HOL/catalogs/lab/10959)

NSX Network Detection and Response
----------------------------------
NSX Network Detection and Response предназначен для определения и предотвращения сетевых атак со стороны злоумышленников и вредоносного ПО, которые не могут быть заблокированы обычными межсетевыми экранами L4-L7. NSX NDR включает в себя компоненты для обнаружения вторжений IDS/IPS, определения вредоносного трафика и анализа вредоносных приложений внутри песочницы. NSX NDR позволяет контролировать как north/south трафик из/в периметровой сети, так и трафик внутренней сети.

Видео с описанием принципа работы NDR: https://www.youtube.com/watch?v=lkw2IQASIdQ
Демонстрация работы продукта: https://www.youtube.com/watch?v=UWvbS1E2r9I

Дополнительная информация о NSX Network Detection and Response: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/NDR-Solution.pdf

NSX Security
------------
NSX Security - отдельный продукт, строящийся на компонентах NSX, нацеленный на обеспечение безопасности виртуальной инфраструктуры. В состав NSX Security входят:
- NSX Distributed Firewall – распределенный файрвол, работающий на уровне гипервизора и позволяющий обеспечить L4-L7 stateful фильтрацию East-West трафика на базе централизованных политик безопасности и реализовать микросегментацию внутри зон безопасности. Можно использовать для защиты нагрузок любого типа: ВМ, контейнеры, физические серверы.
- NSX Distributed IDS/IPS – распределенная система обнаружения/предотвращения вторжений, работающая на уровне гипервизора, осуществляющая сигнатурный анализ East-West трафика, в том числе и внутри зон безопасности без необходимости перенастройки сети и дублирования сетевого трафика. Можно использовать для защиты нагрузок в среде виртуализации и в перспективе физических серверов.
- NSX Intelligence – система аналитики, позволяющая на практике перейти к модели Zero Trust за счет автоматизации процесса описания существующих взаимодействий, даже внутри зон безопасности (правила для NSX Distributed Firewallгенерируются автоматически при помощи данной системы)
- NSX Gateway Firewall – файрвол периметра, в форм-факторе ВМ или физического сервера с  L4-L7 stateful фильтрацией, фильтрацией URL и т д, позволяющий осуществлять фильтрацию трафика на границе сети или между зонами безопасности. Не требует специализированного «железа», работает на серверах x86 архитектуры, поддерживая высокий уровень взаимозаменяемости аппаратных компонентов внутри ИТ-инфраструктуры. Можно использовать для защиты виртуальных нагрузок или физических серверов.
- vRealize Network Insight – зонтичная система мониторинга, которая позволяет проводить быструю диагностику на стыках между виртуальной и физической инфраструктуры, и профилирует сетевые взаимодействия между информационными системами внутри ЦОД, используя netflow. Можно использовать для мониторинга виртуальной и физической инфраструктуры и получения полной видимости за сетевыми взаимодействиями внутри и между зонами безопасности.
 
NSX Distributed IDS/IPS и NSX Gateway Firewall продаются по модели подписки.

SD-WAN
------
SD-WAN – это решение, обеспечивающее построение надежных каналов передачи данных между филиалами, ЦОД и публичными облаками. SD-WAN представляет собой программно-аппаратный комплекс, который использует пограничные устройства (SD-WAN Edge), устанавливаемые в филиалах и ЦОД, а также консоль управления SD-WAN Orchestrator для централизованного управления и мониторинга пограничных устройств. По сравнению с традиционными подходами к построению WAN сетей SD-WAN предоставляет следующие преимущества:
- Построение надежных каналов передачи данных. Для организации связи между Edge устройствами автоматически строится туннелированное соединение, которое задействует все имеющиеся каналы (WAN, WWAN, MPLS) для передачи данных. В случае ухудшения параметров одного канала (увеличения задержек, появления jitter, потери пакетов), Edge устройства запускают механизмы коррекции, обеспечивая заданный уровень сервиса для приложений. SD-WAN позволяет настраивать требования к доступности, производительности для отдельных приложений. Например, для трафика Skype for Business применять одни настройки и настраивать более высокий приоритет, а для трафика социальных сетей – другие.
- Снижение стоимости владения. Edge устройства доступны в нескольких форм-факторах – в зависимости от требований к производительности и кол-ва сетевых интерфейсов, и могут выполнять роль маршрутизатора, пограничного МСЭ, VPN сервера, Wi-Fi точки доступа в филиалах.
- Удобство и простота развертывания и эксплуатации. Edge устройства поддерживают функцию zero touch provisioning - устройство с завода может быть доставлено непосредственно в филиал и настроено в соответствии с заданными политиками без выезда инженера. Для всех устройств выполняется централизованный мониторинг каналов передачи данных, собирается статистика по объемам трафика, источнику и назначению передаваемого трафика и используемым протоколам. Настройка, мониторинг и управление всеми устройствами осуществляется через единый веб портал SD-WAN Orchestrator.

Дополнительная информация о VMware SD-WAN: https://sdwan.vmware.com/content/dam/digitalmarketing/velocloud/en/documents/208805aq-so-vcloud-sd-wan-simplfd-uslet.pdf

Для построения инфраструктуры SD-WAN требуется приобрести устройства SD-WAN Edge, а также оформить подписку на ПО SD-WAN. Информация по лицензированию приведена в документе: https://www.velocloud.com/content/dam/digitalmarketing/velocloud/en/documents/SD-WAN-Edge-VeloCloud-DS.pdf

Видео о работе SD-WAN: https://www.youtube.com/watch?v=ET3v2n6DC40 и https://www.youtube.com/watch?v=nV8USrXISPY

Лабораторные работы на сайте https://labs.hol.vmware.com по теме SD-WAN:
- Building Managed Services with VMware SD-WAN (HOL-2240-02-NET) (https://labs.hol.vmware.com/HOL/catalogs/lab/10270)

Site Recovery
-------------
Site Recovery - облачный сервис, доступный заказчикам, использующим VMware Cloud on AWS. Site Recovery позволяет настроить репликацию ВМ между частной виртуальной инфраструктурой и публичным облаком VMC on AWS, либо между несколькими публичными облаками VMC on AWS, и создать план аварийного восстановления, который может быть запущен в случае отказа основной площадки. Site Recovery использует механизм асинхронной репликации данных vSphere Replication с минимальным интервалом репликации (RPO) в 5 минут, не требует применения специализированных средств репликации на уровне СХД. Помимо аварийного восстановления, Site Recovery также предоставляет функции тестового восстановления без влияния на производственную инфраструктуру.

Основные сценарии использования Site Recovery:
- Миграция виртуальных нагрузок из внутренней инфраструктуры в облако и обратно. Site Recovery позволяет быстро перенести ВМ из внутренней инфраструктуры в облако с минимальным простоем,
- Катастрофоустойчивая защита виртуальной инфраструктуры vSphere.
	
Site Recovery предоставляется по модели подписки и лицензируется по числу защищаемых/мигрируемых ВМ.

Дополнительная информация о VMware Site Recovery доступна по ссылке: https://cloud.vmware.com/vmware-site-recovery

Site Recovery Manager
---------------------
VMware Site Recovery Manager – ПО для построения катастрофоустойчивой инфраструктуры. SRM позволяет заранее создать план восстановления, описывающий последовательность операций по восстановлению ВМ. В случае аварии на основной площадке администратор запускает план, который автоматически восстанавливает ВМ на резервной площадке, используя локальные реплики данных. SRM поддерживает различные варианты репликации, например, репликацию средствами СХД Dell-EMC, HPE, IBM, HDS и других производителей, а также встроенную программную репликацию vSphere Replication. vSphere Replication позволяет реплицировать отдельные ВМ, не требует дополнительных лицензий и обеспечивает допустимую потерю данных (RPO) в 5 минут. Помимо запуска ВМ в нужном порядке, SRM также проверяет корректность включения ВМ, меняет сетевые настройки гостевых ОС (при отсутствии L2 связности между площадками) и выполняет внутри ВМ команды для восстановления сервисов.

Преимущества использования SRM:
- Восстановление инфраструктуры по нажатию одной кнопки. SRM автоматизирует операции по восстановлению ВМ, снижая влияние человеческого фактора и уменьшая время восстановления (RTO).
- Плановое восстановление инфраструктуры (Disaster Avoidance) без потери данных и с минимальным временем простоя. При плановом восстановлении SRM выключает ВМ на основной площадке, синхронизирует изменения, и запускает ВМ на резервной площадке. 
- Тестирование аварийного восстановления (Test Recovery). SRM запускает копии ВМ в изолированных тестовых сетях, что позволяет проводить тестовое восстановление в рабочее время без влияния на производственную инфраструктуру.
- После восстановления инфраструктуры SRM позволяет настроить защиту ВМ в обратную сторону и вернуть ВМ на основную площадку (Reprotect).
- Поддержка репликации средствами систем хранения данных корпоративного уровня.
- Поддержка различных схем защиты ВМ на основных и резервных площадках: основная и резервная, active-active площадки, с несколькими основными площадками и одной резервной и другие.

SRM доступен в двух основных редакциях (Standard и Enterprise) и лицензируется по числу защищаемых ВМ. SRM Enterprise используется в инфраструктурах, где требуется защищать более 75 ВМ. Также SRM Enterprise предоставляет функции по интеграции с NSX Data Center для автоматической настройки сетевой инфраструктуры в момент восстановления и поддерживает защиту ВМ, размещаемых на территориально-распределенных (Stretched) СХД.

Дополнительная информация о SRM приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/site-recovery-manager/vmware-site-recovery-manager-datasheet.pdf 

Видео: https://www.youtube.com/watch?v=OBQNuT_z9ro 

Лабораторные работы на сайте https://labs.hol.vmware.com по теме Site Recovery Manager:
- VMware Site Recovery Manager - Data Center Migration and Disaster Recovery (HOL-2205-01-SDC) (https://labs.hol.vmware.com/HOL/catalogs/lab/10302)

Tanzu Application Catalog
-------------------------
Tanzu Application Catalog - облачный сервис, позволяющий создавать и обновлять образы Open Source приложений для корпоративного репозитория.

Возможности TAC:
- Автоматизация создания образов приложений для Docker Registry и Helm Charts. TAC загружает актуальные версии приложений, инсталлирует их в базовый образ ОС, сохраняет в виде образа контейнера и добавляет в корпоративный репозиторий. TAC поддерживает различные базовые ОС, включая Debian, CentOS, Photon OS и другие.
- Тестирование образов. TAC проверяет работоспособность созданных образов, включая юнит-тесты и функциональное тестирование, выполняет антивирусное сканирование образов и сканирование на наличие уязвимостей.
- Подготовка отчетов по каждому созданному образу, содержащих информацию о процессе подготовки, результатах тестов, а также всех компонентах, включенных в образ, включая версии, потенциальные уязвимости и используемые лицензии.

Дополнительная информация: https://tanzu.vmware.com/application-catalog

Обзор возможностей и демонстрация TAC: https://www.youtube.com/watch?v=PRd3_2TyFbQ

Tanzu Build Service
-------------------
Tanzu Build Service – платформа для автоматической сборки OCI-совместимых образов приложений для различных языков программирования. Позволяет управлять необходимыми зависимостями и базовыми образами операционных систем.
 
Возможности TBS:
- Автоматическая сборка OCI-совместимых образов и публикация их в заданный репозиторий. Сборка может запускаться в ответ на изменения исходного кода (rebuild) или применения патча для образов базовых ОС (rebase), использующихся в приложениях. Rebase даёт возможности для простого и массового устранения уязвимостей (patching) для сотен образов контейнеров.
- Управление необходимыми зависимостями для приложений. Технология Buildbacks позволяет избавить разработчиков от необходимости писать Dockerfiles и вручную загружать зависимости в образ контейнера. TBS определяет, какие зависимости нужны для компиляции и запуска приложений внутри образа контейнера. В состав TBS входит набор Buildpacks для разных языков программирования.
- TBS ведет аудит используемых внутри образа зависимостей и позволяет командам разработки и ИБ понимать, какие компоненты используются внутри приложений.

Дополнительная информация: https://tanzu.vmware.com/build-service

Tanzu Kubernetes Grid
---------------------
Tanzu Kubernetes Grid основан на наработках компании Heptio, которую VMware приобрела в 2018 году. Grid предназначен для организаций, которые хотят снизить свои затраты на развертывание и обслуживание сред Kubernetes и для которых важно наличие поддержки от производителя.
 
TKG доступен по модели подписки и лицензируется по числу ядер хостов Kubernetes, либо по количеству запущенных POD. Доступна подписка на 1 или на 3 года. В рамках подписки на Grid заказчики получают:
- Инструменты для автоматизированного развертывания кластеров Kubernetes из командной строки или графического интерфейса. 
- Upstream версию Kubernetes и Opensource компоненты: Contour, Calico, Dex и др., необходимые для построения инфраструктуры Kubernetes.
- Материалы по рекомендуемой архитектуре Kubernetes, содержащие HLD/LLD, схемы, руководства по внедрению и тестированию, перечень рекомендаций и требований к оборудованию и смежному ПО для развертывания полнофункционального, надежного кластера Kubernetes.
- Поддержку решения в режиме 24x7.

Расширенная версия TKG+ предоставляет следующие дополнительные возможности:
- Корпоративный репозиторий образов VMware Harbor.
- Средство резервного копирования Velero.
- Ingress контроллер Contour.
- Средство аудита и сбора информации о конфигурации Sonobuoy.
- Расширенная поддержка.  Помимо возможности заведение кейсов по проблемам в эксплуатации, инженеры поддержки оказывают консультации по установке, настройке и обновлению компонентов, помогают в инсталляции кластеров и выполняют регулярный healthcheck инфраструктуры. VMware как один из основных maintainer'ов проекта Kubernetes регулярно вносит изменения в upstream код для оперативного исправления багов и добавления новых функциональных возможностей.

Полный список отличий TKG и TKG+ приведен в статье: https://kb.vmware.com/s/article/78173

TKG лицензируется по модели подписки на 1 или 3 года по числу физических ядер хост-серверов или по числу запускаемых POD. Минимальное количество ядер или POD составляет 500 шт.

Дополнительная информация о Tanzu Kubernetes Grid доступна по ссылке: https://tanzu.vmware.com/content/solution-overviews/vmware-tanzu-kubernetes-grid-solution-overview


Лабораторные работы на сайте https://labs.hol.vmware.com по теме Tanzu Kubernetes Grid:
- VMware Tanzu Kubernetes Grid (HOL-2233-02-MAP) (https://labs.hol.vmware.com/HOL/catalogs/lab/10659)

Tanzu Kubernetes Grid Integrated / Enterprise PKS
-------------------------------------------------
TKG-I - решение корпоративного уровня для управления контейнерными средами Kubernetes. TKG-I позволяет автоматически развертывать новые кластеры Kubernetes по запросу, а также централизованно управлять, мониторить и обновлять существующие кластеры. В состав TKG-I входит NSX-T, обеспечивающий интеграцию контейнеров с сетевой инфраструктурой. NSX-T решает задачи сегментации, маршрутизации, межсетевого экранирования и балансирования нагрузки. TKG-I включает в себя плагины для интеграции с СХД для обеспечения постоянного хранения (Persistent Volume) и корпоративный репозиторий образов контейнеров (VMware Harbor). TKG-I поддерживает интеграцию со службами каталога (Microsoft Active Directory / LDAP) для организации ролевого доступа пользователей к проектам и рабочим группам. Для работы с кластерами Kubernetes и Kubernetes Pod могут использоваться стандартные инструменты (REST API, веб-консоль, kubectl). 
 
Основные компоненты TKG-I:
- Bosh – обеспечивает централизованное развертывание и обновление кластеров Kubernetes.
- NSX - обеспечивает различные сетевые сервисы для Kubernetes, включая сегментацию, маршрутизацию, межсетевое экранирование и балансирование трафика.
- Pivotal Ops Manager – портал самообслуживания для управления Kubernetes из GUI.
- Harbor – репозиторий для хранения образов контейнеров. 
- EMPC (Enterprise PKS Management Console) – графическая консоль для управления кластерами Kubernetes.

Дополнительная информация по TKG-I (Enterprise PKS): https://docs.vmware.com/en/VMware-Tanzu-Kubernetes-Grid-Integrated-Edition/index.html

TKG-I распространяется по модели подписки на 1 или 3 года и лицензируется по физическим ядрам хост-серверов или по числу запущенных POD. TKG-I также включает в себя техническую поддержку всех компонентов в режиме 24 на 7.
 
Краткий обзор Enterprise PKS: https://www.youtube.com/watch?v=xbIexBUODwg

Лабораторные работы на сайте https://labs.hol.vmware.com по теме Tanzu Kubernetes Grid Integrated:
- VMware Tanzu Kubernetes Grid Integrated (TKGI) with Management Console Simulation (HOL-2233-91-ISM) (https://labs.hol.vmware.com/HOL/catalogs/lab/10892)

Tanzu Mission Control
---------------------
Tanzu Mission Control (TMC) - облачный сервис для централизованного управления кластерами Kubernetes.

TMC предоставляет следующие возможности:
- Управление и мониторинг Kubernetes. TMC поддерживает любые кластеры Kubernetes, отвечающие требованиям стандарта CNCF Certified Kubernetes. Администратор может использовать единую панель мониторинга (dashboard) для получения оперативной информации обо всех кластерах Kubernetes, включая используемую платформу, версию и статус кластера, а также уровень утилизации ресурсов.
- Автоматизированное создание и обновление кластеров Kubernetes на платформе виртуализации VMware vSphere или в публичных облаках Amazon.
- Управление безопасностью и доступом для кластеров Kubernetes. Используя графическую консоль, Администратор может назначать пользователям права на доступ к кластерам Kubernetes, разрешать или запрещать доступ к определенным репозиториям образов и настраивать сетевые политики для разрешения или запрета передачи трафика между POD.
- Диагностика кластеров Kubernetes (Conformance). TMC проверяет конфигурацию кластера и компонентов, запускает функциональные тесты и выдает отчет о работоспособности кластера и обнаруженных проблемах.

Краткая информация о TMC: https://tanzu.vmware.com/mission-control#faq

Видео с демонстрацией возможностей TMC: https://tanzu.vmware.com/content/tanzu-mission-control/tanzu-mission-control-overview

Лабораторные работы на сайте https://labs.hol.vmware.com по теме Tanzu Kubernetes Mission Control:
- HOL-2132-91-ISM - VMware Tanzu Mission Control Simulation (https://labs.hol.vmware.com/HOL/catalogs/lab/8516)

Tanzu Observability by Wavefront
--------------------------------
Tanzu Observability - облачный сервис мониторинга. TO собирает, анализирует и отображает различные метрики приложений и облачных сервисов. Благодаря распределенной трассировке TO позволяет быстро обнаружить источники сбоев и проблем с производительностью внутри приложений и может использоваться в качестве APM и для построения карты приложений. Благодаря SDK разработчики могут встраивать сенсоры TO в собственные приложения для отправки данных в систему мониторинга.

Перечень поддерживаемых "из-коробки" систем и приложений: https://tanzu.vmware.com/content/vmware-tanzu-observability-features/ingest-and-visualize-all-your-telemetry-quickly

Дополнительная информация о Tanzu Observability: https://tanzu.vmware.com/observability

Tanzu Service Mesh
------------------
Tanzu Service Mesh - облачный сервис, расширяющий возможности кластеров Kubernetes в части сетевых сервисов. Пример функций реализуемых с помощью TSM:
- End-to-End шифрование трафика между Pod.
- Визуализация сетевых взаимодействий между Pod в Kubernetes.
- Фильтрация входящего и исходящего трафика Pod.
- Ingress Controller для Pod.
- Организация Global Namespace для разрешения имен, Service Discovery и обеспечение сетевой связности между Pod, работающих в различных кластерах Kubernetes.

Дополнительная информация по Tanzu Service Mesh: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/nsx/vmware-nsx-service-mesh-solution-brief.pdf

Видео с демонстрацией возможностей Tanzu Service Mesh: https://www.youtube.com/watch?v=EquVhIkS1oc

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме Tanzu Service Mesh:
- HOL-2132-92-ISM - VMware Tanzu Service Mesh Simulation (https://labs.hol.vmware.com/HOL/catalogs/lab/8509)

Unified Access Gateway
----------------------
Unified Access Gateway предназначен для публикации доступа и организации защищенного подключения к сервисами VMware (Horizon, Identity Manager, Workspace ONE) из сети Интернет.

Пользователи из Интернет подключаются к UAG, аутентифицируются и устанавливают туннелированное защищенное соединение через UAG к своим виртуальным десктопам во внутренней сети или получают доступ к порталу Identity Manager с опубликованными приложениями.

Преимущества UAG:
- Поддержка туннелирования различных протоколов удаленного доступа (RDP, PCoIP и BLAST).
- Работа в отказоустойчивом режиме (High Availability кластер).
- Простота развертывания и обслуживания.
- Не требователен к вычислительным ресурсам.
- Не требует дополнительного лицензирования (право на использование входит в состав Horizon и Workspace ONE).
	
Видео с описанием сценариев использования UAG: https://www.youtube.com/watch?v=xaN9mYOJqAs

vCenter Server
--------------
vCenter Server - ПО для централизованного управления серверами виртуализации ESXi. vCenter предоставляет следующие функциональные возможности:
- Централизованное управление виртуальной инфраструктурой, включая серверы виртуализации, кластеры, ВМ, хранилища и виртуальные сети.
- Настройка и управление функциями vSphere: High Availability, Distributed Switch, vMotion, vSAN и другими.
- Создание и клонирование ВМ из шаблонов, включая настройку параметров гостевых ОС в момент развертывания.
- Автоматизированное обновление серверов виртуализации: установка обновлений безопасности, новых версий гипервизоров и драйверов.
- Встроенные функции мониторинга загрузки и здоровья серверов виртуализации и ВМ.

vCenter Server лицензируется по числу установленных экземпляров (Instances) и доступен в двух основных редакциях: Foundation и Standard.

vCenter Server Foundation используется для небольших инсталляциях vSphere позволяет управлять максимум четырьмя серверами VMware ESXi.

vCenter Server Standard предоставляет следующие дополнительные возможности:
- Управление до 2000 серверов виртуализации ESXi.
- Встроенный механизм обеспечения высокой доступности сервера управления vCenter HA, позволяющий защитить vCenter Server от отказа оборудования или сбоя на уровне ПО.
- Возможность объединения нескольких инсталляций vCenter Server (Linked Mode) для централизованного мониторинга и управления серверами и ВМ из единой консоли vSphere Client.
- Возможность запуска произвольных сценариев при помощи vRealize Orchestrator для автоматизации типовых операций.
- Встроенные функции резервного копирования и восстановления конфигурации и журналов работы vCenter Server.

Дополнительная информация о vCenter Server приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/vCenter/vmw-datasheetvcenter.pdf

VMware Cloud on AWS
-------------------
VMC on AWS - публичный облачный сервис, позволяющий арендовать выделенный виртуальный ЦОД. 

Основные возможности и преимущества облака VMC on AWS:
- VMC on AWS построен с использованием современного программно-определяемого подхода и использует ПО VMware Cloud Foundation: vSphere, NSX и vSAN для запуска ВМ, организации хранения и построения сетевой инфраструктуры.
- Обслуживание, обновление поддержка инфраструктуры, ПО виртуализации и оборудования осуществляется специалистами VMware в режиме 24 x 7.
- Виртуальные ЦОД включает в себя высокопроизводительные серверы для размещения ВМ. От 36 ядер Intel Xeon E5 v4, 512 ГБ ОЗУ, 25 Гбит/с Ethernet адаптер и 10.7 ТБ All-Flash NVMe на один физический сервер.
- Быстрое выделение и возврат вычислительных ресурсов. Новые физические серверы могут быть введены в работу в течение часа. VMC on AWS поддерживает функцию автоматической балансировки нагрузки Elastic DRS, которая позволяет автоматически добавлять дополнительные физические серверы в кластер при нехватке ресурсов, и отключать неиспользуемые серверы при избытке ресурсов.
- Инфраструктура VMC on AWS размещается в ЦОД по всему Миру (США, Ирландия, Англия, Франция, Германия, Австралия и др.).
- Управление частной виртуальной инфраструктурой и публичным облаком из единой консоли (vCenter Hybrid Linked Mode).
- Доступ к публичным сервисами Amazon по высокоскоростным каналам передачи данных.
- Простая организация катастрофоустойчивой инфраструктуры с использованием VMware Site Recovery.

Основные сценарии использования VMC on AWS:
- Миграция ВМ из внутренней виртуальной инфраструктуры в публичное облако. VMC on AWS предоставляет простой способ миграции в публичное облако без необходимости обучения специалистов работе с новыми продуктами, технологиями и сервисами.
- Построение инфраструктуры гибридного облака. VMC on AWS позволяет быстро получать необходимые вычислительные ресурсы в облаке и переносить ВМ между внутренней инфраструктурой и публичным облаком.
- Создание катастрофоустойчивой инфраструктуры. VMC on AWS может использовать в качестве резервной площадки для восстановления ВМ в случае аварии на площадке заказчика.
- Развертывание VDI инфраструктуры в связке с VMware Horizon Cloud для организации доступа пользователей к рабочим столам и работы с терминальными приложениями. 

VMC on AWS предоставляется по модели подписки, стоимость сервиса зависит от количества арендуемых серверов и длительности аренды. Возможны варианты приобретения ресурсов по модели Pay as you Go с почасовой оплатой или аренда серверов на 1 или 3 года с предварительной оплатой.

Дополнительная информация о VMC on AWS приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/support/vmw-cloud-aws-service-description.pdf

Лабораторные работы на сайте https://labs.hol.vmware.com по теме VMC on AWS:
- VMware Cloud on AWS - Fundamentals (HOL-2387-01-ISM) (https://labs.hol.vmware.com/HOL/catalogs/lab/12113)

vRealize Automation / VMware Aria Automation
--------------------------
vRealize Automation включает в себя три основных компонента (Cloud Assembly, Service Broker и Code Stream):
- Cloud Assembly позволяет объединить вычислительные ресурсы различных платформ виртуализации и публичных облачных сервисов под единой системой управления, и автоматизировать процедуру развертывания и управления жизненным циклом виртуальных машин.
- Service Broker предоставляет функции портала самообслуживания, с помощью которого пользователи могут запрашивать необходимые ИТ-сервисы. В каталог Service Broker могут быть добавлены шаблонов сервисов из Cloud Assembly, Amazon CloudFormation и vRealize Orchestrator. 
- Code Stream позволяет построить pipeline для автоматизации различных этапов разработки, включая тестирование и развертывание новых версий приложений. Функции Code Stream могут быть расширены благодаря интеграции со сторонними системами для разработки (Artifactory, Jenkins, Jira, Git, Gerrit и другими).

Пример создания Pipeline для разработки приложения:
https://www.youtube.com/watch?v=nJkN1IR5Qiw 

Пример интеграции с контейнерами Kubernetes:
https://www.youtube.com/watch?v=19Q3pPX-VjI 

Дополнительная информация по vRA приведена в документе:
https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/vrealize-automation/vmw-vrealize-automation-8.0-datasheet.pdf

vRealize Automation может лицензироваться отдельно, либо в составе vCloud Suite. Дополнительная информация о vCloud Suite приведены в документе:
https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/whitepaper/vrealize-suite-licensing-pricing-packaging.pdf

На сайте https://labs.hol.vmware.com доступны лабораторные работы по теме vRealize Automation:
- Getting Started with vRealize Automation (HOL-2201-02-CMP) (https://labs.hol.vmware.com/HOL/catalogs/lab/10127)

vRealize Log Insight / VMware Aria Operations for Logs
--------------------
vRealize Log Insight – средство сбора и анализа журналов работы. Поддерживает сбор логов по протоколу Syslog и через агентов, устанавливаемых на ОС Windows или Linux. Помимо сбора и хранения vRLI предоставляет функции поиска и визуализации данных. Используя фильтры, администратор может построить графики и диаграммы по интересующим событиям и увидеть корреляцию событий друг с другом. Возможности vRLI по анализу журналов расширяются благодаря дополнительным модулям (Content Pack), которые содержат готовые фильтры и dashboard, отображающие важную информацию об объектах мониторинга.

vRLI интегрируется с vRealize Operations Manager и может отправлять vROps уведомление (Alerts) при нахождении определенного события в журнале.

vRLI лицензируется по процессорам (при сборе журналов с компонентов виртуальной инфраструктуры vSphere), либо по OSI (объектам, с которых собираются журналы, если требуется сбор журналов со стороннего оборудования, либо физических серверов).

Дополнительная информация о vRealize Log Insight приведена в документе:
https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/vrealize-log-insight/vrealize-log-insight-datasheet.pdf 

Короткое видео по возможностям vRLI: https://www.youtube.com/watch?v=8h6_pSiGFSg

Лабораторные работы на сайте https://labs.hol.vmware.com по теме vRealize Log Insight: 
- Getting Started with vRealize Log Insight (HOL-2201-03-CMP) (https://labs.hol.vmware.com/HOL/catalogs/lab/10128)

vRealize Network Insight / VMware Aria Operations for Networks
------------------------
vRealize Network Insight – решение по мониторингу и обнаружению неисправностей в виртуальной и физической сетевой инфраструктуре. vRNI собирает и хранит информацию о сетевом оборудовании: коммутаторах, маршрутизаторах, межсетевых экранах и платформе виртуализации, позволяет визуализировать сетевую топологию и отображать путь прохождения трафика между конечными устройствами, а также показывать различные сетевые метрики: информацию о загрузке, потерях пакетов, видах трафика. Для сбора данных используются NetFlow, SSH, REST.
Сценарии использования vRNI:
- Ускорение решения инцидентов. vRNI позволяет обнаружить проблему в сетевой инфраструктуре и определить причину сбоя: отказ оборудования, изменение настроек, обрыв каналов передачи данных.
- Микросегментация сети. vRNI анализирует сетевой трафик и выдает перечень рекомендуемых правил для настройки на межсетевых экранах.
- Обнаружение и визуализация сервисов (Service Discovery). vRNI стоит диаграммы взаимодействия между узлами в сети и группирует узлы в единый сервис. Это позволяет администраторам лучше понимать взаимосвязь различных компонентов инфраструктуры и их зависимость от сети.

Дополнительная информация о vRNI приведена по ссылке: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/vmw-vrealize-network-insight-datasheet.pdf

VMware vRNI доступен в двух редакциях (Advanced и Enterprise) и лицензируется по числу процессоров. Также vRNI Advanced входит в состав VMware NSX Data Center Enterprise Plus.

Лабораторные работы на сайте https://labs.hol.vmware.com по теме vRealize Network Insight: 
- Getting Started with vRealize Network Insight (HOL-2202-01-CMP) (https://labs.hol.vmware.com/HOL/catalogs/lab/10345)

vRealize Operations / VMware Aria Operations
-------------------
vRealize Operations обеспечивает сквозной мониторинг производительности и здоровья виртуальной инфраструктуры, включая серверное оборудование (серверы, СХД), ПО виртуализации, гостевые ОС (Windows, Linux) и приложения.

vROps позволяет:
- Отображать взаимосвязь объектов виртуальной инфраструктуры, оборудования, виртуальных машин и работающих на них приложений для более простого поиска и устранения неисправностей.
- Оптимизировать производительность виртуальных машин и выдавать рекомендации по конфигурации ВМ (кол-во процессоров, объем памяти и дисков) на основании исторических данных о реальном потреблении ресурсов.
- Выполнять What-If анализ, который показывает, когда в виртуальной инфраструктуре закончатся вычислительные ресурсы и спланировать загрузку инфраструктуры перед запуском новых проектов.
- Оценивать стоимость владения виртуализованными сервисами с помощью встроенного калькулятора затрат. 

Функциональные возможности по мониторингу vROps расширяются благодаря дополнительным пакетам мониторинга (Management Packs): https://marketplace.vmware.com/vsx/ и https://docs.vmware.com/en/VMware-vRealize-True-Visibility-Suite/index.html. Пакеты мониторинга добавляют возможность мониторинга стороннего оборудования и содержат готовые отчеты, рекомендации и панели мониторинга. 

vROps входит в состав vRealize Suite, vCloud Suite и Cloud Foundation, а также может лицензироваться отдельно по процессорам серверов виртуализации (CPU), либо по числу объектов мониторинга (OSI).

Описание возможностей и сравнение различных редакций vROps доступно по ссылке: https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/vcenter/vmware-vrealize-operations-datasheet.pdf

Короткое видео о vROps:
- https://www.youtube.com/watch?v=lxKeC4AUEAE

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме vRealize Operations:
- Getting Started with vRealize Operations (HOL-2201-01-CMP) (https://labs.hol.vmware.com/HOL/catalogs/lab/10126)

vRealize Orchestrator
---------------------
vRealize Orchestrator - средство автоматизации задач, выполняемых администраторами. Позволяет создавать и запускать произвольные сценарии (workflow), состоящие из последовательности действий или других сценариев.

vRO не требует отдельного лицензирования и поставляется вместе с vCenter Server Standard (Standalone версия) и vRealize Automation. vRO, входящий в состав vRealize Automation, имеет следующие преимущества в сравнении с Standalone версией:
- Поддержка Multi-tenancy. По умолчанию все сценарии запускаются под единственной учетной записью, под которой настраивается подключение к соответствующему сервису (например, все сценарии с обращением к vCenter Server будут выполняться под учетной записью administrator@vsphere.local). При настройке в режиме multi-tenancy сценарии vRO будут использовать права той учетной записи, под которой они запущены.
- Поддержка сторонних модулей расширения. Помимо встроенных модулей vRO поддерживает возможность добавления модулей для интеграции с решениями сторонних производителей. Перечень встроенных модулей расширения: vRealize Automation Center Infrastructure Administration Plug-In, vRealize Automation Plug-In, vRealize Orchestrator vCenter Server Plug-In, vRealize Orchestrator Mail Plug-In, vRealize Orchestrator SQL Plug-In, vRealize Orchestrator SSH Plug-In, vRealize Orchestrator SOAP Plug-In, vRealize Orchestrator HTTP-REST Plug-In, vRealize Orchestrator Plug-In for Microsoft Active Directory, vRealize Orchestrator AMQP Plug-In, vRealize Orchestrator SNMP Plug-In, vRealize Orchestrator PowerShell Plug-In, vRealize Orchestrator Multi-Node Plug-In, vRealize Orchestrator Dynamic Types, vRealize Orchestrator vCloud Suite API (vAPI) Plug-In, vRealize Orchestrator Plug-In for vRealize Automation
			
Лабораторные работы на сайте https://labs.hol.vmware.com  по теме vRealize Orchestrator:
- Getting Started with vRealize Orchestrator (HOL-2201-13-CMP) (https://labs.hol.vmware.com/HOL/catalogs/lab/10141)

VMware vRealize Suite
---------------------
VMware vRealize Suite – это набор лицензий, который включает в себя лицензии на ПО для мониторинга и автоматизации инфраструктуры.  В состав vRealize Suite входят следующие продукты/решения:
- vRealize Automation (vRA) – позволяет создать портал самообслуживания и автоматизировать типовые задачи по созданию и управлению жизненным циклом виртуальных машин и ИТ-сервисов. https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/vrealize/vmware-whats-new-vrealize-automation.pdf 
- vRealize Operations (vROps) – выполняет мониторинг виртуальной инфраструктуры, оборудования, ОС и приложений. https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/vcenter/vmware-vrealize-operations-datasheet.pdf 
- vRealize Log Insight (vRLI) – Собирает и анализирует журналы работы систем. https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/vrealize-log-insight/vrealize-log-insight-datasheet.pdf 
vRealize Suite доступен в трех редакциях (Standard, Advanced и Enterprise), лицензируются по физическим процессорам/сокетам физических серверов (CPU) для платформы виртуализации VMware vSphere, либо управляемые объекты/ВМ (OSI) для сторонних платформ виртуализации, физических серверов или публичных облаков. Дополнительная информация по лицензированию и составу vCloud Suite/vRealize Suite приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/whitepaper/vrealize-suite-licensing-pricing-packaging.pdf 

Сравнение функциональных возможностей различных редакций: https://docs.vmware.com/en/vRealize-Suite/7.0/com.vmware.vrealizesuite.overview.doc/GUID-B65AFD87-05D9-4047-ABB3-0E9635E9B3D8.html 

vRealize Suite Lifecycle Manager
--------------------------------
vRealize Suite Lifecycle Manager - средство, предназначенное для развертывания и управления жизненным циклом продуктов, входящих в vRealize Suite: vRealize Automation, vRealize Operations, vRealize Log Insight, vRealize Network Insight, vRealize Business for Cloud и Identity Manager.

Преимущества использования Lifecycle Manager:
- Быстрое развертывание. Lifecycle Manager позволяет администратору задать необходимые настройки через графический интерфейс, после чего LCM самостоятельно выполнит установку и настройку всех компонентов в соответствии с лучшими практиками VMware.
- Управление конфигурацией и проверка здоровья установленного ПО. Lifecycle Manager отслеживает здоровье и текущие параметры компонентов vRS и при нахождении отклонений или сбоев в работе компонентов сообщает об этом администратору.
- Простое обновление. Lifecycle Manager загружает и при необходимости выполняет установку обновлений. Lifecycle Manager контроллирует совместимость всех компонентов, а также предоставляет возможность отката изменений в случае возникновения ошибок в процессе обновления.
- Встроенный каталог (Marketplace). Позволяет загружать, устанавливать и обновлять модули расширения для vRealize SuiteS, включая Management Pack для vRealize Operations, Content Pack для vRealize Log Insight, Plug-in для vRealize Orchestrator.
- Хранение и синхронизация артефактов между разными инсталляциями ПО vRealize Suite. Lifecycle Manager поддерживает работу с шаблонами ВМ из vCenter Server, сценариями vRealize Orchestrator, шаблонами vRealize Automation и другими типами объектов.

LCM не требует приобретения дополнительных лицензий и доступен во всех редакциях vRealize Suite.

Дополнительная информация о LCM: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/vmware-vRealize-Suit-Lifecycle-Manager-8.0-Datasheet.pdf

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме vRealize Suite Lifecycle Manager:
- Getting Started with vRealize Suite Lifecycle Manager (HOL-2201-04-CMP) (https://labs.hol.vmware.com/HOL/catalogs/lab/10129)

vRealize True Visibility Suite / VMware Aria Operations for Integrations
------------------------------
vRealize True Visibility Suite (TVS) - это набор пакетов мониторинга для vRealize Operations, который добавляет возможность мониторинга оборудования (серверов, СХД, сетевого оборудования) различных производителей: HPE, Dell, Cisco, Lenovo, NetApp и других, а также СУБД (Oracle Database, Microsoft SQL, PostgreSQL и др.) и приложений (SAP, ServiceNOW, SAP HANA, Apache, Microsoft IIS и др.). TVS в связке с vROps обеспечивает сквозной мониторинг, который работает на всех уровнях - от оборудования до приложений. Это позволяет упростить и ускорить решения инцидентов благодаря видимости связи и зависимости объектов и метрик на различных уровнях, а также встроенным панелям мониторинга, отчетам и рекомендациям.

TVS доступен в нескольких редакциях (Standard, Advanced, Enterprise), различающихся кол-вом доступных пакетов мониторинга, и лицензируется аналогично vRealize Operations - по процессорам серверов виртуализации (CPU) или по количеству объектов мониторинга (OSI).

Дополнительная информация о TVS приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/professional-services/vmw-solution-brief-vrealize-true-visibility-suite.pdf 

Список пакетов мониторинга TVS: https://www.vmware.com/products/vrealize-operations/true-visibility-suite.html#managementtools

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме VMware vSAN: 
- Extending vRealize Operations with True Visibility Suite (HOL-2101-92-ISM) (https://labs.hol.vmware.com/HOL/catalogs/lab/8668)

vSAN
----
VMware vSAN - это решение в области программно-определяемого хранения данных (Sofware-Defined Storage). vSAN позволяет создать надежное, масштабируемое хранилище для виртуальной инфраструктуры, используя локальные накопители, установленные в серверах (поддерживаются жесткие диски, SSD/Flash накопители, накопители Intel Optane). В связке с VMware vSphere ПО vSAN является основой для построения гиперконвергентной инфраструктуры для размещения любых типов виртуальных нагрузок.

Среди преимуществ vSAN:
- Работа на стандартных x86 серверах. vSAN не требует специализированного оборудования, и поддерживается на оборудовании различных производителей: HPE, Dell, Lenovo, Cisco, Fujitsu, Intel, Supermicro и др.
- Снижение затрат на хранение за счет поддержки функций дедупликации, компрессии, тонких дисков (Thin Provisioning), Erasure Coding (распределенный RAID-5/RAID-6). Лицензии vSAN могут быть перенесены на новое оборудование без дополнительных затрат.
- Простота установки и управления. Управление vSAN осуществляется из единой консоли vSphere Client. Настройки хранения (отказоустойчивость, производительность) задаются с помощью политик на уровне отдельных виртуальных машин и виртуальных дисков и могут легко перенастраиваться без необходимости создавать и управлять отдельными хранилищами виртуальных машин.
- Поддержка работы в распределенном режиме на нескольких площадках (Stretched Cluster) для обеспечения катастрофоустойчивой защиты виртуальной инфраструктуры.
- Возможность развертывания виртуальной инфраструктуры в филиалах всего на двух физических серверах с централизованным управлением всеми филиалами из единой консоли.

Дополнительная информация о vSAN приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/vsan/vmware-vsan-datasheet.pdf

Двухузловой кластер vSAN для филиалов: https://www.vmware.com/files/pdf/products/vsan/vmware-vsan-robo-solution-overview.pdf

vSAN доступен в нескольких редакциях и лицензируется по числу процессоров. Информация по функциональным возможностям редакций vSAN приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/vsan/vmware-vsan-licensing-guide.pdf 

Короткое видео о vSAN:
- https://www.youtube.com/watch?v=D5pDF8nhqgs

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме VMware vSAN:
- VMware vSAN - Getting Started (HOL-2208-01-HCI) (https://labs.hol.vmware.com/HOL/catalogs/lab/10284)

VMware vSphere
--------------
VMware vSphere - решение для построения виртуальных инфраструктур. Включает в себя гипервизор ESXi и, в зависимости от редакции, дополнительные компоненты.

ESXi Free (vSphere Hypervisor) - бесплатная версия гипервизора. В сравнении с коммерческими версиями (vSphere) ESXi Free имеет следующие ограничения:
- Одной ВМ может быть выделено не более 8 виртуальных процессоров (vCPU), даже если на хосте доступно больше ядер/процессоров.
- ESXi Free не может интегрироваться с системами резервного копирования, мониторинга и управления (например, он не работает с vCenter Server). Как следствие, отсутствуют функции, которые настраиваются или работают в связке с vCenter Server (нет vMotion, High Availability, Distributed Switch и пр.).
- Для бесплатной версии не предоставляется техническая поддержка. 

VMware vSphere доступен в нескольких редакциях - vSphere Standard, vSphere Enterprise Plus, Essentials Kit, ROBO. В коммерческих версиях нет ограничений ESXi Free, и они могут управляться централизованно средствами vCenter Server. Отличия редакций vSphere приведены в документах: 
https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/vsphere/vmw-flyr-comparevsphereeditions-uslet.pdf 
https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/vsphere/vmw-flyr-vspherecomparekits-uslet.pdf 
https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/vsphere/vmw-flyr-vsphererobo-uslet.pdf 

vSphere Enterprise Plus
vSphere Enterprise Plus предоставляет расширенные функциональные возможности по сравнению с vSphere Standard, направленные на повышение производительности, доступности и безопасности виртуальных машин. Пример некоторых из функций:
- DRS – мониторит загрузку процессоров, ОЗУ и сетевых адаптеров физических серверов и автоматически мигрирует ВМ с более загруженных серверов на менее загруженные. DRS позволяет более эффективно использовать вычислительные ресурсы платформы виртуализации и снять с администраторов нагрузку по мониторингу и ручному переносу ВМ между серверами. В сценариях, когда нагрузка на ВМ возникает периодически, DRS использует исторические данные мониторинга vRealize Operations и выполняет миграцию ВМ заранее до наступления пиковой утилизации на серверах. Также DRS обеспечивает работу Affinity Rules, которые гарантируют, что определенные ВМ могут или не могут работать вместе на одном сервере виртуализации, что важно при использовании кластеризованных решений внутри гостевых ОС (кластеры серверов приложений, СУБД и пр.).
- Fault Tolerance – позволяет защищать высококритичные ВМ от отказа физического оборудования и гарантировать для них постоянную доступность (RTO=0). FT создает и в реальном времени синхронизирует состояние двух копий ВМ, одна из которых является активной. В случае отказа активной ВМ, FT мгновенно активирует пассивную копию без потери состояния (гостевая ОС не перезагружается, сервисы не останавливаются, TCP сессии не прерываются). Данный механизм предназначен для ВМ, для которых нет возможности обеспечить высокую доступность другими методами, например, при использовании устаревших ОС или при отсутствии средств кластеризации на уровне приложений.
- Proactive HA – следит за состоянием компонентов физического сервера, и при ухудшении метрик здоровья переносит ВМ на другие серверы до того, как это приведет к сбою и повлияет на доступность ВМ.
- Resource Pools, Reservations, Storage I/O Control, Network I/O Control позволяют управлять доступными вычислительными, дисковыми и сетевыми ресурсами и перераспределять их между ВМ в зависимости от уровня критичности, гарантируя заданный уровень производительности.
- VM Encryption и Virtual TPM – обеспечивают безопасное хранение критичных данных внутри ВМ, защищая их от кражи злоумышленниками или вредоносным ПО. Поддерживает различные типы хранилищ и работает с различными версиями гостевых ОС и приложениями, установленными внутри ВМ.
 
Наборы vSphere Essentials
vSphere Essentials и Essentials Plus представляют собой наборы, включающие лицензии ESXi Essentials (или Essentials Plus) для установки на три двухпроцессорных сервера и одной лицензии vCenter Server Essentials. Essentials Kit используется для небольших инсталляций - для SMB организаций и в филиалах, где требуется разместить до 3-х серверов виртуализации.

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме VMware vSphere:
- Virtualization 101 (HOL-2210-01-SDC) (https://labs.hol.vmware.com/HOL/catalogs/lab/9388)

vSphere with Tanzu
---------------------------------------
vSphere with Tanzu - платформа, поддерживающая запуск виртуальных машин и контейнерных приложений Kubernetes.

vSphere with Tanzu предоставляет возможность:
- Совместимость с инструментами Kubernetes (kubectl, REST API и др.) для развертывания, запуска и управления Kubernetes Pod.
- Централизованное управление и мониторинг контейнеров и ВМ через vCenter Server. Администраторы могут создавать пространства имен (Namespace), которые позволяют делегировать доступ к Kubernetes для пользователей, а также ограничивать доступные ресурсы: процессоры, оперативную память, хранилища.
- Автоматизированное развертывание и обновление инфраструктуры Kubernetes. Администратор может включить поддержку Kubernetes прямо из консоли vSphere Client. Установка новых версий Kubernetes на хост-серверы выполняется централизованно.
- Поддержка функциональных возможностей платформы vSphere для контейнеров, включая: vMotion, DRS, Resource Pools, Distributed Switch и пр.
- Встроенный корпоративный реестр образов VMware Harbor.
- Интеграция с NSX-T Data Center для предоставления контейнерам сетевых сервисов: сегментации, маршрутизации, балансирования нагрузки, фильтрации и мониторинга сетевого трафика.
- Интеграция с распределенным хранилищем vSAN для управления хранением с использованием политик Storage Policies. Администратор может управлять Persistent Volumes, создавать и подключать их к одному или нескольких Pod в режим multi-read / multi-write.
- Возможность развертывания кластеров Kubernetes внутри виртуальных машин vSphere. При необходимости использования различных версий Kubernetes или выдачи административных прав целиком на кластер, администратор может создать один или несколько отдельных кластеров Tanzu Kubernetes Grid, входящих в состав vSphere with Kubernetes.

vSphere with Tanzu доступен в качестве дополнительной подписки к лицензиям vSphere или Cloud Foundation сроком на 1 или 3 года, и лицензируется по числу физических процессоров.

Дополнительная информация: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/vsphere/vmw-vsphere7-solution-brochure.pdf

Видео с демонстрацией возможностей Kubernetes with Tanzu: https://www.youtube.com/watch?v=z-rxqWFC2OU 

Лабораторные работы на сайте https://labs.hol.vmware.com  по теме vSphere with Tanzu:
- vSphere with Tanzu (HOL-2213-01-SDC) (https://labs.hol.vmware.com/HOL/catalogs/lab/10402)

Workspace ONE Access / Identity Manager
---------------------------------------
Workspace ONE Access - решение для публикации приложений и управления доступом. WO Access предоставляет следующие преимущества для организаций:
- Self-Service Unified App Catalog - каталог ИТ-сервисов, доступных конечным пользователям. WO Access предоставляет для пользователей доступ ко всем типам приложений: внутренний и публичным веб-сервисам, терминальным приложениям, виртуальным рабочим станциям (VDI) и мобильным приложениям из единого окна. Пользователи могут подключаться к каталогу через веб-браузер или через клиентское приложение для платформ Windows, iOS или Android.
- Enterprise Single Sign On - WO Access поддерживает различные варианты аутентификации, включая логин-пароль, passthrough аутентификацию, цифровые сертификаты, одноразовые пароли и пр., и поддерживает сквозную аутентификацию (SSO) для любых опубликованных приложений. WO Access работает с различными типами клиентских устройств, доступ к порталу может осуществляться через веб-браузер, либо мобильное приложение VMware Hub (для платформ iOS и Android).
- Conditional Access Policies - позволяет разрешать или запрещать доступ к опубликованным приложениям на основании групп безопасности, места, откуда подключаются пользователи, типа устройства и способе аутентификации.

Workspace ONE Access входит в состав Workspace ONE или Horizon Advanced и Enterprise и не требует отдельного лицензирования.

Краткий обзор Workspace ONE Access: https://www.youtube.com/watch?v=LGQRUe2vKWs 

Дополнительная информация о WO Access приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/identity-manager/vmw-workspace-one-access.pdf

Workspace ONE Assist / Advanced Remote Management
-------------------------------------------------
Workspace ONE Assist позволяет администраторам и сотрудникам поддержки удаленно подключаться, просматривать (Apple iOS) и управлять (Google Android, Apple MAC OS X, Microsoft Windows) устройствами пользователей, а также получать оперативную информацию об устройствах - уровень заряда батареи, сигнал, свободное дисковое пространство и пр.

WO Assist доступен в виде постоянных лицензий  или по модели подписки и лицензируется по числу устройств или пользователей.

Видео с демонстрацией работы WO Assist: https://www.youtube.com/watch?v=1m3OM7AJZ7E

Workspace ONE Intelligence
--------------------------
Workspace ONE Intelligence - облачный сервис, который расширяет функциональные возможности Workspace ONE UEM в части сбора, хранения и отображения информации о работе мобильных устройств и пользователей.

WO Intelligence выполняет следующие функции:
- Создание панелей мониторинга (dashboard) и кастомизированных отчетов, содержащих расширенную аналитическую информацию об используемых пользователями устройствах и приложениях.
- Автоматизация задач по установке обновлений и применению настроек при наступлении определенных событий, например, WO Intelligence может заблокировать устройство, если оно перестанет соответствовать Compliance политикам, и отправить уведомление администратору и пользователю.

Workspace ONE Intelligence доступен по модели подписки и лицензируется по числу пользователей или устройств.

Видео о возможностях Workspace ONE Intelligence: https://www.youtube.com/watch?v=vNhp6_U3org

Workspace ONE UEM / AirWatch
----------------------------
Workspace ONE UEM - это решение по управлению устройствами пользователей. Выполняет инвентаризацию, мониторинг и настройку устройств под управлением ОС Windows, Linux, Mac OS X, iOS, Android, Windows Phone, Chrome OS. Workspace ONE UEM позволяет централизованно настраивать почту, VPN, безопасность, а также доставлять и устанавливать приложения на устройства. Дополнительно Workspace ONE UEM позволяет организовать портал самообслуживания Workspace ONE Access, через который пользователи могут получать доступ ко всем опубликованными приложениям, включая внутренние или облачные приложения, приложения с терминальных серверов и виртуальные рабочие станции.
 
Дополнительная информация по продукту: https://www.vmware.com/content/dam/digitalmarketing/vmware/ru/pdf/products/workspace-one/vmware-workspace-one-datasheet.pdf 
 
Сравнение редакций Workspace ONE:
https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/workspace-one/workspace-one-editions-comparison.pdf 
 
Видео: https://www.youtube.com/watch?v=ozkMl845tZQ 

Лабораторные работы на сайте https://labs.hol.vmware.com по теме VMware Workspace ONE:
- HOL-2251-09-DWS - Workspace ONE UEM - Getting Started with the Digital Workspace (https://labs.hol.vmware.com/HOL/catalogs/lab/10193)

Workstation Player / Workstation Pro
------------------------------------
VMware Workstation Player - гипервизор, который устанавливается на персональный компьютер пользователя поверх клиентской ОС Windows или Linux , и позволяет запускать виртуальные машины с различными гостевыми операционными системами.

Сценарии использования VMware Workstation:
- Работа с унаследованными приложениями на устаревших ОС, например, Windows XP, Windows Vista, Windows 7, которые не поддерживают аппаратное обеспечение компьютера.
- Одновременный запуск нескольких экземпляров или нескольких версий приложения в разных гостевых ОС.
- Запуск защищенных контейнеров для работы с корпоративными приложениями и сервисами организации без необходимости настройки и управления хостовой ОС компьютера.

VMware Workstation Player доступен для загрузки с сайта VMware и может использоваться для персональных нужд, а также некоммерческими организациями без дополнительных затрат: https://www.vmware.com/ru/products/workstation-player/workstation-player-evaluation.html

Сравнение Workstation Player и Workstation Pro приведено по ссылке: https://www.vmware.com/products/workstation-pro.html#compare
