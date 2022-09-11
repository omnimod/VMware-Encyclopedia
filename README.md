На данной странице приведено краткое описание продуктов и сервисов компании VMware.

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

Advanced Monitoring powered by Control Up
------------------------------------------------

VMware Advanced Monitoring собирает, анализирует и отображает информацию о работе хостов, виртуальных рабочих столов, серверов Horizon и активных сессиях пользователей. VMware Advanced Monitoring позвляет обнаружить и устранить причины длительного входа пользователя в сессию, определить запущенные приложения, которые создают наибольшую нагрузку на рабочие столы, а также оптимизировать потребление ресурсов для неактивных рабочих столов. 
 
VMware Advanced Monitoring позволяет централизованно запускать произвольные сценарии внутри рабочих столов вручную, или при срабатывании определенного тригера, что позволяет упростить и ускорить выполнение типовых операций по обслуживанию VDI инфраструктуры.

VMware Advanced Monitoring лицензируется по пользователям или конкурентным подключениям и доступен по модели подписки в виде облачного сервиса, а также для установки внутри существующей инфраструктуры.

Описание сценариев использования VMware Advanced Monitoring: https://blogs.vmware.com/euc/2020/09/vmware-advanced-monitoring-for-horizon-powered-by-controlup.html

Видео с демонстрацией возможностей VMware Advanced Monitoring: https://www.youtube.com/watch?v=l1ClNdH76_8 

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

VMware Carbon Black Cloud Endpoint
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

VMware Cloud Director
---------------------
Cloud Director – это ПО для создания публичного IaaS сервиса, которое могут использовать организации-провайдеры для предоставления услуг хостинга конечным заказчикам. Cloud Director доступен провайдерам в рамках программы VSPP (VMware Service Provider Program).

Дополнительные материалы по Cloud Director: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/products/vcloud/vmware-vcloud-director-data-sheet.pdf

Лабораторные работы на сайте https://labs.hol.vmware.com по теме Cloud  Director:
- Using VMware Cloud Director and VMware Cloud Foundation on VxRail (HOL-2260-01-ISM) (https://labs.hol.vmware.com/HOL/catalogs/lab/9387)

VMware vCloud Availability
--------------------------
VMware vCloud Availability - сервис катастрофоустойчивой защиты для ВМ, работающих на платформе виртуализации vSphere или в публичных облаках сервис провайдеров (VMware Service Provider Program).
Возможности vCAv:
- Настройка защиты ВМ в различных сценариях (On Premise <-> Cloud и Cloud <-> Cloud), управление защитой и восстановлением ВМ из единой консоли.
- Интеграция консоли vCAv в интерфейс vSphere Client и vCloud Director, поддержка функций Self-Service для аварийного восстановления или миграции ВМ.
- Встроенный механизм репликации vSphere Replication с минимальным RPO в 5 минут.
- Функция тестового восстановления для проверки корректности DR плана и репликации ВМ.

Основные сценарии использования vCAv:
- Миграция ВМ из on-premise инфраструкруктуры в публичное облако и обратно, миграция ВМ между публичными облаками различных провайдеров. vCAv позволяет оперативно перенести ВМ между разными площадками с минимальными трудозатратами и минимальным простоем.
- Реализация Disaster Recovery сценария для защиты ВМ. vCAv обеспечивает репликацию и автоматизированное восстановление ВМ на резервной площадке/в облаке. vCAv поддерживает смену сетевых настроек при восстановлении ВМ.

vCAv доступен в качестве дополнительной услуги в облаках сервис провайдеров VSPP.

Дополнительная информация о vCloud Availability приведена в документе: https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/vcloud/vmw-vcloud-availability-3.0-datasheet.pdf

Короткое видео по теме: https://www.youtube.com/watch?v=H3h78GjqpHE

Лабораторные работы на сайте https://labs.hol.vmware.com по теме vCloud Availability:
- Mware Cloud Provider Platform - DR and Migration using VMware Cloud Director Availability (HOL-2282-01-HBD) (https://labs.hol.vmware.com/HOL/catalogs/lab/12207)

VMware Cloud Disaster Recovery
------------------------------
VMware Cloud Disaster Recovery - это облачный сервис, обеспечивающий защиту и аварийное восстановление ВМ на VMware Cloud on AWS. VMware Cloud DR может использоваться как для защиты нагрузок, работающих внутри ЦОД организации, так и в облаках VMware Cloud on AWS, работающих в разных регионах.

Преимущества VMware Cloud DR:
- Повышение готовности. VMware Cloud DR упрощает развертывание и обслуживание резервной площадки благодаря использованию стандартного набора технологий для запуска ВМ, хранения данных и обеспечения сетевых сервисов, что позволяет администраторам, имеющим опыт в эксплуатации продуктов vSphere, vSAN и NSX в on-prem инфраструктуре, использовать те же инструменты и навыки для управления облаком.
- Уменьшение ошибок и влияния человеческого фактора. VMware Cloud DR имеет встроенные механизмы проверки здоровья компонентов, тестирования аварийного восстановления и создания отчетов о работе инфраструктуры.
- Снижение совокупной стоимости владения. VMware Cloud DR предоставляется по модели подписки и не требует предварительного развертывания всех хостов виртуализации. Требуемые ресурсы могут быть выделены из облака в момент восстановления, без необходимости оплачивать их, пока они не требуются для запуска нагрузок.

Дополинтельная информация о VMware Cloud DR доступна по ссылке: https://www.vmware.com/products/cloud-disaster-recovery.html

Видео о принципах работы VMware Cloud DR: https://www.youtube.com/watch?v=Yz9v3C3_6WY 

VMware Cloud Foundation
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

CloudHealth by VMware
---------------------
VMware CloudHealth – облачный сервис для оценки стоимости и оптимизации затрат в различных публичных облачных сервисах (AWS, Microsoft Azure, Google Cloud Platform).

На сайте доступна 30-дневная тестовая версия: https://www.cloudhealthtech.com/

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

VMware Horizon Cloud
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

